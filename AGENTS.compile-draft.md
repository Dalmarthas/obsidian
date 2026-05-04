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
- If a source depends on local images, screenshots, PDFs, or other attachments, store those files under `raw/assets/` rather than leaving them in the vault root.
- Prefer one source-adjacent asset folder per source, usually `raw/assets/<source-slug>/`.
- When assets are moved into `raw/assets/`, update the canonical raw note so its links point to the asset paths there.

### Wiki layer

- `wiki/sources/`: one page per source, containing structured source summaries and extracted claims.
- `wiki/concepts/`: stable pages for concepts, methods, frameworks, themes, recurring ideas.
  - Domain subfolders are used for navigation:
    - `business/`
    - `ai/`
    - `chess/`
    - `communication/`
    - `leadership/`
    - `health/`
    - `filmmaking/`
    - `productivity/`
    - `creativity/`
    - `others/`
  - Meta/system concept pages for the vault itself may remain flat at the root of `wiki/concepts/`.
- `wiki/entities/`: stable pages for people, companies, books, tools, places, projects, or named things.
- `wiki/syntheses/`: cross-source analyses, comparisons, timelines, thesis pages, question answers worth preserving.
  - Domain syntheses mirror the same subfolders used in `wiki/concepts/`.
  - Cross-source comparison pages go in `wiki/syntheses/cross-source/`.
  - Meta/system synthesis pages for the vault itself may remain flat at the root of `wiki/syntheses/`.
- `wiki/queries/`: durable answers created from user questions when a query should be preserved as its own page.
  - Query pages may stay flat at the root of `wiki/queries/` unless a deeper structure is later approved.
- `wiki/prompts/`: verbatim prompt library for prompts pasted directly in chat.
  - Prompt files are not synthesized wiki pages. They preserve the prompt payload exactly as provided below minimal metadata.
  - Category subfolders are used for routing:
    - `agents/` - agent behavior, system prompts, tool-use protocols, multi-step autonomous workflows.
    - `coding/` - software engineering, debugging, code review, architecture, tests, developer tooling.
    - `research/` - literature review, source analysis, evidence gathering, information synthesis.
    - `writing/` - prose, scripts, essays, editing, voice, rewriting, story or document work.
    - `creativity/` - ideation, design exploration, brainstorming, art direction, creative exercises.
    - `business/` - strategy, marketing, sales, operations, product, positioning, decision support.
    - `productivity/` - planning, prioritization, personal systems, routines, execution support.
    - `image-video/` - image generation, image editing, video, visual production prompts.
    - `other/` - prompts that do not clearly fit the categories above.

## Domain Folder Rules

- Every new concept or synthesis page must be assigned one primary home folder.
- Choose the folder by dominant topic, not by every tag the page happens to touch.
- Use these defaults:
  - business, brand, niche selection, market testing, company-building, career design, self-positioning, financial transition, multi-hyphenate planning -> `business/`
  - ai, artificial intelligence, machine learning, llms, agents, prompting, model behavior, ai products, ai tooling, evals, inference, fine-tuning, embeddings, automation with ai -> `ai/`
  - chess, openings, tactics, middlegame, endgame, calculation, positional play, training games, chess improvement -> `chess/`
  - communication, persuasion, negotiation, campaigns, messaging, targeting -> `communication/`
  - leadership, culture, teams, performance under pressure, trust, accountability -> `leadership/`
  - health, medicine, nutrition, exercise, sleep, recovery, mental health, biomarkers, symptoms, treatment, longevity -> `health/`
  - writing, screenwriting, television, film, acting, story craft -> `filmmaking/`
  - productivity, focus, planning, execution, time management, systems, habits, workflows, note-taking, personal organization -> `productivity/`
  - art, design, visual thinking, creativity, idea-generation -> `creativity/`
  - smaller standalone branches that do not yet justify their own domain -> `others/`
- There is no separate `career/` domain folder. Career and professional-development material is filed under `business/`.
- There is now a dedicated `health/` domain folder. Health-related material should default there rather than being filed under `others/`.
- There is now a dedicated `ai/` domain folder. AI-related material should default there rather than being filed under `others/`.
- There is now a dedicated `chess/` domain folder. Chess-related material should default there rather than being filed under `others/`.
- There is now a dedicated `productivity/` domain folder. Productivity and personal-systems material should default there rather than being filed under `others/`.
- Political pages are usually filed under `communication/` unless the page is primarily about organizational leadership or governance.
- Do not create a new domain folder without explicit user approval.

