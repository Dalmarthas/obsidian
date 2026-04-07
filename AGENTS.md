# LLM Wiki Schema

This vault is operated as an LLM-maintained wiki. This file is the authoritative schema for how the wiki is structured, how sources are ingested, how questions are answered, and how maintenance is performed.

## Status

- Active starting `2026-04-07`.
- From this point forward, every interaction in this vault follows this schema unless you explicitly override it.
- The latest explicit user instruction overrides this file. If there is no conflict, follow this file exactly.

## Purpose

The wiki is a persistent, compounding knowledge artifact. The goal is not to re-discover knowledge from raw documents on every query. The goal is to compile, refine, and maintain durable markdown pages that accumulate understanding over time.

## Roles

- Human role: curate sources, direct attention, ask questions, decide what matters.
- LLM role: read sources, extract structure, update pages, maintain cross-links, surface contradictions, keep the wiki coherent.

## Three Layers

### 1. Raw sources

- Path: `raw/`
- New, unprocessed source files arrive in the root of `raw/`, not in `raw/inbox/`.
- Raw sources are immutable after capture except for filename normalization when needed and the post-ingest move from `raw/` to `raw/inbox/`.
- If a new source to be ingested is in `.txt` format, convert it to `.md` before ingesting it.
- After ingest, move the canonical raw source into `raw/inbox/`.
- Raw sources are the source of truth.
- The LLM may read raw sources, but must not rewrite their content during normal wiki maintenance.

### 2. Wiki

- Path: `wiki/`
- The wiki contains LLM-authored derived artifacts.
- Pages may be created, merged, split, updated, and cross-linked freely.
- The wiki should prefer synthesis over duplication.

### 3. Schema

- Path: `AGENTS.md`
- This file defines the operating contract for the vault.
- When the workflow changes, update this file deliberately.

## Core Files

- `index.md`: content-oriented catalog of the wiki.
- `log.md`: append-only chronological record of important operations.

## Directory Conventions

### Raw layer

- `raw/`: landing zone for newly added source documents before ingest. New ingest discovery happens here.
- `raw/inbox/`: canonical normalized raw sources after ingest.
- `raw/assets/`: downloaded images, attachments, PDFs, and other source-adjacent files.

### Wiki layer

- `wiki/sources/`: one page per source, containing structured source summaries and extracted claims.
- `wiki/concepts/`: stable pages for concepts, methods, frameworks, themes, recurring ideas.
- `wiki/entities/`: stable pages for people, companies, books, tools, places, projects, or named things.
- `wiki/syntheses/`: cross-source analyses, comparisons, timelines, thesis pages, question answers worth preserving.

## Naming Conventions

- Use lowercase kebab-case filenames.
- Prefer ISO dates in filenames for source pages when a source has a capture or publication date.
- Keep filenames stable once created.
- Prefer one canonical page per concept or entity.

Examples:

- `raw/David Lynch writing summary.txt`
- `raw/inbox/2026-04-07-llm-wiki-idea.md`
- `wiki/sources/2026-04-07-llm-wiki-idea.md`
- `wiki/concepts/llm-wiki.md`
- `wiki/entities/obsidian.md`
- `wiki/syntheses/this-vault-operating-model.md`

## Language Handling

- Detect the source language at the start of ingest.
- If a new source in `raw/` is primarily in Russian, operate in Russian for that ingest and for any pages materially created or updated because of it.
- For Russian ingests, write human-facing wiki content in Russian:
  - titles
  - section headings
  - summaries and extracted claims
  - concept, entity, source, and synthesis prose
  - tags
  - index entry descriptions
  - log summaries
- Keep schema-critical structure stable even during Russian ingests:
  - YAML keys stay in the schema's standard form
  - required structural values such as `type: source`, `type: concept`, `type: entity`, and `type: synthesis` remain unchanged
- Do not mix English and Russian prose inside one page unless the user explicitly asks for a bilingual page.
- If a Russian source overlaps with an existing English page, prefer creating or maintaining a Russian counterpart and cross-linking it rather than turning one page into a mixed-language document.
- Filenames must still follow lowercase kebab-case. For Russian pages, use a stable transliterated kebab-case slug unless the user explicitly asks for a different naming style.

