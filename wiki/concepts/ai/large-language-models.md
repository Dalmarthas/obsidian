---
type: concept
title: Large Language Models
created: 2026-04-09
updated: 2026-04-23
status: active
tags:
  - ai
  - llms
  - language
source_pages:
  - wiki/sources/2026-04-09-google-beginner-ai-course
  - wiki/sources/2026-04-09-riceco-prompt-framework
  - wiki/sources/2026-04-23-large-language-models-explained-briefly
  - wiki/sources/2026-04-23-how-large-language-models-work
  - wiki/sources/2026-04-23-most-devs-dont-understand-how-llm-tokens-work
  - wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips
related:
  - wiki/entities/google
  - wiki/concepts/ai/deep-learning
  - wiki/concepts/ai/generative-ai
  - wiki/concepts/ai/foundation-models
  - wiki/concepts/ai/open-weight-models
  - wiki/concepts/ai/fine-tuning
  - wiki/concepts/ai/tokenization
  - wiki/concepts/ai/prompt-engineering
  - wiki/concepts/ai/riceco-prompt-framework
  - wiki/concepts/ai/few-shot-prompting
  - wiki/syntheses/ai/ai-stack-overview
  - wiki/syntheses/ai/llm-training-and-inference-overview
  - wiki/syntheses/ai/llm-tokenization-and-cost-overview
  - wiki/syntheses/ai/prompt-design-workflow
---

# What It Is

Large language models are deep-learning systems trained on very large text corpora to predict the next token in sequence. That simple training objective, scaled across huge datasets and parameter counts, produces systems that can generate, summarize, classify, translate, and answer questions.

# Why It Matters

LLMs are currently the most socially visible layer of the AI stack and the main bridge between general-purpose models and many practical AI applications. They also matter because they compress several otherwise separate topics into one practical object: pre-training, transformer architecture, inference-time sampling, post-training alignment, and prompt-conditioned behavior.

# Evidence In This Vault

- [[wiki/sources/2026-04-09-google-beginner-ai-course]] presents LLMs as a specialized subset of deep learning with broad language competence acquired through large-scale pre-training.
- The source also emphasizes that LLMs become more domain-specific through later fine-tuning.
- It frames LLMs as infrastructure that can be adapted for sector-specific use cases rather than as one fixed consumer chatbot category.
- [[wiki/sources/2026-04-09-riceco-prompt-framework]] adds the first practical usage layer in the vault: prompt quality, examples, constraints, and output formatting materially shape how useful a general-purpose LLM feels at inference time.
- [[wiki/sources/2026-04-23-large-language-models-explained-briefly]] adds the missing mechanistic layer. It makes explicit that the core learning objective is next-token prediction, that training updates parameters through backpropagation over massive corpora, that transformers rely on embeddings plus attention to encode context, and that chatbot behavior reflects post-training with human feedback rather than raw pre-training alone.
- The source also clarifies a useful practical distinction between parameter determinism and response variability: the underlying model is fixed for a given input, but sampled decoding can still produce different outputs across runs.
- [[wiki/sources/2026-04-23-how-large-language-models-work]] adds two useful framing upgrades: LLMs are treated explicitly as a type of foundation model, and their practical organizational value is illustrated through customer support, content drafting, and software-development assistance.
- [[wiki/sources/2026-04-23-most-devs-dont-understand-how-llm-tokens-work]] closes a key missing implementation layer by explaining how text is encoded into token IDs, why providers count the same prompt differently, how tokenization affects billing and context usage, and why vocabulary design creates language- and code-specific efficiency differences.
- [[wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips]] updates the branch from `what an LLM is` to `what modern LLM development now looks like`: most frontier systems still inherit the GPT-style autoregressive transformer core, major gains now come from post-training, systems engineering, sparse MoE-style scaling, and tool-use integration, and open-weight availability has become a major practical branch in its own right.

# Tensions / Open Questions

- The branch now has a better account of next-token prediction, transformers, attention, RLHF, and tokenization, but it still needs stronger sources on context-window management, retrieval, evaluation, and tool use.
- It distinguishes prompting from post-training more clearly now, but still needs better sources on when prompting alone is enough and when fine-tuning, retrieval, or agent structure is the better intervention.
- It now distinguishes LLMs from the broader foundation-model category more clearly, but still needs stronger sources on where that category boundary is most useful in practice.
- It now has first-pass material on open weights, tool use, and modern training stacks, but still needs more explicit pages or comparisons if the branch keeps growing around post-training, retrieval-versus-tools, and dense-versus-sparse architectures.

# Related Pages

- [[wiki/entities/google|Google]]
- [[wiki/concepts/ai/deep-learning|Deep Learning]]
- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/foundation-models|Foundation Models]]
- [[wiki/concepts/ai/open-weight-models|Open-Weight Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/concepts/ai/tokenization|Tokenization]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
- [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]]
- [[wiki/syntheses/ai/llm-tokenization-and-cost-overview|LLM Tokenization and Cost Overview]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
