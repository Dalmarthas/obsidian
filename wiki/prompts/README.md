# Prompt Library

This folder stores prompts pasted directly into the vault through the `prompt-ingest` workflow.

Prompt files are tagged artifacts. When a user says `ingest this prompt`, save the prompt payload exactly as provided below minimal YAML metadata, choose the best category folder, and add concise searchable tags.

## Categories

- `agents/` - agent behavior, system prompts, tool-use protocols, multi-step autonomous workflows.
- `coding/` - software engineering, debugging, code review, architecture, tests, developer tooling.
- `research/` - literature review, source analysis, evidence gathering, information synthesis.
- `writing/` - prose, scripts, essays, editing, voice, rewriting, story or document work.
- `creativity/` - ideation, design exploration, brainstorming, art direction, creative exercises.
- `business/` - strategy, marketing, sales, operations, product, positioning, decision support.
- `productivity/` - planning, prioritization, personal systems, routines, execution support.
- `image-video/` - image generation, image editing, video, visual production prompts.
- `other/` - prompts that do not clearly fit the categories above.

## File Rules

- Use lowercase kebab-case filenames.
- Prefer `YYYY-MM-DD-short-descriptive-slug.md`.
- Use `YYYY-MM-DD-prompt.md` when there is no clear title or purpose.
- Add a numeric suffix only when needed to avoid collisions.
- Use YAML frontmatter with `type: prompt`, `title`, `created`, `updated`, `category`, `tags`, and `cssclasses: prompt-note`.
- Put the exact prompt payload under a `# Prompt` heading inside a fenced code block.
- Use triple backticks by default; if the prompt contains triple backticks, use a longer fence.
- Do not hard-wrap long prompt lines. Obsidian display wrapping is handled by `.obsidian/snippets/prompt-code-wrap.css`.
- Do not summarize, rewrite, normalize, translate, fix grammar, redact, or reformat the prompt payload itself. The code fence is only a copy-friendly storage wrapper.
