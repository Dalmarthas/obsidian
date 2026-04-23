---
type: concept
title: Foundation Models
created: 2026-04-23
updated: 2026-04-23
status: active
tags:
  - ai
  - foundation-models
  - pre-training
source_pages:
  - wiki/sources/2026-04-09-google-beginner-ai-course
  - wiki/sources/2026-04-23-how-large-language-models-work
  - wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips
related:
  - wiki/concepts/ai/generative-ai
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/open-weight-models
  - wiki/concepts/ai/fine-tuning
  - wiki/concepts/ai/deep-learning
  - wiki/syntheses/ai/ai-stack-overview
---

# What It Is

Foundation models are broadly pre-trained models built on very large datasets so they can transfer to many downstream tasks instead of being designed for only one narrow use case from the start.

# Why It Matters

This concept helps the AI branch separate `broad reusable base model` from `specific application layer`. It also clarifies why fine-tuning, prompting, retrieval, or tooling are usually discussed as ways of adapting a general model rather than building every system from scratch.

# Evidence In This Vault

- [[wiki/sources/2026-04-23-how-large-language-models-work]] explicitly places large language models inside the broader category of foundation models and uses that hierarchy to explain how GPT-style systems relate to the wider model landscape.
- The source also frames foundation models as pre-trained on massive unlabeled corpora in a self-supervised way before narrower adaptation.
- [[wiki/sources/2026-04-09-google-beginner-ai-course]] does not foreground the term as strongly, but it already supports the underlying pattern: broad pre-training followed by narrower adaptation through fine-tuning.
- [[wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips]] deepens the concept by showing that many current foundation-model differences are now about openness, licensing, tool-use training, sparse-vs-dense tradeoffs, and post-training regimes more than about abandoning the core transformer lineage.

# Tensions / Open Questions

- The current branch still needs stronger sources distinguishing foundation models from other generative families such as diffusion or multimodal systems.
- It now has better material on open weights and tool use, but still needs cleaner comparisons between prompting, fine-tuning, retrieval, tool use, and broader agent structure.
- Future sources may justify splitting text-first foundation models from multimodal foundation models more explicitly.

# Related Pages

- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/open-weight-models|Open-Weight Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/concepts/ai/deep-learning|Deep Learning]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