## Linking Rules

- Use Obsidian wikilinks for internal references.
- Prefer explicit folder-qualified targets when ambiguity is possible, for example `[[wiki/concepts/llm-wiki|LLM Wiki]]`.
- Every durable page should link to at least one other durable page.
- New pages should be linked from `index.md` on creation.
- When a page becomes important, add reciprocal links from related pages.

## Citation Rules

- Distinguish clearly between source-grounded claims, synthesis, and speculation.
- Source-grounded claims should cite the relevant source page, not just the raw file.
- When useful, cite the raw source as well.
- If a claim is uncertain, mark it as tentative.
- If newer material contradicts older material, preserve both and record the tension explicitly.

## Frontmatter Schema

Use YAML frontmatter on all wiki pages.

### Source page

Required keys:

- `type: source`
- `title`
- `created`
- `updated`
- `raw_source`
- `status`
- `tags`

Optional keys:

- `source_kind`
- `source_date`
- `author`
- `source_count`

### Concept page

Required keys:

- `type: concept`
- `title`
- `created`
- `updated`
- `status`
- `tags`

Optional keys:

- `aliases`
- `related`
- `source_pages`

### Entity page

Required keys:

- `type: entity`
- `title`
- `created`
- `updated`
- `status`
- `tags`

Optional keys:

- `aliases`
- `related`
- `source_pages`

### Synthesis page

Required keys:

- `type: synthesis`
- `title`
- `created`
- `updated`
- `status`
- `tags`

Optional keys:

- `question`
- `basis`
- `related`

## Page Templates

### Source page sections

Use this structure unless the source demands something more specific:

1. `# Summary`
2. `# Key Claims`
3. `# Important Details`
4. `# Tensions / Caveats`
5. `# Links`
6. `# Open Questions`

### Concept page sections

1. `# What It Is`
2. `# Why It Matters`
3. `# Evidence In This Vault`
4. `# Source Comparisons` when two or more sources materially overlap on the concept
5. `# Tensions / Open Questions`
6. `# Related Pages`

### Entity page sections

1. `# Overview`
2. `# Role In This Vault`
3. `# Evidence In This Vault`
4. `# Related Pages`

### Synthesis page sections

1. `# Question`
2. `# Answer`
3. `# Basis`
4. `# Comparisons` when the synthesis is explicitly cross-source
5. `# Gaps`
6. `# Related Pages`

## Deep Extraction Standard

The default goal is not a thin summary. The goal is a source-to-wiki transformation strong enough that the raw source is usually needed only for full detail, obscure examples, or verbatim wording.

For every substantial source, extract as many of the following as are materially present:

- top-level thesis or governing idea
- frameworks, models, heuristics, and named principles
- distinctions, contrasts, and paradoxes
- step-by-step methods and operating procedures
- examples and case studies that change how a concept is understood
- failure modes, caveats, and boundary conditions
- tensions, disagreements, and unresolved questions
- advice that is generalizable beyond the original context
- source-specific style or worldview that should not be over-generalized

Do not stop once the main 3 to 5 points are captured if the source obviously contains more reusable structure.

## Cross-Source Integration Rules

When a new or revisited source overlaps with existing material:

- identify the overlapping concepts explicitly
- prefer updating a canonical concept page instead of leaving the overlap trapped in parallel source-local pages
- record who says what when multiple sources discuss the same concept differently
- preserve important differences in framing, scope, or emphasis instead of flattening them into fake agreement
- create a dedicated comparison synthesis when two or more sources materially agree, disagree, or complement each other
- link both the shared concept page and the source-specific pages so a reader can move between the merged view and the original framing

The wiki should increasingly behave like a compiled knowledge base, not a stack of adjacent summaries.

## Completeness Check

Before closing an ingest or re-ingest, run this mental checklist:

- Are the key frameworks, methods, distinctions, and tensions out of the raw file and into the wiki?
- Are any important ideas still trapped only in the source page?
- Did overlapping concepts get merged or sharpened rather than duplicated?
- If two sources discuss the same concept, is there a place where their agreement and difference are both visible?
- Would I need the raw source mainly for full detail or quotes, rather than because the wiki missed the core ideas?