## Naming Conventions

- Use lowercase kebab-case filenames.
- Prefer ISO dates in filenames for source pages when a source has a capture or publication date.
- Keep filenames stable once created.
- Prefer one canonical page per concept or entity.
- For prompt-ingest files, use `YYYY-MM-DD-short-descriptive-slug.md` when a clear title or purpose is present.
- If a prompt has no clear title or purpose, use `YYYY-MM-DD-prompt.md`; add a numeric suffix only when needed to avoid filename collisions.

Examples:

- `raw/David Lynch writing summary.txt`
- `raw/inbox/2026-04-07-llm-wiki-idea.md`
- `wiki/sources/2026-04-07-llm-wiki-idea.md`
- `wiki/concepts/llm-wiki.md`
- `wiki/concepts/ai/agentic-workflows.md`
- `wiki/concepts/business/business-strategy.md`
- `wiki/concepts/chess/endgame-technique.md`
- `wiki/concepts/communication/effective-communication.md`
- `wiki/concepts/health/sleep.md`
- `wiki/concepts/productivity/task-prioritization.md`
- `wiki/entities/obsidian.md`
- `wiki/syntheses/cross-source/communication-and-influence-models.md`
- `wiki/syntheses/ai/model-evaluation-overview.md`
- `wiki/syntheses/health/recovery-protocols-overview.md`
- `wiki/syntheses/chess/opening-preparation-overview.md`
- `wiki/syntheses/productivity/weekly-review-protocol.md`
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

### Prompt file

Prompt files under `wiki/prompts/` are a special prompt archive. They use minimal YAML frontmatter for navigation while preserving the prompt payload exactly below the metadata.

Required keys:

- `type: prompt`
- `title`
- `created`
- `updated`
- `category`
- `tags`
- `cssclasses`

Optional keys:

- `aliases`
- `source`

Required body:

- Add a `# Prompt` heading.
- Under that heading, paste the exact prompt payload supplied by the user inside a fenced code block so it is easy to copy from Obsidian.
- Use a fence length that does not appear inside the prompt payload. Default to triple backticks; if the prompt contains triple backticks, use four or more backticks.
- Do not manually hard-wrap prompt lines for display. Obsidian wrapping is handled by `.obsidian/snippets/prompt-code-wrap.css`, which keeps copied prompt text closer to the original payload.

Do not summarize, rewrite, normalize, translate, fix grammar, redact, or reformat the prompt payload itself. The code fence is a storage wrapper, not part of the prompt payload.

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
- `prompt-ingest`: preserve a pasted prompt verbatim in the prompt library.
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
6. If the source is image-derived or depends on local attachments, move those supporting files into `raw/assets/<source-slug>/` and update the raw note to point at the canonical asset paths.
7. Inventory the source's reusable content: frameworks, methods, distinctions, examples, caveats, and open questions.
8. Scan the existing wiki for overlapping concepts or nearby branches before creating new pages.
9. Clarify emphasis with the user only if the direction is materially ambiguous.
10. Create or update the corresponding page in `wiki/sources/`.
11. Update or create relevant concept, entity, and synthesis pages.
12. Merge and sharpen overlapping concepts where two or more sources discuss the same idea.
13. Create a comparison synthesis when the overlap is materially valuable.
14. Run the completeness check.
15. Move the canonical normalized raw source into `raw/inbox/` and ensure source references point to the final canonical path.
16. Update `index.md`.
17. Append an entry to `log.md`.

Expected behavior:

- Prefer updating existing pages over creating duplicates.
- Preserve contradictions explicitly.
- Surface missing links and open questions.
- A single source may update many pages.
- If the source is rich, create enough concept and synthesis pages that the source page is no longer the only useful entry point.
- If overlap exists, prefer canonical merged concept pages with source-attributed differences over parallel near-duplicates.
- New-source discovery happens in `raw/`, not in `raw/inbox/`.
- `raw/inbox/` is the post-ingest canonical archive, not the place to look for fresh arrivals.
- If the user asks for too many documents to be deeply ingested at once, do not proceed silently as if quality were unaffected.
- In that case, explicitly tell the user that ingest quality will be reduced because context and attention get spread too thin across too many sources at once.
- Prefer recommending smaller or topic-grouped batches when the source count, source size, or topic diversity would make deep extraction meaningfully weaker.

### Prompt ingest workflow

