---
type: source
title: LLM Wiki Idea
created: 2026-04-07
updated: 2026-04-07
raw_source: raw/inbox/2026-04-07-llm-wiki-idea.md
source_kind: user-brief
status: active
tags:
  - source
  - llm-wiki
  - second-brain
---

# Summary

This source proposes replacing query-time-only retrieval with a persistent, LLM-maintained markdown wiki that compiles knowledge over time. The central move is to insert a maintained wiki layer between raw sources and future answers, so synthesis, contradictions, and cross-links accumulate instead of being recomputed from scratch. Source: [[raw/inbox/2026-04-07-llm-wiki-idea|Raw source]].

# Key Claims

- A persistent wiki compounds value because the LLM integrates each new source into an evolving set of pages instead of rediscovering the same facts on every query.
- The wiki should sit between raw sources and answers as the maintained knowledge layer.
- The most important durable operations are ingest, query, and lint.
- `index.md` should be content-oriented, while `log.md` should be chronological and append-only.
- The human should curate and direct; the LLM should handle the maintenance burden.

# Important Details

- Raw sources are immutable and remain the source of truth.
- The wiki layer may include summaries, concept pages, entity pages, comparisons, theses, and other derived artifacts.
- The schema file is the operational contract that keeps the LLM acting like a disciplined maintainer rather than a generic chatbot.
- Useful answers to later questions should often be filed back into the wiki as new synthesis pages.
- At small scale, a well-maintained `index.md` can replace the need for RAG infrastructure.

# Tensions / Caveats

- The source is intentionally abstract and does not prescribe one final directory structure.
- The wiki depends on disciplined maintenance; the schema must be updated as the operating model matures.
- Search tooling may become necessary as the number of pages grows.

# Links

- Core concept: [[wiki/concepts/llm-wiki|LLM Wiki]]
- Local synthesis: [[wiki/syntheses/this-vault-operating-model|This Vault Operating Model]]
- Operating schema: [[AGENTS]]

# Open Questions

- When this vault grows beyond index-first navigation, should it add a local search tool such as qmd?
- Which domains should receive dedicated hub or synthesis pages first: personal, projects, research, or health?
