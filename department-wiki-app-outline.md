# Department Wiki App Outline

## Core Idea

A department wiki app turns scattered workplace knowledge into a structured, searchable, interconnected knowledge base.

Instead of relying on disconnected Google Docs, Sheets, checklists, Slack threads, and tribal knowledge, each department gets a living wiki with clean articles, concept pages, process pages, onboarding paths, and source-backed operational knowledge.

The app is not primarily an AI chatbot. The main product is a browsable and searchable wiki that humans can use directly. AI can assist with ingestion, maintenance, summarization, and optional question-answering later, but the core interface should remain useful without AI.

## What The App Would Look Like

The first screen would be a practical knowledge workspace, not a marketing page.

It would likely include:

- A search bar for finding articles, concepts, tools, processes, and checklists.
- A left sidebar with department sections.
- A main article view.
- Clickable internal links between related concepts and pages.
- Tags and filters for narrowing search.
- A glossary or concepts area.
- Source references or source history where needed.
- Page metadata such as owner, status, last updated date, and review cycle.

Example sections:

- Start Here
- Onboarding
- Processes
- Tools
- Checklists
- Glossary
- Roles And Ownership
- Common Mistakes
- Source Library

## Knowledge Structure

The app should preserve the separation between raw source material and derived wiki pages.

### Raw Sources

Original documents remain available as source material:

- Google Docs
- Google Sheets
- checklists
- PDFs
- exported notes
- SOPs
- internal documents
- meeting summaries
- Slack excerpts when appropriate

These sources are not the main user experience. They are the evidence layer.

### Wiki Pages

The wiki contains cleaned and structured pages:

- onboarding guides
- process explanations
- tool pages
- department policies
- standard operating procedures
- checklists
- troubleshooting guides
- common questions

### Concepts

Concept pages explain terms that appear across many documents:

- deterministic attribution
- Facebook Ads
- UTM
- lead quality
- CAC
- Meta pixel
- approval workflow

### Syntheses

Synthesis pages explain higher-level systems:

- how the department works
- how a campaign moves from request to launch
- first 30 days for a new hire
- reporting workflow
- common operational failure modes

## User Experience

A new employee should be able to enter the department wiki and understand:

- what the department does
- what tools are used
- what terms mean
- how work flows
- who owns what
- what to do in week one
- where to find deeper explanations
- which pages are current and trustworthy

A normal employee should be able to search:

- "Facebook Ads"
- "deterministic attribution"
- "campaign QA"
- "how do I launch a campaign"
- "reporting checklist"

The result should show relevant articles, not only files.

Inside an article, every important term should be clickable so the reader can move through the knowledge graph naturally.

## Trust And Maintenance

The app should make freshness visible.

Each operational page should ideally include:

- owner
- department
- status
- last updated date
- review cycle
- source pages
- related pages

This prevents the wiki from becoming a pile of stale docs. If a process page has not been reviewed in eight months, the UI should make that visible.

## Possible Architecture

The simplest version:

- Markdown files are the source of truth.
- GitHub stores version history.
- A static site generator turns the wiki into a web app.
- Search is generated automatically.
- Internal links become clickable pages.

Possible tools:

- Docusaurus
- MkDocs Material
- Quartz
- VitePress
- Astro/Starlight
- custom Next.js app

A more advanced version:

- Next.js frontend
- Markdown or MDX content
- Postgres for metadata
- Meilisearch, Typesense, or Algolia for search
- authentication and permissions
- department spaces
- page ownership
- stale-page warnings
- analytics for searches and page usage
- optional AI answers with citations

## Why It Is Useful

The main value is onboarding and operational clarity.

New employees learn faster because they are not forced to ask dozens of small questions.

Senior employees lose fewer hours repeating explanations.

The department becomes less dependent on memory, scattered documents, and informal handoffs.

The wiki becomes a compounding asset: every ingestion and cleanup pass makes the department easier to understand.

## Important Product Principle

The UI should not be built before the knowledge model is clear.

The real product is not just a website. The real product is:

1. A source preservation system.
2. A structured wiki.
3. A linking model.
4. A maintenance protocol.
5. A clean interface over that knowledge.

The best first version would be a simple web wiki with excellent search, links, page metadata, and a disciplined ingestion workflow.

## Previous Response

Yes, it’s very possible. What you’re describing is basically a department-specific knowledge graph/wiki, built from scattered operational knowledge.

The core idea is strong because most departments have knowledge split across:

- Google Docs
- Sheets
- Slack messages
- checklists
- SOPs
- onboarding docs
- random “ask Sarah” tribal knowledge
- old process files nobody trusts anymore

A structured wiki turns that into durable, navigable knowledge.

