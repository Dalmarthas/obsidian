---
type: synthesis
title: This Vault Operating Model
created: 2026-04-07
updated: 2026-04-07
status: active
tags:
  - synthesis
  - operating-model
  - second-brain
question: How is the LLM Wiki pattern instantiated in this vault right now?
basis:
  - wiki/sources/2026-04-07-llm-wiki-idea.md
  - AGENTS.md
related:
  - wiki/concepts/llm-wiki.md
---

# Question

How is the general LLM Wiki pattern being turned into a working second brain in this Obsidian vault?

# Answer

This vault uses a simple two-layer content structure plus a schema file:

- `raw/` holds immutable source material.
- `wiki/` holds LLM-authored derived knowledge.
- `AGENTS.md` defines how every future interaction should operate.

The first-pass navigation model is intentionally lightweight:

- `index.md` is the content map.
- `log.md` is the chronological operation history.

The first ingest stores the user's implementation brief as a raw source, creates a structured source summary, distills the core concept into a reusable concept page, and records the setup in the log. This is the default pattern for future ingests.

# Basis

- Source summary: [[wiki/sources/2026-04-07-llm-wiki-idea|LLM Wiki Idea (Source Summary)]]
- Schema: [[AGENTS]]
- Catalog: [[index]]
- Timeline: [[log]]

# Gaps

- No entity pages exist yet because the first source was architectural rather than entity-heavy.
- No dedicated domain hubs exist yet; those should emerge after a few real sources are ingested.
- No local search tool is installed yet; index-first navigation is sufficient for now.

# Related Pages

- [[wiki/concepts/llm-wiki|LLM Wiki]]
- [[index]]
