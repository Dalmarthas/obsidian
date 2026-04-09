---
type: concept
title: Large Language Models
created: 2026-04-09
updated: 2026-04-09
status: active
tags:
  - ai
  - llms
  - language
source_pages:
  - wiki/sources/2026-04-09-google-beginner-ai-course
  - wiki/sources/2026-04-09-riceco-prompt-framework
related:
  - wiki/entities/google
  - wiki/concepts/ai/deep-learning
  - wiki/concepts/ai/generative-ai
  - wiki/concepts/ai/fine-tuning
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/riceco-prompt-framework
  - wiki/concepts/ai/few-shot-prompting
  - wiki/syntheses/ai/ai-stack-overview
  - wiki/syntheses/ai/prompt-design-workflow
---

# What It Is

Large language models are deep-learning systems trained on very large text corpora so they can perform a broad range of language tasks such as generation, summarization, classification, and question answering.

# Why It Matters

LLMs are currently the most socially visible layer of the AI stack and the main bridge between general-purpose models and many practical AI applications.

# Evidence In This Vault

- [[wiki/sources/2026-04-09-google-beginner-ai-course]] presents LLMs as a specialized subset of deep learning with broad language competence acquired through large-scale pre-training.
- The source also emphasizes that LLMs become more domain-specific through later fine-tuning.
- It frames LLMs as infrastructure that can be adapted for sector-specific use cases rather than as one fixed consumer chatbot category.
- [[wiki/sources/2026-04-09-riceco-prompt-framework]] adds the first practical usage layer in the vault: prompt quality, examples, constraints, and output formatting materially shape how useful a general-purpose LLM feels at inference time.

# Tensions / Open Questions

- The branch still needs stronger sources on tokenization, context windows, inference behavior, retrieval, and evaluation.
- It now distinguishes prompting from fine-tuning more clearly, but still needs better sources on when prompting alone is enough and when structural intervention is required.
- Later sources may justify separating general-purpose language models from task-specific assistants and agents more explicitly.

# Related Pages

- [[wiki/entities/google|Google]]
- [[wiki/concepts/ai/deep-learning|Deep Learning]]
- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