**How It Could Work**
You would have the same layers as our vault:

1. **Raw sources**
   Original docs, sheets, checklists, exports, PDFs, meeting notes. These stay preserved.

2. **Wiki pages**
   Clean derived pages:
   - onboarding process
   - Facebook Ads
   - campaign QA checklist
   - reporting workflow
   - common errors
   - department glossary
   - tools and owners
   - role responsibilities

3. **Concept/entity pages**
   Reusable terms:
   - deterministic attribution
   - UTM
   - Meta pixel
   - CAC
   - lead quality
   - escalation path
   - approval workflow

4. **Syntheses**
   Higher-level explanations:
   - “How our paid acquisition system works”
   - “New hire first 30 days”
   - “How campaign setup flows from request to launch”
   - “Common failure modes in reporting”

This becomes much better than dumping docs into one folder because the LLM compiles the material into a real knowledge structure.

**For Onboarding**
This is probably one of the best use cases.

A new person could start with:

- “Start here”
- “Team overview”
- “Tools we use”
- “Common vocabulary”
- “First week checklist”
- “How work moves through the department”
- “Who owns what”
- “Things people usually misunderstand”

Then every term links outward. They don’t need to ask a senior person 40 small questions.

**UI Wrapper**
Yes, also possible.

There are a few levels.

**Simple Version**
A static web app generated from markdown.

You keep the wiki as markdown files, then render it as a website with:

- search bar
- article pages
- clickable links
- sidebar navigation
- tags
- glossary
- backlinks
- maybe “related articles”

Good tools for this style:

- Docusaurus
- MkDocs Material
- Quartz
- VitePress
- Astro/Starlight
- custom Next.js app

This would be fast, cheap, easy to host, and easy to update from GitHub.

**More Product-Like Version**
A web app with:

- login
- department spaces
- role-based access
- search
- tags
- article pages
- source references
- edit history
- “suggest improvement”
- stale-page warnings
- owners per page
- onboarding paths
- analytics for what people search

This could use:

- Next.js frontend
- Markdown or MDX content
- Postgres for metadata
- Meilisearch / Typesense / Algolia for search
- GitHub or a CMS as content backend

**AI Optional**
You said “not AI, just UI,” and yes, that works.

The UI can just do normal search:

- title search
- full-text search
- tag search
- category filtering

Then later you can add AI as an optional layer:

- “Ask the department wiki”
- answer with citations
- suggest relevant pages
- detect missing docs
- flag contradictions

But the core wiki should not depend on AI to be useful. That’s important.

**Best Architecture**
My preferred version:

- Markdown files are the source of truth.
- GitHub stores version history.
- A static site renders the wiki.
- Search index is built automatically.
- LLM helps ingest/update pages, but humans can browse without AI.
- Every page has:
  - title
  - summary
  - owner
  - last updated
  - tags
  - source links
  - related pages

Example page structure:

```yaml
type: concept
title: Facebook Ads
department: marketing
owner: paid-media
updated: 2026-04-24
tags:
  - acquisition
  - meta
  - paid-media
  - advertising
```

Then body:

```md
# What It Is

# Why It Matters

# How We Use It

# Common Mistakes

# Related Pages
```

**Important Improvement**
Add ownership and freshness.

Business wikis fail when nobody knows whether a page is still true.

So every operational page should have:

- `owner`
- `updated`
- `status`
- `review_cycle`
- `source_pages`

Example:

```yaml
owner: marketing-ops
status: active
review_cycle: quarterly
```

Then the UI can show:

- “This page is current”
- “Needs review”
- “Last updated 8 months ago”
- “Owner: Marketing Ops”

That makes it much more trustworthy.

**The Real Product Idea**
This could become an internal “department OS”:

- knowledge base
- onboarding path
- glossary
- SOP library
- process map
- search
- ownership
- source-backed answers
- change log
- review reminders

For each department, you could have:

```text
/company-wiki/
  marketing/
  sales/
  support/
  product/
  finance/
  operations/
```

And shared concepts can connect across departments.

Example:

- Sales page links to `lead quality`
- Marketing page links to `lead quality`
- Support page links to `customer segment`
- Finance page links to `CAC`

That’s where it becomes interconnected and valuable.

**My Take**
This is not only possible, it is probably one of the highest-ROI uses of this wiki pattern.

The key is not the UI first. The key is the ingestion and maintenance protocol:

1. Gather messy docs.
2. Preserve raw sources.
3. Compile clean pages.
4. Link concepts.
5. Add ownership and freshness.
6. Expose it through search/UI.
7. Keep improving it as work changes.

A simple static web version would be enough to start. Later, if it proves useful, wrap it in a more polished web app with permissions, analytics, and optional AI search.
