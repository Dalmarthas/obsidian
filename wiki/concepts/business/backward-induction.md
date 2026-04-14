---
type: concept
title: Backward Induction
created: 2026-04-13
updated: 2026-04-13
status: active
tags:
  - concept
  - business
  - strategy
  - game-theory
  - timing
source_pages:
  - wiki/sources/2026-04-13-game-theory-yale-university-ben-polak.md
related:
  - wiki/concepts/business/game-theory.md
  - wiki/concepts/business/business-strategy.md
  - wiki/syntheses/business/game-theory-cooperation-and-competition-framework.md
---

# What It Is

Backward induction is a way of solving finite sequential decisions by starting from the last possible move, identifying the best action there, and then reasoning step by step backward to the present. In the vault, it matters as a timing and sequence tool: some strategic errors come not from choosing the wrong action class but from acting at the wrong moment because the endpoint logic was never worked backward. Main source: [[wiki/sources/2026-04-13-game-theory-yale-university-ben-polak|Game Theory (Yale University - Ben Polak)]].

# Why It Matters

- It gives the game-theory branch a practical method for timing problems and multi-step decisions.
- It helps distinguish `what eventually to do` from `when to do it`.
- It offers a disciplined way to reason through launches, negotiations, races, and other finite-horizon contests.

# Evidence In This Vault

- The current source uses a sponge duel to show how the right action depends on distance and turn order rather than on aggression alone.
- The core method is:
  - solve the last certain decision point
  - infer what the previous player should do knowing that endpoint
  - continue backward until the present move is pinned down
- The source also contributes an important caution:
  - backward induction is more assumption-sensitive than dominance reasoning
  - it works best where players can reasonably model one another as similarly rational and aware
  - it becomes shakier when cognition, information, or common knowledge break down

# Source Comparisons

- Compared with [[wiki/concepts/business/game-theory|Game Theory]], this concept is narrower. Game theory names the field; backward induction is one method inside sequential finite games.
- Compared with [[wiki/concepts/business/business-strategy|Business Strategy]], backward induction is more local and procedural. Strategy chooses the arena and priorities; backward induction helps decide the order and timing of moves inside a given arena.

# Tensions / Open Questions

- The cleaner the finite endpoint, the more useful backward induction becomes; open-ended or noisy environments weaken it quickly.
- Decision-makers often overtrust proactive action and underweight the value of waiting for better odds.
- The vault still needs stronger material on signaling, commitment, and imperfect-information cases where backward induction must be modified or supplemented.

# Related Pages

- [[wiki/concepts/business/game-theory|Game Theory]]
- [[wiki/concepts/business/business-strategy|Business Strategy]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework|Game Theory Cooperation and Competition Framework]]
- [[wiki/sources/2026-04-13-game-theory-yale-university-ben-polak|Game Theory (Yale University - Ben Polak)]]
