---
type: concept
title: Reverse Prompting
created: 2026-04-09
updated: 2026-04-21
status: active
tags:
  - ai
  - prompting
  - clarification
  - workflows
source_pages:
  - wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity
  - wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity
related:
  - wiki/entities/jeremy-utley
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/context-engineering
  - wiki/concepts/ai/large-language-models
  - wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework
  - wiki/syntheses/ai/prompt-design-workflow
---

# What It Is

Reverse prompting means instructing the model to ask clarifying questions before answering when key information is missing.

# Why It Matters

It changes the interaction from blind completion to collaborative elicitation. This is useful when the main failure mode is not weak generation but under-specified input.

# Evidence In This Vault

- [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]] presents reverse prompting as a direct response to AI's tendency to answer eagerly even when it lacks enough information.
- The source frames this technique as a way to reduce misleading outputs and improve alignment before the real answer is produced.
- It also positions reverse prompting as part of a broader coaching stance rather than as a one-off trick.
- [[wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity]] sharpens the failure mode: without explicit permission to ask questions, the model may invent missing details or produce a plausible answer against unstated assumptions.
- The newer source frames the first back-and-forth as scoping rather than delay; the cost of questions is meant to reduce later hallucination and rework.

# Tensions / Open Questions

- The branch still needs better sources on when clarifying questions help versus when they create too much friction.
- Future sources may justify splitting clarification-first prompting from multi-step elicitation workflows or agent-style planning.
- Reverse prompting is less useful when the task is intentionally exploratory and the user wants divergent possibilities before narrowing requirements.

# Related Pages

- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