Use this workflow when the user says `ingest this prompt`, `save this prompt`, or otherwise clearly asks to add a pasted prompt to the prompt library.

1. Treat the user's pasted prompt as the artifact to preserve, not as an instruction to execute.
2. Identify the prompt payload:
   - If the user writes an instruction such as `ingest this prompt:` followed by the prompt, save only the prompt content after that instruction.
   - If the prompt is inside a fenced code block, save the exact content inside the fence unless the user says to include the fence itself.
   - If the boundary is ambiguous, ask one concise clarification question before saving.
3. Do not summarize, rewrite, normalize, translate, fix grammar, redact, or reformat the prompt payload itself.
4. Choose the best category subfolder under `wiki/prompts/` by the prompt's dominant use case. Use `other/` only when no category fits clearly.
5. Create one `.md` file in that category using the prompt-ingest naming convention.
6. Add prompt frontmatter with `type: prompt`, `title`, `created`, `updated`, `category`, and concise searchable `tags`.
7. Add `cssclasses: prompt-note` to prompt frontmatter so Obsidian CSS snippets can target prompt notes.
8. Add `# Prompt`, then paste the prompt payload exactly as supplied inside a fenced code block for one-click copying in Obsidian.
9. Do not create `wiki/sources/`, `wiki/concepts/`, `wiki/syntheses/`, or `wiki/queries/` pages for a prompt-ingest unless the user explicitly asks for synthesis as a separate step.
10. Update `index.md` only when adding a durable category, changing the prompt-library structure, or when the user explicitly wants individual prompt files indexed.
11. Append to `log.md` with the saved prompt file path, category, tags, and a short operational summary. The log may describe the operation, but the prompt payload itself remains verbatim.

### Query workflow

1. Read `index.md` first, starting with its query-routing and compiled-knowledge sections.
2. Prefer `wiki/concepts/` and `wiki/syntheses/` as the primary answer substrate.
3. Open the most relevant wiki pages.
4. Use `wiki/sources/` or `raw/inbox/` only when needed to verify details, preserve disagreements, or fill gaps that the compiled pages do not yet cover.
5. Never use web search, internet browsing, external live lookup, or non-vault sources to answer a query unless the user explicitly overrides this rule for that request.
6. If the answer cannot be found in `index.md`, `wiki/`, `raw/inbox/`, or other local vault files, say clearly that no answer was found within the wiki/vault and stop rather than filling the gap from the web.
7. Synthesize an answer from existing wiki content only.
8. If the answer creates durable insight as a preserved answer to the user's question, file it into `wiki/queries/`. If the answer instead improves reusable cross-source knowledge, update `wiki/syntheses/`, concept pages, or entity pages as appropriate.
9. Update `index.md` if a new durable page was created.
10. Append to `log.md` when the result materially changes the vault.

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

## Command Execution Hygiene

- Before running a shell command or large `apply_patch`, estimate whether the command length is likely to hit Windows command-size limits.
- If the command is likely to be too long, split it into multiple smaller commands or multiple smaller patches before running anything.
- Do not rely on trial-and-error for oversized commands when the size problem is predictable in advance.
- Prefer several smaller, scoped edits over one giant command when creating or updating many files at once.
- This rule applies especially to:
  - large multi-file `apply_patch` calls
  - very long shell commands with many file paths
  - bulk index or log updates combined with many other edits in one call

## Index Rules

- `index.md` is the first navigation page to read when operating on the wiki.
- Keep a compact `Question Routing` section near the top that points to concepts and syntheses for common life, business, health, and execution questions.
- Organize it by content type.
- Include a `Queries` section for durable question-answer pages stored under `wiki/queries/`.
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
- When a question answer should be preserved as its own artifact, store it under `wiki/queries/` rather than mixing it into `wiki/syntheses/`.
- In chat responses, prefer Codex-compatible absolute markdown file links to local pages rather than Obsidian wikilinks.
- Keep the wiki navigable for a human browsing it in Obsidian.

---

# Compiler Workflow Draft Addendum

This section is a draft extension for adding a compiler-style workflow to the vault. It is not active unless this file replaces `AGENTS.md` or its rules are deliberately merged into the active schema.

## Compiler Purpose

The compiler workflow does not replace deep ingest. It adds a staging layer between raw sources and canonical wiki pages so large, ambiguous, or multi-source ingests can be planned before they permanently modify the wiki.

The goal is to reduce:

