---
type: concept
title: Shapley Value
created: 2026-04-13
updated: 2026-04-13
status: active
tags:
  - concept
  - business
  - fairness
  - cooperation
  - game-theory
source_pages:
  - wiki/sources/2026-04-13-how-decision-making-is-actually-science-game-theory-explained.md
related:
  - wiki/concepts/business/game-theory.md
  - wiki/concepts/communication/negotiation-and-mediation.md
  - wiki/syntheses/business/game-theory-cooperation-and-competition-framework.md
---

# What It Is

Shapley value is a cooperative-game-theory method for dividing gains or costs according to each participant's average marginal contribution across all possible coalition orderings. In the vault, it matters as a fairness framework for situations where equal splits feel too blunt but simple output-counting also misses how value emerges through collaboration. Main source: [[wiki/sources/2026-04-13-how-decision-making-is-actually-science-game-theory-explained|How Decision Making is Actually Science: Game Theory Explained]].

# Why It Matters

- It gives the vault a principled language for contribution-based allocation.
- It separates `fairness` from both naive equality and pure power.
- It is useful for thinking about equity splits, team rewards, shared costs, and coalition design.

# Evidence In This Vault

- The current source frames Shapley value as the cooperative counterpart to equilibrium logic in competitive games.
- Value is assigned through average marginal contribution rather than through fixed titles or one arbitrary contribution order.
- The source names four fairness conditions behind the method:
  - interchangeable contributors should be treated equally
  - dummy players receive zero under the formal model
  - contribution should be measured by what changes when a player is removed
  - multi-part games should be decomposed consistently rather than priced by one crude aggregate split
- The cookie-baking example supplies the vault's main intuition:
  - collaboration can create extra surplus beyond what each person produces alone
  - fairness therefore cannot always be read directly from solo output
  - averaging marginal contributions gives a more defensible split when synergy is real

# Source Comparisons

- Compared with [[wiki/concepts/communication/negotiation-and-mediation|Negotiation and Mediation]], Shapley value is less about persuasion and more about allocation logic after cooperation is possible.
- Compared with [[wiki/concepts/business/game-theory|Game Theory]], this concept is narrower. Game theory covers strategic interaction broadly; Shapley value is one fairness rule inside cooperative coalition settings.

# Tensions / Open Questions

- The `dummy player` axiom is analytically tidy but ethically controversial in human systems that protect people during illness, leave, or temporary incapacity.
- Precision can create false confidence if the underlying contribution estimates are weak, political, or impossible to observe cleanly.
- The current branch still lacks stronger sources on when contribution-based fairness should yield to solidarity, simplicity, or institution-level values.

# Related Pages

- [[wiki/concepts/business/game-theory|Game Theory]]
- [[wiki/concepts/communication/negotiation-and-mediation|Negotiation and Mediation]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework|Game Theory Cooperation and Competition Framework]]
- [[wiki/sources/2026-04-13-how-decision-making-is-actually-science-game-theory-explained|How Decision Making is Actually Science: Game Theory Explained]]
