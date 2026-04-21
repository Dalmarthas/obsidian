---
type: source
title: The 5 Step Playbook for 10x Your AI Productivity
created: 2026-04-21
updated: 2026-04-21
raw_source: raw/inbox/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity.md
status: active
tags:
  - ai
  - prompting
  - productivity
  - llms
  - critical-thinking
source_kind: secondary-summary
source_date: 2026-04-21
author: Jeremy Utley
---

# Summary

This source deepens the existing Jeremy Utley AI branch by framing AI productivity as a coaching problem rather than a prompt-wording problem. Utley argues that strong users treat AI as an eager but conflict-averse thinking partner: they supply complete context, ask for explicit reasoning or rationale, provide examples, force clarification before generation, assign useful roles, and use roleplay loops as practice environments for difficult conversations.

Its most reusable contribution is the claim that AI can either weaken or sharpen human judgment depending on how the human structures the collaboration. Passive users outsource thinking and accept the model's agreeable confidence. Active users ask the model to expose assumptions, challenge weak logic, simulate friction, and widen the adjacent possible.

# Key Claims

- AI behaves like a helpful intern: fast, compliant, and often reluctant to contradict the user unless explicitly instructed to critique.
- The main productivity gain comes from managing the collaboration, not from finding a magic prompt.
- Context engineering should pass the "human colleague test": if a capable colleague could not complete the task from the provided brief, the model probably cannot either.
- Few-shot examples let the model imitate the user's real standards rather than defaulting to generic internet-average output.
- Reverse prompting reduces hallucination and misalignment by making the model ask for missing information before answering.
- Role assignment selects a useful lens, style, or corpus of associations; roleplay turns that lens into a simulator for practice.
- AI can preserve critical thinking when it is instructed to challenge assumptions, surface bias, and offer alternatives instead of acting as a yes-man.
- The deeper opportunity is not only faster output but expansion of the user's adjacent possible: ideas and options that would not have occurred to them unaided.

# Important Details

- The five-step playbook is context engineering, chain-of-thought-style reasoning or visible rationale, few-shot prompting, reverse prompting, and role/roleplay design.
- The source's "bad software, good people" framing means current AI products can be awkward while the underlying capability is still useful if managed like a human collaborator.
- The source treats fabricated confidence as a practical risk: the model may invent sales figures or produce plausible nonsense unless the user creates a clarification and verification loop.
- Few-shot prompting is strengthened by collecting the user's "greatest hits" and, when useful, adding a bad example plus an explanation of why it fails.
- The roleplay workflow has three stages: profile the counterpart, run a simulated conversation with tuned realism, then score the transcript with a feedback-oriented model.
- The source implicitly suggests multi-agent workflow design: specialized AI roles can pass artifacts such as profiles, instruction sets, transcripts, and evaluations between stages.
- The note includes a modern caveat: some assistants may not expose detailed internal chain-of-thought, so users may need to ask for concise rationale, assumptions, checks, or decision criteria rather than hidden reasoning.

# Tensions / Caveats

- This is a practical secondary summary of a talk, not a technical evaluation of prompt methods across model families.
- The source's chain-of-thought recommendation needs updating for current assistants that may provide useful summaries or rationales without revealing private reasoning.
- Role assignment can improve perspective, but named-person roles can become shallow imitation if the user does not add task-specific criteria and evidence.
- The "AI as intern" metaphor is useful for prompting behavior, but it can understate differences between human responsibility, model reliability, tool access, and data provenance.

# Links

- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/ai/ai-roleplay-simulation|AI Roleplay Simulation]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]

# Open Questions

- Which parts of the five-step playbook remain robust as models become better at asking questions, using tools, and following long instructions by default?
- When should a user rely on conversational prompting versus building a repeatable workflow with saved prompts, retrieval, tools, or agents?
- How can users preserve critical thinking without adding so much critique and friction that the workflow becomes slower than unaided work?