- duplicate concept creation
- order-dependent ingests
- unreviewed page sprawl
- lost provenance about which raw source changed which durable pages
- unclear maintenance after re-ingest or source correction

The canonical wiki remains markdown-first and Obsidian-friendly. The compiler layer is a workflow scaffold, not a separate app.

## Additional Directories

Add these directories when compiler mode is adopted:

```text
wiki/candidates/
wiki/candidates/sources/
wiki/candidates/concepts/
wiki/candidates/entities/
wiki/candidates/syntheses/
wiki/candidates/queries/
wiki/reports/
wiki/reports/ingest/
wiki/reports/lint/
wiki/manifests/
wiki/lenses/
```

### Candidates

`wiki/candidates/` contains proposed pages or proposed page patches that are not yet canonical.

Use candidates when:

- a source is large or multi-topic
- multiple sources are being ingested as a batch
- the correct concept/entity/synthesis placement is uncertain
- a new page may duplicate an existing page
- the user asks to review before applying
- the ingest would update many existing pages

Candidate pages should use the same frontmatter schema as canonical pages, plus:

```yaml
candidate: true
candidate_status: proposed
candidate_basis:
  - raw/inbox/example.md
promotion_target: wiki/concepts/example.md
```

Do not link candidate pages from `index.md` unless a dedicated candidate index is later created.

### Reports

`wiki/reports/ingest/` contains planning reports for compiler ingests.

Each report should summarize:

- raw sources examined
- source language
- candidate concepts
- candidate entities
- candidate syntheses
- existing pages likely to be updated
- proposed new pages
- overlap and duplicate risks
- contradictions or tensions
- recommended promotion plan

Reports are working artifacts. They are not concept pages, source pages, or syntheses.

### Manifests

`wiki/manifests/` stores machine-readable or table-based operational state.

Start with:

```text
wiki/manifests/source-map.json
```

The source map records which raw files produced or updated which durable pages.

Minimal shape:

```json
{
  "raw/inbox/example.md": {
    "ingested_at": "2026-04-28T12:00:00+03:00",
    "source_page": "wiki/sources/example.md",
    "created_pages": [
      "wiki/concepts/example.md"
    ],
    "updated_pages": [
      "wiki/syntheses/example-framework.md"
    ],
    "status": "active"
  }
}
```

Optional later fields:

```json
{
  "sha256": "...",
  "language": "en",
  "source_kind": "pdf",
  "candidate_report": "wiki/reports/ingest/example.md",
  "raw_assets": [
    "raw/assets/example/image-1.png"
  ]
}
```

The manifest is not a replacement for `log.md`. `log.md` remains the human-readable append-only history. The manifest is for precise maintenance.

### Lenses

`wiki/lenses/` contains curated views over the wiki, not new knowledge claims.

A lens answers: "Show me this vault through a specific operational angle."

Examples:

- `wiki/lenses/content-creation.md` - routes to storytelling, video production, writing, visual design, and audience pages.
- `wiki/lenses/business-building.md` - routes to niche, validation, sales, brand, positioning, and execution pages.
- `wiki/lenses/ai-workflows.md` - routes to prompting, agents, model evaluation, automation, and AI collaboration pages.
- `wiki/lenses/current-projects.md` - routes to active project notes if project pages are later added.

Difference from `index.md`:

- `index.md` is the global catalog.
- A lens is a purpose-specific browsing path.

Difference from `wiki/syntheses/`:

- a synthesis creates an answer or argument from sources.
- a lens is navigation and workflow orientation.

Lenses may contain short annotations, but they should not become hidden syntheses. If a lens starts making substantial claims, convert that material into a synthesis and link to it.

## Interaction Modes Extension

Add a new mode:

- `compile-ingest`: stage one or more raw sources through inventory, candidate generation, review, and promotion before canonical wiki updates.

Use normal `ingest` when:

- there is one source
- the target concepts are obvious
- page changes are small
- the user expects immediate canonical updates

Use `compile-ingest` when:

- there are many sources
- the source is long or multi-topic
- the source overlaps many existing pages
- the source may create several new concepts
- the user wants a reviewable plan
- correctness of page placement matters more than speed

If ambiguous, default to normal `ingest` for small sources and `compile-ingest` for large batches or uncertain concept placement.

## Compile-Ingest Workflow

