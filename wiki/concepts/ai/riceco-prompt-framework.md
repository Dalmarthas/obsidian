---
type: concept
title: RICECO Prompt Framework
created: 2026-04-09
updated: 2026-04-09
status: active
tags:
  - ai
  - prompting
  - frameworks
  - llms
source_pages:
  - wiki/sources/2026-04-09-riceco-prompt-framework
related:
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/few-shot-prompting
  - wiki/concepts/ai/large-language-models
  - wiki/syntheses/ai/prompt-design-workflow
---

# What It Is

RICECO is a six-part prompt framework: Role, Instruction, Context, Examples, Constraints, and Output Format.

# Why It Matters

It turns vague prompting advice into a simple reusable checklist. The framework is useful because it helps users diagnose what is missing from a prompt instead of only guessing that a prompt is "bad."

# Evidence In This Vault

- [[wiki/sources/2026-04-09-riceco-prompt-framework]] presents RICECO as the main practical structure for writing better prompts across major LLMs.
- The source also offers the ICC shortcut, Instruction, Context, Constraints, as the lower-friction version that captures most everyday value.
- It especially highlights examples and constraints as the levers that push outputs from generic to aligned and reusable.

# Source Comparisons

- The current source frames RICECO as a prompt-construction method, while the existing AI foundations branch focuses on what model families are.
- Within RICECO itself, ICC is presented as a faster subset rather than a competing framework.

# Tensions / Open Questions

- The branch still needs stronger sources on which RICECO elements matter most by task type.
- Future sources may justify splitting role prompting, output schemas, and evaluation loops into their own canonical pages.

# Related Pages

- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
