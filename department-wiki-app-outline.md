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

## Critical Review: Downsides, Blind Spots, And Fixes

The idea is strong, but the failure modes are real. The biggest risk is mistaking “we built a wiki” for “the organization now has usable knowledge.”

**1. Stale Knowledge Becomes Worse Than No Knowledge**

A bad process doc can cause real damage because people trust it.

If the wiki says “use this approval flow” but the team changed it three months ago, a new hire follows the wrong process with confidence.

Fix:
Every operational page needs:

```yaml
owner:
updated:
status:
review_cycle:
```

And the UI should visibly mark pages as:

- current
- needs review
- deprecated
- draft

Do not let process pages exist without an owner.

**2. Ingestion Can Create Polished Lies**

An LLM can turn messy, contradictory documents into something that sounds coherent but is not actually true.

This is dangerous in business operations because inconsistencies often encode reality: “officially we do X, but in practice we do Y.”

Fix:
Keep source citations and tension sections.

Each important page should say:

- “Source-backed”
- “Confirmed by owner”
- “Unresolved contradiction”
- “Practice differs from written policy”

The wiki should not just summarize. It should expose uncertainty.

**3. The Hard Part Is Governance, Not UI**

The UI is the easy part. The hard part is deciding:

- who approves pages
- who updates them
- who owns truth
- what happens when two departments disagree
- who can delete or deprecate pages
- how often reviews happen

Without governance, the wiki becomes another abandoned knowledge base.

Fix:
Create a lightweight operating model:

- every page has an owner
- every department has a wiki steward
- important pages require owner approval
- stale pages get flagged automatically
- deprecated pages are archived, not silently deleted

**4. People May Not Use It**

Employees often default to asking a person or searching Slack because it feels faster.

A wiki only works if it becomes the path of least resistance.

Fix:
Integrate it into actual workflows:

- onboarding checklists link to wiki pages
- Slack answers link back to wiki pages
- managers say “update the wiki” after process changes
- recurring meetings review stale pages
- search must be fast and good
- pages must be shorter and clearer than the raw docs

If search is mediocre, adoption collapses.

**5. Too Much Structure Can Kill Contribution**

If every page requires perfect metadata, citations, schema, tags, ownership, and review status, people stop contributing.

Fix:
Use two tiers:

- lightweight notes for capture
- reviewed wiki pages for trusted knowledge

Let messy input exist, but clearly separate it from official pages.

**6. Access Control Gets Complicated Fast**

Department knowledge may include sensitive material:

- salaries
- performance issues
- client data
- strategy
- legal risks
- HR procedures
- credentials or tool access instructions

A public-ish internal wiki can leak things to the wrong employees.

Fix:
Design permissions early.

At minimum:

- public department pages
- restricted department pages
- leadership-only pages
- source files with stricter access than summaries

Do not assume one wiki equals one permission level.

**7. Source Material May Be Legally Or Operationally Sensitive**

Copying Google Docs, Sheets, and Slack content into another system can create compliance problems.

Fix:
Before ingestion, define:

- what can be imported
- what must be redacted
- what must stay linked, not copied
- retention policy
- who has export rights
- whether client/customer data is allowed

This matters especially for regulated teams, HR, finance, legal, healthcare, and client services.

**8. Cross-Linking Can Become Noise**

If every term becomes a link, pages become unreadable. Users don’t need every mention of “campaign” linked.

Fix:
Use selective linking.

Link:

- first occurrence of important terms
- ambiguous terms
- department-specific concepts
- pages needed for onboarding
- concepts with real operational consequences

Do not link generic words.

**9. Search May Return Documents Instead Of Answers**

A simple search UI might return ten articles when the user wants one clear path.

Fix:
Design search result types:

- best answer
- official process
- glossary term
- checklist
- source document
- related pages

Also create “Start Here” pages for common intents, not only search.

**10. It Can Preserve Bureaucracy Instead Of Improving It**

If the source docs describe bad processes, the wiki may make bad processes easier to follow.

That is useful, but limited. It can also entrench nonsense.

Fix:
Every ingestion should allow comments like:

- “This process appears duplicated.”
- “This approval step has no clear owner.”
- “This checklist overlaps with another.”
- “This policy contradicts actual practice.”

The wiki should be allowed to reveal operational debt.

**11. The LLM Maintainer Can Become A Bottleneck**

If every update requires one expert LLM operator, the system does not scale.

Fix:
Build contribution paths:

- raw capture form
- page edit suggestions
- owner approval queue
- simple templates
- automated stale checks
- human-in-the-loop review

The LLM should accelerate maintenance, not become the only way the wiki changes.

**12. “One Wiki For Everything” Can Become Too Broad**

If you combine too many departments too early, navigation gets muddy.