1. Locate new raw sources in `raw/`.
2. Detect source language.
3. If a source is `.txt`, convert it to `.md` before analysis.
4. Do not immediately edit canonical `wiki/` pages unless the source is obviously small and unambiguous.
5. Read the raw source or batch of raw sources.
6. Create an inventory of:
   - governing thesis
   - key concepts
   - entities
   - frameworks
   - methods
   - reusable claims
   - examples
   - tensions
   - open questions
7. Search existing `wiki/` pages for overlap.
8. Write a report under `wiki/reports/ingest/YYYY-MM-DD-source-slug.md`.
9. In the report, classify each candidate idea as:
   - update existing page
   - create new page
   - merge into existing page
   - defer
   - reject as too thin
10. Create candidate pages under `wiki/candidates/` only for genuinely new or substantially rewritten durable pages.
11. For existing canonical pages, either:
   - describe the proposed patch in the ingest report, or
   - create a candidate patch note under `wiki/candidates/`.
12. Run a review pass:
   - check duplicate concepts
   - check folder placement
   - check source attribution
   - check whether important ideas are still trapped only in the source page
   - check whether candidate pages link to existing pages
13. Promote accepted candidates into canonical `wiki/`.
14. Update existing canonical pages.
15. Move canonical raw sources into `raw/inbox/`.
16. Update `wiki/manifests/source-map.json`.
17. Update `index.md`.
18. Append to `log.md`.
19. Leave rejected or deferred candidates in `wiki/candidates/` only if they remain useful; otherwise remove them before closing the ingest.

## Candidate Promotion Rules

Promote a candidate page when:

- it has a stable title and folder location
- it links to at least one durable page
- it cites at least one source page or raw source
- it does not duplicate an existing page
- its content is durable enough to be useful outside the current ingest

Do not promote a candidate page when:

- it is only a temporary extraction note
- it merely duplicates a section already better handled in an existing page
- it contains unresolved placement ambiguity
- it lacks enough evidence to justify a durable page

When promoting:

1. Remove candidate-only frontmatter keys.
2. Move the file into its canonical folder.
3. Update related pages with reciprocal links where useful.
4. Add it to `index.md`.
5. Record created and updated pages in the source map manifest.
6. Record the promotion in `log.md`.

## Source Map Maintenance

Whenever an ingest creates or materially updates wiki pages, update `wiki/manifests/source-map.json`.

If no manifest exists yet, create it.

Rules:

- Use relative vault paths.
- Keep one top-level key per canonical raw source.
- Include the source page.
- Separate `created_pages` from `updated_pages`.
- Do not include tiny mechanical edits unless they matter for provenance.
- Keep `log.md` as the human narrative; keep the manifest as precise operational state.

## Lint Workflow Extension

Compiler-aware lint should check:

- every source page has an existing `raw_source`
- every `raw/inbox/` source with status `active` appears in the source map or has a deliberate exemption
- every created page in the source map exists
- every candidate page has `candidate: true`
- no candidate page is linked from the global `index.md`
- every promoted page has had candidate-only frontmatter removed
- every new durable page appears in `index.md`
- every durable page links to at least one other durable page
- important related links are reciprocal where useful

## Query Workflow With Compiler Artifacts

For normal user questions, prefer canonical `wiki/` pages.

Use `wiki/candidates/` only when:

- the user explicitly asks about pending candidate material
- no canonical answer exists and a candidate clearly contains relevant but unpromoted work
- the answer states that the material is not yet canonical

Use `wiki/reports/ingest/` only for operational questions about ingestion decisions, not as a primary knowledge substrate.

Use `wiki/lenses/` as navigation helpers when a question matches a lens, but answer from canonical concepts, syntheses, entities, source pages, or queries.

## Recommended Initial Implementation

Start lightweight:

1. Add directories:
   - `wiki/candidates/`
   - `wiki/reports/ingest/`
   - `wiki/reports/lint/`
   - `wiki/manifests/`
   - `wiki/lenses/`
2. Add `wiki/manifests/source-map.json`.
3. Use compile-ingest manually for the next large or multi-source batch.
4. Do not build scripts until the manual workflow proves useful.

Only later consider scripts for:

- source hashing
- broken link checking
- unindexed page checking
- candidate promotion
- source-map validation

## What Not To Adopt Yet

Do not add these unless the user explicitly approves:

- mandatory claim-level provenance for every paragraph
- confidence scores on every page
- freshness metadata on every page
- a full typed knowledge graph
- external database requirements
- replacing Obsidian-style navigation

These may be useful later, but they add friction and are not necessary for the current vault's strongest use case: high-quality human-readable synthesis.