If the answer to the last question is no, the extraction is not deep enough yet.

## Interaction Modes

Every future interaction should be interpreted as one or more of these modes:

- `ingest`: add or process a new source.
- `query`: answer a question using the current wiki.
- `lint`: health-check the wiki and propose or apply maintenance.
- `admin`: change schema, structure, naming, or system setup.

If the user message is ambiguous, infer the most likely mode and proceed.

## Standard Workflow

### Ingest workflow

1. Capture or locate the new raw source in the root of `raw/`.
2. Detect the source language.
3. If the raw source is primarily Russian, set the working language for human-facing wiki output to Russian while keeping schema-critical structure stable.
4. If the raw source is a `.txt` file, convert it to `.md` before continuing.
5. Read the source from `raw/`.
6. Inventory the source's reusable content: frameworks, methods, distinctions, examples, caveats, and open questions.
7. Scan the existing wiki for overlapping concepts or nearby branches before creating new pages.
8. Clarify emphasis with the user only if the direction is materially ambiguous.
9. Create or update the corresponding page in `wiki/sources/`.
10. Update or create relevant concept, entity, and synthesis pages.
11. Merge and sharpen overlapping concepts where two or more sources discuss the same idea.
12. Create a comparison synthesis when the overlap is materially valuable.
13. Run the completeness check.
14. Move the canonical normalized raw source into `raw/inbox/` and ensure source references point to the final canonical path.
15. Update `index.md`.
16. Append an entry to `log.md`.

Expected behavior:

- Prefer updating existing pages over creating duplicates.
- Preserve contradictions explicitly.
- Surface missing links and open questions.
- A single source may update many pages.
- If the source is rich, create enough concept and synthesis pages that the source page is no longer the only useful entry point.
- If overlap exists, prefer canonical merged concept pages with source-attributed differences over parallel near-duplicates.
- New-source discovery happens in `raw/`, not in `raw/inbox/`.
- `raw/inbox/` is the post-ingest canonical archive, not the place to look for fresh arrivals.

### Query workflow

1. Read `index.md` first.
2. Open the most relevant wiki pages.
3. Synthesize an answer from existing wiki content.
4. If the answer creates durable insight, file it into `wiki/syntheses/` or update existing pages.
5. Update `index.md` if a new durable page was created.
6. Append to `log.md` when the result materially changes the vault.

### Lint workflow

Check for:

- contradictions
- stale claims
- orphan pages
- weak or missing cross-links
- concepts mentioned without their own page
- pages that should be merged
- unanswered open questions
- obvious research gaps

If a lint pass produces durable changes, record them in `log.md`.

## Index Rules

- `index.md` is the first navigation page to read when operating on the wiki.
- Organize it by content type.
- Each entry should have a link and a one-line description.
- Keep it compact enough to scan quickly.
- Update it whenever a durable page is added or materially re-scoped.

## Log Rules

- `log.md` is append-only.
- Each entry must start with a heading in this form:
  - `## [YYYY-MM-DD HH:mm] mode | Title`
- Include the pages touched and a short summary of what changed.
- Log ingests, durable queries, lint passes, and schema/admin changes.

## Quality Bar

- Do not silently collapse conflicting evidence into false certainty.
- Do not leave obviously important facts trapped only in source pages if they belong on concept or entity pages.
- Prefer concise, high-signal prose over long paraphrase.
- Keep pages updated in place rather than spawning near-duplicates.
- When a better page structure becomes obvious, refactor the wiki.
- Treat thin extraction as a quality failure when the source contains reusable structure that was not externalized.
- Aim for source pages to be gateways, not bottlenecks.
- Make cross-source agreement and disagreement legible in the wiki itself.

## Initial Scope

This vault starts as a general-purpose personal second brain with a research-friendly layout. It can cover personal notes, projects, health, reading, research, planning, and general knowledge, as long as raw sources remain distinct from derived wiki pages.

## Operational Default

From now on:

- Treat this vault as an LLM Wiki by default.
- Prefer durable edits over one-off chat answers when the result would be useful later.
- Keep the wiki navigable for a human browsing it in Obsidian.
