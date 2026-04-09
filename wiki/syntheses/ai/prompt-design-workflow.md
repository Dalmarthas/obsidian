---
type: synthesis
title: Prompt Design Workflow
created: 2026-04-09
updated: 2026-04-09
status: active
tags:
  - ai
  - prompting
  - workflows
  - llms
question: What practical workflow does the current vault support for writing better prompts?
basis:
  - wiki/sources/2026-04-09-riceco-prompt-framework
  - wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity
related:
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/riceco-prompt-framework
  - wiki/concepts/ai/few-shot-prompting
  - wiki/concepts/ai/context-engineering
  - wiki/concepts/ai/reverse-prompting
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/fine-tuning
  - wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework
---

# Question

What practical workflow does the current vault support for writing better prompts?

# Answer

The current source base supports a seven-step workflow:

1. Start with a clear instruction rather than a vague request.
2. Add context about audience, goal, scenario, or tone so the output is situated.
3. Add constraints and desired output format so the answer is easier to use downstream.
4. Add role and examples when the task is more specialized, stylistic, or high-stakes.
5. Let the model ask clarifying questions first when the brief is incomplete.
6. Ask for critique, alternatives, or tougher evaluation instead of accepting eager agreement.
7. Iterate instead of treating the first answer as final.

RICECO is the structured checklist version of this workflow. ICC, Instruction, Context, Constraints, is the lightweight version. The Jeremy Utley source adds the stronger collaboration stance: coach the model, do not just phrase requests at it.

# Basis

- [[wiki/sources/2026-04-09-riceco-prompt-framework]] provides the full RICECO structure and the ICC shortcut.
- The source also explicitly frames prompting as an iterative optimization process rather than a static formula.
- [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]] adds context engineering, reverse prompting, role assignment, and critique loops as collaboration methods that deepen the same workflow.

# Gaps

- The branch still lacks stronger material on prompt evaluation, prompt chaining, retrieval-based prompting, and model-specific prompt behavior.
- It now compares prompting and fine-tuning more clearly, but still needs richer comparisons with retrieval, tool use, and system-level workflow design.

# Related Pages

- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
