---
type: concept
title: Fine-Tuning
created: 2026-04-09
updated: 2026-04-09
status: active
tags:
  - ai
  - fine-tuning
  - llms
source_pages:
  - wiki/sources/2026-04-09-google-beginner-ai-course
  - wiki/sources/2026-04-09-riceco-prompt-framework
related:
  - wiki/entities/google
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/generative-ai
  - wiki/concepts/ai/machine-learning
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/riceco-prompt-framework
  - wiki/syntheses/ai/ai-stack-overview
  - wiki/syntheses/ai/prompt-design-workflow
---

# What It Is

Fine-tuning is the process of adapting a broadly trained model to a narrower task, domain, or data distribution using additional specialized examples.

# Why It Matters

This is the concept that connects large general-purpose models to specific real-world use cases. It explains how one broad model can become more useful in particular industries or workflows.

# Evidence In This Vault

- [[wiki/sources/2026-04-09-google-beginner-ai-course]] presents fine-tuning as the step that turns broadly pre-trained LLMs into more specialized systems for domains like healthcare, retail, and finance.
- The source also uses fine-tuning to explain how smaller organizations can build on top of general-purpose foundation models instead of training everything from scratch.
- [[wiki/sources/2026-04-09-riceco-prompt-framework]] sharpens the contrast: many practical gains can come from better prompting, examples, constraints, and formatting without touching the model weights at all.

# Tensions / Open Questions

- The branch now has a first prompting source, but still needs stronger evidence on when fine-tuning is better than prompting, retrieval, tooling, or workflow design.
- Future sources may justify separate pages for pre-training, instruction tuning, domain adaptation, and evaluation after adaptation.

# Related Pages

- [[wiki/entities/google|Google]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/machine-learning|Machine Learning]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
