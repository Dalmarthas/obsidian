---
type: synthesis
title: Prompt Design Workflow
created: 2026-04-09
updated: 2026-04-21
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
  - wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity
related:
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/riceco-prompt-framework
  - wiki/concepts/ai/few-shot-prompting
  - wiki/concepts/ai/context-engineering
  - wiki/concepts/ai/reverse-prompting
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/fine-tuning
  - wiki/concepts/ai/ai-critical-thinking-partner
  - wiki/concepts/ai/ai-roleplay-simulation
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

The newer Utley source adds two refinements. First, use a "human colleague test" for context: if a capable person could not complete the task from the brief and attachments, add more context. Second, preserve your own thinking by asking for assumptions, critique, alternatives, and missing information checks rather than accepting a fluent first pass.

# Basis

- [[wiki/sources/2026-04-09-riceco-prompt-framework]] provides the full RICECO structure and the ICC shortcut.
- The source also explicitly frames prompting as an iterative optimization process rather than a static formula.
- [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]] adds context engineering, reverse prompting, role assignment, and critique loops as collaboration methods that deepen the same workflow.
- [[wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity]] adds the "yes-man" risk, the human colleague test, few-shot greatest-hits libraries, and roleplay simulation as a prompt-to-workflow bridge.

# Gaps

- The branch still lacks stronger material on prompt evaluation, prompt chaining, retrieval-based prompting, and model-specific prompt behavior.
- It now compares prompting and fine-tuning more clearly, but still needs richer comparisons with retrieval, tool use, and system-level workflow design.
- Chain-of-thought-style prompts need current adaptation: request useful rationale, assumptions, checks, or decision criteria when detailed private reasoning is unavailable or inappropriate.

# Related Pages

- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/ai/ai-roleplay-simulation|AI Roleplay Simulation]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