Fix:
Start with one department and one use case.

Best starting wedge:

- onboarding
- SOPs
- glossary
- common mistakes
- recurring checklists

Then expand once the structure proves useful.

**13. Employees May Resist Because Knowledge Is Power**

Some people benefit from being the only person who knows how things work.

Making knowledge explicit can threaten status.

Fix:
Frame contribution as leverage, not replacement.

Reward people for making the team less dependent on them. Make page ownership visible as expertise, not admin work.

**14. The Wiki Can Become A Dumping Ground**

If ingestion means “throw everything in,” quality degrades quickly.

Fix:
Separate:

- raw source archive
- draft extraction
- reviewed wiki
- deprecated pages

Do not let raw imports appear as trusted knowledge.

**15. Metrics Can Incentivize Bad Behavior**

If you track page views or contributions badly, people may optimize for activity instead of usefulness.

Fix:
Measure practical outcomes:

- onboarding time reduced
- repeated questions reduced
- stale pages reviewed
- search queries with no result
- pages marked helpful/not helpful
- process errors reduced

**My Critical Take**

This idea is viable, but only if it is treated as an operational system, not a documentation project.

The app needs three things from day one:

1. **Trust model**: owner, status, freshness, source backing.
2. **Maintenance model**: review cycles, stale-page alerts, easy corrections.
3. **Adoption model**: search, onboarding paths, Slack/workflow integration.

Without those, it becomes a prettier version of the same scattered-doc problem.

## Sales Positioning And Presentation Script

**Unique Sales Proposition**

Your company does not have a documentation problem. It has a knowledge transfer problem.

This app turns scattered department knowledge into a living, searchable operating manual for how the team actually works.

Not a folder of dead docs. Not another Notion graveyard. Not an AI chatbot making things up.

A source-backed department wiki that gives every employee the same map:

- what things mean
- how processes work
- who owns what
- what is current
- what is outdated
- where the original source came from
- what a new hire should read first

The pitch:

**“We turn your department’s scattered documents into a trusted onboarding and operations wiki, so new hires ramp faster and experienced employees stop answering the same questions every week.”**

**Core Sales Pitch**

Most companies already have the knowledge they need.

It is just trapped in the wrong places.

It is in old Google Docs. Half-updated Sheets. Slack threads. Personal checklists. One person’s memory. A process doc that everyone knows is outdated but nobody wants to touch.

So when a new employee joins, they do not really onboard. They interrogate the team.

They ask:

- Where is this doc?
- What does this acronym mean?
- Is this still current?
- Who owns this?
- Do we actually follow this process?
- Why does this checklist contradict that one?

That is expensive.

Not because one question is expensive. Because the same questions repeat forever.

This app fixes that by building a department-specific knowledge system.

We collect the scattered source material, preserve it, clean it into structured wiki pages, connect related terms and processes, assign ownership, and make it searchable through a simple web interface.

The result is a living map of how the department works.

**Sales Presentation Script**

Let me start with the problem.

Your department probably does not lack documentation.

In fact, you probably have too much documentation.

The issue is that nobody fully trusts it.

Some of it is in Google Docs. Some of it is in Sheets. Some of it is in Slack. Some of it lives in a senior employee’s head. Some of it is technically written down, but nobody knows whether it is current.

So every time someone new joins, onboarding becomes a scavenger hunt.

They do not just learn the job. They have to reconstruct the department.

They ask one person how a process works, then another person gives a different answer. They find a checklist, but it references an old tool. They see a term like “deterministic attribution” or “lead quality” or “campaign QA,” but there is no clean explanation of what it means inside your company.

That creates three costs.

First, new hires ramp slowly.

Second, senior people lose time answering repeat questions.

Third, the team makes avoidable mistakes because people are working from different mental maps.

Our app solves that.

We build a department wiki that is not just a document folder. It is an operating map.

Here is how it works.

We start by collecting your existing knowledge sources:

Google Docs, Sheets, SOPs, onboarding docs, checklists, PDFs, exported notes, and important internal references.

We preserve those as raw sources.

Then we transform them into clean, structured wiki pages.

So instead of a new hire opening ten scattered docs, they can open one page called “Campaign Launch Process” and see:

- what the process is
- who owns it
- what tools are used
- what each step means
- what common mistakes to avoid
- which source documents support it
- which related concepts they should understand next

Important terms become clickable.

If the page mentions “Meta pixel,” they can click it.

If it mentions “UTM,” they can click it.

If it mentions “lead quality,” they can click it.

Now the wiki behaves like a connected knowledge graph, not a pile of documents.

And the most important part is trust.

Every operational page can show:

- owner
- status
- last updated date
- review cycle
- source backing

