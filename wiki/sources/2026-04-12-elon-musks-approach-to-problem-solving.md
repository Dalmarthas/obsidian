---
type: source
title: "Elon Musk's Approach to Problem-Solving"
created: 2026-04-12
updated: 2026-04-12
raw_source: raw/inbox/2026-04-12-elon-musks-approach-to-problem-solving.md
author: Elon Musk
source_kind: secondary-summary
status: active
tags:
  - source
  - business
  - productivity
  - systems
  - engineering
  - leadership
---

# Summary

This source is a secondary summary of Elon Musk describing a five-step first-principles algorithm for technical and organizational problem-solving. Its strongest additions to the vault are a sharper deletion-first sequence of question requirements, delete, optimize, speed up, then automate, a stronger warning against automating things that should not exist, and a more explicit leadership rule that real system understanding requires direct immersion in frontline work rather than management-by-abstraction. Raw source: [[raw/inbox/2026-04-12-elon-musks-approach-to-problem-solving|Raw source]].

# Key Claims

- Good problem-solving starts by challenging requirements rather than assuming the initial question is correct.
- Deletion should come before optimization, acceleration, or automation, and teams should expect to restore some removed items if they have deleted aggressively enough.
- People systematically overcompensate for past painful deletions, which leads to unnecessary complexity.
- Optimization and speed-ups are often wasted when applied before questioning whether the remaining steps should exist.
- Automation belongs last in the sequence because it can otherwise lock in waste.
- Technical leadership improves when leaders personally do frontline tasks and understand concrete failure modes, constraints, and fragilities.

# Important Details

- The source adds a clean five-step algorithm:
  - question requirements
  - delete
  - optimize or simplify
  - speed up
  - automate
- The order is the core insight:
  - many teams optimize what should be removed
  - then accelerate it
  - then automate it
  - which compounds waste instead of reducing it
- The deletion rule is stronger than ordinary simplification advice:
  - if nothing has to be restored later, the team likely did not delete enough
  - reintroduction is framed as evidence that the simplification pass was serious
  - this is meant to counter fear-driven complexity accumulation
- The source also adds a bias model:
  - people remember the rare painful case where something removed turned out to matter
  - they then add protective complexity broadly
  - the algorithm is partly an anti-overcorrection discipline
- The AI-cluster example grounds the framework in real infrastructure:
  - distributed systems can be limited by power jitter, cooling, cabling, and synchronization rather than by the glamorous software layer alone
  - mundane physical constraints therefore belong inside first-principles analysis
  - software-heavy teams cannot assume hardware and facilities are secondary
- The leadership layer is especially reusable:
  - Musk argues that leaders should personally do real frontline work
  - this creates a more reliable map of where requirements are dumb, where fragility lives, and where bottlenecks are falsely described
  - it also reduces abstraction errors made by leaders who only review summaries and dashboards

# Tensions / Caveats

- This is a secondary summary of a conversational clip rather than a formal engineering doctrine with validated thresholds.
- The `restore about 10%` rule is heuristic, not a tested universal metric.
- The source is strong on simplification discipline, but it may understate cases where safety margins, redundancy, or process slack are genuinely necessary.
- Frontline immersion is clarifying, but the vault should preserve that leaders can also distort systems if they over-index on anecdotal local experience instead of broader evidence.

# Links

- [[wiki/entities/elon-musk|Elon Musk]]
- [[wiki/concepts/business/first-principles-problem-solving|First-Principles Problem-Solving]]
- [[wiki/concepts/business/business-systems|Business Systems]]
- [[wiki/concepts/business/operational-productivity|Operational Productivity]]
- [[wiki/concepts/productivity/workflow-redesign|Workflow Redesign]]
- [[wiki/syntheses/business/elon-musk-problem-solving-framework|Elon Musk Problem-Solving Framework]]

# Open Questions

- When does aggressive deletion improve clarity, and when does it remove necessary resilience or safety?
- How should teams test whether a requirement is truly dumb versus merely costly or poorly explained?
- What is the best way for leaders to stay grounded in frontline work without degrading into performative micromanagement?
