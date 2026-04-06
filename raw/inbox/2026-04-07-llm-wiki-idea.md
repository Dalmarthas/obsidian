---
type: raw-source
title: LLM Wiki
captured: 2026-04-07
source_kind: user-brief
status: immutable
tags:
  - source
  - llm-wiki
---

# LLM Wiki

A pattern for building personal knowledge bases using LLMs.

This is an idea file, it is designed to be copy pasted to your own LLM Agent (e.g. OpenAI Codex, Claude Code, OpenCode / Pi, or etc.). Its goal is to communicate the high level idea, but your agent will build out the specifics in collaboration with you.

## The core idea

Most people's experience with LLMs and documents looks like RAG: you upload a collection of files, the LLM retrieves relevant chunks at query time, and generates an answer. This works, but the LLM is rediscovering knowledge from scratch on every question. There's no accumulation. Ask a subtle question that requires synthesizing five documents, and the LLM has to find and piece together the relevant fragments every time. Nothing is built up. NotebookLM, ChatGPT file uploads, and most RAG systems work this way.

The idea here is different. Instead of just retrieving from raw documents at query time, the LLM incrementally builds and maintains a persistent wiki - a structured, interlinked collection of markdown files that sits between you and the raw sources. When you add a new source, the LLM doesn't just index it for later retrieval. It reads it, extracts the key information, and integrates it into the existing wiki - updating entity pages, revising topic summaries, noting where new data contradicts old claims, strengthening or challenging the evolving synthesis. The knowledge is compiled once and then kept current, not re-derived on every query.

This is the key difference: the wiki is a persistent, compounding artifact. The cross-references are already there. The contradictions have already been flagged. The synthesis already reflects everything you've read. The wiki keeps getting richer with every source you add and every question you ask.

You never (or rarely) write the wiki yourself - the LLM writes and maintains all of it. You're in charge of sourcing, exploration, and asking the right questions. The LLM does all the grunt work - the summarizing, cross-referencing, filing, and bookkeeping that makes a knowledge base actually useful over time. In practice, I have the LLM agent open on one side and Obsidian open on the other. The LLM makes edits based on our conversation, and I browse the results in real time - following links, checking the graph view, reading the updated pages. Obsidian is the IDE; the LLM is the programmer; the wiki is the codebase.

This can apply to a lot of different contexts. A few examples:

- Personal: tracking your own goals, health, psychology, self-improvement - filing journal entries, articles, podcast notes, and building up a structured picture of yourself over time.
- Research: going deep on a topic over weeks or months - reading papers, articles, reports, and incrementally building a comprehensive wiki with an evolving thesis.
- Reading a book: filing each chapter as you go, building out pages for characters, themes, plot threads, and how they connect. By the end you have a rich companion wiki.
- Business/team: an internal wiki maintained by LLMs, fed by Slack threads, meeting transcripts, project documents, customer calls.
- Competitive analysis, due diligence, trip planning, course notes, hobby deep-dives - anything where you're accumulating knowledge over time and want it organized rather than scattered.

## Architecture

There are three layers:

1. Raw sources - your curated collection of source documents. Articles, papers, images, data files. These are immutable - the LLM reads from them but never modifies them. This is your source of truth.
2. The wiki - a directory of LLM-generated markdown files. Summaries, entity pages, concept pages, comparisons, an overview, a synthesis. The LLM owns this layer entirely. It creates pages, updates them when new sources arrive, maintains cross-references, and keeps everything consistent. You read it; the LLM writes it.
3. The schema - a document (e.g. `CLAUDE.md` for Claude Code or `AGENTS.md` for Codex) that tells the LLM how the wiki is structured, what the conventions are, and what workflows to follow when ingesting sources, answering questions, or maintaining the wiki.

## Operations

### Ingest

You drop a new source into the raw collection and tell the LLM to process it. An example flow: the LLM reads the source, discusses key takeaways with you, writes a summary page in the wiki, updates the index, updates relevant entity and concept pages across the wiki, and appends an entry to the log.

### Query

You ask questions against the wiki. The LLM searches for relevant pages, reads them, and synthesizes an answer with citations. Good answers can be filed back into the wiki as new pages, so explorations compound.

### Lint

Periodically, ask the LLM to health-check the wiki for contradictions, stale claims, orphan pages, missing cross-references, data gaps, and promising next questions.

## Indexing and logging

Two special files help the LLM and the human navigate the wiki:

- `index.md` is content-oriented. It catalogs the pages in the wiki with links and one-line summaries.
- `log.md` is chronological. It records what happened and when, using consistent headings like `## [2026-04-02] ingest | Article Title`.

## Optional: CLI tools

At larger scale, local search tools such as qmd can help the LLM operate over the wiki more efficiently than a single index page.

## Tips and tricks

- Obsidian Web Clipper can convert articles to markdown.
- Download images locally so the LLM can inspect them later if needed.
- Obsidian's graph view is useful for seeing the structure of the wiki.
- Marp can turn markdown into slide decks.
- Dataview can build dynamic lists from frontmatter.
- The wiki is just a git repo of markdown files.

## Why this works

The hard part of maintaining a knowledge base is bookkeeping. Updating cross-references, keeping summaries current, and reconciling contradictions is tedious for humans and cheap for LLMs. The human curates and thinks. The LLM maintains the system.

The idea is related in spirit to Vannevar Bush's Memex: a personal, curated knowledge store where the associative trails between documents are as valuable as the documents themselves. The missing piece historically was maintenance; the LLM supplies that piece.

## Note

This document is intentionally abstract. It communicates the pattern, not a fixed implementation. The directory structure, page formats, metadata, and tooling should be adapted collaboratively to the user's needs.
