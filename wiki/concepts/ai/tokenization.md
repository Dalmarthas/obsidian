---
type: concept
title: Tokenization
created: 2026-04-23
updated: 2026-04-23
status: active
tags:
  - ai
  - tokenization
  - llms
  - cost
source_pages:
  - wiki/sources/2026-04-23-most-devs-dont-understand-how-llm-tokens-work
related:
  - wiki/concepts/ai/large-language-models
  - wiki/concepts/ai/foundation-models
  - wiki/syntheses/ai/llm-training-and-inference-overview
  - wiki/syntheses/ai/llm-tokenization-and-cost-overview
---

# What It Is

Tokenization is the process that converts raw text into the discrete units a language model actually processes. In practice, those units are usually learned subword pieces mapped to numeric IDs rather than whole words in any simple human sense.

# Why It Matters

This concept explains several practical realities that otherwise look arbitrary: billing is token-based, context limits are token-based, providers count the same text differently, and some languages or codebases are more expensive and less efficient than others for the same visible amount of text.

# Evidence In This Vault

- [[wiki/sources/2026-04-23-most-devs-dont-understand-how-llm-tokens-work]] explains tokenization as the encoding-and-decoding layer between human-readable text and LLM computation.
- The source shows why provider differences matter: each tokenizer has its own vocabulary and segmentation behavior, so cost and token counts vary across vendors even for the same prompt.
- It also sharpens the vocabulary tradeoff: larger vocabularies often reduce token count for common patterns, but they increase memory and model complexity.
- The same source highlights a distributional consequence: rare words, underrepresented languages, and less common programming languages can be split into more tokens, which can raise cost and sometimes reduce efficiency.

# Tensions / Open Questions

- The branch still needs stronger sources on how tokenization interacts with context windows, caching, latency, and retrieval-system design.
- It also needs more precise material on tokenizer families and training algorithms before the vault should distinguish BPE-style, unigram, and other schemes in detail.
- Future sources may justify a separate page on prompt-cost design or context budgeting if the practical engineering branch keeps expanding.

# Related Pages

- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/foundation-models|Foundation Models]]
- [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]]
- [[wiki/syntheses/ai/llm-tokenization-and-cost-overview|LLM Tokenization and Cost Overview]]