So the employee does not have to guess whether the page is current.

They can see it.

This is the difference between a wiki people ignore and a wiki people use.

We are not selling “documentation.”

We are selling faster onboarding, fewer repeat questions, and less operational confusion.

Imagine a new employee joining your department.

On day one, they open the department wiki.

They see:

- Start Here
- First Week Checklist
- Team Glossary
- Tools We Use
- How Work Moves Through The Department
- Common Mistakes
- Key Processes
- Who Owns What

They do not need to ask, “Where do I start?”

The system tells them.

Now imagine an experienced employee needs to check a process.

They search “campaign QA.”

They do not get a random folder full of docs.

They get the official checklist, the current process page, the related troubleshooting page, and the owner.

That is the product.

A single trusted place where department knowledge becomes findable, connected, and maintained.

**Short Pitch**

Most teams already have the knowledge they need. It is just scattered, stale, and trapped in people’s heads.

We turn that mess into a source-backed department wiki with search, ownership, freshness, onboarding paths, and clickable concepts.

So new hires ramp faster, senior people answer fewer repeat questions, and the team stops depending on tribal knowledge.

**More Aggressive Pitch**

Your current documentation is probably lying to your employees.

Not intentionally.

But if nobody knows what is current, what is outdated, who owns the process, or which doc is the real one, then your knowledge base is creating confusion while pretending to create clarity.

We fix that.

We do not just organize docs.

We turn department knowledge into an operational system:

- source-backed
- searchable
- owned
- reviewed
- interconnected
- built for onboarding and daily use

**Founder-Style Pitch**

Every department has an invisible operating system.

It is made of habits, acronyms, checklists, handoffs, exceptions, shortcuts, and “ask Sarah, she knows.”

The problem is that this operating system is usually undocumented.

Or worse, half-documented.

Our app makes the department’s operating system visible.

It converts scattered knowledge into a living wiki that new hires can learn from, managers can trust, and teams can maintain.

**Demo Script**

Let me show you what this looks like.

Here is the department home page.

At the top, we have search.

On the left, we have the main areas:

- Onboarding
- Processes
- Tools
- Glossary
- Checklists
- Common Mistakes
- Source Library

Let’s say I am a new hire in marketing.

I click “Start Here.”

Now I see the first-week path:

Day one: team overview, tools, core vocabulary.

Day two: campaign lifecycle.

Day three: reporting workflow.

Day four: QA checklist.

Day five: common mistakes and escalation paths.

Now let’s open “Campaign Launch Process.”

This page is not just text.

At the top, I can see:

- Owner: Marketing Ops
- Status: Active
- Last Updated: April 2026
- Review Cycle: Quarterly
- Source-backed: Yes

Then the page explains the process in plain language.

Inside the article, terms like “Meta pixel,” “UTM,” and “lead quality” are clickable.

If I click “lead quality,” I get a concept page explaining what it means, how the department uses it, common misunderstandings, and related pages.

Now let’s use search.

I type “Facebook Ads.”

The system shows:

- Facebook Ads overview
- Meta pixel
- Campaign launch checklist
- Common Facebook Ads QA mistakes
- Reporting workflow
- Original source documents

This is the difference.

You are not searching a file dump.

You are searching a structured map of how the department works.

**Objection Handling**

Objection: “We already have Google Drive.”

Answer:
Google Drive stores files. It does not tell people which file is current, how concepts relate, what a new hire should read first, or where contradictions exist. This sits above Drive as the organized knowledge layer.

Objection: “We already use Notion.”

Answer:
Notion is a tool. This is a system. If your Notion is already clean, owned, reviewed, and source-backed, great. Most are not. We can either build this inside Notion or create a cleaner dedicated layer.

Objection: “People will not maintain it.”

Answer:
That is why ownership and review cycles are part of the product. Every important page has an owner, status, and freshness indicator. The system can surface stale pages before they become harmful.

Objection: “Can AI answer questions from it?”

Answer:
Yes, eventually. But the point is that the wiki should work before AI. AI answers are only useful if the underlying knowledge is structured, trusted, and current.

Objection: “This sounds like documentation work.”

Answer:
It is not documentation for its own sake. It is onboarding infrastructure and operational risk reduction. The outcome is fewer repeated questions, faster ramp time, and fewer process mistakes.

**Closing Pitch**

The question is not whether your team has knowledge.

It does.

The question is whether that knowledge is findable, current, connected, and teachable.

Right now, a lot of it is probably scattered across documents, tools, messages, and people’s heads.

We turn that into a living department wiki.

One place where a new hire can learn the department.

One place where employees can find the current process.

One place where concepts connect.

One place where ownership and freshness are visible.

That is what this app does.

It turns tribal knowledge into operational infrastructure.
