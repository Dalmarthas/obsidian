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
  - wiki/sources/2026-04-21-how-to-master-ai-powered-creativity-in-just-13-minutes-jeremy-utley
  - wiki/sources/2026-04-21-jeremy-utley-ai-ignites-human-creativity
related:
  - wiki/concepts/ai/ai-powered-creativity
  - wiki/concepts/creativity/idea-flow
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

The current source base supports an eleven-step workflow:

1. Start with a clear instruction rather than a vague request.
2. Add context about audience, goal, scenario, or tone so the output is situated.
3. Add constraints and desired output format so the answer is easier to use downstream.
4. Add role and examples when the task is more specialized, stylistic, or high-stakes.
5. Let the model ask clarifying questions first when the brief is incomplete.
6. Ask for critique, alternatives, or tougher evaluation instead of accepting eager agreement.
7. Iterate instead of treating the first answer as final.
8. Use AI expert consultation when the task is not one prompt but discovering where AI can help: have the model interview you about workflows, responsibilities, KPIs, and objectives.
9. For creative work, request volume and variation before filtering so the first adequate output does not become the ceiling.
10. Use voice when typing creates a bottleneck: speak the messy context first, then ask the model to structure it.
11. Regenerate and compare for non-trivial creative work, then tell the model why certain options worked before asking for a better next batch.

RICECO is the structured checklist version of this workflow. ICC, Instruction, Context, Constraints, is the lightweight version. The Jeremy Utley source adds the stronger collaboration stance: coach the model, do not just phrase requests at it.

The newer Utley sources add four refinements. First, use a "human colleague test" for context: if a capable person could not complete the task from the brief and attachments, add more context. Second, preserve your own thinking by asking for assumptions, critique, alternatives, and missing information checks rather than accepting a fluent first pass. Third, when you do not know where AI belongs in the work, prompt the model to interview you and propose both obvious and non-obvious workflow uses. Fourth, for idea work, treat the model as a sampling partner: ask for many options, regenerate, compare, and give taste-based feedback.

# Basis

- [[wiki/sources/2026-04-09-riceco-prompt-framework]] provides the full RICECO structure and the ICC shortcut.
- The source also explicitly frames prompting as an iterative optimization process rather than a static formula.
- [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]] adds context engineering, reverse prompting, role assignment, and critique loops as collaboration methods that deepen the same workflow.
- [[wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity]] adds the "yes-man" risk, the human colleague test, few-shot greatest-hits libraries, and roleplay simulation as a prompt-to-workflow bridge.
- [[wiki/sources/2026-04-21-how-to-master-ai-powered-creativity-in-just-13-minutes-jeremy-utley]] adds AI expert consultation for workflow discovery and the anti-satisficing rule of asking for multiple alternatives before choosing.
- [[wiki/sources/2026-04-21-jeremy-utley-ai-ignites-human-creativity]] adds voice-first thought capture, repeated regeneration, and explicit response loops as prompt-workflow habits.

# Gaps

- The branch still lacks stronger material on prompt evaluation, prompt chaining, retrieval-based prompting, and model-specific prompt behavior.
- It now compares prompting and fine-tuning more clearly, but still needs richer comparisons with retrieval, tool use, and system-level workflow design.
- Chain-of-thought-style prompts need current adaptation: request useful rationale, assumptions, checks, or decision criteria when detailed private reasoning is unavailable or inappropriate.
- More variants do not automatically mean better creative judgment; the workflow still needs explicit filtering criteria, taste, or user-owned standards.
- Hallucination can supply surprising creative angles, but factual use still requires separate verification and evidence.

# Related Pages

- [[wiki/concepts/ai/ai-powered-creativity|AI-Powered Creativity]]
- [[wiki/concepts/creativity/idea-flow|Idea Flow]]
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
