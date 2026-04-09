---
type: source
title: RICECO Prompt Framework
created: 2026-04-09
updated: 2026-04-09
raw_source: raw/inbox/2026-04-09-riceco-prompt-framework.md
status: active
tags:
  - ai
  - prompting
  - llms
  - productivity
  - workflows
source_kind: secondary-summary
---

# Summary

This source introduces RICECO as a practical framework for writing stronger prompts for large language models. Its strongest contribution is a usable six-part structure for prompt design, plus the simpler ICC shortcut and an explicit iterate-evaluate-optimize loop.

# Key Claims

- Prompt quality strongly shapes output quality.
- The full RICECO structure is Role, Instruction, Context, Examples, Constraints, and Output Format.
- For many fast-use cases, ICC, or Instruction, Context, Constraints, captures most of the value.
- Examples and constraints become more important as tasks become more custom, creative, or exacting.
- Prompting should be treated as an iterative workflow, not as one-and-done phrasing.

# Important Details

- The source treats role assignment as a way to shift tone, perspective, and depth.
- It treats examples as a few-shot anchoring mechanism rather than decoration.
- It treats output-format specification as a practical way to reduce post-processing and downstream cleanup.
- It recommends self-critique, alternatives, and rewrites as part of prompt refinement.

# Tensions / Caveats

- This is a secondary summary of a practical prompt-design video, not a technical research source.
- The framework is intentionally broad and tool-agnostic, so it simplifies differences between models and tasks.
- The raw text contains encoding noise.

# Links

- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework|RICECO Prompt Framework]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]

# Open Questions

- When is prompting enough, and when do workflow design, retrieval, or fine-tuning become the better lever?
- Which parts of RICECO stay robust across different model families, and which are most model-specific?
