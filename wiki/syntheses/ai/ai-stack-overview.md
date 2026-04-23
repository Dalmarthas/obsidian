---
type: synthesis
title: AI Stack Overview
created: 2026-04-09
updated: 2026-04-23
status: active
tags:
  - ai
  - foundations
  - overview
question: How does the current vault explain the relationship between AI, machine learning, deep learning, generative AI, and LLMs?
basis:
  - wiki/sources/2026-04-09-google-beginner-ai-course
  - wiki/sources/2026-04-23-how-large-language-models-work
  - wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips
related:
  - wiki/entities/google
  - wiki/concepts/ai/artificial-intelligence
  - wiki/concepts/ai/machine-learning
  - wiki/concepts/ai/deep-learning
  - wiki/concepts/ai/generative-ai
  - wiki/concepts/ai/foundation-models
  - wiki/concepts/ai/open-weight-models
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/supervised-and-unsupervised-learning
  - wiki/concepts/ai/fine-tuning
  - wiki/concepts/ai/prompt-engineering
  - wiki/syntheses/ai/prompt-design-workflow
---

# Question

How does the current vault explain the relationship between AI, machine learning, deep learning, generative AI, and LLMs?

# Answer

The current AI branch supports a layered stack:

1. Artificial intelligence is the outer umbrella.
2. Machine learning is the data-driven learning subdomain inside AI.
3. Deep learning is the neural-network-heavy subdomain inside machine learning.
4. Generative AI is the output-producing layer inside the deep-learning landscape.
5. Foundation models are broadly pre-trained reusable bases inside modern generative-model practice.
6. Large language models are a major language-focused specialization inside the foundation-model and generative-AI landscape.

The branch also supports three important training distinctions:

- supervised versus unsupervised learning for the basic ML layer
- discriminative versus generative behavior for model-output logic
- broad pre-training followed by narrower fine-tuning for LLM specialization

And it now supports one hierarchy distinction that the older branch state lacked:

- foundation model as the broad reusable base category
- LLM as the text-and-code-focused branch inside that category

This overview is intentionally beginner-friendly. Its value is not technical completeness, but giving the vault a clear foundational map that later AI sources can deepen.

# Basis

- [[wiki/sources/2026-04-09-google-beginner-ai-course]] is currently the foundational source for the AI branch and explicitly organizes the stack in this layered way.
- The source also provides the beginner distinctions around supervision, generation, and fine-tuning that make the hierarchy more usable.
- [[wiki/sources/2026-04-23-how-large-language-models-work]] adds the missing foundation-model layer and makes the LLM branch more operational by tying it to self-supervised pre-training, transformer context handling, fine-tuning, and early business use cases.
- [[wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips]] updates the branch toward the modern ecosystem by showing that open-weight strategy, tool use, post-training, and systems efficiency now matter almost as much as the original stack taxonomy.

# Gaps

- The branch now has a first prompting layer, but still lacks stronger sources on model evaluation, embeddings, retrieval, agent design, and current product ecosystems.
- It also needs more technical material before this overview should be treated as sufficient for builders rather than general readers.
- The current foundation-model layer is still text-heavy and does not yet cleanly cover multimodal or non-LLM foundation-model families.
- It now has a first open-weight layer, but still needs clearer sources on licensing categories, local inference tradeoffs, and geopolitical model ecosystems beyond this one snapshot.

# Related Pages

- [[wiki/entities/google|Google]]
- [[wiki/concepts/ai/artificial-intelligence|Artificial Intelligence]]
- [[wiki/concepts/ai/machine-learning|Machine Learning]]
- [[wiki/concepts/ai/deep-learning|Deep Learning]]
- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/foundation-models|Foundation Models]]
- [[wiki/concepts/ai/open-weight-models|Open-Weight Models]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/supervised-and-unsupervised-learning|Supervised and Unsupervised Learning]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
