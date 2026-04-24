# Log

Append-only record of durable operations in this vault.

## [2026-04-07 02:20] admin | LLM Wiki bootstrap

Summary: Initialized the vault as an LLM Wiki and created the first schema, index, log, and core wiki pages.

Pages touched:

- [[AGENTS]]
- [[index]]
- [[log]]
- [[wiki/concepts/llm-wiki]]
- [[wiki/sources/2026-04-07-llm-wiki-idea]]
- [[wiki/syntheses/this-vault-operating-model]]

## [2026-04-07 02:20] ingest | LLM Wiki Idea

Raw source: [[raw/inbox/2026-04-07-llm-wiki-idea]]

Summary: Captured the user-provided idea file as the first immutable source, created a structured source page, distilled the core concept into a concept page, and documented the local operating model for this vault.

Pages touched:

- [[raw/inbox/2026-04-07-llm-wiki-idea]]
- [[wiki/sources/2026-04-07-llm-wiki-idea]]
- [[wiki/concepts/llm-wiki]]
- [[wiki/syntheses/this-vault-operating-model]]
- [[index]]

## [2026-04-07 02:25] ingest | 5 Simple Rules For Turning Your Cool Idea Into A Screenplay

Raw source: [[raw/inbox/2010-01-08-5-simple-rules-for-turning-your-cool-idea-into-a-screenplay]]

Summary: Ingested a clipped article on screenplay preparation, normalized the raw filename into the vault convention, created a structured source page, spun out concept pages for screenwriting and three-act structure, and filed a reusable pre-draft checklist.

Pages touched:

- [[raw/inbox/2010-01-08-5-simple-rules-for-turning-your-cool-idea-into-a-screenplay]]
- [[wiki/sources/2010-01-08-5-simple-rules-for-turning-your-cool-idea-into-a-screenplay]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/syntheses/filmmaking/screenplay-starting-checklist]]
- [[index]]

## [2026-04-07 11:45] ingest | Aaron Sorkin Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-07-aaron-sorkin-masterclass-complete-summary]]

Summary: Ingested a large secondary summary of Aaron Sorkin's masterclass by normalizing the raw file into `raw/inbox`, creating a source page, adding an Aaron Sorkin entity page, extracting durable craft concepts for intention and obstacle, audience collaboration, dialogue musicality, and screenplay rewriting, and updating the existing screenwriting and structure pages.

Pages touched:

- [[raw/inbox/2026-04-07-aaron-sorkin-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-aaron-sorkin-masterclass-complete-summary]]
- [[wiki/entities/aaron-sorkin]]
- [[wiki/concepts/filmmaking/intention-and-obstacle]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/screenplay-rewriting]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/syntheses/filmmaking/sorkin-screenwriting-framework]]
- [[index]]

## [2026-04-07 12:29] admin | Require txt-to-md normalization before ingest

Summary: Updated the schema so any new raw source arriving as a `.txt` file must be converted to `.md` before the ingest workflow proceeds.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-09 00:28] ingest | GothamChess How to Win at Chess

Summary: Ingested a new English chess source as the vault's first chess branch, then moved the canonical raw file into `raw/inbox/`. Created a source page, a GothamChess entity page, canonical chess pages for [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/tactical-awareness]], and [[wiki/concepts/chess/endgame-conversion]], plus a reusable synthesis page for the overall practical-improvement framework. The source was treated as a secondary summary with visible encoding artifacts, so the durable value was extracted into clean wiki pages rather than left trapped in the raw note, and stale raw-root references were removed from [[.obsidian/workspace.json]] after archiving.

Pages touched:

- [[raw/inbox/2026-04-09-gothamchess-how-to-win-at-chess]]
- [[wiki/sources/2026-04-09-gothamchess-how-to-win-at-chess]]
- [[wiki/entities/gothamchess]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 09:13] admin | Add AI Domain Folder

Summary: Added a dedicated `ai/` domain to the vault structure. Created [[wiki/concepts/ai]] and [[wiki/syntheses/ai]], then updated [[AGENTS]] so AI-related sources now route into the new domain by default instead of falling into `others/`. The schema now explicitly covers AI, machine learning, LLMs, agents, prompting, model behavior, evals, embeddings, fine-tuning, and AI tooling.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-09 02:09] ingest | Ben Finegold Blunders in Chess

Summary: Ingested a new English Ben Finegold chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a new entity page at [[wiki/entities/ben-finegold]], a canonical concept page at [[wiki/concepts/chess/resignation-psychology]], and a reusable synthesis page at [[wiki/syntheses/chess/ben-finegold-blunder-management-framework]]. Then deepened [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/tactical-awareness]], [[wiki/concepts/chess/endgame-conversion]], and [[wiki/syntheses/cross-source/chess-improvement-models]]. The main gain is a practical-resilience layer around premature resignation, anti-complacency discipline, hidden saving resources, and the claim that many results are still decided by the final blunder rather than the earlier quality of play. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-ben-finegold-blunders-in-chess]]
- [[wiki/sources/2026-04-09-ben-finegold-blunders-in-chess]]
- [[wiki/entities/ben-finegold]]
- [[wiki/concepts/chess/resignation-psychology]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/syntheses/chess/ben-finegold-blunder-management-framework]]
- [[wiki/syntheses/cross-source/chess-improvement-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 02:04] ingest | Polgar Long-Term Chess Improvement Plan

Summary: Ingested a new English chess-training source rooted in Laszlo Polgar's philosophy and moved the canonical raw file into `raw/inbox/`. Created a new source page, a new entity page at [[wiki/entities/laszlo-polgar]], a canonical concept page at [[wiki/concepts/chess/problem-first-chess-training]], a reusable synthesis page at [[wiki/syntheses/chess/polgar-long-term-chess-improvement-framework]], and a cross-source comparison page at [[wiki/syntheses/cross-source/chess-improvement-models]]. Then deepened [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/calculation-in-chess]], [[wiki/concepts/chess/board-vision]], and [[wiki/concepts/chess/tactical-awareness]]. The main gain is a long-horizon training layer around position-solving, physical-board work, sparse explanation, and delayed opening emphasis. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-polgar-long-term-chess-improvement-plan]]
- [[wiki/sources/2026-04-09-polgar-long-term-chess-improvement-plan]]
- [[wiki/entities/laszlo-polgar]]
- [[wiki/concepts/chess/problem-first-chess-training]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/calculation-in-chess]]
- [[wiki/concepts/chess/board-vision]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/polgar-long-term-chess-improvement-framework]]
- [[wiki/syntheses/cross-source/chess-improvement-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:46] ingest | John Bartholomew Undefended Pieces

Summary: Ingested a new English John Bartholomew chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a canonical concept page at [[wiki/concepts/chess/undefended-pieces]], and a reusable synthesis page at [[wiki/syntheses/chess/john-bartholomew-piece-safety-framework]], then deepened [[wiki/entities/john-bartholomew]], [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/board-vision]], [[wiki/concepts/chess/tactical-awareness]], [[wiki/concepts/chess/piece-coordination]], and [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]. The main gain is a sharper anti-blunder layer around loose-piece scanning, overprotection, two-sided danger sense, and using piece safety as a first practical filter before more advanced study. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-undefended-pieces]]
- [[wiki/sources/2026-04-09-john-bartholomew-undefended-pieces]]
- [[wiki/concepts/chess/undefended-pieces]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/board-vision]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/concepts/chess/piece-coordination]]
- [[wiki/syntheses/chess/john-bartholomew-piece-safety-framework]]
- [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-07 12:43] ingest | Dan Brown Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-07-dan-brown-masterclass-complete-summary]]

Summary: Ingested a new raw source that arrived as `.txt` by first converting and normalizing it to `.md` per schema, then created a source page, added a Dan Brown entity page, extracted durable thriller-writing concepts for the Three C's, question-and-answer suspense, and process protection, and added a reusable framework synthesis.

Pages touched:

- [[raw/inbox/2026-04-07-dan-brown-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-dan-brown-masterclass-complete-summary]]
- [[wiki/entities/dan-brown]]
- [[wiki/concepts/filmmaking/thriller-writing]]
- [[wiki/concepts/filmmaking/contract-clock-crucible]]
- [[wiki/concepts/filmmaking/question-and-answer-structure]]
- [[wiki/concepts/filmmaking/protect-the-process]]
- [[wiki/syntheses/filmmaking/dan-brown-thriller-framework]]
- [[index]]

## [2026-04-07 12:50] ingest | Goodby Silverstein Masterclass Summary

Raw source: [[raw/inbox/2026-04-07-advertising-goodby-silverstein-masterclass-summary]]

Summary: Ingested a new-source branch on advertising by first converting the raw `.txt` file to `.md` per schema, then creating a source page, adding an entity page for Goodby Silverstein & Partners, extracting durable concepts for advertising, mass intimacy, brand strategy, and creative pitching, and filing a reusable advertising framework synthesis.

Pages touched:

- [[raw/inbox/2026-04-07-advertising-goodby-silverstein-masterclass-summary]]
- [[wiki/sources/2026-04-07-advertising-goodby-silverstein-masterclass-summary]]
- [[wiki/entities/goodby-silverstein-partners]]
- [[wiki/concepts/business/advertising]]
- [[wiki/concepts/business/mass-intimacy]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/creative-pitching]]
- [[wiki/syntheses/business/goodby-silverstein-advertising-framework]]
- [[index]]

## [2026-04-07 12:50] ingest | Bill Clinton Leadership Masterclass Master Summary

Raw source: [[raw/inbox/2026-04-07-bill-clinton-leadership-masterclass-master-summary]]

Summary: Ingested a new leadership branch by first converting the raw `.txt` file to `.md` per schema, then creating a source page, adding a Bill Clinton entity page, extracting durable concepts for leadership, diverse teams, negotiation and mediation, and leadership communication, and filing a reusable leadership framework synthesis.

Pages touched:

- [[raw/inbox/2026-04-07-bill-clinton-leadership-masterclass-master-summary]]
- [[wiki/sources/2026-04-07-bill-clinton-leadership-masterclass-master-summary]]
- [[wiki/entities/bill-clinton]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/diverse-teams]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/syntheses/leadership/clinton-leadership-framework]]
- [[index]]

## [2026-04-07 12:50] ingest | Building a Career Elaine Welteroth Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-07-building-a-career-elaine-welteroth-masterclass-complete-summary]]

Summary: Ingested a new career-design branch by first converting the raw `.txt` file to `.md` per schema, then creating a source page, adding an Elaine Welteroth entity page, extracting durable concepts for creative entrepreneurship, zone of genius, career blueprinting, and financial confidence, and filing a reusable career framework synthesis.

Pages touched:

- [[raw/inbox/2026-04-07-building-a-career-elaine-welteroth-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-building-a-career-elaine-welteroth-masterclass-complete-summary]]
- [[wiki/entities/elaine-welteroth]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/business/zone-of-genius]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/business/financial-confidence]]
- [[wiki/syntheses/business/welteroth-career-framework]]
- [[index]]

## [2026-04-07 12:50] ingest | Conversation Jane Goodall Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-07-conversation-jane-goodall-masterclass-complete-summary]]

Summary: Ingested a new conservation branch by first converting the raw `.txt` file to `.md` per schema, then creating a source page, adding a Jane Goodall entity page, extracting durable concepts for conservation, animal cognition, interconnectedness, and community-based conservation, and filing a reusable conservation framework synthesis.

Pages touched:

- [[raw/inbox/2026-04-07-conversation-jane-goodall-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-conversation-jane-goodall-masterclass-complete-summary]]
- [[wiki/entities/jane-goodall]]
- [[wiki/concepts/others/conservation]]
- [[wiki/concepts/others/animal-cognition]]
- [[wiki/concepts/others/interconnectedness-principle]]
- [[wiki/concepts/others/community-based-conservation]]
- [[wiki/syntheses/others/goodall-conservation-framework]]
- [[index]]

## [2026-04-07 17:40] admin | Raise extraction depth standard

Summary: Updated the schema to require deeper extraction, completeness checks, canonical overlap handling, and cross-source comparison syntheses so the wiki compiles more of each source's reusable structure.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-07 17:40] lint | Deepen writing-branch extraction across old sources

Sources revisited:

- [[raw/inbox/2010-01-08-5-simple-rules-for-turning-your-cool-idea-into-a-screenplay]]
- [[raw/inbox/2026-04-07-aaron-sorkin-masterclass-complete-summary]]
- [[raw/inbox/2026-04-07-dan-brown-masterclass-complete-summary]]

Summary: Reprocessed three previously ingested writing sources under the new extraction rules, created shared cross-source concept pages for story propulsion and writing process, sharpened existing overlap pages with source comparisons, and filed a comparison synthesis showing where the sources agree and differ.

Pages touched:

- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/concepts/filmmaking/question-and-answer-structure]]
- [[wiki/concepts/filmmaking/screenplay-rewriting]]
- [[wiki/concepts/filmmaking/protect-the-process]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/thriller-writing]]
- [[wiki/sources/2010-01-08-5-simple-rules-for-turning-your-cool-idea-into-a-screenplay]]
- [[wiki/sources/2026-04-07-aaron-sorkin-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-dan-brown-masterclass-complete-summary]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]

## [2026-04-07 23:07] lint | Deepen remaining non-writing branches

Sources revisited:

- [[raw/inbox/2026-04-07-advertising-goodby-silverstein-masterclass-summary]]
- [[raw/inbox/2026-04-07-bill-clinton-leadership-masterclass-master-summary]]
- [[raw/inbox/2026-04-07-building-a-career-elaine-welteroth-masterclass-complete-summary]]
- [[raw/inbox/2026-04-07-conversation-jane-goodall-masterclass-complete-summary]]

Summary: Reprocessed the remaining non-writing branches under the deeper extraction rules, extracted shared cross-source concepts for authentic communication, trust-based collaboration, framework-driven action, head and heart harmony, and ethical consumerism, added an intention-and-impact page, sharpened the existing source summaries and nearby concept pages, and filed a comparison synthesis for the shared human-centered change model.

Pages touched:

- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/leadership/head-and-heart-harmony]]
- [[wiki/concepts/communication/intention-and-impact]]
- [[wiki/concepts/business/ethical-consumerism]]
- [[wiki/concepts/leadership/diverse-teams]]
- [[wiki/concepts/business/advertising]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/creative-pitching]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/others/conservation]]
- [[wiki/concepts/others/interconnectedness-principle]]
- [[wiki/concepts/others/community-based-conservation]]
- [[wiki/sources/2026-04-07-advertising-goodby-silverstein-masterclass-summary]]
- [[wiki/sources/2026-04-07-bill-clinton-leadership-masterclass-master-summary]]
- [[wiki/sources/2026-04-07-building-a-career-elaine-welteroth-masterclass-complete-summary]]
- [[wiki/sources/2026-04-07-conversation-jane-goodall-masterclass-complete-summary]]
- [[wiki/syntheses/business/goodby-silverstein-advertising-framework]]
- [[wiki/syntheses/leadership/clinton-leadership-framework]]
- [[wiki/syntheses/business/welteroth-career-framework]]
- [[wiki/syntheses/others/goodall-conservation-framework]]
- [[wiki/syntheses/cross-source/human-centered-change-models]]
- [[index]]

## [2026-04-08 01:26] ingest | Five-source batch: Duffer, Lynch, Carson, Baldacci, and Iger

Raw sources:

- [[raw/inbox/2026-04-08-duffer-brothers-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-david-lynch-writing-summary]]
- [[raw/inbox/2026-04-08-david-carson-design-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-david-baldacci-masterclass-summary]]
- [[raw/inbox/2026-04-08-bob-iger-disney-leadership-masterclass-complete-summary]]

Summary: Converted five new raw `.txt` files into canonical `.md` raw sources, created source pages and entity pages for each, extracted new durable branches for television pilot writing, filmmaking, graphic design, immersive thriller craft, business strategy, and brand stewardship, then applied the deeper extraction method by merging the new material into existing writing, leadership, communication, and brand pages and expanding the cross-source syntheses.

Pages touched:

- [[wiki/sources/2026-04-08-duffer-brothers-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-david-lynch-writing-summary]]
- [[wiki/sources/2026-04-08-david-carson-design-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-david-baldacci-masterclass-summary]]
- [[wiki/sources/2026-04-08-bob-iger-disney-leadership-masterclass-complete-summary]]
- [[wiki/entities/duffer-brothers]]
- [[wiki/entities/david-lynch]]
- [[wiki/entities/david-carson]]
- [[wiki/entities/david-baldacci]]
- [[wiki/entities/bob-iger]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/television-pilot-writing]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/concepts/creativity/graphic-design]]
- [[wiki/concepts/creativity/typography-as-image]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/brand-stewardship]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/thriller-writing]]
- [[wiki/concepts/filmmaking/question-and-answer-structure]]
- [[wiki/concepts/filmmaking/protect-the-process]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/syntheses/filmmaking/duffer-pilot-development-framework]]
- [[wiki/syntheses/creativity/lynch-creative-framework]]
- [[wiki/syntheses/creativity/carson-design-framework]]
- [[wiki/syntheses/filmmaking/baldacci-thriller-framework]]
- [[wiki/syntheses/business/iger-strategy-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[wiki/syntheses/cross-source/human-centered-change-models]]
- [[index]]

## [2026-04-08 01:43] admin | Change raw-source landing rule and add Russian ingest mode

Summary: Updated the schema so new source discovery happens in `raw/`, canonical raw files are moved into `raw/inbox/` after ingest, and Russian-language raw sources trigger Russian-language wiki output for titles, headings, tags, summaries, index descriptions, and log summaries while keeping schema-critical YAML structure stable.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-08 01:59] ingest | Five-source batch: Stephanopoulos, Koons, Auriemma, Hamilton, and Voss

Raw sources:

- [[raw/inbox/2026-04-08-george-stephanopoulos-effective-communication-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-jeff-koons-art-and-creativity-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-geno-auriemma-leadership-and-team-building-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-lewis-hamilton-masterclass-master-summary]]
- [[raw/inbox/2026-04-08-chris-voss-negotiation-masterclass-master-summary]]

Summary: Converted five new raw `.txt` files into canonical `.md` raw sources, moved them into `raw/inbox/`, created source and entity pages for communication, art, team leadership, performance, and negotiation, extracted canonical concepts for effective communication, tactical empathy, high-performance mindset, high-performance team culture, art making, and viewer-centered art, then merged the new material into existing communication, leadership, trust, and creative-integrity pages and filed cross-source comparison syntheses.

Pages touched:

- [[raw/inbox/2026-04-08-george-stephanopoulos-effective-communication-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-jeff-koons-art-and-creativity-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-geno-auriemma-leadership-and-team-building-masterclass-complete-summary]]
- [[raw/inbox/2026-04-08-lewis-hamilton-masterclass-master-summary]]
- [[raw/inbox/2026-04-08-chris-voss-negotiation-masterclass-master-summary]]
- [[wiki/sources/2026-04-08-george-stephanopoulos-effective-communication-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-jeff-koons-art-and-creativity-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-geno-auriemma-leadership-and-team-building-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-lewis-hamilton-masterclass-master-summary]]
- [[wiki/sources/2026-04-08-chris-voss-negotiation-masterclass-master-summary]]
- [[wiki/entities/george-stephanopoulos]]
- [[wiki/entities/jeff-koons]]
- [[wiki/entities/geno-auriemma]]
- [[wiki/entities/lewis-hamilton]]
- [[wiki/entities/chris-voss]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/concepts/creativity/art-making]]
- [[wiki/concepts/creativity/viewer-centered-art]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/diverse-teams]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/syntheses/communication/george-stephanopoulos-communication-framework]]
- [[wiki/syntheses/communication/chris-voss-negotiation-framework]]
- [[wiki/syntheses/leadership/geno-auriemma-team-leadership-framework]]
- [[wiki/syntheses/leadership/lewis-hamilton-performance-framework]]
- [[wiki/syntheses/creativity/jeff-koons-art-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[wiki/syntheses/cross-source/high-performance-leadership-models]]
- [[index]]

## [2026-04-08 02:06] admin | Add oversized-batch ingest warning rule

Summary: Updated the schema so that if the user asks to ingest too many documents at once, the assistant must explicitly warn that quality will drop because context and attention get spread too thin, and should recommend smaller or topic-grouped batches.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-08 02:12] ingest | Daniel Pink Persuasion Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-08-daniel-pink-persuasion-masterclass-complete-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Daniel Pink source page and entity page, extracted new canonical concepts for persuasion, attunement, buoyancy, problem-finding, and timing and sequencing, then merged the overlap into the existing communication and influence branch so the new source compounds with Voss, Stephanopoulos, Clinton, and Iger rather than sitting alone.

Pages touched:

- [[raw/inbox/2026-04-08-daniel-pink-persuasion-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-daniel-pink-persuasion-masterclass-complete-summary]]
- [[wiki/entities/daniel-pink]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/concepts/communication/attunement]]
- [[wiki/concepts/leadership/buoyancy]]
- [[wiki/concepts/communication/problem-finding]]
- [[wiki/concepts/communication/timing-and-sequencing]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/syntheses/communication/daniel-pink-persuasion-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]

## [2026-04-08 02:20] admin | Add command-length precheck rule

Summary: Updated the schema so the assistant must estimate command length before running shell commands or large `apply_patch` calls on Windows and proactively split oversized work into smaller commands or patches instead of waiting for command-length failures.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-08 02:28] ingest | Axelrod Rove Political Campaign Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-08-axelrod-rove-political-campaign-masterclass-complete-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a campaign source page plus entity pages for David Axelrod and Karl Rove, extracted new canonical concepts for political campaigns, voter targeting, opposition research, and ground game and GOTV, then merged the overlap into persuasion, authenticity, leadership communication, leadership, framework-driven action, and the existing communication-and-influence synthesis.

Pages touched:

- [[raw/inbox/2026-04-08-axelrod-rove-political-campaign-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-axelrod-rove-political-campaign-masterclass-complete-summary]]
- [[wiki/entities/david-axelrod]]
- [[wiki/entities/karl-rove]]
- [[wiki/concepts/communication/political-campaigns]]
- [[wiki/concepts/communication/voter-targeting]]
- [[wiki/concepts/communication/opposition-research]]
- [[wiki/concepts/communication/ground-game-and-gotv]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/syntheses/communication/axelrod-rove-campaign-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]

## [2026-04-08 02:35] ingest | Salman Rushdie Writing Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-08-salman-rushdie-writing-masterclass-complete-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Salman Rushdie source page and entity page, extracted new canonical concepts for fiction writing, narrative voice and perspective, setting as character, and writer worldview, then merged Rushdie's craft model into the existing writing-process, creative-integrity, dialogue, idea-development, immersive-research, story-propulsion, and writing-overlap branches.

Pages touched:

- [[raw/inbox/2026-04-08-salman-rushdie-writing-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-salman-rushdie-writing-masterclass-complete-summary]]
- [[wiki/entities/salman-rushdie]]
- [[wiki/concepts/filmmaking/fiction-writing]]
- [[wiki/concepts/filmmaking/narrative-voice-and-perspective]]
- [[wiki/concepts/filmmaking/setting-as-character]]
- [[wiki/concepts/filmmaking/writer-worldview]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/syntheses/filmmaking/salman-rushdie-fiction-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]

## [2026-04-08 02:46] ingest | Martin Scorsese Masterclass Complete Summary

Raw source: [[raw/inbox/2026-04-08-martin-scorsese-masterclass-complete-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Martin Scorsese source page and entity page, extracted new canonical concepts for visual literacy, casting and performance direction, and editing as discovery, then merged Scorsese's filmmaking model into the existing filmmaking, creative-integrity, idea-development, immersive-research, trust-based-collaboration, and writing-process branches so the source compounds with Lynch and the broader narrative-craft layer instead of sitting alone. Also removed the stale old `.txt` workspace reference so Obsidian points only at the canonical archived raw file.

Pages touched:

- [[raw/inbox/2026-04-08-martin-scorsese-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-martin-scorsese-masterclass-complete-summary]]
- [[wiki/entities/martin-scorsese]]
- [[wiki/concepts/creativity/visual-literacy]]
- [[wiki/concepts/filmmaking/casting-and-performance-direction]]
- [[wiki/concepts/filmmaking/editing-as-discovery]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/scorsese-filmmaking-framework]]
- [[.obsidian/workspace.json]]
- [[index]]

## [2026-04-08 02:58] ingest | Shonda Rhimes TV Writing and Showrunning Masterclass Summary

Raw source: [[raw/inbox/2026-04-08-shonda-rhimes-tv-writing-and-showrunning-masterclass-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Shonda Rhimes source page and entity page, extracted new canonical concepts for character-driven storytelling, text and subtext, showrunning, and writers' room craft, then merged Rhimes's television model into the existing television-pilot-writing, screenwriting, story-propulsion, dialogue, audience, process, leadership, team-culture, and collaboration branches so the source compounds with the Duffer, Sorkin, and broader leadership material instead of staying isolated. Also removed the stale old `.txt` workspace reference so Obsidian points only at the canonical archived raw file.

Pages touched:

- [[raw/inbox/2026-04-08-shonda-rhimes-tv-writing-and-showrunning-masterclass-summary]]
- [[wiki/sources/2026-04-08-shonda-rhimes-tv-writing-and-showrunning-masterclass-summary]]
- [[wiki/entities/shonda-rhimes]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/text-and-subtext]]
- [[wiki/concepts/filmmaking/showrunning]]
- [[wiki/concepts/filmmaking/writers-room-craft]]
- [[wiki/concepts/filmmaking/television-pilot-writing]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/syntheses/filmmaking/shonda-tv-writing-and-showrunning-framework]]
- [[.obsidian/workspace.json]]
- [[index]]

## [2026-04-08 03:06] ingest | Kevin Spacey Acting Masterclass Master Summary

Raw source: [[raw/inbox/2026-04-08-kevin-spacey-acting-masterclass-master-summary]]

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Kevin Spacey source page and entity page, extracted new canonical concepts for acting craft, monologue preparation, and auditioning, then merged the acting source into the existing performance, character, dialogue, audience, and creative-integrity branches so the new acting material compounds with Scorsese, Sorkin, Rhimes, and the broader creative layer instead of staying isolated. Also removed the stale old `.txt` workspace reference so Obsidian points only at the canonical archived raw file.

Pages touched:

- [[raw/inbox/2026-04-08-kevin-spacey-acting-masterclass-master-summary]]
- [[wiki/sources/2026-04-08-kevin-spacey-acting-masterclass-master-summary]]
- [[wiki/entities/kevin-spacey]]
- [[wiki/concepts/filmmaking/acting-craft]]
- [[wiki/concepts/filmmaking/monologue-preparation]]
- [[wiki/concepts/filmmaking/auditioning]]
- [[wiki/concepts/filmmaking/casting-and-performance-direction]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/syntheses/filmmaking/kevin-spacey-acting-framework]]
- [[.obsidian/workspace.json]]
- [[index]]

## [2026-04-08 03:16] ingest | Howard Schultz Starbucks Values-Driven Leadership Masterclass Summary

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, created a Howard Schultz source page and entity page, extracted new canonical concepts for values-driven companies, organizational culture, and self-disruption, then merged Schultz's company-building model into the existing leadership, strategy, brand, trust, team-culture, and framework branches so the source compounds with Iger, Goodby, Clinton, Rhimes, and the broader business layer instead of staying isolated. Also removed the stale old `.txt` workspace reference so Obsidian points only at the canonical archived raw file.

Pages touched:

- [[raw/inbox/2026-04-08-howard-schultz-starbucks-values-driven-leadership-masterclass-summary]]
- [[wiki/sources/2026-04-08-howard-schultz-starbucks-values-driven-leadership-masterclass-summary]]
- [[wiki/entities/howard-schultz]]
- [[wiki/concepts/business/values-driven-companies]]
- [[wiki/concepts/leadership/organizational-culture]]
- [[wiki/concepts/business/self-disruption]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/brand-stewardship]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/syntheses/business/schultz-values-driven-leadership-framework]]
- [[.obsidian/workspace.json]]
- [[index]]

## [2026-04-08 03:27] ingest | Chris Voss Workplace Negotiation Masterclass Complete Summary

Summary: Converted the new raw `.txt` source into a canonical `.md` file, moved it into `raw/inbox/`, and treated it as a second, more detailed Chris Voss source rather than a new standalone branch. Created a dedicated source page plus new canonical technique pages for mirroring, labeling, calibrated questions, dynamic silence, no-oriented questions, and accusation audit. Then deepened the existing Voss, negotiation, communication, and persuasion branches so the new material sharpens the vault's tactical-influence layer instead of duplicating it. Also removed the stale old `.txt` workspace reference so Obsidian points only at the canonical archived raw file.

Pages touched:

- [[raw/inbox/2026-04-08-chris-voss-workplace-negotiation-masterclass-complete-summary]]
- [[wiki/sources/2026-04-08-chris-voss-workplace-negotiation-masterclass-complete-summary]]
- [[wiki/concepts/communication/mirroring]]
- [[wiki/concepts/communication/labeling]]
- [[wiki/concepts/communication/calibrated-questions]]
- [[wiki/concepts/communication/dynamic-silence]]
- [[wiki/concepts/communication/no-oriented-questions]]
- [[wiki/concepts/communication/accusation-audit]]
- [[wiki/entities/chris-voss]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/syntheses/communication/chris-voss-negotiation-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[.obsidian/workspace.json]]
- [[index]]

## [2026-04-08 11:45] ingest | Выбор ниши для бизнеса — полная сводка

Summary: Нормализовал новый raw `.txt` источник в канонический `.md` и переместил его в `raw/inbox/`. Создал русскоязычную source page и новую бизнес-ветку вокруг выбора ниши, подниши, MVP-тестирования спроса и мегатрендов. Затем встроил источник в существующие страницы [[wiki/concepts/business/business-strategy|Business Strategy]] и [[wiki/concepts/business/framework-driven-action|Framework-Driven Action]], чтобы новый материал работал как ранний слой стратегии и execution, а не как изолированная русская заметка.

Pages touched:

- [[raw/inbox/2026-04-08-vybor-nishi-dlya-biznesa-polnaya-svodka]]
- [[wiki/sources/2026-04-08-vybor-nishi-dlya-biznesa-polnaya-svodka]]
- [[wiki/concepts/business/vybor-nishi]]
- [[wiki/concepts/business/podnisha]]
- [[wiki/concepts/business/mvp-testirovanie-nishi]]
- [[wiki/concepts/business/megatrendy]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/syntheses/business/freymvork-vybora-nishi-dlya-biznesa]]
- [[index]]

## [2026-04-08 12:27] admin | Domain Folder Reorganization

Summary: Reorganized `wiki/concepts/` and `wiki/syntheses/` into domain folders to reduce navigation sprawl. Created the approved domain structure across business, career, communication, leadership, filmmaking, creativity, and others, plus `wiki/syntheses/cross-source/` for comparison pages. Moved existing concept and synthesis pages into their primary homes, updated vault-wide links to the new canonical paths, fixed post-move duplicated path artifacts, and updated the schema so future pages follow the same routing rules.

Pages touched:

- [[AGENTS]]
- [[index]]
- [[log]]
- [[.obsidian/workspace.json]]
- [[wiki/concepts/llm-wiki]]
- [[wiki/syntheses/this-vault-operating-model]]

## [2026-04-08 12:31] admin | Merge Career Into Business

Summary: Removed `career/` as a separate domain and merged its concept and synthesis pages into `business/`. Updated vault-wide links so existing references now point to the new canonical business paths, and updated the schema so future ingests file career-design and professional-development material under `business/` by default.

Pages touched:

- [[AGENTS]]
- [[index]]
- [[log]]
- [[.obsidian/workspace.json]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/business/financial-confidence]]
- [[wiki/concepts/business/zone-of-genius]]
- [[wiki/syntheses/business/welteroth-career-framework]]

## [2026-04-08 12:47] ingest | Выбор ниши для бизнеса — полная сводка 2

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, затем заингестил его как вторую, более детализированную source page в уже существующую ветку по выбору ниши. Вместо дубля branch усилил общие canonical pages: углубил `Выбор ниши`, `Подниша`, `MVP-тестирование ниши`, `Мегатренды`, расширил общий synthesis до merged view по двум сводкам и вынес два reusable concepts — формулу `что кому как` и `КЭФ`. После ingest перенес нормализованный raw source в `raw/inbox/`.

Pages touched:

- [[raw/inbox/2026-04-08-vybor-nishi-dlya-biznesa-polnaya-svodka-2]]
- [[wiki/sources/2026-04-08-vybor-nishi-dlya-biznesa-polnaya-svodka-2]]
- [[wiki/concepts/business/vybor-nishi]]
- [[wiki/concepts/business/podnisha]]
- [[wiki/concepts/business/mvp-testirovanie-nishi]]
- [[wiki/concepts/business/megatrendy]]
- [[wiki/concepts/business/chto-komu-kak]]
- [[wiki/concepts/business/kef-klyuchevoi-etap-voronki]]
- [[wiki/syntheses/business/freymvork-vybora-nishi-dlya-biznesa]]
- [[index]]

## [2026-04-08 13:13] ingest | Мастер-класс по продажам — полная сводка

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, заингестил его как отдельную sales-ветку и затем перенес финальный raw source в `raw/inbox/`. Вместо одного summary-файла вынес из источника отдельные durable pages под продажи как систему, этапы продажи, выявление боли, квалификацию, предзакрытие, обработку возражений и формулу `свойство -> выгода`. Дополнительно связал новую ветку с существующими influence-концептами через сравнения с [[wiki/concepts/communication/persuasion|Persuasion]] и [[wiki/concepts/communication/tactical-empathy|Tactical Empathy]], обновил [[index]] и убрал stale recent-file references на временный raw-path и исходный `.txt` из [[.obsidian/workspace.json]].

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-prodazhi-polnaya-svodka]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-prodazhi-polnaya-svodka]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/concepts/business/prodazhi]]
- [[wiki/concepts/business/etapy-prodazhi]]
- [[wiki/concepts/business/vyyavlenie-boli-klienta]]
- [[wiki/concepts/business/kvalifikaciya-klienta]]
- [[wiki/concepts/business/predzakrytie]]
- [[wiki/concepts/business/obrabotka-vozrazhenii]]
- [[wiki/concepts/business/svoistvo-vygoda]]
- [[wiki/syntheses/business/freymvork-prodazhi-grebenyuka]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 13:31] ingest | Мастер-класс: продуктовое мышление в бизнесе — полная сводка

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, затем заингестил его как вторую ветку Михаила Гребенюка, но уже про продукт, а не про продажи. Вместо thin summary вынес из source отдельные durable pages по продуктовому мышлению, архитектуре продукта, полному контуру продукта, карте эмоций клиента, ККЦ и матрице приоритизации улучшений. Дополнительно углубил [[wiki/entities/mikhail-grebenyuk|entity page]] и встроил новый source в общие business hubs [[wiki/concepts/business/business-strategy|Business Strategy]] и [[wiki/concepts/business/framework-driven-action|Framework-Driven Action]], чтобы product-layer был виден рядом с нишей, стратегией и execution frameworks. После ingest перенес финальный raw source в `raw/inbox/`, обновил [[index]] и очистил stale recent-file references из [[.obsidian/workspace.json]].

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-produkt-polnaya-svodka]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-produkt-polnaya-svodka]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/business/produktovoe-myshlenie]]
- [[wiki/concepts/business/arhitektura-produkta]]
- [[wiki/concepts/business/polnyi-kontur-produkta]]
- [[wiki/concepts/business/karta-emocii-klienta]]
- [[wiki/concepts/business/kkc-klyuchevye-klientskie-cennosti]]
- [[wiki/concepts/business/matrica-prioritizacii-bystro-silno]]
- [[wiki/syntheses/business/freymvork-produktovogo-myshleniya-grebenyuka]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 13:58] ingest | Мастер-класс по управлению — полная сводка

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, затем заингестил его как третью ветку Михаила Гребенюка — уже не про продажи и не про продукт, а про управление людьми и системами. Вынес из source отдельные durable pages по управлению, системам и стандартизации, найму и обновлению команды, делегированию и контролю, боевому духу команды и управленческим компромиссам. Дополнительно переписал [[wiki/entities/mikhail-grebenyuk|entity page]] как трехслойную ветку `продажи -> продукт -> управление`, обновил [[index]] и после ingest перенес финальный raw source в `raw/inbox/`.

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-upravlenie-polnaya-svodka]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-upravlenie-polnaya-svodka]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/concepts/leadership/upravlenie]]
- [[wiki/concepts/leadership/sistemy-i-standartizaciya]]
- [[wiki/concepts/leadership/naim-i-obnovlenie-komandy]]
- [[wiki/concepts/leadership/delegirovanie-i-kontrol]]
- [[wiki/concepts/leadership/boevoi-duh-komandy]]
- [[wiki/concepts/leadership/upravlencheskie-kompromissy]]
- [[wiki/syntheses/leadership/freymvork-upravleniya-grebenyuka]]
- [[index]]

## [2026-04-08 14:14] ingest | Мастер-класс «Реальный HR» — модуль 1 из 3

Summary: Нормализовал новый русский raw `.txt` в canonical `.md` с явной пометкой `modul-1`, чтобы не спутать его с будущими модулями 2 и 3, затем заингестил как partial HR-branch внутри Grebenyuk ветки. Вынес из source отдельные durable pages по HR-отделу, ГФД, воронке найма, адаптации сотрудников и стратсессиям; параллельно углубил русские leadership pages по управлению, найму, системам и боевому духу команды. Обновил entity page Гребенюка как уже четырехслойную ветку `продукт -> продажи -> управление -> HR`, дополнил `index.md`, записал историю и переместил финальный raw source в `raw/inbox/`.

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-1]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-1]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/concepts/leadership/hr-otdel]]
- [[wiki/concepts/leadership/gfd-grob-fail-dolzhnosti]]
- [[wiki/concepts/leadership/voronka-naima]]
- [[wiki/concepts/leadership/adaptaciya-sotrudnikov]]
- [[wiki/concepts/business/stratsessii]]
- [[wiki/concepts/leadership/upravlenie]]
- [[wiki/concepts/leadership/naim-i-obnovlenie-komandy]]
- [[wiki/concepts/leadership/sistemy-i-standartizaciya]]
- [[wiki/concepts/leadership/boevoi-duh-komandy]]
- [[wiki/syntheses/leadership/freymvork-realnogo-hr-grebenyuka]]
- [[index]]

## [2026-04-08 15:15] ingest | Мастер-класс «Реальный HR» — модуль 2 из 3

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, встроил модуль 2 не как параллельную ветку, а как углубление существующего partial branch `realnyi-hr`, а затем переместил финальный raw source в `raw/inbox/`. Вынес из source отдельные durable pages по аватару кандидата, академии обучения, «химии» в найме и справедливой мотивации; одновременно перепрошил канонические HR-узлы через многоканальную воронку, academy-layer, бескомпромиссный отбор, слой мотивации и логику эффективного масштабирования. Обновил общий HR synthesis до покрытия модулей 1-2 из 3, дополнил `index.md` и очистил stale recent-file references на временный raw-path и исходный `.txt` из [[.obsidian/workspace.json]].

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-2]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-1]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-2]]
- [[wiki/concepts/leadership/avatar-kandidata]]
- [[wiki/concepts/leadership/akademiya-obucheniya]]
- [[wiki/concepts/leadership/himiya-v-naime]]
- [[wiki/concepts/leadership/spravedlivaya-motivaciya]]
- [[wiki/concepts/leadership/hr-otdel]]
- [[wiki/concepts/leadership/voronka-naima]]
- [[wiki/concepts/leadership/adaptaciya-sotrudnikov]]
- [[wiki/concepts/leadership/sistemy-i-standartizaciya]]
- [[wiki/concepts/leadership/naim-i-obnovlenie-komandy]]
- [[wiki/concepts/leadership/boevoi-duh-komandy]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/syntheses/leadership/freymvork-realnogo-hr-grebenyuka]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 15:27] ingest | Мастер-класс «Реальный HR» — модуль 3 из 3

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, использовал его как завершающий модуль 3 для уже существующего branch `realnyi-hr`, а затем достроил ветку до полного покрытия по модулям 1-3. Вынес из source отдельные durable pages по гравитации команды, каздеву и проклятым проблемам, а также перепрошил ключевые canonical pages через retention-layer, антигравитационные силы и зрелую методику стратсессий. Обновил source pages модулей 1-2, entity page Гребенюка, общий HR synthesis, `index.md`, а stale recent-file references на временный raw-path и исходный `.txt` после перемещения raw source в `raw/inbox/` были очищены из [[.obsidian/workspace.json]].

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-3]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-1]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-2]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-hr-modul-3]]
- [[wiki/concepts/leadership/gravitaciya-komandy]]
- [[wiki/concepts/leadership/kazdev]]
- [[wiki/concepts/business/proklyatye-problemy]]
- [[wiki/concepts/business/stratsessii]]
- [[wiki/concepts/leadership/hr-otdel]]
- [[wiki/concepts/leadership/adaptaciya-sotrudnikov]]
- [[wiki/concepts/leadership/boevoi-duh-komandy]]
- [[wiki/concepts/leadership/spravedlivaya-motivaciya]]
- [[wiki/concepts/leadership/upravlenie]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[wiki/syntheses/leadership/freymvork-realnogo-hr-grebenyuka]]
- [[index]]

## [2026-04-08 15:47] ingest | Мастер-класс «Реальный миллион» — полная сводка

Summary: Нормализовал новый русский raw `.txt` в канонический `.md`, заингестил его как отдельный Grebenyuk branch про owner-growth и затем переместил финальный raw source в `raw/inbox/`. Вынес из source отдельные durable pages по мышлению и деньгам, отстрелу балласта, `5 единичкам`, флажкам роста, налогу учредителя и метафоре «команда не семья», а также собрал новый synthesis `Фреймворк «Реального миллиона»`. Параллельно углубил уже существующие canonical pages по business strategy, framework-driven action, управлению, делегированию и entity page Михаила Гребенюка, чтобы ключевые идеи source не остались локально внутри одной source note. Обновил `index.md`, а stale recent-file references на временный raw-path и исходный `.txt` убрал из [[.obsidian/workspace.json]].

Pages touched:

- [[raw/inbox/2026-04-08-mikhail-grebenyuk-realnyi-million]]
- [[wiki/sources/2026-04-08-mikhail-grebenyuk-realnyi-million]]
- [[wiki/concepts/business/myshlenie-i-dengi]]
- [[wiki/concepts/business/otstrel-ballasta]]
- [[wiki/concepts/business/pyat-edinichek]]
- [[wiki/concepts/business/flazhki-rosta]]
- [[wiki/concepts/business/nalog-uchreditelya]]
- [[wiki/concepts/leadership/komanda-ne-semya]]
- [[wiki/syntheses/business/freymvork-realnogo-milliona-grebenyuka]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/leadership/upravlenie]]
- [[wiki/concepts/leadership/delegirovanie-i-kontrol]]
- [[wiki/entities/mikhail-grebenyuk]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 16:10] admin | Add Health Domain Folder

Summary: Added a dedicated `health/` domain to the vault structure for upcoming health-related ingests. Created `wiki/concepts/health/` and `wiki/syntheses/health/`, updated `AGENTS.md` so health topics now route there by default, and clarified that health material should no longer fall back into `others/` unless explicitly justified.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-08 22:36] ingest | Rhonda Patrick Sleep Tips

Summary: Ingested a new English health source as the first real branch inside the `health/` domain, then moved the canonical raw file into `raw/inbox/`. Created a source page, a Rhonda Patrick entity page, canonical health concepts for sleep quality, circadian alignment, nighttime awakenings, and sleep supplementation, and a reusable synthesis page for the overall sleep protocol. Also updated [[wiki/concepts/leadership/high-performance-mindset]] so the vault's performance branch now links recovery to a more concrete physiological sleep layer instead of leaving it abstract.

Pages touched:

- [[raw/inbox/2026-04-08-rhonda-patrick-sleep-tips]]
- [[wiki/sources/2026-04-08-rhonda-patrick-sleep-tips]]
- [[wiki/entities/rhonda-patrick]]
- [[wiki/concepts/health/sleep-quality]]
- [[wiki/concepts/health/circadian-alignment]]
- [[wiki/concepts/health/sleep-supplementation]]
- [[wiki/concepts/health/nighttime-awakenings]]
- [[wiki/syntheses/health/rhonda-patrick-sleep-protocol]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 23:19] ingest | Michael Greger Plant-Based Nutrition

Summary: Ingested a new English health source as the vault's first nutrition-centered branch, then moved the canonical raw file into `raw/inbox/`. Created a source page, a Michael Greger entity page, canonical health concepts for whole-food plant-based diet, diet and chronic disease, lifestyle medicine, `Daily Dozen`, and healthspan, plus a reusable synthesis page for the overall preventive-health framework. Also updated [[wiki/concepts/health/sleep-quality]] so the existing sleep branch now links forward into a broader healthspan model instead of remaining isolated as a recovery-only note, and removed stale raw-root references from [[.obsidian/workspace.json]] after archiving the source.

Pages touched:

- [[raw/inbox/2026-04-08-michael-greger-plant-based-nutrition]]
- [[wiki/sources/2026-04-08-michael-greger-plant-based-nutrition]]
- [[wiki/entities/michael-greger]]
- [[wiki/concepts/health/whole-food-plant-based-diet]]
- [[wiki/concepts/health/diet-and-chronic-disease]]
- [[wiki/concepts/health/lifestyle-medicine]]
- [[wiki/concepts/health/daily-dozen]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/concepts/health/sleep-quality]]
- [[wiki/syntheses/health/michael-greger-nutrition-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 23:41] ingest | Longevity Health Tips Composite Summary

Summary: Ingested a new English health source as a mixed longevity branch, then moved the canonical raw file into `raw/inbox/`. Because the raw file was not a clean single-speaker transcript, I treated it as a composite secondary summary: extracted a David Sinclair-centered aging layer around aging as disease and the information theory of aging, created a practical longevity layer around fundamentals and biohack skepticism, and preserved the source-level caveat that later sections blend broader health advice and duplicate some of the existing sleep branch. I also updated [[wiki/concepts/health/healthspan]] so the health domain now shows a clearer three-way overlap between sleep, nutrition, and longevity, created a new cross-source synthesis at [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]], and removed stale raw-root references from [[.obsidian/workspace.json]] after archiving the source.

Pages touched:

- [[raw/inbox/2026-04-08-longevity-health-tips-composite-summary]]
- [[wiki/sources/2026-04-08-longevity-health-tips-composite-summary]]
- [[wiki/entities/david-sinclair]]
- [[wiki/concepts/health/aging-as-disease]]
- [[wiki/concepts/health/information-theory-of-aging]]
- [[wiki/concepts/health/longevity-fundamentals]]
- [[wiki/concepts/health/biohack-skepticism]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/syntheses/health/longevity-health-fundamentals-framework]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-08 23:53] ingest | Pavel Tsatsouline Strength and Conditioning

Summary: Ingested a new English health source as the vault's first explicit strength-training branch, then moved the canonical raw file into `raw/inbox/`. Created a source page, a Pavel Tsatsouline entity page, canonical health concepts for strength training, minimal effective dose training, `greasing the groove`, and recovery plus heterochronicity, and a reusable synthesis page for the overall strength-and-conditioning framework. I also updated [[wiki/concepts/health/longevity-fundamentals]], [[wiki/concepts/health/healthspan]], and the existing cross-source synthesis [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health domain now includes a clearer movement-capacity layer instead of treating exercise as a generic recommendation, and removed stale raw-root references from [[.obsidian/workspace.json]] after archiving the source.

Pages touched:

- [[raw/inbox/2026-04-08-pavel-tsatsouline-strength-and-conditioning]]
- [[wiki/sources/2026-04-08-pavel-tsatsouline-strength-and-conditioning]]
- [[wiki/entities/pavel-tsatsouline]]
- [[wiki/concepts/health/strength-training]]
- [[wiki/concepts/health/minimal-effective-dose-training]]
- [[wiki/concepts/health/greasing-the-groove]]
- [[wiki/concepts/health/recovery-and-heterochronicity]]
- [[wiki/concepts/health/longevity-fundamentals]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/syntheses/health/pavel-tsatsouline-strength-framework]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:02] ingest | Keep Your Brain Sharp at 90 Summary

Summary: Ingested a new English health source as a brain-health and cognitive-aging branch, then moved the canonical raw file into `raw/inbox/`. Created a source page plus canonical health concepts for brain health and cognitive aging, aerobic exercise and brain health, glymphatic clearance, and multivitamins plus cognition, along with a reusable synthesis page for the overall brain-sharpness protocol. I also updated [[wiki/concepts/health/sleep-quality]], [[wiki/concepts/health/longevity-fundamentals]], [[wiki/concepts/health/healthspan]], and the existing cross-source synthesis [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health domain now shows a clearer cognitive endpoint for why sleep, exercise, and long-horizon prevention matter, and removed stale raw-root references from [[.obsidian/workspace.json]] after archiving the source.

Pages touched:

- [[raw/inbox/2026-04-08-keep-your-brain-sharp-at-90-summary]]
- [[wiki/sources/2026-04-08-keep-your-brain-sharp-at-90-summary]]
- [[wiki/concepts/health/brain-health-and-cognitive-aging]]
- [[wiki/concepts/health/aerobic-exercise-and-brain-health]]
- [[wiki/concepts/health/glymphatic-clearance]]
- [[wiki/concepts/health/multivitamins-and-cognition]]
- [[wiki/concepts/health/sleep-quality]]
- [[wiki/concepts/health/longevity-fundamentals]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/syntheses/health/brain-sharpness-at-90-protocol]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:15] ingest | Harry Dry Copywriting Tips

Summary: Ingested a new English business and communication source as the vault's first explicit copywriting branch, then moved the canonical raw file into `raw/inbox/`. Created a source page, a Harry Dry entity page, canonical pages for [[wiki/concepts/business/copywriting]] and [[wiki/concepts/communication/concrete-specificity]], plus a reusable synthesis page for the overall copywriting framework. I also updated [[wiki/concepts/business/advertising]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/persuasion]], and [[wiki/syntheses/cross-source/communication-and-influence-models]] so the vault now has a clearer written-persuasion layer built around vivid specificity, falsifiable claims, and brand-distinctive truth, and removed stale raw-root references from [[.obsidian/workspace.json]] after archiving the source.

Pages touched:

- [[raw/inbox/2026-04-09-harry-dry-copywriting-tips]]
- [[wiki/sources/2026-04-09-harry-dry-copywriting-tips]]
- [[wiki/entities/harry-dry]]
- [[wiki/concepts/business/copywriting]]
- [[wiki/concepts/communication/concrete-specificity]]
- [[wiki/concepts/business/advertising]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/syntheses/business/harry-dry-copywriting-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:20] admin | Add Chess and Productivity Domains

Summary: Added dedicated `chess/` and `productivity/` domain folders to the wiki structure so future ingests no longer have to fall back to `others/` for these branches. Created the new concept and synthesis directories, updated [[AGENTS]] so both domains are part of the official folder taxonomy and default routing rules, and recorded the routing expectations for future ingests.

Pages touched:

- [[AGENTS]]
- [[log]]

## [2026-04-09 00:36] ingest | GothamChess Beginner Chess Guide

Summary: Ingested a second English GothamChess source into the existing chess branch, then moved the canonical raw file into `raw/inbox/`. Created a new source page and new canonical chess concepts for [[wiki/concepts/chess/board-vision]], [[wiki/concepts/chess/trade-evaluation]], and [[wiki/concepts/chess/time-management-in-chess]], then deepened [[wiki/entities/gothamchess]], [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/tactical-awareness]], [[wiki/concepts/chess/endgame-conversion]], and [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]] so the branch now captures beginner anti-blunder discipline rather than only phase-level play. The source was treated as a secondary summary with encoding artifacts, and stale raw-root references were removed from [[.obsidian/workspace.json]] after archiving.

Pages touched:

- [[raw/inbox/2026-04-09-gothamchess-beginner-chess-guide]]
- [[wiki/sources/2026-04-09-gothamchess-beginner-chess-guide]]
- [[wiki/entities/gothamchess]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/board-vision]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/time-management-in-chess]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:42] ingest | Chess Calculation Guide

Summary: Ingested a new English chess-calculation source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a canonical concept page at [[wiki/concepts/chess/calculation-in-chess]], and a reusable synthesis page at [[wiki/syntheses/chess/chess-calculation-process]], then deepened [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/board-vision]], [[wiki/concepts/chess/time-management-in-chess]], and [[wiki/concepts/chess/tactical-awareness]] so the chess branch now distinguishes tactical scanning from fuller candidate-move calculation and opponent-best-response testing. The source was left unattributed at the entity layer because the raw summary did not clearly identify a named teacher, and stale raw-root references were removed from [[.obsidian/workspace.json]] after archiving.

Pages touched:

- [[raw/inbox/2026-04-09-chess-calculation-guide]]
- [[wiki/sources/2026-04-09-chess-calculation-guide]]
- [[wiki/concepts/chess/calculation-in-chess]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/board-vision]]
- [[wiki/concepts/chess/time-management-in-chess]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/chess-calculation-process]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:49] ingest | John Bartholomew Trades in Chess

Summary: Ingested a new English chess source by John Bartholomew and moved the canonical raw file into `raw/inbox/`. Created a new source page, a John Bartholomew entity page, and a reusable synthesis page at [[wiki/syntheses/chess/john-bartholomew-trade-discipline-framework]], then deepened [[wiki/concepts/chess/trade-evaluation]], [[wiki/concepts/chess/calculation-in-chess]], [[wiki/concepts/chess/endgame-conversion]], and [[wiki/concepts/chess/chess]] so the branch now treats exchanges less as simplification and more as structure-aware, activity-aware, and tactic-sensitive decisions. Stale raw-root references for both the current John source and the prior calculation source were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-trades-in-chess]]
- [[wiki/sources/2026-04-09-john-bartholomew-trades-in-chess]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/calculation-in-chess]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/concepts/chess/chess]]
- [[wiki/syntheses/chess/john-bartholomew-trade-discipline-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 00:59] ingest | John Bartholomew Pawn Play in Chess

Summary: Ingested a new English chess source by John Bartholomew and moved the canonical raw file into `raw/inbox/`. Created a new source page, new canonical chess concepts for [[wiki/concepts/chess/pawn-play]], [[wiki/concepts/chess/pawn-breaks]], and [[wiki/concepts/chess/pawn-structure-weaknesses]], plus a reusable synthesis page at [[wiki/syntheses/chess/john-bartholomew-pawn-play-framework]]. I also deepened [[wiki/entities/john-bartholomew]], [[wiki/concepts/chess/trade-evaluation]], and [[wiki/concepts/chess/chess]] so the chess branch now includes an explicit structural layer around isolated, doubled, and backward pawns, hooks, and break preparation rather than treating pawn play as background. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-pawn-play-in-chess]]
- [[wiki/sources/2026-04-09-john-bartholomew-pawn-play-in-chess]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/pawn-play]]
- [[wiki/concepts/chess/pawn-breaks]]
- [[wiki/concepts/chess/pawn-structure-weaknesses]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/chess]]
- [[wiki/syntheses/chess/john-bartholomew-pawn-play-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:05] ingest | John Bartholomew Beginner Chess Mistakes

Summary: Ingested a new English chess source by John Bartholomew and moved the canonical raw file into `raw/inbox/`. Created a new source page, new canonical chess concepts for [[wiki/concepts/chess/piece-coordination]] and [[wiki/concepts/chess/weak-squares-and-outposts]], plus a reusable synthesis page at [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]. I also deepened [[wiki/entities/john-bartholomew]], [[wiki/concepts/chess/board-vision]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/pawn-breaks]], and [[wiki/concepts/chess/tactical-awareness]] so the branch now captures beginner mistake patterns around opponent threats, loose pieces, sequencing, strategic squares, and development-to-break conversion. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-beginner-chess-mistakes]]
- [[wiki/sources/2026-04-09-john-bartholomew-beginner-chess-mistakes]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/piece-coordination]]
- [[wiki/concepts/chess/weak-squares-and-outposts]]
- [[wiki/concepts/chess/board-vision]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/pawn-breaks]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:11] ingest | Essential Chess Principles

Summary: Ingested a new English generic chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a canonical concept page at [[wiki/concepts/chess/piece-activity]], and a reusable synthesis page at [[wiki/syntheses/chess/essential-chess-principles-framework]], then deepened [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/piece-coordination]], [[wiki/concepts/chess/pawn-structure-weaknesses]], [[wiki/concepts/chess/trade-evaluation]], [[wiki/concepts/chess/endgame-conversion]], [[wiki/concepts/chess/calculation-in-chess]], and [[wiki/concepts/chess/tactical-awareness]] so the chess branch now has a clearer principle-level map of activity, structure, exchanges, endgame technique, and anti-"hope chess" discipline. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-essential-chess-principles]]
- [[wiki/sources/2026-04-09-essential-chess-principles]]
- [[wiki/concepts/chess/piece-activity]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/piece-coordination]]
- [[wiki/concepts/chess/pawn-structure-weaknesses]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/concepts/chess/calculation-in-chess]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/essential-chess-principles-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:21] ingest | John Bartholomew Piece and Pawn Coordination

Summary: Ingested a new English John Bartholomew chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a canonical concept page at [[wiki/concepts/chess/development-tempo]], and a reusable synthesis page at [[wiki/syntheses/chess/john-bartholomew-coordination-framework]], then deepened [[wiki/entities/john-bartholomew]], [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/piece-coordination]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/pawn-play]], [[wiki/concepts/chess/trade-evaluation]], and [[wiki/concepts/chess/tactical-awareness]] so the chess branch now has a clearer coordination layer around pawn restraint, development lag, undefended pieces, and mini-goal recovery. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-piece-and-pawn-coordination]]
- [[wiki/sources/2026-04-09-john-bartholomew-piece-and-pawn-coordination]]
- [[wiki/concepts/chess/development-tempo]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/piece-coordination]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/pawn-play]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/john-bartholomew-coordination-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:26] ingest | John Bartholomew Recurring Beginner Chess Mistakes

Summary: Ingested a new English John Bartholomew chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page and deepened the existing beginner-improvement cluster instead of spawning a duplicate branch: updated [[wiki/entities/john-bartholomew]], [[wiki/concepts/chess/piece-coordination]], [[wiki/concepts/chess/development-tempo]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/pawn-breaks]], [[wiki/concepts/chess/weak-squares-and-outposts]], [[wiki/concepts/chess/tactical-awareness]], [[wiki/concepts/chess/calculation-in-chess]], and [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]. The main gain is a sharper case-study layer around forcing-reply blindness, development-sensitive pawn-break timing, weak-square creation, and recurring club-level planning errors. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-bartholomew-recurring-beginner-chess-mistakes]]
- [[wiki/sources/2026-04-09-john-bartholomew-recurring-beginner-chess-mistakes]]
- [[wiki/entities/john-bartholomew]]
- [[wiki/concepts/chess/piece-coordination]]
- [[wiki/concepts/chess/development-tempo]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/pawn-breaks]]
- [[wiki/concepts/chess/weak-squares-and-outposts]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/concepts/chess/calculation-in-chess]]
- [[wiki/syntheses/chess/john-bartholomew-beginner-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:32] ingest | GothamChess Essential Chess Tips

Summary: Ingested a new English GothamChess chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page and a canonical concept page at [[wiki/concepts/chess/imbalances-in-chess]], then deepened [[wiki/entities/gothamchess]], [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/opening-preparation]], [[wiki/concepts/chess/trade-evaluation]], [[wiki/concepts/chess/tactical-awareness]], and [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]. The main gain is a stronger planning layer around opening-to-middlegame continuity, imbalance recognition, attack conditions, repertoire depth, and calm principled play against offbeat moves. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-gothamchess-essential-chess-tips]]
- [[wiki/sources/2026-04-09-gothamchess-essential-chess-tips]]
- [[wiki/concepts/chess/imbalances-in-chess]]
- [[wiki/entities/gothamchess]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/opening-preparation]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/tactical-awareness]]
- [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 01:38] ingest | GothamChess Beating Beginner Chess Bots

Summary: Ingested a new English GothamChess chess source and moved the canonical raw file into `raw/inbox/`. Created a new source page plus a canonical concept page at [[wiki/concepts/chess/training-with-chess-bots]], then deepened [[wiki/entities/gothamchess]], [[wiki/concepts/chess/chess]], [[wiki/concepts/chess/trade-evaluation]], [[wiki/concepts/chess/time-management-in-chess]], [[wiki/concepts/chess/endgame-conversion]], and [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]. The main gain is a clearer training-context layer around principled play versus weak bots, simplification when ahead, conversion drills, and the warning that bots should support learning rather than replace human opponents and analysis. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-gothamchess-beating-beginner-chess-bots]]
- [[wiki/sources/2026-04-09-gothamchess-beating-beginner-chess-bots]]
- [[wiki/concepts/chess/training-with-chess-bots]]
- [[wiki/entities/gothamchess]]
- [[wiki/concepts/chess/chess]]
- [[wiki/concepts/chess/trade-evaluation]]
- [[wiki/concepts/chess/time-management-in-chess]]
- [[wiki/concepts/chess/endgame-conversion]]
- [[wiki/syntheses/chess/gothamchess-practical-improvement-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 09:55] ingest | RICECO Prompt Framework

Summary: Ingested a new English AI prompting source and moved the canonical raw file into `raw/inbox/`. Created a new source page, canonical concept pages at [[wiki/concepts/ai/prompt-engineering]], [[wiki/concepts/ai/riceco-prompt-framework]], and [[wiki/concepts/ai/few-shot-prompting]], plus a synthesis page at [[wiki/syntheses/ai/prompt-design-workflow]]. Then deepened [[wiki/concepts/ai/large-language-models]], [[wiki/concepts/ai/fine-tuning]], and [[wiki/syntheses/ai/ai-stack-overview]]. The main gain is the first practical AI-use layer in the vault: structured prompting, examples, constraints, output formatting, and iteration as reusable workflow elements. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-riceco-prompt-framework]]
- [[wiki/sources/2026-04-09-riceco-prompt-framework]]
- [[wiki/concepts/ai/prompt-engineering]]
- [[wiki/concepts/ai/riceco-prompt-framework]]
- [[wiki/concepts/ai/few-shot-prompting]]
- [[wiki/concepts/ai/large-language-models]]
- [[wiki/concepts/ai/fine-tuning]]
- [[wiki/syntheses/ai/prompt-design-workflow]]
- [[wiki/syntheses/ai/ai-stack-overview]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 09:22] ingest | Google Beginner AI Course

Summary: Ingested a new English AI foundations source and moved the canonical raw file into `raw/inbox/`. Created a new source page, a new entity page at [[wiki/entities/google]], six core AI concept pages at [[wiki/concepts/ai/artificial-intelligence]], [[wiki/concepts/ai/machine-learning]], [[wiki/concepts/ai/deep-learning]], [[wiki/concepts/ai/generative-ai]], [[wiki/concepts/ai/large-language-models]], [[wiki/concepts/ai/supervised-and-unsupervised-learning]], plus [[wiki/concepts/ai/fine-tuning]], and added a synthesis page at [[wiki/syntheses/ai/ai-stack-overview]]. The main gain is the first structured AI branch in the vault: a durable hierarchy linking AI, ML, deep learning, generative AI, LLMs, supervision, and fine-tuning. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-google-beginner-ai-course]]
- [[wiki/sources/2026-04-09-google-beginner-ai-course]]
- [[wiki/entities/google]]
- [[wiki/concepts/ai/artificial-intelligence]]
- [[wiki/concepts/ai/machine-learning]]
- [[wiki/concepts/ai/deep-learning]]
- [[wiki/concepts/ai/generative-ai]]
- [[wiki/concepts/ai/large-language-models]]
- [[wiki/concepts/ai/supervised-and-unsupervised-learning]]
- [[wiki/concepts/ai/fine-tuning]]
- [[wiki/syntheses/ai/ai-stack-overview]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:02] ingest | Jeremy Utley AI Creativity and Productivity

Summary: Ingested a new English AI-collaboration source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]], a new entity page at [[wiki/entities/jeremy-utley]], two new concept pages at [[wiki/concepts/ai/context-engineering]] and [[wiki/concepts/ai/reverse-prompting]], and a new synthesis page at [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework]]. Deepened [[wiki/concepts/ai/prompt-engineering]], [[wiki/concepts/ai/few-shot-prompting]], and [[wiki/syntheses/ai/prompt-design-workflow]] so the AI branch now captures coaching-style model use, context-rich briefing, clarifying-question loops, examples, critique, and iteration as a compiled collaboration model. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-jeremy-utley-ai-creativity-and-productivity]]
- [[wiki/sources/2026-04-09-jeremy-utley-ai-creativity-and-productivity]]
- [[wiki/entities/jeremy-utley]]
- [[wiki/concepts/ai/context-engineering]]
- [[wiki/concepts/ai/reverse-prompting]]
- [[wiki/concepts/ai/prompt-engineering]]
- [[wiki/concepts/ai/few-shot-prompting]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework]]
- [[wiki/syntheses/ai/prompt-design-workflow]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:14] ingest | John Truby Screenwriting and Story Structure

Summary: Ingested a new English screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-john-truby-screenwriting-and-story-structure]], a new entity page at [[wiki/entities/john-truby]], two new concept pages at [[wiki/concepts/filmmaking/genre-mastery]] and [[wiki/concepts/filmmaking/premise-testing]], and a new synthesis page at [[wiki/syntheses/filmmaking/john-truby-story-architecture-framework]]. Deepened [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/three-act-structure]], [[wiki/concepts/filmmaking/writing-process-and-revision]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures genre-first design, premise stress-testing, anti-formula structure, and the link between character weakness and plot architecture. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-truby-screenwriting-and-story-structure]]
- [[wiki/sources/2026-04-09-john-truby-screenwriting-and-story-structure]]
- [[wiki/entities/john-truby]]
- [[wiki/concepts/filmmaking/genre-mastery]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/john-truby-story-architecture-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:33] ingest | John Truby Screenwriting Mastery and Endurance

Summary: Ingested a second English Truby source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-john-truby-screenwriting-mastery-and-endurance]], a new concept page at [[wiki/concepts/filmmaking/craft-mastery]], and a new synthesis page at [[wiki/syntheses/filmmaking/john-truby-screenwriting-mastery-model]]. Deepened [[wiki/entities/john-truby]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/three-act-structure]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures undertraining risk, anti-shortcut learning, long-horizon creative endurance, and the distinction between access problems and craft problems. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-john-truby-screenwriting-mastery-and-endurance]]
- [[wiki/sources/2026-04-09-john-truby-screenwriting-mastery-and-endurance]]
- [[wiki/entities/john-truby]]
- [[wiki/concepts/filmmaking/craft-mastery]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/syntheses/filmmaking/john-truby-screenwriting-mastery-model]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:41] ingest | Storytelling Core Elements and Writing Process

Summary: Ingested a new English storytelling source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-storytelling-core-elements-and-writing-process]] and a new concept page at [[wiki/concepts/filmmaking/transformation-in-storytelling]]. Deepened [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/syntheses/filmmaking/screenplay-starting-checklist]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures transformation as story purpose, logline-as-north-star development, diagnostic self-questioning, and the rule that scenes must advance goal, conflict, or stakes. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-storytelling-core-elements-and-writing-process]]
- [[wiki/sources/2026-04-09-storytelling-core-elements-and-writing-process]]
- [[wiki/concepts/filmmaking/transformation-in-storytelling]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/screenplay-starting-checklist]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:49] ingest | William C. Martell How Is This My Story

Summary: Ingested a new English screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-william-c-martell-how-is-this-my-story]], a new entity page at [[wiki/entities/william-c-martell]], a new concept page at [[wiki/concepts/filmmaking/personal-doorway]], and a new synthesis page at [[wiki/syntheses/filmmaking/william-c-martell-personal-doorway-framework]]. Deepened [[wiki/concepts/creativity/creative-integrity]], [[wiki/concepts/filmmaking/writer-worldview]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures assignment authenticity, project fit, doorway-based reframing, and the rule that commercial work still needs a real emotional angle. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-william-c-martell-how-is-this-my-story]]
- [[wiki/sources/2026-04-09-william-c-martell-how-is-this-my-story]]
- [[wiki/entities/william-c-martell]]
- [[wiki/concepts/filmmaking/personal-doorway]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/writer-worldview]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/william-c-martell-personal-doorway-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 10:58] ingest | Jeff Deverett Getting an Indie Film onto Netflix

Summary: Ingested a new English filmmaking-distribution source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-jeff-deverett-getting-an-indie-film-onto-netflix]], a new entity page at [[wiki/entities/jeff-deverett]], a new concept page at [[wiki/concepts/filmmaking/film-distribution]], and a new synthesis page at [[wiki/syntheses/filmmaking/jeff-deverett-netflix-distribution-framework]]. Deepened [[wiki/concepts/business/creative-pitching]] and [[wiki/concepts/filmmaking/filmmaking]] so the filmmaking branch now includes the commercial delivery layer: compressed platform pitching, distributor bottlenecks, technical delivery requirements, credibility as an asset, and persistence through gatekeeping. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-jeff-deverett-getting-an-indie-film-onto-netflix]]
- [[wiki/sources/2026-04-09-jeff-deverett-getting-an-indie-film-onto-netflix]]
- [[wiki/entities/jeff-deverett]]
- [[wiki/concepts/filmmaking/film-distribution]]
- [[wiki/concepts/business/creative-pitching]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/jeff-deverett-netflix-distribution-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 11:17] ingest | Screenwriting Roundtable on Avoiding Boring Scripts

Summary: Ingested a new English screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-screenwriting-roundtable-on-avoiding-boring-scripts]], a new concept page at [[wiki/concepts/filmmaking/arena-vs-story]], and a new synthesis page at [[wiki/syntheses/filmmaking/screenwriting-anti-boredom-framework]]. Deepened [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/writing-process-and-revision]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures arena-versus-story diagnosis, anti-cliche ideation drills, public-versus-private character pressure, and a stronger model of how scripts become boring before or during drafting. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-screenwriting-roundtable-on-avoiding-boring-scripts]]
- [[wiki/sources/2026-04-09-screenwriting-roundtable-on-avoiding-boring-scripts]]
- [[wiki/concepts/filmmaking/arena-vs-story]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/screenwriting-anti-boredom-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 11:37] ingest | Screenwriting Roundtable on Dialogue Craft

Summary: Ingested a new English screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-screenwriting-roundtable-on-dialogue-craft]], a new concept page at [[wiki/concepts/filmmaking/visual-storytelling-first]], and a new synthesis page at [[wiki/syntheses/filmmaking/screenwriting-dialogue-craft-framework]]. Deepened [[wiki/concepts/filmmaking/dialogue-as-music]], [[wiki/concepts/filmmaking/text-and-subtext]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/writing-process-and-revision]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures visual-first scene design, objective-driven lines, subtext through misunderstanding, ruthless trimming, and dialogue revision through the ear. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-screenwriting-roundtable-on-dialogue-craft]]
- [[wiki/sources/2026-04-09-screenwriting-roundtable-on-dialogue-craft]]
- [[wiki/concepts/filmmaking/visual-storytelling-first]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/text-and-subtext]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/screenwriting-dialogue-craft-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:17] ingest | Chris Gore Hollywood Studio System and Indie Film

Summary: Ingested a new English filmmaking-culture source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chris-gore-hollywood-studio-system-and-indie-film]], a new entity page at [[wiki/entities/chris-gore]], a new concept page at [[wiki/concepts/filmmaking/factory-filmmaking]], and a new synthesis page at [[wiki/syntheses/filmmaking/chris-gore-hollywood-and-indie-framework]]. Deepened [[wiki/concepts/filmmaking/audience-as-collaborator]], [[wiki/concepts/creativity/creative-integrity]], [[wiki/concepts/filmmaking/character-driven-storytelling]], and [[wiki/concepts/filmmaking/filmmaking]] so the vault now captures studio-system risk aversion, audience sophistication, indie film as a corrective, and the distinction between creator-led work and franchise-factory maintenance. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chris-gore-hollywood-studio-system-and-indie-film]]
- [[wiki/sources/2026-04-09-chris-gore-hollywood-studio-system-and-indie-film]]
- [[wiki/entities/chris-gore]]
- [[wiki/concepts/filmmaking/factory-filmmaking]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/chris-gore-hollywood-and-indie-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:39] ingest | Glenn Gers Six Essential Story Questions

Summary: Ingested a new English storytelling and screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-glenn-gers-six-essential-story-questions]], a new entity page at [[wiki/entities/glenn-gers]], a new concept page at [[wiki/concepts/filmmaking/six-essential-story-questions]], and a new synthesis page at [[wiki/syntheses/filmmaking/glenn-gers-story-questions-framework]]. Deepened [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures Gers's six-question diagnostic, theory-of-mind characterization, and a more adaptive iterative-process model. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-glenn-gers-six-essential-story-questions]]
- [[wiki/sources/2026-04-09-glenn-gers-six-essential-story-questions]]
- [[wiki/entities/glenn-gers]]
- [[wiki/concepts/filmmaking/six-essential-story-questions]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/glenn-gers-story-questions-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:46] ingest | Michael Hauge Act One Foundation and Outer Motivation

Summary: Ingested a new English screenwriting source focused on Act 1 and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-michael-hauge-act-one-foundation-and-outer-motivation]], a new entity page at [[wiki/entities/michael-hauge]], a new concept page at [[wiki/concepts/filmmaking/outer-motivation]], and a new synthesis page at [[wiki/syntheses/filmmaking/michael-hauge-act-one-foundation-framework]]. Deepened [[wiki/concepts/filmmaking/three-act-structure]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/intention-and-obstacle]], [[wiki/concepts/filmmaking/character-driven-storytelling]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures Hauge's first-act diagnostic around empathy-first setup, visible finish lines, and the risk of rushing the story launch. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-michael-hauge-act-one-foundation-and-outer-motivation]]
- [[wiki/sources/2026-04-09-michael-hauge-act-one-foundation-and-outer-motivation]]
- [[wiki/entities/michael-hauge]]
- [[wiki/concepts/filmmaking/outer-motivation]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/intention-and-obstacle]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/syntheses/filmmaking/michael-hauge-act-one-foundation-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:56] ingest | David Lynch Screenwriting Skeletons and Scene Cards

Summary: Ingested a new English David Lynch screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-david-lynch-screenwriting-skeletons-and-scene-cards]] and a new concept page at [[wiki/concepts/filmmaking/scene-card-method]]. Deepened [[wiki/entities/david-lynch]], [[wiki/concepts/creativity/idea-development]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/syntheses/creativity/lynch-creative-framework]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the Lynch branch now captures skeletal drafting, 3x5 scene cards, lightweight structural scaffolding, and a clearer bridge between intuition and practical screenwriting. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-david-lynch-screenwriting-skeletons-and-scene-cards]]
- [[wiki/sources/2026-04-09-david-lynch-screenwriting-skeletons-and-scene-cards]]
- [[wiki/concepts/filmmaking/scene-card-method]]
- [[wiki/entities/david-lynch]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/creativity/lynch-creative-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:12] ingest | Simon Rich Comedy Premise Generation

Summary: Ingested a new English Simon Rich writing source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-simon-rich-comedy-premise-generation]], a new entity page at [[wiki/entities/simon-rich]], a new concept page at [[wiki/concepts/filmmaking/premise-generation]], and a new synthesis page at [[wiki/syntheses/filmmaking/simon-rich-comedy-premise-framework]]. Deepened [[wiki/concepts/creativity/idea-development]], [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures high-volume premise generation, playful ideation frameworks, abundance-before-filtering, and the upstream difference between generating ideas and testing them. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-simon-rich-comedy-premise-generation]]
- [[wiki/sources/2026-04-09-simon-rich-comedy-premise-generation]]
- [[wiki/entities/simon-rich]]
- [[wiki/concepts/filmmaking/premise-generation]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/simon-rich-comedy-premise-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:26] ingest | Eric Edson Screenplay Structure and Hero Goal Sequence

Summary: Ingested a new English screenwriting-structure source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-eric-edson-screenplay-structure-and-hero-goal-sequence]], a new entity page at [[wiki/entities/eric-edson]], a new concept page at [[wiki/concepts/filmmaking/hero-goal-sequence]], and a new synthesis page at [[wiki/syntheses/filmmaking/eric-edson-hero-goal-sequence-framework]]. Deepened [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/three-act-structure]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/writing-process-and-revision]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures Hero Goal Sequence logic, `three worlds`, stunning-surprise act turns, active-hero pressure, and a more explicit sequence-level audit for stalled drafts. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-eric-edson-screenplay-structure-and-hero-goal-sequence]]
- [[wiki/sources/2026-04-09-eric-edson-screenplay-structure-and-hero-goal-sequence]]
- [[wiki/entities/eric-edson]]
- [[wiki/concepts/filmmaking/hero-goal-sequence]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/three-act-structure]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/eric-edson-hero-goal-sequence-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 12:33] ingest | Chris Gore Movie Quality Decline and Studio Malpractice

Summary: Ingested a second English Chris Gore filmmaking-culture source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chris-gore-movie-quality-decline-and-studio-malpractice]] and a new concept page at [[wiki/concepts/filmmaking/franchise-stewardship]]. Deepened [[wiki/entities/chris-gore]], [[wiki/concepts/filmmaking/factory-filmmaking]], [[wiki/concepts/filmmaking/audience-as-collaborator]], [[wiki/concepts/filmmaking/filmmaking]], and [[wiki/syntheses/filmmaking/chris-gore-hollywood-and-indie-framework]] so the Gore branch now captures studio malpractice, franchise stewardship failure, adaptation risk aversion, and the gap between marketing promise and actual film quality. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chris-gore-movie-quality-decline-and-studio-malpractice]]
- [[wiki/sources/2026-04-09-chris-gore-movie-quality-decline-and-studio-malpractice]]
- [[wiki/entities/chris-gore]]
- [[wiki/concepts/filmmaking/franchise-stewardship]]
- [[wiki/concepts/filmmaking/factory-filmmaking]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/chris-gore-hollywood-and-indie-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:19] ingest | Succession Writers' Room Methodology

Summary: Ingested a new English television-writing source about `Succession` and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-succession-writers-room-methodology]], a new entity page at [[wiki/entities/succession]], and a new synthesis page at [[wiki/syntheses/filmmaking/succession-writing-framework]]. Deepened [[wiki/concepts/filmmaking/writers-room-craft]], [[wiki/concepts/filmmaking/showrunning]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/dialogue-as-music]], [[wiki/concepts/filmmaking/text-and-subtext]], [[wiki/concepts/filmmaking/immersive-research]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the TV-writing branch now captures open-then-narrow room process, psychologically specific ensemble writing, anti-transferable humor, realism-through-research, and a stronger truthfulness standard. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-succession-writers-room-methodology]]
- [[wiki/sources/2026-04-09-succession-writers-room-methodology]]
- [[wiki/entities/succession]]
- [[wiki/concepts/filmmaking/writers-room-craft]]
- [[wiki/concepts/filmmaking/showrunning]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/text-and-subtext]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/succession-writing-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:27] ingest | Believable Character Writing Methodologies

Summary: Ingested a new English character-writing source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-believable-character-writing-methodologies]], a new concept page at [[wiki/concepts/filmmaking/character-interviews]], and a new synthesis page at [[wiki/syntheses/filmmaking/believable-character-writing-framework]]. Deepened [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/intention-and-obstacle]], [[wiki/concepts/filmmaking/immersive-research]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures empathy-for-every-character, hypocrisy as realism, multiple-POV depth, character interviews, and the difference between character dossiers and believable scene behavior. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-believable-character-writing-methodologies]]
- [[wiki/sources/2026-04-09-believable-character-writing-methodologies]]
- [[wiki/concepts/filmmaking/character-interviews]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/intention-and-obstacle]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/believable-character-writing-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:43] ingest | Screenwriters on Overcoming Writer's Block

Summary: Ingested a new English composite screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-screenwriters-on-overcoming-writers-block]], a new concept page at [[wiki/concepts/creativity/creative-incubation]], and a new synthesis page at [[wiki/syntheses/filmmaking/writers-block-recovery-framework]]. Deepened [[wiki/concepts/filmmaking/protect-the-process]], [[wiki/concepts/creativity/idea-development]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures writer's block normalization, project rotation, off-page incubation, and non-linear re-entry as canonical process knowledge rather than source-local advice. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-screenwriters-on-overcoming-writers-block]]
- [[wiki/sources/2026-04-09-screenwriters-on-overcoming-writers-block]]
- [[wiki/concepts/creativity/creative-incubation]]
- [[wiki/concepts/filmmaking/protect-the-process]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/filmmaking/writers-block-recovery-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:51] ingest | Bong Joon-Ho on Parasite and Story Construction

Summary: Ingested a new English filmmaking source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-bong-joon-ho-on-parasite-and-story-construction]], a new entity page at [[wiki/entities/bong-joon-ho]], a new concept page at [[wiki/concepts/filmmaking/spatial-storytelling]], and a new synthesis page at [[wiki/syntheses/filmmaking/bong-joon-ho-parasite-framework]]. Deepened [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/setting-as-character]], [[wiki/concepts/creativity/visual-literacy]], and [[wiki/concepts/filmmaking/filmmaking]] so the filmmaking branch now captures interaction-first characterization, moral ambiguity, family pressure, architectural suspense, and universality-through-specificity as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-bong-joon-ho-on-parasite-and-story-construction]]
- [[wiki/sources/2026-04-09-bong-joon-ho-on-parasite-and-story-construction]]
- [[wiki/entities/bong-joon-ho]]
- [[wiki/concepts/filmmaking/spatial-storytelling]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/setting-as-character]]
- [[wiki/concepts/creativity/visual-literacy]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/bong-joon-ho-parasite-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 13:58] ingest | Paul Thomas Anderson on Screenwriting and Storytelling

Summary: Ingested a new English screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-paul-thomas-anderson-on-screenwriting-and-storytelling]], a new entity page at [[wiki/entities/paul-thomas-anderson]], a new concept page at [[wiki/concepts/filmmaking/screenplay-economy]], and a new synthesis page at [[wiki/syntheses/filmmaking/paul-thomas-anderson-screenwriting-framework]]. Deepened [[wiki/concepts/creativity/creative-integrity]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/acting-craft]], [[wiki/concepts/filmmaking/casting-and-performance-direction]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the writing branch now captures personal rhythm, screenplay economy, productive imperfection, character pushback, and collaborative mutability as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-paul-thomas-anderson-on-screenwriting-and-storytelling]]
- [[wiki/sources/2026-04-09-paul-thomas-anderson-on-screenwriting-and-storytelling]]
- [[wiki/entities/paul-thomas-anderson]]
- [[wiki/concepts/filmmaking/screenplay-economy]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/acting-craft]]
- [[wiki/concepts/filmmaking/casting-and-performance-direction]]
- [[wiki/syntheses/filmmaking/paul-thomas-anderson-screenwriting-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 14:03] ingest | Aaron Sorkin on The Social Network

Summary: Ingested a new English Aaron Sorkin source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-aaron-sorkin-on-the-social-network]] and a new concept page at [[wiki/concepts/filmmaking/conflicting-perspectives]]. Deepened [[wiki/entities/aaron-sorkin]], [[wiki/syntheses/filmmaking/sorkin-screenwriting-framework]], [[wiki/concepts/filmmaking/audience-as-collaborator]], [[wiki/concepts/filmmaking/immersive-research]], [[wiki/concepts/filmmaking/intention-and-obstacle]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/dialogue-as-music]], and [[wiki/concepts/filmmaking/screenwriting]] so the Sorkin branch now captures conflicting narrators, evidence-backed ambiguity, audience autonomy, antihero empathy, and rehearsal-heavy dialogue precision as compiled vault knowledge rather than source-local notes. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-aaron-sorkin-on-the-social-network]]
- [[wiki/sources/2026-04-09-aaron-sorkin-on-the-social-network]]
- [[wiki/concepts/filmmaking/conflicting-perspectives]]
- [[wiki/entities/aaron-sorkin]]
- [[wiki/syntheses/filmmaking/sorkin-screenwriting-framework]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/filmmaking/intention-and-obstacle]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/dialogue-as-music]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 14:10] ingest | Todd Phillips on Joker

Summary: Ingested a new English Todd Phillips filmmaking source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-todd-phillips-on-joker]], a new entity page at [[wiki/entities/todd-phillips]], a new concept page at [[wiki/concepts/filmmaking/trojan-horse-storytelling]], and a new synthesis page at [[wiki/syntheses/filmmaking/todd-phillips-joker-framework]]. Deepened [[wiki/concepts/filmmaking/filmmaking]], [[wiki/concepts/filmmaking/factory-filmmaking]], [[wiki/concepts/creativity/creative-integrity]], [[wiki/concepts/filmmaking/character-driven-storytelling]], and [[wiki/concepts/filmmaking/genre-mastery]] so the filmmaking branch now captures comic-book property as strategic access, grounded villain-myth design, antihero empathy without absolution, and the contrast between Trojan-horse risk and factory-safe IP handling. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-todd-phillips-on-joker]]
- [[wiki/sources/2026-04-09-todd-phillips-on-joker]]
- [[wiki/entities/todd-phillips]]
- [[wiki/concepts/filmmaking/trojan-horse-storytelling]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/concepts/filmmaking/factory-filmmaking]]
- [[wiki/concepts/creativity/creative-integrity]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/genre-mastery]]
- [[wiki/syntheses/filmmaking/todd-phillips-joker-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 14:25] ingest | Creating The Sopranos

Summary: Ingested a new English television-writing source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-creating-the-sopranos]], a new entity page at [[wiki/entities/the-sopranos]], a new concept page at [[wiki/concepts/filmmaking/thematic-storyline-unity]], and a new synthesis page at [[wiki/syntheses/filmmaking/the-sopranos-writing-framework]]. Deepened [[wiki/concepts/filmmaking/showrunning]], [[wiki/concepts/filmmaking/writers-room-craft]], [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/audience-as-collaborator]], and [[wiki/concepts/filmmaking/screenplay-economy]] so the TV branch now captures anti-formula prestige storytelling, thematic A/B/C/D episode structure, anecdote-driven room discovery, morally ambiguous protagonists, and the refusal of least-offensive programming as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-creating-the-sopranos]]
- [[wiki/sources/2026-04-09-creating-the-sopranos]]
- [[wiki/entities/the-sopranos]]
- [[wiki/concepts/filmmaking/thematic-storyline-unity]]
- [[wiki/concepts/filmmaking/showrunning]]
- [[wiki/concepts/filmmaking/writers-room-craft]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/filmmaking/screenplay-economy]]
- [[wiki/syntheses/filmmaking/the-sopranos-writing-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 14:31] ingest | Screenwriters on Outlining Approaches

Summary: Ingested a new English composite screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-screenwriters-on-outlining-approaches]], a new canonical concept page at [[wiki/concepts/filmmaking/outline-flexibility]], and a new cross-source synthesis at [[wiki/syntheses/cross-source/screenwriting-outlining-models]]. Deepened [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/scene-card-method]], [[wiki/concepts/creativity/idea-development]], [[wiki/concepts/filmmaking/screenwriting]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures structure-first consensus, outline-density pluralism, cards-versus-beats-versus-sequences, pacing visibility, and the difference between useful structural heuristics and rigid orthodoxy as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-screenwriters-on-outlining-approaches]]
- [[wiki/sources/2026-04-09-screenwriters-on-outlining-approaches]]
- [[wiki/concepts/filmmaking/outline-flexibility]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/scene-card-method]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/syntheses/cross-source/screenwriting-outlining-models]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 14:53] ingest | Vince Gilligan on Writing Breaking Bad

Summary: Ingested a new English Vince Gilligan television-writing source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-vince-gilligan-on-writing-breaking-bad]], a new entity page at [[wiki/entities/vince-gilligan]], a new concept page at [[wiki/concepts/filmmaking/psychology-driven-plot]], and a new synthesis page at [[wiki/syntheses/filmmaking/vince-gilligan-breaking-bad-framework]]. Deepened [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/television-pilot-writing]], [[wiki/concepts/filmmaking/writers-room-craft]], and [[wiki/concepts/filmmaking/transformation-in-storytelling]] so the TV branch now captures anti-stasis character change, plot-from-psychology, pilot flash-forward hooking, intelligent antagonists, and room-level authenticity checks as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-vince-gilligan-on-writing-breaking-bad]]
- [[wiki/sources/2026-04-09-vince-gilligan-on-writing-breaking-bad]]
- [[wiki/entities/vince-gilligan]]
- [[wiki/concepts/filmmaking/psychology-driven-plot]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/television-pilot-writing]]
- [[wiki/concepts/filmmaking/writers-room-craft]]
- [[wiki/concepts/filmmaking/transformation-in-storytelling]]
- [[wiki/syntheses/filmmaking/vince-gilligan-breaking-bad-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:01] ingest | Christopher Nolan on The Dark Knight

Summary: Ingested a new English Christopher Nolan filmmaking source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-christopher-nolan-on-the-dark-knight]], a new entity page at [[wiki/entities/christopher-nolan]], a new concept page at [[wiki/concepts/filmmaking/worldview-antagonist]], and a new synthesis page at [[wiki/syntheses/filmmaking/christopher-nolan-dark-knight-framework]]. Deepened [[wiki/concepts/filmmaking/character-driven-storytelling]], [[wiki/concepts/filmmaking/genre-mastery]], [[wiki/concepts/creativity/visual-literacy]], and [[wiki/concepts/filmmaking/filmmaking]] so the filmmaking branch now captures philosophy-driven antagonists, moral-paradox hero design, blockbuster noir hybridization, and daylight menace as deliberate visual expectation reversal. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-christopher-nolan-on-the-dark-knight]]
- [[wiki/sources/2026-04-09-christopher-nolan-on-the-dark-knight]]
- [[wiki/entities/christopher-nolan]]
- [[wiki/concepts/filmmaking/worldview-antagonist]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/genre-mastery]]
- [[wiki/concepts/creativity/visual-literacy]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/christopher-nolan-dark-knight-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:13] ingest | George R.R. Martin on A Song of Ice and Fire and Adaptation

Summary: Ingested a new English George R.R. Martin fiction-and-adaptation source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-george-r-r-martin-on-a-song-of-ice-and-fire-and-adaptation]], a new entity page at [[wiki/entities/george-r-r-martin]], a new canonical concept page at [[wiki/concepts/filmmaking/adaptation-divergence]], and a new synthesis page at [[wiki/syntheses/filmmaking/george-r-r-martin-fiction-and-adaptation-framework]]. Deepened [[wiki/concepts/filmmaking/fiction-writing]], [[wiki/concepts/filmmaking/narrative-voice-and-perspective]], [[wiki/concepts/filmmaking/writer-worldview]], and [[wiki/concepts/filmmaking/immersive-research]] so the filmmaking branch now captures medium separation, adaptation butterfly effects, agency-based POV selection, historically grounded worldbuilding, and long-horizon narrative integrity under fan and production pressure. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-george-r-r-martin-on-a-song-of-ice-and-fire-and-adaptation]]
- [[wiki/sources/2026-04-09-george-r-r-martin-on-a-song-of-ice-and-fire-and-adaptation]]
- [[wiki/entities/george-r-r-martin]]
- [[wiki/concepts/filmmaking/adaptation-divergence]]
- [[wiki/concepts/filmmaking/fiction-writing]]
- [[wiki/concepts/filmmaking/narrative-voice-and-perspective]]
- [[wiki/concepts/filmmaking/writer-worldview]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/syntheses/filmmaking/george-r-r-martin-fiction-and-adaptation-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:32] ingest | Fight Club Creative Process and Adaptation

Summary: Ingested a new English *Fight Club* cross-medium source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-fight-club-creative-process-and-adaptation]], a new work-centered entity page at [[wiki/entities/fight-club]], a new canonical concept page at [[wiki/concepts/filmmaking/externalizing-interiority]], and a new synthesis page at [[wiki/syntheses/filmmaking/fight-club-story-and-adaptation-framework]]. Deepened [[wiki/concepts/filmmaking/adaptation-divergence]], [[wiki/concepts/filmmaking/visual-storytelling-first]], [[wiki/concepts/filmmaking/character-interviews]], and [[wiki/concepts/creativity/idea-development]] so the vault now captures adaptation through external behavior, rule-built social systems, charged-scene-first drafting, and social beta-testing of ideas as compiled knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-fight-club-creative-process-and-adaptation]]
- [[wiki/sources/2026-04-09-fight-club-creative-process-and-adaptation]]
- [[wiki/entities/fight-club]]
- [[wiki/concepts/filmmaking/externalizing-interiority]]
- [[wiki/concepts/filmmaking/adaptation-divergence]]
- [[wiki/concepts/filmmaking/visual-storytelling-first]]
- [[wiki/concepts/filmmaking/character-interviews]]
- [[wiki/concepts/creativity/idea-development]]
- [[wiki/syntheses/filmmaking/fight-club-story-and-adaptation-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:38] ingest | 29 Common Screenwriting Mistakes

Summary: Ingested a new English generic screenwriting-diagnostics source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-29-common-screenwriting-mistakes]], a new canonical concept page at [[wiki/concepts/filmmaking/screenplay-diagnostics]], and a new synthesis page at [[wiki/syntheses/filmmaking/screenwriting-mistakes-diagnostic-framework]]. Deepened [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/character-driven-storytelling]], and [[wiki/concepts/filmmaking/writing-process-and-revision]] so the filmmaking branch now captures recurring failure modes around soft concepts, weak goals, rushed setup, flat stakes, thin vulnerability, and premature submission as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-29-common-screenwriting-mistakes]]
- [[wiki/sources/2026-04-09-29-common-screenwriting-mistakes]]
- [[wiki/concepts/filmmaking/screenplay-diagnostics]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/screenwriting-mistakes-diagnostic-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:44] ingest | Modern Hollywood Blockbuster Quality Decline

Summary: Ingested a new English generic blockbuster-critique source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-modern-hollywood-blockbuster-quality-decline]], a new canonical concept page at [[wiki/concepts/filmmaking/stimulation-over-tension]], and a new synthesis page at [[wiki/syntheses/filmmaking/modern-blockbuster-decline-model]]. Deepened [[wiki/concepts/filmmaking/factory-filmmaking]], [[wiki/concepts/filmmaking/franchise-stewardship]], [[wiki/concepts/filmmaking/audience-as-collaborator]], and [[wiki/concepts/filmmaking/filmmaking]] so the vault now captures demographic smoothing, generic emotional triggering, boredom-panic pacing, and the difference between sensory stimulation and earned dramatic tension as compiled knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-modern-hollywood-blockbuster-quality-decline]]
- [[wiki/sources/2026-04-09-modern-hollywood-blockbuster-quality-decline]]
- [[wiki/concepts/filmmaking/stimulation-over-tension]]
- [[wiki/concepts/filmmaking/factory-filmmaking]]
- [[wiki/concepts/filmmaking/franchise-stewardship]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/filmmaking/filmmaking]]
- [[wiki/syntheses/filmmaking/modern-blockbuster-decline-model]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 15:55] ingest | Max Landis on Good Screenplays

Summary: Ingested a new English Max Landis screenwriting source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-max-landis-on-good-screenplays]], a new entity page at [[wiki/entities/max-landis]], a new canonical concept page at [[wiki/concepts/filmmaking/screenplay-readability]], and a new synthesis page at [[wiki/syntheses/filmmaking/max-landis-screenplay-readability-framework]]. Deepened [[wiki/concepts/filmmaking/screenplay-economy]], [[wiki/concepts/filmmaking/screenwriting]], [[wiki/concepts/filmmaking/story-propulsion]], [[wiki/concepts/filmmaking/writing-process-and-revision]], and [[wiki/syntheses/cross-source/writing-craft-overlaps]] so the filmmaking branch now captures page-level readability, fun-to-read screenplays, anti-overdirection, read-aloud dialogue testing, and the difference between writing well, selling, and being produced as compiled vault knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-max-landis-on-good-screenplays]]
- [[wiki/sources/2026-04-09-max-landis-on-good-screenplays]]
- [[wiki/entities/max-landis]]
- [[wiki/concepts/filmmaking/screenplay-readability]]
- [[wiki/concepts/filmmaking/screenplay-economy]]
- [[wiki/concepts/filmmaking/screenwriting]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/syntheses/filmmaking/max-landis-screenplay-readability-framework]]
- [[wiki/syntheses/cross-source/writing-craft-overlaps]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 16:00] ingest | Hollywood Romance Myths and Healthy Relationships

Summary: Ingested a new English relationship-media critique source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-hollywood-romance-myths-and-healthy-relationships]], new canonical concept pages at [[wiki/concepts/others/hollywood-romance-myths]], [[wiki/concepts/others/drama-vs-secure-connection]], and [[wiki/concepts/others/romantic-completion-myth]], and a new synthesis page at [[wiki/syntheses/others/healthy-relationship-countermodel]]. I did not create an entity page because the raw summary does not clearly identify a named speaker. The new `others` branch now captures media-shaped romance myths, the confusion of drama with quality, and the idea that self-acceptance, boundaries, friendship, and family matter more than romantic rescue fantasies. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-hollywood-romance-myths-and-healthy-relationships]]
- [[wiki/sources/2026-04-09-hollywood-romance-myths-and-healthy-relationships]]
- [[wiki/concepts/others/hollywood-romance-myths]]
- [[wiki/concepts/others/drama-vs-secure-connection]]
- [[wiki/concepts/others/romantic-completion-myth]]
- [[wiki/syntheses/others/healthy-relationship-countermodel]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 16:20] ingest | Chase Hughes Goal Programming and Future Self

Summary: Ingested a new English Chase Hughes productivity source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-goal-programming-and-future-self]], a new entity page at [[wiki/entities/chase-hughes]], new canonical concept pages at [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/productivity/fear-goal-programming]], and [[wiki/concepts/productivity/behavior-journaling]], and a new synthesis page at [[wiki/syntheses/productivity/chase-hughes-goal-programming-framework]]. Deepened [[wiki/concepts/business/framework-driven-action]] and [[wiki/concepts/leadership/high-performance-mindset]] so the first productivity branch now compiles future-self decision rules, FEAR-based goal installation, daily behavior tracking, and the link between personal frameworks and repeatable performance. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-goal-programming-and-future-self]]
- [[wiki/sources/2026-04-09-chase-hughes-goal-programming-and-future-self]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/productivity/fear-goal-programming]]
- [[wiki/concepts/productivity/behavior-journaling]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/syntheses/productivity/chase-hughes-goal-programming-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 16:29] ingest | Chase Hughes Orion Principle and Mask Behavior

Summary: Ingested a new English Chase Hughes behavioral-pattern source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-orion-principle-and-mask-behavior]], new canonical concept pages at [[wiki/concepts/others/mask-behavior]], [[wiki/concepts/others/inversion-patterns]], [[wiki/concepts/others/projection-as-self-signal]], and [[wiki/concepts/others/orion-principle]], and a new synthesis page at [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]]. Deepened [[wiki/entities/chase-hughes]] so the vault now preserves a second Chase Hughes branch on masks, shame-driven overcompensation, projection, and compassion-first interpretation, while explicitly treating the Orion model as heuristic rather than settled psychology. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-orion-principle-and-mask-behavior]]
- [[wiki/sources/2026-04-09-chase-hughes-orion-principle-and-mask-behavior]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/others/mask-behavior]]
- [[wiki/concepts/others/inversion-patterns]]
- [[wiki/concepts/others/projection-as-self-signal]]
- [[wiki/concepts/others/orion-principle]]
- [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 16:38] ingest | Chase Hughes Deal with Bullies the Right Way

Summary: Ingested a new English Chase Hughes anti-bullying source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-deal-with-bullies-the-right-way]], a new psychology concept at [[wiki/concepts/others/bullying-as-defense]], a new communication concept at [[wiki/concepts/communication/face-saving-de-escalation]], and a new synthesis page at [[wiki/syntheses/communication/chase-hughes-anti-bullying-framework]]. Deepened [[wiki/entities/chase-hughes]], [[wiki/concepts/communication/tactical-empathy]], [[wiki/concepts/communication/effective-communication]], and [[wiki/concepts/others/projection-as-self-signal]] so the vault now preserves a third Chase Hughes branch on fear-based aggression, shame-driven bullying, face-saving de-escalation, and empathy-based interruption without becoming hostile in return. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-deal-with-bullies-the-right-way]]
- [[wiki/sources/2026-04-09-chase-hughes-deal-with-bullies-the-right-way]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/others/bullying-as-defense]]
- [[wiki/concepts/communication/face-saving-de-escalation]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/others/projection-as-self-signal]]
- [[wiki/syntheses/communication/chase-hughes-anti-bullying-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 16:52] ingest | Sam Esmail on Mr. Robot Creative Process

Summary: Ingested a new English Sam Esmail filmmaking source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-sam-esmail-on-mr-robot-creative-process]], a new entity page at [[wiki/entities/sam-esmail]], a new canonical concept page at [[wiki/concepts/filmmaking/voiceover-as-interiority]], and a new synthesis page at [[wiki/syntheses/filmmaking/sam-esmail-mr-robot-framework]]. Deepened [[wiki/concepts/filmmaking/showrunning]], [[wiki/concepts/filmmaking/writers-room-craft]], [[wiki/concepts/filmmaking/writing-process-and-revision]], [[wiki/concepts/filmmaking/immersive-research]], [[wiki/concepts/filmmaking/externalizing-interiority]], and [[wiki/concepts/filmmaking/psychology-driven-plot]] so the TV branch now preserves purposeful voiceover, authenticity of subculture and mental-state portrayal, goalpost-first season design, and reverse-engineered emotional logic as compiled knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-sam-esmail-on-mr-robot-creative-process]]
- [[wiki/sources/2026-04-09-sam-esmail-on-mr-robot-creative-process]]
- [[wiki/entities/sam-esmail]]
- [[wiki/concepts/filmmaking/voiceover-as-interiority]]
- [[wiki/concepts/filmmaking/showrunning]]
- [[wiki/concepts/filmmaking/writers-room-craft]]
- [[wiki/concepts/filmmaking/writing-process-and-revision]]
- [[wiki/concepts/filmmaking/immersive-research]]
- [[wiki/concepts/filmmaking/externalizing-interiority]]
- [[wiki/concepts/filmmaking/psychology-driven-plot]]
- [[wiki/syntheses/filmmaking/sam-esmail-mr-robot-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 17:00] ingest | Johnny Harris Explainer Storytelling Formula

Summary: Ingested a new English explainer-storytelling source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-johnny-harris-explainer-storytelling-formula]], a new entity page at [[wiki/entities/johnny-harris]], a new canonical concept page at [[wiki/concepts/communication/anchor-bridge-structure]], and a new synthesis page at [[wiki/syntheses/communication/johnny-harris-explainer-framework]]. Deepened [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/concrete-specificity]], [[wiki/concepts/filmmaking/audience-as-collaborator]], and [[wiki/concepts/creativity/visual-literacy]] so the vault now preserves experience-before-explanation, visual anchors, concise contextual bridges, and research-backed explainer rhythm as compiled knowledge. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-johnny-harris-explainer-storytelling-formula]]
- [[wiki/sources/2026-04-09-johnny-harris-explainer-storytelling-formula]]
- [[wiki/entities/johnny-harris]]
- [[wiki/concepts/communication/anchor-bridge-structure]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/concrete-specificity]]
- [[wiki/concepts/filmmaking/audience-as-collaborator]]
- [[wiki/concepts/creativity/visual-literacy]]
- [[wiki/syntheses/communication/johnny-harris-explainer-framework]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 22:21] ingest | Chase Hughes 90-Second Brain Capture

Summary: Ingested a new English Chase Hughes influence source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-90-second-brain-capture]], new canonical communication concepts at [[wiki/concepts/communication/installation-vs-persuasion]] and [[wiki/concepts/communication/permission-bridge]], and a new synthesis page at [[wiki/syntheses/communication/chase-hughes-brain-capture-framework]]. Deepened [[wiki/entities/chase-hughes]], [[wiki/concepts/communication/tactical-empathy]], [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/persuasion]], and [[wiki/syntheses/cross-source/communication-and-influence-models]] so the vault now preserves a fourth Chase Hughes branch on first-90-second interaction design, narrator-level installation, depth sequencing, and the ethical risk of influence-by-bypassing reflective evaluation. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-90-second-brain-capture]]
- [[wiki/sources/2026-04-09-chase-hughes-90-second-brain-capture]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/communication/installation-vs-persuasion]]
- [[wiki/concepts/communication/permission-bridge]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/syntheses/communication/chase-hughes-brain-capture-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 22:36] ingest | Studio Script Reader Strengths and Weaknesses

Summary: Ingested a new English image-derived screenwriting source built from three screenshots and moved the canonical raw note into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-studio-script-reader-strengths-and-weaknesses]] and a new synthesis page at [[wiki/syntheses/filmmaking/studio-script-reader-scorecard]], then deepened [[wiki/concepts/filmmaking/screenplay-diagnostics]], [[wiki/concepts/filmmaking/screenplay-readability]], [[wiki/concepts/filmmaking/premise-testing]], [[wiki/concepts/filmmaking/story-propulsion]], and [[wiki/concepts/filmmaking/character-driven-storytelling]] so the vault now preserves a reader-side scorecard for premise, hook, protagonist, antagonist, world, action, dialogue, escalation, and ending control, along with the mirrored failure patterns that make scripts feel generic, passive, confusing, repetitive, or anti-climactic. OCR quality was strong enough for a normal ingest, but the source page preserves that this branch came from images rather than a conventional text source. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-studio-script-reader-strengths-and-weaknesses]]
- [[wiki/sources/2026-04-09-studio-script-reader-strengths-and-weaknesses]]
- [[wiki/concepts/filmmaking/screenplay-diagnostics]]
- [[wiki/concepts/filmmaking/screenplay-readability]]
- [[wiki/concepts/filmmaking/premise-testing]]
- [[wiki/concepts/filmmaking/story-propulsion]]
- [[wiki/concepts/filmmaking/character-driven-storytelling]]
- [[wiki/syntheses/filmmaking/studio-script-reader-scorecard]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 22:41] admin | Canonicalize Image-Derived Source Assets

Summary: Updated the schema so image-derived or attachment-backed sources store their supporting files under `raw/assets/<source-slug>/` instead of leaving them in the vault root. Then normalized the current studio-reader image source by moving its three PNG screenshots into [[raw/assets/2026-04-09-studio-script-reader-strengths-and-weaknesses]], updating the canonical raw note to point at those asset paths, and cleaning recent-file references in [[.obsidian/workspace.json]].

Pages touched:

- [[AGENTS]]
- [[raw/inbox/2026-04-09-studio-script-reader-strengths-and-weaknesses]]
- [[.obsidian/workspace.json]]
- [[log]]

## [2026-04-09 22:48] ingest | Chase Hughes Reading Minds, Influence, and Confidence

Summary: Ingested a new English Chase Hughes communication source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-reading-minds-influence-and-confidence]], new canonical concept pages at [[wiki/concepts/communication/elicitation]], [[wiki/concepts/communication/frame-control]], and [[wiki/concepts/others/emotional-gravity]], and a new synthesis page at [[wiki/syntheses/communication/chase-hughes-influence-and-confidence-framework]]. Deepened [[wiki/entities/chase-hughes]], [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/tactical-empathy]], [[wiki/concepts/communication/persuasion]], [[wiki/concepts/leadership/high-performance-mindset]], and [[wiki/syntheses/cross-source/communication-and-influence-models]] so the vault now preserves a fifth Chase Hughes branch on empathy as trainable decoding, elicitation instead of interrogation, composure and frame control under pressure, emotional gravity as a repeated-pattern model, and confidence through self-forgiveness. The source page preserves the main caveat that several neuroscience-like claims here are asserted more strongly than they are evidenced in the summary. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-reading-minds-influence-and-confidence]]
- [[wiki/sources/2026-04-09-chase-hughes-reading-minds-influence-and-confidence]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/communication/elicitation]]
- [[wiki/concepts/communication/frame-control]]
- [[wiki/concepts/others/emotional-gravity]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/syntheses/communication/chase-hughes-influence-and-confidence-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 23:04] ingest | Chase Hughes Behavioral Framework for Influence

Summary: Ingested a new English Chase Hughes source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-behavioral-framework-for-influence]], new canonical concept pages at [[wiki/concepts/communication/interactional-authority]], [[wiki/concepts/communication/behavioral-profiling]], and [[wiki/concepts/communication/social-needs-profiling]], plus a new umbrella synthesis at [[wiki/syntheses/communication/chase-hughes-behavioral-influence-framework]]. Deepened [[wiki/entities/chase-hughes]], [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/tactical-empathy]], [[wiki/concepts/communication/persuasion]], [[wiki/concepts/communication/installation-vs-persuasion]], [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/productivity/fear-goal-programming]], [[wiki/concepts/leadership/high-performance-mindset]], [[wiki/syntheses/productivity/chase-hughes-goal-programming-framework]], and [[wiki/syntheses/cross-source/communication-and-influence-models]]. The branch now preserves Chase's broader system around self-mastery, authority, behavioral reading, need-diagnosis, identity-and-context persuasion, FEAR carryover, and manipulation-resistant attention, while explicitly marking the cue-reading and neuroscience-like claims as heuristic rather than settled science. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-behavioral-framework-for-influence]]
- [[wiki/sources/2026-04-09-chase-hughes-behavioral-framework-for-influence]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/communication/interactional-authority]]
- [[wiki/concepts/communication/behavioral-profiling]]
- [[wiki/concepts/communication/social-needs-profiling]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/concepts/communication/installation-vs-persuasion]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/productivity/fear-goal-programming]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/syntheses/communication/chase-hughes-behavioral-influence-framework]]
- [[wiki/syntheses/productivity/chase-hughes-goal-programming-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]

## [2026-04-09 23:17] ingest | Chase Hughes Influence, Identity, and Human Connection

Summary: Ingested a new English Chase Hughes source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-chase-hughes-influence-identity-and-human-connection]], new canonical concept pages at [[wiki/concepts/communication/pcp-model]], [[wiki/concepts/communication/negative-dissociation]], and [[wiki/concepts/others/childhood-development-triangle]], plus a new synthesis at [[wiki/syntheses/communication/chase-hughes-identity-and-permission-framework]]. Deepened [[wiki/entities/chase-hughes]], [[wiki/concepts/communication/installation-vs-persuasion]], [[wiki/concepts/communication/authentic-communication]], [[wiki/concepts/others/mask-behavior]], [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]], [[wiki/syntheses/communication/chase-hughes-behavioral-influence-framework]], and [[wiki/syntheses/cross-source/communication-and-influence-models]]. The branch now preserves Chase's PCP sequence, indirect identity priming, developmental script logic, and the explicit tension between real human connection and highly engineered pseudo-connection. Stale raw-root references were removed from [[.obsidian/workspace.json]] during cleanup.

Pages touched:

- [[raw/inbox/2026-04-09-chase-hughes-influence-identity-and-human-connection]]
- [[wiki/sources/2026-04-09-chase-hughes-influence-identity-and-human-connection]]
- [[wiki/entities/chase-hughes]]
- [[wiki/concepts/communication/pcp-model]]
- [[wiki/concepts/communication/negative-dissociation]]
- [[wiki/concepts/others/childhood-development-triangle]]
- [[wiki/concepts/communication/installation-vs-persuasion]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/others/mask-behavior]]
- [[wiki/syntheses/communication/chase-hughes-identity-and-permission-framework]]
- [[wiki/syntheses/communication/chase-hughes-behavioral-influence-framework]]
- [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]
- [[.obsidian/workspace.json]]

## [2026-04-09 23:24] ingest | Why Many Entrepreneurs Struggle Despite Implementing Systems

Summary: Ingested a new English business-systems source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-why-many-entrepreneurs-struggle-despite-implementing-systems]], a new canonical concept page at [[wiki/concepts/business/business-systems]], and a new synthesis at [[wiki/syntheses/business/scalable-business-systems-framework]]. Deepened [[wiki/concepts/business/framework-driven-action]] so the broader business branch now preserves the distinction between documentation and real systems, the input-process-output-feedback model, and the bottleneck-first logic for scaling. The branch now links the new English systems model to existing product, management, and owner-growth material without mixing languages inside the canonical pages.

Pages touched:

- [[raw/inbox/2026-04-09-why-many-entrepreneurs-struggle-despite-implementing-systems]]
- [[wiki/sources/2026-04-09-why-many-entrepreneurs-struggle-despite-implementing-systems]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/syntheses/business/scalable-business-systems-framework]]
- [[index]]

## [2026-04-09 23:32] ingest | Jurgen Klopp Coaching Legacy

Summary: Ingested a new English leadership source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-09-jurgen-klopp-coaching-legacy]], a new entity page at [[wiki/entities/jurgen-klopp]], a new canonical concept page at [[wiki/concepts/leadership/individualized-leadership]], and a new synthesis at [[wiki/syntheses/leadership/jurgen-klopp-leadership-framework]]. Deepened [[wiki/concepts/leadership/leadership]], [[wiki/concepts/leadership/high-performance-team-culture]], [[wiki/concepts/leadership/organizational-culture]], [[wiki/concepts/leadership/trust-based-collaboration]], and [[wiki/syntheses/cross-source/high-performance-leadership-models]] so the leadership branch now preserves Klopp's emphasis on authentic coaching, person-specific motivation inside common standards, emotionally bonded intensity, and legacy as continuity rather than self-display.

Pages touched:

- [[raw/inbox/2026-04-09-jurgen-klopp-coaching-legacy]]
- [[wiki/sources/2026-04-09-jurgen-klopp-coaching-legacy]]
- [[wiki/entities/jurgen-klopp]]
- [[wiki/concepts/leadership/individualized-leadership]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/concepts/leadership/organizational-culture]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/syntheses/leadership/jurgen-klopp-leadership-framework]]
- [[wiki/syntheses/cross-source/high-performance-leadership-models]]
- [[index]]

## [2026-04-10 00:53] ingest | Выдержки из книги «Атомные привычки» Джеймса Клира

Summary: Ингестировал новый русскоязычный raw-источник и переместил канонический файл в `raw/inbox/` под нормализованным именем. Создал исходную страницу [[wiki/sources/2026-04-09-vyderzhki-iz-knigi-atomnye-privychki-dzheimsa-klira]], сущность [[wiki/entities/dzheims-klir]], канонические концепт-страницы [[wiki/concepts/productivity/sistemy-vmesto-celei]], [[wiki/concepts/productivity/uchet-vremeni]] и [[wiki/concepts/productivity/samoupravlenie]], а также синтез-страницу [[wiki/syntheses/productivity/freymvork-samoupravleniya-cherez-sistemy-i-privychki]]. Ветка теперь явно фиксирует, что заметка смешивает клировскую линию про накопительный эффект привычек и системы вместо целей с друкеровским слоем про учет времени, сильные стороны, приоритеты и самоуправление, не выдавая этот короткий источник за полную карту книги «Атомные привычки». Обновлен [[index]] с новыми записями по raw-файлу, исходной странице, сущности, концептам и синтезу.

Pages touched:

- [[raw/inbox/2026-04-09-vyderzhki-iz-knigi-atomnye-privychki-dzheimsa-klira]]
- [[wiki/sources/2026-04-09-vyderzhki-iz-knigi-atomnye-privychki-dzheimsa-klira]]
- [[wiki/entities/dzheims-klir]]
- [[wiki/concepts/productivity/sistemy-vmesto-celei]]
- [[wiki/concepts/productivity/uchet-vremeni]]
- [[wiki/concepts/productivity/samoupravlenie]]
- [[wiki/syntheses/productivity/freymvork-samoupravleniya-cherez-sistemy-i-privychki]]
- [[index]]

## [2026-04-10 11:15] ingest | Rory Sutherland Marketing Psychology and Perceived Value

Summary: Ingested a new English Rory Sutherland source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-rory-sutherland-marketing-psychology-and-perceived-value]], a new entity page at [[wiki/entities/rory-sutherland]], new canonical concept pages at [[wiki/concepts/business/reverse-benchmarking]] and [[wiki/concepts/business/perception-driven-value]], plus a new synthesis at [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. Deepened [[wiki/concepts/business/advertising]] and [[wiki/concepts/business/brand-strategy]] so the advertising branch now explicitly preserves Sutherland's psychological-value layer around framing, fat-tailed breakthroughs, category-neglected differentiation, and the risk that logic-heavy optimization can suppress uncommon value creation.

Pages touched:

- [[raw/inbox/2026-04-10-rory-sutherland-marketing-psychology-and-perceived-value]]
- [[wiki/sources/2026-04-10-rory-sutherland-marketing-psychology-and-perceived-value]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/concepts/business/reverse-benchmarking]]
- [[wiki/concepts/business/perception-driven-value]]
- [[wiki/concepts/business/advertising]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-10 11:23] ingest | Conversation Commandments for Better Connection

Summary: Ingested a new English composite conversation source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-conversation-commandments-for-better-connection]], new canonical concept pages at [[wiki/concepts/communication/conversational-curiosity]] and [[wiki/concepts/communication/charismatic-presence]], plus a new synthesis at [[wiki/syntheses/communication/conversation-connection-framework]]. Deepened [[wiki/concepts/communication/effective-communication]] so the communication branch now explicitly preserves the source's everyday connection layer around curiosity-first conversation, presence-warmth-power as a trainable charisma model, emotionally richer question design, and listening that proves the other person actually landed.

Pages touched:

- [[raw/inbox/2026-04-10-conversation-commandments-for-better-connection]]
- [[wiki/sources/2026-04-10-conversation-commandments-for-better-connection]]
- [[wiki/concepts/communication/conversational-curiosity]]
- [[wiki/concepts/communication/charismatic-presence]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/syntheses/communication/conversation-connection-framework]]
- [[index]]

## [2026-04-10 11:33] ingest | Simon Sinek Trust and Team Selection

Summary: Ingested a new English Simon Sinek source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-trust-and-team-selection]], a new entity page at [[wiki/entities/simon-sinek]], a new canonical concept page at [[wiki/concepts/leadership/trust-performance-matrix]], and a new synthesis at [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]. Deepened [[wiki/concepts/leadership/trust-based-collaboration]] and [[wiki/concepts/leadership/high-performance-team-culture]] so the leadership branch now explicitly preserves Sinek's trust-versus-output selection logic, the risk of rewarding toxic high performers, and the need to make `glue` contributions visible in hiring, promotion, and recognition decisions.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-trust-and-team-selection]]
- [[wiki/sources/2026-04-10-simon-sinek-trust-and-team-selection]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/leadership/trust-performance-matrix]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]
- [[index]]

## [2026-04-10 11:46] ingest | Jefferson Fisher Fake Apologies and Manipulative Communication

Summary: Ingested a new English Jefferson Fisher source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-jefferson-fisher-fake-apologies-and-manipulative-communication]], a new entity page at [[wiki/entities/jefferson-fisher]], a new canonical concept page at [[wiki/concepts/communication/boundary-language]], and a new synthesis at [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework]]. Deepened [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/intention-and-impact]], and [[wiki/syntheses/cross-source/communication-and-influence-models]] so the communication branch now explicitly preserves Fisher's map of fake-apology structures, compact manipulation-resistant accountability language, and the role of pauses and fewer words in hard conversations.

Pages touched:

- [[raw/inbox/2026-04-10-jefferson-fisher-fake-apologies-and-manipulative-communication]]
- [[wiki/sources/2026-04-10-jefferson-fisher-fake-apologies-and-manipulative-communication]]
- [[wiki/entities/jefferson-fisher]]
- [[wiki/concepts/communication/boundary-language]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/intention-and-impact]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]

## [2026-04-10 11:58] ingest | Kelly McGonigal Stress Mindset and Social Resilience

Summary: Ingested a new English Kelly McGonigal source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-kelly-mcgonigal-stress-mindset-and-social-resilience]], a new entity page at [[wiki/entities/kelly-mcgonigal]], a new canonical concept page at [[wiki/concepts/health/stress-mindset]], and a new synthesis at [[wiki/syntheses/health/kelly-mcgonigal-stress-resilience-framework]]. Deepened [[wiki/concepts/health/healthspan]], [[wiki/concepts/leadership/high-performance-mindset]], and [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health branch now explicitly preserves McGonigal's stress-mindset model, the social-connection side of stress biology, and the tension between useful challenge and genuinely harmful overload.

Pages touched:

- [[raw/inbox/2026-04-10-kelly-mcgonigal-stress-mindset-and-social-resilience]]
- [[wiki/sources/2026-04-10-kelly-mcgonigal-stress-mindset-and-social-resilience]]
- [[wiki/entities/kelly-mcgonigal]]
- [[wiki/concepts/health/stress-mindset]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/syntheses/health/kelly-mcgonigal-stress-resilience-framework]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]
## [2026-04-10 12:10] ingest | Daniel Levitin Stress Premortems and Decision Hygiene
Summary: Ingested a new English Daniel Levitin source and moved the canonical raw file into `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-daniel-levitin-stress-premortems-and-decision-hygiene]], a new entity page at [[wiki/entities/daniel-levitin]], a new canonical concept page at [[wiki/concepts/health/premortem]], and a new synthesis at [[wiki/syntheses/health/daniel-levitin-decision-hygiene-framework]]. Deepened [[wiki/concepts/communication/timing-and-sequencing]], [[wiki/concepts/health/healthspan]], and [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health branch now explicitly preserves Levitin's premortem method, his stress-impaired-judgment model, and the role of advance planning in protecting decision quality. Created a new source page at [[wiki/sources/2026-04-10-daniel-levitin-stress-premortems-and-decision-hygiene]], a new entity page at [[wiki/entities/daniel-levitin]], a new canonical concept page at [[wiki/concepts/health/premortem]], and a new synthesis at [[wiki/syntheses/health/daniel-levitin-decision-hygiene-framework]]. Deepened [[wiki/concepts/communication/timing-and-sequencing]], [[wiki/concepts/health/healthspan]], and [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health branch now explicitly preserves Levitin's premortem method, his stress-impaired-judgment model, and the role of advance planning in protecting decision quality.
Pages touched:
- [[raw/inbox/2026-04-10-daniel-levitin-stress-premortems-and-decision-hygiene]]
- [[wiki/sources/2026-04-10-daniel-levitin-stress-premortems-and-decision-hygiene]]
- [[wiki/entities/daniel-levitin]]
- [[wiki/concepts/health/premortem]]
- [[wiki/concepts/communication/timing-and-sequencing]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/syntheses/health/daniel-levitin-decision-hygiene-framework]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]

## [2026-04-10 12:35] ingest | Eric Ries The Lean Startup

Summary: Ingested a new English Eric Ries source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-eric-ries-the-lean-startup]], a new entity page at [[wiki/entities/eric-ries]], a new canonical concept page at [[wiki/concepts/business/validated-learning]], and a new synthesis at [[wiki/syntheses/business/lean-startup-validation-framework]]. Deepened [[wiki/concepts/business/framework-driven-action]] so the business branch now explicitly preserves Lean Startup logic as a general uncertainty-handling framework, while keeping the overlap with the existing Russian MVP niche-testing branch legible rather than duplicated.

Pages touched:

- [[raw/inbox/2026-04-10-eric-ries-the-lean-startup]]
- [[wiki/sources/2026-04-10-eric-ries-the-lean-startup]]
- [[wiki/entities/eric-ries]]
- [[wiki/concepts/business/validated-learning]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/syntheses/business/lean-startup-validation-framework]]
- [[index]]

## [2026-04-10 12:46] ingest | Simon Sinek Finite vs Infinite Games

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-finite-vs-infinite-games]], a new canonical concept page at [[wiki/concepts/leadership/infinite-game-mindset]], and a new synthesis at [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]. Deepened [[wiki/entities/simon-sinek]] and [[wiki/concepts/leadership/leadership]] so the existing Simon branch now spans both trust-centered team selection and the longer-horizon finite-versus-infinite-games frame instead of splitting those ideas into disconnected pages.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-finite-vs-infinite-games]]
- [[wiki/sources/2026-04-10-simon-sinek-finite-vs-infinite-games]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]
- [[index]]

## [2026-04-10 12:56] ingest | Clayton Christensen Sustainable Growth and Jobs to Be Done

Summary: Ingested a new English Clayton Christensen source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-clayton-christensen-sustainable-growth-and-jobs-to-be-done]], a new entity page at [[wiki/entities/clayton-christensen]], a new canonical concept page at [[wiki/concepts/business/jobs-to-be-done]], and a new synthesis at [[wiki/syntheses/business/clayton-christensen-growth-framework]]. Deepened [[wiki/concepts/business/business-strategy]] so the business branch now explicitly preserves Christensen's innovation-portfolio logic, jobs framing, and metrics-trap warning instead of leaving those ideas isolated in a source-only page.

Pages touched:

- [[raw/inbox/2026-04-10-clayton-christensen-sustainable-growth-and-jobs-to-be-done]]
- [[wiki/sources/2026-04-10-clayton-christensen-sustainable-growth-and-jobs-to-be-done]]
- [[wiki/entities/clayton-christensen]]
- [[wiki/concepts/business/jobs-to-be-done]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/syntheses/business/clayton-christensen-growth-framework]]
- [[index]]

## [2026-04-10 13:06] ingest | Michael Pollan Psychedelics and Therapeutic Transformation

Summary: Ingested a new English Michael Pollan source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-michael-pollan-psychedelics-and-therapeutic-transformation]], a new entity page at [[wiki/entities/michael-pollan]], a new canonical concept page at [[wiki/concepts/health/psychedelic-assisted-therapy]], and a new synthesis at [[wiki/syntheses/health/michael-pollan-psychedelic-therapy-framework]]. Deepened [[wiki/concepts/health/healthspan]], [[wiki/concepts/health/biohack-skepticism]], and [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]] so the health branch now preserves Pollan's set-and-setting logic, integration-centered caution, and the tension between therapeutic promise and hype-heavy adoption.

Pages touched:

- [[raw/inbox/2026-04-10-michael-pollan-psychedelics-and-therapeutic-transformation]]
- [[wiki/sources/2026-04-10-michael-pollan-psychedelics-and-therapeutic-transformation]]
- [[wiki/entities/michael-pollan]]
- [[wiki/concepts/health/psychedelic-assisted-therapy]]
- [[wiki/concepts/health/healthspan]]
- [[wiki/concepts/health/biohack-skepticism]]
- [[wiki/syntheses/health/michael-pollan-psychedelic-therapy-framework]]
- [[wiki/syntheses/cross-source/preventive-health-and-longevity-models]]
- [[index]]

## [2026-04-10 13:18] ingest | Eric Ries Core Concepts of the Lean Startup Methodology

Summary: Ingested a second English Eric Ries source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-eric-ries-core-concepts-of-the-lean-startup-methodology]] and a new canonical concept page at [[wiki/concepts/business/innovation-accounting]]. Deepened [[wiki/entities/eric-ries]], [[wiki/concepts/business/validated-learning]], [[wiki/concepts/business/framework-driven-action]], [[wiki/concepts/business/business-strategy]], and [[wiki/syntheses/business/lean-startup-validation-framework]] so the Lean Startup branch now preserves startup-definition logic, build-measure-learn speed, and the accountability layer around experimentation instead of leaving those ideas trapped in the new source alone.

Pages touched:

- [[raw/inbox/2026-04-10-eric-ries-core-concepts-of-the-lean-startup-methodology]]
- [[wiki/sources/2026-04-10-eric-ries-core-concepts-of-the-lean-startup-methodology]]
- [[wiki/concepts/business/innovation-accounting]]
- [[wiki/entities/eric-ries]]
- [[wiki/concepts/business/validated-learning]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/syntheses/business/lean-startup-validation-framework]]
- [[index]]

## [2026-04-10 13:44] ingest | Daniel Goleman Social Intelligence at Google

Summary: Ingested a new English Daniel Goleman source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-daniel-goleman-social-intelligence-at-google]], a new entity page at [[wiki/entities/daniel-goleman]], a new canonical concept page at [[wiki/concepts/leadership/emotional-intelligence]], and a new synthesis at [[wiki/syntheses/leadership/daniel-goleman-emotional-intelligence-framework]]. Deepened [[wiki/concepts/communication/attunement]], [[wiki/concepts/leadership/high-performance-mindset]], [[wiki/concepts/leadership/leadership]], and [[wiki/syntheses/cross-source/high-performance-leadership-models]] so the leadership branch now preserves Goleman's EQ, social-intelligence, and anti-amygdala-hijack logic instead of leaving it isolated in a source-only page.

Pages touched:

- [[raw/inbox/2026-04-10-daniel-goleman-social-intelligence-at-google]]
- [[wiki/sources/2026-04-10-daniel-goleman-social-intelligence-at-google]]
- [[wiki/entities/daniel-goleman]]
- [[wiki/concepts/leadership/emotional-intelligence]]
- [[wiki/concepts/communication/attunement]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/syntheses/leadership/daniel-goleman-emotional-intelligence-framework]]
- [[wiki/syntheses/cross-source/high-performance-leadership-models]]
- [[index]]


## [2026-04-10 14:10] ingest | Daniel Kahneman Two-Systems Thinking

Summary: Ingested a new English Daniel Kahneman source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-daniel-kahneman-two-systems-thinking]], a new entity page at [[wiki/entities/daniel-kahneman]], new canonical concept pages at [[wiki/concepts/others/two-systems-thinking]] and [[wiki/concepts/others/expert-intuition]], and a new cross-source synthesis at [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]. This ingest gives the vault a durable cognition branch for fast versus slow judgment, the conditions under which intuition is actually trustworthy, and a clearer bridge from Kahneman's bias model to Levitin's decision-hygiene procedures.

Pages touched:

- [[raw/inbox/2026-04-10-daniel-kahneman-two-systems-thinking]]
- [[wiki/sources/2026-04-10-daniel-kahneman-two-systems-thinking]]
- [[wiki/entities/daniel-kahneman]]
- [[wiki/concepts/others/two-systems-thinking]]
- [[wiki/concepts/others/expert-intuition]]
- [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]
- [[index]]


## [2026-04-10 14:18] ingest | Chris Voss Power of No and Tactical Empathy

Summary: Ingested a new English Chris Voss source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-chris-voss-power-of-no-and-tactical-empathy]] and updated the canonical Voss branch in [[wiki/entities/chris-voss]], [[wiki/concepts/communication/no-oriented-questions]], [[wiki/concepts/communication/tactical-empathy]], and [[wiki/syntheses/communication/chris-voss-negotiation-framework]]. The branch now preserves this source's stronger emphasis on `no` as safety, compromise as a frequent value leak, and assertive-accommodator-analyst style adaptation without spawning duplicate negotiation concepts.

Pages touched:

- [[raw/inbox/2026-04-10-chris-voss-power-of-no-and-tactical-empathy]]
- [[wiki/sources/2026-04-10-chris-voss-power-of-no-and-tactical-empathy]]
- [[wiki/entities/chris-voss]]
- [[wiki/concepts/communication/no-oriented-questions]]
- [[wiki/concepts/communication/tactical-empathy]]
- [[wiki/syntheses/communication/chris-voss-negotiation-framework]]
- [[index]]

## [2026-04-10 14:24] ingest | Robert Greene The Laws of Human Nature

Summary: Ingested a new English Robert Greene source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-robert-greene-the-laws-of-human-nature]], a new entity page at [[wiki/entities/robert-greene]], a new canonical concept page at [[wiki/concepts/others/shadow-integration]], and a new cross-source synthesis at [[wiki/syntheses/cross-source/hidden-motives-and-social-behavior]]. Deepened [[wiki/concepts/others/mask-behavior]], [[wiki/concepts/leadership/organizational-culture]], and [[wiki/concepts/leadership/emotional-intelligence]] so the vault now preserves Greene's hidden-motive, shadow, and culture-contagion logic in the existing branch structure instead of leaving it trapped in a source-only page.

Pages touched:

- [[raw/inbox/2026-04-10-robert-greene-the-laws-of-human-nature]]
- [[wiki/sources/2026-04-10-robert-greene-the-laws-of-human-nature]]
- [[wiki/entities/robert-greene]]
- [[wiki/concepts/others/shadow-integration]]
- [[wiki/concepts/others/mask-behavior]]
- [[wiki/concepts/leadership/organizational-culture]]
- [[wiki/concepts/leadership/emotional-intelligence]]
- [[wiki/syntheses/cross-source/hidden-motives-and-social-behavior]]
- [[index]]

## [2026-04-10 14:32] ingest | Steve Jobs 2005 Stanford Commencement

Summary: Ingested a new English Steve Jobs source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-steve-jobs-2005-stanford-commencement]], a new entity page at [[wiki/entities/steve-jobs]], and a new business synthesis at [[wiki/syntheses/business/steve-jobs-stanford-framework]]. Deepened [[wiki/concepts/business/career-blueprint]], [[wiki/concepts/business/creative-entrepreneurship]], [[wiki/concepts/communication/authentic-communication]], and [[wiki/concepts/leadership/high-performance-mindset]] so the vault now preserves Jobs's `connecting the dots`, reinvention, mortality, and anti-dogma logic inside the existing career and performance branches.

Pages touched:

- [[raw/inbox/2026-04-10-steve-jobs-2005-stanford-commencement]]
- [[wiki/sources/2026-04-10-steve-jobs-2005-stanford-commencement]]
- [[wiki/entities/steve-jobs]]
- [[wiki/syntheses/business/steve-jobs-stanford-framework]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[index]]

## [2026-04-10 14:40] ingest | Jordan Peterson Excessive Agreeableness and Assertiveness

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-jordan-peterson-excessive-agreeableness-and-assertiveness]], a new entity page at [[wiki/entities/jordan-peterson]], a new canonical concept page at [[wiki/concepts/communication/assertiveness]], and a new synthesis at [[wiki/syntheses/communication/assertiveness-agreeableness-and-self-advocacy]]. Deepened [[wiki/concepts/communication/boundary-language]] and [[wiki/concepts/others/childhood-development-triangle]] so the vault now preserves both the in-the-moment language of boundaries and the upstream agreeableness-and-conflict-avoidance patterns that make self-advocacy difficult.

Pages touched:

- [[raw/inbox/2026-04-10-jordan-peterson-excessive-agreeableness-and-assertiveness]]
- [[wiki/sources/2026-04-10-jordan-peterson-excessive-agreeableness-and-assertiveness]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/concepts/communication/assertiveness]]
- [[wiki/concepts/communication/boundary-language]]
- [[wiki/concepts/others/childhood-development-triangle]]
- [[wiki/syntheses/communication/assertiveness-agreeableness-and-self-advocacy]]
- [[index]]


## [2026-04-10 14:00] ingest | Carol Dweck Fixed and Growth Mindsets

Summary: Ingested a new English Carol Dweck source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-carol-dweck-fixed-and-growth-mindsets]], a new entity page at [[wiki/entities/carol-dweck]], a new canonical concept page at [[wiki/concepts/leadership/growth-mindset]], and a new synthesis at [[wiki/syntheses/leadership/carol-dweck-growth-mindset-framework]]. Deepened [[wiki/concepts/leadership/high-performance-mindset]], [[wiki/concepts/leadership/organizational-culture]], and [[wiki/concepts/leadership/leadership]] so the leadership branch now preserves Dweck's fixed-versus-growth logic, process-praise distinction, and developmental-culture warning instead of leaving those ideas isolated in a source-only page.

Pages touched:

- [[raw/inbox/2026-04-10-carol-dweck-fixed-and-growth-mindsets]]
- [[wiki/sources/2026-04-10-carol-dweck-fixed-and-growth-mindsets]]
- [[wiki/entities/carol-dweck]]
- [[wiki/concepts/leadership/growth-mindset]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/leadership/organizational-culture]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/syntheses/leadership/carol-dweck-growth-mindset-framework]]
- [[index]]

## [2026-04-10 14:56] ingest | Simon Sinek Golden Circle Framework

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-golden-circle-framework]], a new canonical concept page at [[wiki/concepts/business/golden-circle]], and a new synthesis at [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]. Deepened [[wiki/entities/simon-sinek]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/values-driven-companies]], [[wiki/concepts/leadership/leadership-communication]], and [[wiki/concepts/business/framework-driven-action]] so the Simon Sinek branch now preserves his why-how-what communication model and its overlap with purpose, values, and audience loyalty instead of leaving it trapped in a source-only page.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-golden-circle-framework]]
- [[wiki/sources/2026-04-10-simon-sinek-golden-circle-framework]]
- [[wiki/concepts/business/golden-circle]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/values-driven-companies]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/business/framework-driven-action]]
- [[index]]

## [2026-04-10 15:07] ingest | Casey Neistat Permissionless Creation

Summary: Ingested a new English Casey Neistat source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-casey-neistat-permissionless-creation]], a new entity page at [[wiki/entities/casey-neistat]], a new canonical concept page at [[wiki/concepts/business/permissionless-creation]], and a new synthesis at [[wiki/syntheses/business/casey-neistat-permissionless-creation-framework]]. Deepened [[wiki/concepts/business/creative-entrepreneurship]], [[wiki/concepts/business/career-blueprint]], and [[wiki/concepts/business/framework-driven-action]] so the career branch now preserves creator-economy entry logic, public iteration, and anti-gatekeeper resourcefulness instead of leaving that material as generic motivational prose.

Pages touched:

- [[raw/inbox/2026-04-10-casey-neistat-permissionless-creation]]
- [[wiki/sources/2026-04-10-casey-neistat-permissionless-creation]]
- [[wiki/entities/casey-neistat]]
- [[wiki/concepts/business/permissionless-creation]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/syntheses/business/casey-neistat-permissionless-creation-framework]]
- [[index]]

## [2026-04-10 15:15] ingest | Simon Sinek Incomplete Success Metrics

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-incomplete-success-metrics]], a new canonical concept page at [[wiki/concepts/business/success-metrics]], and a new synthesis at [[wiki/syntheses/business/simon-sinek-success-metrics-framework]]. Deepened [[wiki/entities/simon-sinek]], [[wiki/concepts/leadership/infinite-game-mindset]], [[wiki/concepts/leadership/trust-performance-matrix]], and [[wiki/concepts/business/business-strategy]] so the Simon Sinek branch now preserves the metric-design consequences of purpose and trust instead of leaving them implicit inside earlier source pages.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-incomplete-success-metrics]]
- [[wiki/sources/2026-04-10-simon-sinek-incomplete-success-metrics]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/syntheses/business/simon-sinek-success-metrics-framework]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset]]
- [[wiki/concepts/leadership/trust-performance-matrix]]
- [[wiki/concepts/business/business-strategy]]
- [[index]]

## [2026-04-10 15:25] ingest | Simon Sinek at Equinix Connect 2025

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-at-equinix-connect-2025]] and deepened [[wiki/concepts/business/golden-circle]], [[wiki/concepts/leadership/leadership-communication]], [[wiki/concepts/business/brand-strategy]], [[wiki/syntheses/business/simon-sinek-golden-circle-framework]], and [[wiki/entities/simon-sinek]] so the Simon Sinek branch now preserves purpose-first selling, story as a bridge to `why`, and the relationship-versus-commodity distinction instead of leaving those ideas trapped in the raw note.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-at-equinix-connect-2025]]
- [[wiki/sources/2026-04-10-simon-sinek-at-equinix-connect-2025]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/business/golden-circle]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]
- [[index]]

## [2026-04-10 15:33] ingest | Robert Greene The 48 Laws of Power

Summary: Ingested a new English Robert Greene source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-robert-greene-the-48-laws-of-power]], a new canonical concept page at [[wiki/concepts/communication/power-dynamics]], and a new synthesis at [[wiki/syntheses/communication/robert-greene-power-framework]]. Deepened [[wiki/entities/robert-greene]], [[wiki/concepts/communication/persuasion]], and [[wiki/syntheses/cross-source/communication-and-influence-models]] so the vault now preserves Greene's adversarial power logic, reputation emphasis, and ethical tension instead of folding everything into the earlier human-nature branch.

Pages touched:

- [[raw/inbox/2026-04-10-robert-greene-the-48-laws-of-power]]
- [[wiki/sources/2026-04-10-robert-greene-the-48-laws-of-power]]
- [[wiki/concepts/communication/power-dynamics]]
- [[wiki/syntheses/communication/robert-greene-power-framework]]
- [[wiki/entities/robert-greene]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/syntheses/cross-source/communication-and-influence-models]]
- [[index]]

## [2026-04-10 16:00] ingest | Simon Sinek Trusting Teams and Leadership Environments

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-simon-sinek-trusting-teams-and-leadership-environments]] and deepened [[wiki/entities/simon-sinek]], [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/concepts/leadership/high-performance-team-culture]], [[wiki/concepts/leadership/organizational-culture]], and [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]] so the Simon Sinek branch now preserves leader-built safety, daily trust maintenance, and the environment-design side of trusting teams rather than only the selection side.

Pages touched:

- [[raw/inbox/2026-04-10-simon-sinek-trusting-teams-and-leadership-environments]]
- [[wiki/sources/2026-04-10-simon-sinek-trusting-teams-and-leadership-environments]]
- [[wiki/entities/simon-sinek]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/high-performance-team-culture]]
- [[wiki/concepts/leadership/organizational-culture]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]
- [[index]]

## [2026-04-10 16:03] ingest | Rory Sutherland Bottleneck Theory

Summary: Ingested a new English Rory Sutherland source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-rory-sutherland-bottleneck-theory]] and a new canonical concept page at [[wiki/concepts/business/bottleneck-theory]]. Deepened [[wiki/entities/rory-sutherland]], [[wiki/concepts/business/framework-driven-action]], [[wiki/concepts/business/business-strategy]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]] so the Rory branch now preserves moving-constraint diagnosis and anti-optimization-theater logic instead of limiting him to perception and framing alone.

Pages touched:

- [[raw/inbox/2026-04-10-rory-sutherland-bottleneck-theory]]
- [[wiki/sources/2026-04-10-rory-sutherland-bottleneck-theory]]
- [[wiki/concepts/business/bottleneck-theory]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/concepts/business/framework-driven-action]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-10 16:30] ingest | Выдержки из книги «4 тысячи недель» Оливера Беркмана

Summary: Ingested a new Russian Oliver Burkeman source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-vyderzhki-iz-knigi-4-tysyachi-nedel-olivera-berkmana]], new canonical concept pages at [[wiki/concepts/productivity/konechnost-vremeni]] and [[wiki/concepts/productivity/lovushka-effektivnosti]], a new entity page at [[wiki/entities/oliver-berkman]], and a new synthesis at [[wiki/syntheses/productivity/antiproduktivnyi-freymvork-olivera-berkmana]]. Deepened [[wiki/concepts/productivity/samoupravlenie]], [[wiki/concepts/productivity/uchet-vremeni]], and [[wiki/concepts/productivity/sistemy-vmesto-celei]] so the productivity branch now preserves the tension between operational discipline and the acceptance of finite time instead of treating productivity as pure optimization.

Pages touched:

- [[raw/inbox/2026-04-10-vyderzhki-iz-knigi-4-tysyachi-nedel-olivera-berkmana]]
- [[wiki/sources/2026-04-10-vyderzhki-iz-knigi-4-tysyachi-nedel-olivera-berkmana]]
- [[wiki/concepts/productivity/konechnost-vremeni]]
- [[wiki/concepts/productivity/lovushka-effektivnosti]]
- [[wiki/concepts/productivity/samoupravlenie]]
- [[wiki/concepts/productivity/uchet-vremeni]]
- [[wiki/concepts/productivity/sistemy-vmesto-celei]]
- [[wiki/entities/oliver-berkman]]
- [[wiki/syntheses/productivity/antiproduktivnyi-freymvork-olivera-berkmana]]
- [[index]]

## [2026-04-10 16:45] ingest | Daniel Pink Productivity Wisdom

Summary: Ingested a new English Daniel Pink productivity source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-daniel-pink-productivity-wisdom]], new canonical concept pages at [[wiki/concepts/productivity/peak-hours]] and [[wiki/concepts/productivity/restorative-breaks]], and a new synthesis at [[wiki/syntheses/productivity/daniel-pink-sustainable-productivity-framework]]. Deepened [[wiki/entities/daniel-pink]], [[wiki/concepts/productivity/behavior-journaling]], and [[wiki/concepts/productivity/samoupravlenie]] so the productivity branch now preserves a stronger sustainable-execution layer around prime work windows, visible progress, and recovery instead of leaning only on tracking, discipline, or anti-overload critique.

Pages touched:

- [[raw/inbox/2026-04-10-daniel-pink-productivity-wisdom]]
- [[wiki/sources/2026-04-10-daniel-pink-productivity-wisdom]]
- [[wiki/concepts/productivity/peak-hours]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/concepts/productivity/behavior-journaling]]
- [[wiki/concepts/productivity/samoupravlenie]]
- [[wiki/entities/daniel-pink]]
- [[wiki/syntheses/productivity/daniel-pink-sustainable-productivity-framework]]
- [[index]]

## [2026-04-10 17:00] ingest | Difficult Rewarding Behaviors and Dopamine Regulation

Summary: Ingested a new English self-regulation source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-difficult-rewarding-behaviors-and-dopamine-regulation]], a new canonical concept page at [[wiki/concepts/productivity/dopamine-regulation]], and a new synthesis at [[wiki/syntheses/productivity/difficult-but-rewarding-behaviors-framework]]. Deepened [[wiki/concepts/productivity/restorative-breaks]] and [[wiki/concepts/productivity/samoupravlenie]] so the productivity branch now preserves a clearer distinction between restoration and overstimulation, plus a stronger reward-environment explanation for why meaningful but effortful behaviors are hard to sustain.

Pages touched:

- [[raw/inbox/2026-04-10-difficult-rewarding-behaviors-and-dopamine-regulation]]
- [[wiki/sources/2026-04-10-difficult-rewarding-behaviors-and-dopamine-regulation]]
- [[wiki/concepts/productivity/dopamine-regulation]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/concepts/productivity/samoupravlenie]]
- [[wiki/syntheses/productivity/difficult-but-rewarding-behaviors-framework]]
- [[index]]

## [2026-04-10 17:05] ingest | Mark Manson Mental Toughness and Resilience

Summary: Ingested a new English Mark Manson resilience source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-mark-manson-mental-toughness-and-resilience]], a new canonical concept page at [[wiki/concepts/leadership/mental-toughness]], a new entity page at [[wiki/entities/mark-manson]], and a new synthesis at [[wiki/syntheses/leadership/mark-manson-resilience-framework]]. Deepened [[wiki/concepts/leadership/high-performance-mindset]], [[wiki/concepts/leadership/buoyancy]], and [[wiki/concepts/health/stress-mindset]] so the resilience branch now distinguishes meaningful challenge from both trivial discomfort and overwhelming trauma instead of treating all stress exposure as uniformly developmental.

Pages touched:

- [[raw/inbox/2026-04-10-mark-manson-mental-toughness-and-resilience]]
- [[wiki/sources/2026-04-10-mark-manson-mental-toughness-and-resilience]]
- [[wiki/concepts/leadership/mental-toughness]]
- [[wiki/entities/mark-manson]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/leadership/buoyancy]]
- [[wiki/concepts/health/stress-mindset]]
- [[wiki/syntheses/leadership/mark-manson-resilience-framework]]
- [[index]]

## [2026-04-10 17:10] ingest | Josh Kaufman The First 20 Hours

Summary: Ingested a new English Josh Kaufman learning source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-josh-kaufman-the-first-20-hours]], a new canonical concept page at [[wiki/concepts/productivity/rapid-skill-acquisition]], a new entity page at [[wiki/entities/josh-kaufman]], and a new synthesis at [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]]. This ingest gives the productivity branch a dedicated rapid-learning model centered on functional proficiency, skill deconstruction, self-correction, effortful practice, and sleep-aware consolidation rather than treating learning as only a motivation or time-management issue.

Pages touched:

- [[raw/inbox/2026-04-10-josh-kaufman-the-first-20-hours]]
- [[wiki/sources/2026-04-10-josh-kaufman-the-first-20-hours]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/entities/josh-kaufman]]
- [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]]
- [[index]]

## [2026-04-10 17:20] ingest | Josh Kaufman Frustration Barrier and 20 Hours

Summary: Ingested a second English Josh Kaufman source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-josh-kaufman-frustration-barrier-and-20-hours]] and merged its distinct value into the existing Kaufman branch rather than spawning duplicate concept pages. Deepened [[wiki/concepts/productivity/rapid-skill-acquisition]], [[wiki/entities/josh-kaufman]], and [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]] so the branch now includes the frustration barrier, barrier removal, pre-commitment, and a clearer distinction between knowing what to practice and actually surviving the beginner phase.

Pages touched:

- [[raw/inbox/2026-04-10-josh-kaufman-frustration-barrier-and-20-hours]]
- [[wiki/sources/2026-04-10-josh-kaufman-frustration-barrier-and-20-hours]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/entities/josh-kaufman]]
- [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]]
- [[index]]

## [2026-04-10 17:30] ingest | Locus of Control and Sustained Motivation

Summary: Ingested a new English motivation source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-locus-of-control-and-sustained-motivation]], a new canonical concept page at [[wiki/concepts/leadership/locus-of-control]], and a new synthesis at [[wiki/syntheses/leadership/locus-of-control-motivation-framework]]. Deepened [[wiki/concepts/leadership/growth-mindset]] and [[wiki/concepts/leadership/mental-toughness]] so the leadership branch now distinguishes between whether abilities can grow, whether actions influence outcomes, and how people function once adversity is already underway.

Pages touched:

- [[raw/inbox/2026-04-10-locus-of-control-and-sustained-motivation]]
- [[wiki/sources/2026-04-10-locus-of-control-and-sustained-motivation]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/concepts/leadership/growth-mindset]]
- [[wiki/concepts/leadership/mental-toughness]]
- [[wiki/syntheses/leadership/locus-of-control-motivation-framework]]
- [[index]]

## [2026-04-10 17:40] ingest | Mark Manson Feeling Lost and Reinvention

Summary: Ingested a second English Mark Manson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-mark-manson-feeling-lost-and-reinvention]], a new canonical concept page at [[wiki/concepts/leadership/feeling-lost-as-transition]], and a new synthesis at [[wiki/syntheses/leadership/mark-manson-reinvention-framework]]. Deepened [[wiki/entities/mark-manson]] and [[wiki/concepts/leadership/high-performance-mindset]] so the Manson branch now distinguishes between resilience under challenge and existential reinvention after drift, comparison, or post-success emptiness.

Pages touched:

- [[raw/inbox/2026-04-10-mark-manson-feeling-lost-and-reinvention]]
- [[wiki/sources/2026-04-10-mark-manson-feeling-lost-and-reinvention]]
- [[wiki/concepts/leadership/feeling-lost-as-transition]]
- [[wiki/entities/mark-manson]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/syntheses/leadership/mark-manson-reinvention-framework]]
- [[index]]

## [2026-04-10 17:50] ingest | Andrew Huberman Morning Routine

Summary: Ingested a new English Andrew Huberman source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-10-andrew-huberman-morning-routine]], a new entity page at [[wiki/entities/andrew-huberman]], and a new synthesis at [[wiki/syntheses/health/andrew-huberman-morning-framework]]. Deepened [[wiki/concepts/health/circadian-alignment]] and [[wiki/concepts/productivity/peak-hours]] so the vault now links circadian timing more explicitly to morning sequencing, hydration, caffeine timing, distraction control, and early cognitive work rather than treating `prime hours` as only a calendar preference.

Pages touched:

- [[raw/inbox/2026-04-10-andrew-huberman-morning-routine]]
- [[wiki/sources/2026-04-10-andrew-huberman-morning-routine]]
- [[wiki/entities/andrew-huberman]]
- [[wiki/concepts/health/circadian-alignment]]
- [[wiki/concepts/productivity/peak-hours]]
- [[wiki/syntheses/health/andrew-huberman-morning-framework]]
- [[index]]

## [2026-04-11 01:25] ingest | ADHD and Anxiety Executive Function Overlap

Summary: Ingested a new English health source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-adhd-and-anxiety-executive-function-overlap]], new canonical concept pages at [[wiki/concepts/health/adhd-and-anxiety-overlap]], [[wiki/concepts/health/executive-function-scaffolding]], and [[wiki/concepts/health/body-doubling]], plus a new synthesis at [[wiki/syntheses/health/adhd-anxiety-management-framework]]. Also deepened [[wiki/concepts/health/stress-mindset]] so the health branch now distinguishes symptom overlap from root-cause difference and captures a support-centered management model built around executive-function scaffolds, social regulation, and slower decisions under overwhelm.

Pages touched:

- [[raw/inbox/2026-04-11-adhd-and-anxiety-executive-function-overlap]]
- [[wiki/sources/2026-04-11-adhd-and-anxiety-executive-function-overlap]]
- [[wiki/concepts/health/adhd-and-anxiety-overlap]]
- [[wiki/concepts/health/executive-function-scaffolding]]
- [[wiki/concepts/health/body-doubling]]
- [[wiki/concepts/health/stress-mindset]]
- [[wiki/syntheses/health/adhd-anxiety-management-framework]]
- [[index]]

## [2026-04-11 02:45] ingest | Judson Brewer Mindfulness and Habit Loops

Summary: Ingested a new English health source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-judson-brewer-mindfulness-and-habit-loops]], a new entity page at [[wiki/entities/judson-brewer]], new canonical concept pages at [[wiki/concepts/health/reward-based-habit-loops]], [[wiki/concepts/health/mindful-curiosity]], and [[wiki/concepts/health/disenchantment]], plus a new synthesis at [[wiki/syntheses/health/judson-brewer-habit-change-framework]]. Also deepened [[wiki/concepts/health/stress-mindset]] so the health branch now contains a clearer behavior-change mechanism for cravings and compulsive habits built around curiosity, reward updating, and the limits of willpower under stress.

Pages touched:

- [[raw/inbox/2026-04-11-judson-brewer-mindfulness-and-habit-loops]]
- [[wiki/sources/2026-04-11-judson-brewer-mindfulness-and-habit-loops]]
- [[wiki/entities/judson-brewer]]
- [[wiki/concepts/health/reward-based-habit-loops]]
- [[wiki/concepts/health/mindful-curiosity]]
- [[wiki/concepts/health/disenchantment]]
- [[wiki/concepts/health/stress-mindset]]
- [[wiki/syntheses/health/judson-brewer-habit-change-framework]]
- [[index]]

## [2026-04-11 02:55] ingest | Effective Practice and Skill Learning

Summary: Ingested a new English productivity source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-effective-practice-and-skill-learning]] and a new canonical concept page at [[wiki/concepts/productivity/effective-practice]], then merged the source's distinct value into [[wiki/concepts/productivity/rapid-skill-acquisition]] and [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]] rather than spawning a redundant parallel learning branch. The productivity branch now captures myelination, slow-before-fast repetition, mental rehearsal, and short break-aware practice structure as part of what makes learning repetitions actually compound.

Pages touched:

- [[raw/inbox/2026-04-11-effective-practice-and-skill-learning]]
- [[wiki/sources/2026-04-11-effective-practice-and-skill-learning]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/syntheses/productivity/josh-kaufman-rapid-skill-acquisition-framework]]
- [[index]]

## [2026-04-11 03:05] ingest | Mark Manson Hard-Learned Life Lessons

Summary: Ingested a new English Mark Manson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-mark-manson-hard-learned-life-lessons]] and a new canonical concept page at [[wiki/concepts/leadership/better-problems]], then merged the source's distinct value into [[wiki/concepts/leadership/mental-toughness]], [[wiki/concepts/leadership/feeling-lost-as-transition]], [[wiki/entities/mark-manson]], and [[wiki/syntheses/leadership/mark-manson-resilience-framework]] rather than splitting the Manson branch into near-duplicates. The leadership branch now captures sacrifice-defined identity, conflict muscle, self-prioritization, and the idea that growth means graduating into better problems rather than escaping struggle.

Pages touched:

- [[raw/inbox/2026-04-11-mark-manson-hard-learned-life-lessons]]
- [[wiki/sources/2026-04-11-mark-manson-hard-learned-life-lessons]]
- [[wiki/concepts/leadership/better-problems]]
- [[wiki/concepts/leadership/mental-toughness]]
- [[wiki/concepts/leadership/feeling-lost-as-transition]]
- [[wiki/entities/mark-manson]]
- [[wiki/syntheses/leadership/mark-manson-resilience-framework]]
- [[index]]

## [2026-04-11 03:16] ingest | Sean Carroll Physics, Philosophy, and Meaning

Summary: Ingested a new English Sean Carroll source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-sean-carroll-physics-philosophy-and-meaning]], a new entity page at [[wiki/entities/sean-carroll]], three new canonical concept pages at [[wiki/concepts/others/emergence-and-levels-of-explanation]], [[wiki/concepts/others/arrow-of-time-and-entropy]], and [[wiki/concepts/others/naturalistic-meaning]], plus a new synthesis at [[wiki/syntheses/others/sean-carroll-poetic-naturalism-framework]]. The `others` branch now captures lawful-pattern explanation over naive teleological causality, entropy as the backdrop for time asymmetry and complexity, and a naturalistic defense of meaning inside finite physical life.

Pages touched:

- [[raw/inbox/2026-04-11-sean-carroll-physics-philosophy-and-meaning]]
- [[wiki/sources/2026-04-11-sean-carroll-physics-philosophy-and-meaning]]
- [[wiki/entities/sean-carroll]]
- [[wiki/concepts/others/emergence-and-levels-of-explanation]]
- [[wiki/concepts/others/arrow-of-time-and-entropy]]
- [[wiki/concepts/others/naturalistic-meaning]]
- [[wiki/syntheses/others/sean-carroll-poetic-naturalism-framework]]
- [[index]]

## [2026-04-11 21:20] ingest | Garry Kasparov, Moderated by Demis Hassabis

Summary: Ingested a new English Kasparov source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-garry-kasparov-moderated-by-demis-hassabis]], new entity pages at [[wiki/entities/garry-kasparov]] and [[wiki/entities/demis-hassabis]], a new canonical AI concept page at [[wiki/concepts/ai/human-machine-collaboration]], and a new synthesis at [[wiki/syntheses/ai/kasparov-human-machine-collaboration-framework]]. Also merged the source's chess-training value into [[wiki/concepts/chess/training-with-chess-bots]] so the chess branch now captures a stronger `calculator not oracle` model for engine use rather than leaving that insight trapped in the AI branch alone.

Pages touched:

- [[raw/inbox/2026-04-11-garry-kasparov-moderated-by-demis-hassabis]]
- [[wiki/sources/2026-04-11-garry-kasparov-moderated-by-demis-hassabis]]
- [[wiki/entities/garry-kasparov]]
- [[wiki/entities/demis-hassabis]]
- [[wiki/concepts/ai/human-machine-collaboration]]
- [[wiki/concepts/chess/training-with-chess-bots]]
- [[wiki/syntheses/ai/kasparov-human-machine-collaboration-framework]]
- [[index]]

## [2026-04-11 21:25] ingest | Ron Siegel Evidence-Based Introduction to Mindfulness

Summary: Ingested a new English Ron Siegel source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-ron-siegel-evidence-based-introduction-to-mindfulness]], a new entity page at [[wiki/entities/ron-siegel]], two new canonical health concepts at [[wiki/concepts/health/mindfulness]] and [[wiki/concepts/health/experiential-avoidance]], and a new synthesis at [[wiki/syntheses/health/ron-siegel-mindfulness-framework]]. Also merged the overlap back into [[wiki/concepts/health/mindful-curiosity]] so the health branch now distinguishes broader mindfulness from Brewer's narrower curiosity-based habit-change use case instead of leaving both collapsed together.

Pages touched:

- [[raw/inbox/2026-04-11-ron-siegel-evidence-based-introduction-to-mindfulness]]
- [[wiki/sources/2026-04-11-ron-siegel-evidence-based-introduction-to-mindfulness]]
- [[wiki/entities/ron-siegel]]
- [[wiki/concepts/health/mindfulness]]
- [[wiki/concepts/health/experiential-avoidance]]
- [[wiki/concepts/health/mindful-curiosity]]
- [[wiki/syntheses/health/ron-siegel-mindfulness-framework]]
- [[index]]

## [2026-04-11 21:33] ingest | Tim Ferriss Monkey Mind Systems and Stoic Tools

Summary: Ingested a new English Tim Ferriss source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-tim-ferriss-monkey-mind-systems-and-stoic-tools]], a new entity page at [[wiki/entities/tim-ferriss]], a new canonical productivity concept at [[wiki/concepts/productivity/voluntary-discomfort]], and a new synthesis at [[wiki/syntheses/productivity/tim-ferriss-self-management-framework]]. Also merged the source's journaling overlap into [[wiki/concepts/productivity/behavior-journaling]] so the productivity branch now includes journaling as cognitive offload and monkey-mind management, not only as measurement and progress tracking.

Pages touched:

- [[raw/inbox/2026-04-11-tim-ferriss-monkey-mind-systems-and-stoic-tools]]
- [[wiki/sources/2026-04-11-tim-ferriss-monkey-mind-systems-and-stoic-tools]]
- [[wiki/entities/tim-ferriss]]
- [[wiki/concepts/productivity/voluntary-discomfort]]
- [[wiki/concepts/productivity/behavior-journaling]]
- [[wiki/syntheses/productivity/tim-ferriss-self-management-framework]]
- [[index]]

## [2026-04-11 21:50] ingest | Kelly McGonigal Willpower and Self-Control

Summary: Ingested a new English Kelly McGonigal source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-kelly-mcgonigal-willpower-and-self-control]], a new canonical productivity concept at [[wiki/concepts/productivity/willpower]], and a new synthesis at [[wiki/syntheses/productivity/kelly-mcgonigal-willpower-framework]]. Also merged the source's overlap into [[wiki/entities/kelly-mcgonigal]], [[wiki/concepts/productivity/future-self-prioritization]], and [[wiki/concepts/health/mindfulness]] so the vault now preserves a fuller self-regulation model built around physiology, future-self vividness, self-compassion after lapses, and urge management rather than leaving the branch split between stress material and isolated habit pages.

Pages touched:

- [[raw/inbox/2026-04-11-kelly-mcgonigal-willpower-and-self-control]]
- [[wiki/sources/2026-04-11-kelly-mcgonigal-willpower-and-self-control]]
- [[wiki/concepts/productivity/willpower]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/health/mindfulness]]
- [[wiki/entities/kelly-mcgonigal]]
- [[wiki/syntheses/productivity/kelly-mcgonigal-willpower-framework]]
- [[index]]

## [2026-04-11 22:05] ingest | Barbara Oakley Learning How to Learn

Summary: Ingested a new English Barbara Oakley source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-barbara-oakley-learning-how-to-learn]], a new entity page at [[wiki/entities/barbara-oakley]], new canonical productivity concepts at [[wiki/concepts/productivity/focused-and-diffuse-learning-modes]] and [[wiki/concepts/productivity/chunking]], plus a new synthesis at [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]. Also merged the source's overlap into [[wiki/concepts/productivity/effective-practice]], [[wiki/concepts/productivity/rapid-skill-acquisition]], and [[wiki/concepts/productivity/restorative-breaks]] so the learning branch now preserves memory structure, active recall, break-driven integration, and process-based anti-procrastination instead of leaving those ideas trapped in a standalone summary.

Pages touched:

- [[raw/inbox/2026-04-11-barbara-oakley-learning-how-to-learn]]
- [[wiki/sources/2026-04-11-barbara-oakley-learning-how-to-learn]]
- [[wiki/entities/barbara-oakley]]
- [[wiki/concepts/productivity/focused-and-diffuse-learning-modes]]
- [[wiki/concepts/productivity/chunking]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]
- [[index]]

## [2026-04-11 22:20] ingest | Yuval Noah Harari 21 Lessons for the 21st Century

Summary: Ingested a new English Yuval Noah Harari source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-yuval-noah-harari-21-lessons-for-the-21st-century]], a new entity page at [[wiki/entities/yuval-noah-harari]], a new canonical AI concept at [[wiki/concepts/ai/ai-and-biotechnology-convergence]], a new canonical `others` concept at [[wiki/concepts/others/shared-fictions]], and a new AI synthesis at [[wiki/syntheses/ai/harari-ai-governance-and-self-knowledge-framework]]. Also deepened [[wiki/concepts/ai/artificial-intelligence]] so the AI branch now captures governance, autonomy, and manipulation risk rather than remaining mostly technical and workflow-oriented.

Pages touched:

- [[raw/inbox/2026-04-11-yuval-noah-harari-21-lessons-for-the-21st-century]]
- [[wiki/sources/2026-04-11-yuval-noah-harari-21-lessons-for-the-21st-century]]
- [[wiki/entities/yuval-noah-harari]]
- [[wiki/concepts/ai/ai-and-biotechnology-convergence]]
- [[wiki/concepts/others/shared-fictions]]
- [[wiki/concepts/ai/artificial-intelligence]]
- [[wiki/syntheses/ai/harari-ai-governance-and-self-knowledge-framework]]
- [[index]]

## [2026-04-11 22:35] ingest | Jordan Peterson Wasting Time and Responsibility

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-jordan-peterson-wasting-time-and-responsibility]], a new canonical leadership concept at [[wiki/concepts/leadership/meaning-through-responsibility]], and a new synthesis at [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]. Also deepened [[wiki/entities/jordan-peterson]], [[wiki/concepts/leadership/locus-of-control]], and [[wiki/concepts/leadership/high-performance-mindset]] so the Peterson branch now includes wasted time, conscience, accepted burden, and the social consequences of personal irresponsibility rather than remaining limited to assertiveness and agreeableness.

Pages touched:

- [[raw/inbox/2026-04-11-jordan-peterson-wasting-time-and-responsibility]]
- [[wiki/sources/2026-04-11-jordan-peterson-wasting-time-and-responsibility]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]
- [[index]]

## [2026-04-11 22:45] ingest | Science and Application of Visual Design Principles

Summary: Ingested a new English visual-design source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-science-and-application-of-visual-design-principles]], a new creativity concept at [[wiki/concepts/creativity/visual-hierarchy]], and a new creativity synthesis at [[wiki/syntheses/creativity/human-centered-visual-design-framework]]. Also deepened [[wiki/concepts/creativity/graphic-design]] and [[wiki/concepts/creativity/visual-literacy]] so the design branch now captures perceptual scanning, focal points, contrast, grouping, and simplification instead of leaning mostly on expressive or cinematic visual language.

Pages touched:

- [[raw/inbox/2026-04-11-science-and-application-of-visual-design-principles]]
- [[wiki/sources/2026-04-11-science-and-application-of-visual-design-principles]]
- [[wiki/concepts/creativity/visual-hierarchy]]
- [[wiki/concepts/creativity/graphic-design]]
- [[wiki/concepts/creativity/visual-literacy]]
- [[wiki/syntheses/creativity/human-centered-visual-design-framework]]
- [[index]]

## [2026-04-11 22:55] ingest | Seth Godin Challenges Creators and Entrepreneurs to Reject the Average for the Masses

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-seth-godin-challenges-creators-and-entrepreneurs-to-reject-the-average-for-the-masses]], a new entity page at [[wiki/entities/seth-godin]], a new canonical business concept at [[wiki/concepts/business/smallest-viable-audience]], and a new business synthesis at [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]. Also deepened [[wiki/concepts/business/brand-strategy]] and [[wiki/concepts/business/permissionless-creation]] so the business branch now captures anti-average positioning, permission, tribe formation, and audience selection more explicitly instead of leaving those ideas diffused across adjacent creator and marketing notes.

Pages touched:

- [[raw/inbox/2026-04-11-seth-godin-challenges-creators-and-entrepreneurs-to-reject-the-average-for-the-masses]]
- [[wiki/sources/2026-04-11-seth-godin-challenges-creators-and-entrepreneurs-to-reject-the-average-for-the-masses]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/permissionless-creation]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-11 23:05] ingest | Robert Greene Presentation at Google: Mastery

Summary: Ingested a new English Robert Greene mastery source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-robert-greene-presentation-at-google-mastery]], a new creativity concept at [[wiki/concepts/creativity/negative-capability]], and a new productivity synthesis at [[wiki/syntheses/productivity/robert-greene-mastery-framework]]. Also deepened [[wiki/entities/robert-greene]], [[wiki/concepts/productivity/rapid-skill-acquisition]], and [[wiki/concepts/productivity/effective-practice]] so the vault now makes the tension between fast competence and long apprenticeship explicit instead of treating learning mostly as practice design and early-skill compression.

Pages touched:

- [[raw/inbox/2026-04-11-robert-greene-presentation-at-google-mastery]]
- [[wiki/sources/2026-04-11-robert-greene-presentation-at-google-mastery]]
- [[wiki/concepts/creativity/negative-capability]]
- [[wiki/entities/robert-greene]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[index]]

## [2026-04-11 23:15] ingest | Seth Godin The Practice and Process Over Outcomes

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-seth-godin-the-practice-and-process-over-outcomes]], a new canonical business concept at [[wiki/concepts/business/process-over-outcomes]], and then deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/permissionless-creation]], [[wiki/concepts/business/creative-entrepreneurship]], [[wiki/concepts/business/smallest-viable-audience]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]. The Seth Godin branch now preserves a fuller creator-operating model built around practice over outcomes, identity through repeated action, filtered feedback, and generosity as a steadier compass than scoreboard obsession.

Pages touched:

- [[raw/inbox/2026-04-11-seth-godin-the-practice-and-process-over-outcomes]]
- [[wiki/sources/2026-04-11-seth-godin-the-practice-and-process-over-outcomes]]
- [[wiki/concepts/business/process-over-outcomes]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/permissionless-creation]]
- [[wiki/concepts/business/creative-entrepreneurship]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-11 23:25] ingest | Values, Motivation, and Sustainable Self-Improvement

Summary: Ingested a new English motivation source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-values-motivation-and-sustainable-self-improvement]], a new canonical leadership concept at [[wiki/concepts/leadership/values-driven-action]], and a new synthesis at [[wiki/syntheses/leadership/values-driven-motivation-framework]]. Also deepened [[wiki/concepts/leadership/locus-of-control]], [[wiki/concepts/leadership/high-performance-mindset]], [[wiki/concepts/productivity/future-self-prioritization]], and [[wiki/syntheses/leadership/locus-of-control-motivation-framework]] so the motivation branch now distinguishes values-driven effort from desire-, emotion-, and prestige-driven effort instead of treating agency alone as enough.

Pages touched:

- [[raw/inbox/2026-04-11-values-motivation-and-sustainable-self-improvement]]
- [[wiki/sources/2026-04-11-values-motivation-and-sustainable-self-improvement]]
- [[wiki/concepts/leadership/values-driven-action]]
- [[wiki/syntheses/leadership/values-driven-motivation-framework]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/syntheses/leadership/locus-of-control-motivation-framework]]
- [[index]]

## [2026-04-11 23:35] ingest | Matthew McConaughey on Fame, Commitment, and Meaning

Summary: Ingested a new English Matthew McConaughey source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-matthew-mcconaughey-on-fame-commitment-and-meaning]], a new entity page at [[wiki/entities/matthew-mcconaughey]], a new canonical leadership concept at [[wiki/concepts/leadership/owners-mentality]], and a new synthesis at [[wiki/syntheses/leadership/matthew-mcconaughey-commitment-framework]]. Also deepened [[wiki/concepts/leadership/meaning-through-responsibility]], [[wiki/concepts/leadership/values-driven-action]], and [[wiki/concepts/leadership/high-performance-mindset]] so the leadership branch now captures wholehearted commitment, the hidden cost of fame and validation, and values-based sacrifice as part of meaning rather than leaving those ideas trapped in a celebrity-interview summary.

Pages touched:

- [[raw/inbox/2026-04-11-matthew-mcconaughey-on-fame-commitment-and-meaning]]
- [[wiki/sources/2026-04-11-matthew-mcconaughey-on-fame-commitment-and-meaning]]
- [[wiki/entities/matthew-mcconaughey]]
- [[wiki/concepts/leadership/owners-mentality]]
- [[wiki/syntheses/leadership/matthew-mcconaughey-commitment-framework]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[wiki/concepts/leadership/values-driven-action]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[index]]

## [2026-04-11 23:45] ingest | Quiet Eye, Visual Attention, and Skill Performance

Summary: Ingested a new English performance-science source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-quiet-eye-visual-attention-and-skill-performance]], a new canonical `others` concept at [[wiki/concepts/others/quiet-eye]], and a new synthesis at [[wiki/syntheses/others/quiet-eye-performance-framework]]. Also deepened [[wiki/concepts/productivity/effective-practice]], [[wiki/concepts/leadership/high-performance-mindset]], and [[wiki/concepts/chess/board-vision]] so the vault now captures visual attention and quiet-eye fixation as part of elite execution rather than leaving `focus` and `seeing the board` too vague. The source page explicitly excludes unrelated appended material in the raw note that overlaps with already-ingested motivation and expertise branches.

Pages touched:

- [[raw/inbox/2026-04-11-quiet-eye-visual-attention-and-skill-performance]]
- [[wiki/sources/2026-04-11-quiet-eye-visual-attention-and-skill-performance]]
- [[wiki/concepts/others/quiet-eye]]
- [[wiki/syntheses/others/quiet-eye-performance-framework]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/chess/board-vision]]
- [[index]]

## [2026-04-11 23:58] ingest | Seth Godin This Is Strategy

Summary: Ingested a new English Seth Godin strategy source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-seth-godin-this-is-strategy]] and a new synthesis at [[wiki/syntheses/business/seth-godin-strategy-framework]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/business-strategy]], [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/smallest-viable-audience]], [[wiki/concepts/business/success-metrics]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the business branch now captures Godin's systems-time-games-empathy model, customer and competitor selection, compounding loops, scaffolding, and decision-quality logic instead of leaving those ideas trapped in a single source summary.

Pages touched:

- [[raw/inbox/2026-04-11-seth-godin-this-is-strategy]]
- [[wiki/sources/2026-04-11-seth-godin-this-is-strategy]]
- [[wiki/syntheses/business/seth-godin-strategy-framework]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 00:08] ingest | Seth Godin Magnetic Brand That Sells Itself

Summary: Ingested a new English Seth Godin brand and marketing source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-seth-godin-magnetic-brand-that-sells-itself]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/brand-stewardship]], [[wiki/concepts/business/success-metrics]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures trust versus attention, referrals as a stronger early truth signal than vanity metrics, brand as expectation and promise, and consistency as a stewardship discipline rather than leaving those ideas trapped in an interview summary.

Pages touched:

- [[raw/inbox/2026-04-11-seth-godin-magnetic-brand-that-sells-itself]]
- [[wiki/sources/2026-04-11-seth-godin-magnetic-brand-that-sells-itself]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/brand-stewardship]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 00:16] ingest | Seth Godin Everything You Probably Dont Know About Marketing

Summary: Ingested a new English Seth Godin marketing source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-11-seth-godin-everything-you-probably-dont-know-about-marketing]] and a new business concept at [[wiki/concepts/business/psychographic-targeting]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/smallest-viable-audience]], [[wiki/concepts/business/values-driven-companies]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures brand versus direct marketing, psychographics over demographics, `people like us do things like this`, and the ethics of shaping culture rather than leaving those reusable structures trapped in one interview summary.

Pages touched:

- [[raw/inbox/2026-04-11-seth-godin-everything-you-probably-dont-know-about-marketing]]
- [[wiki/sources/2026-04-11-seth-godin-everything-you-probably-dont-know-about-marketing]]
- [[wiki/concepts/business/psychographic-targeting]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/concepts/business/values-driven-companies]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 00:30] ingest | Seth Godin How to Get Your Ideas to Spread

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-how-to-get-your-ideas-to-spread]] and a new business concept at [[wiki/concepts/business/connection-economy]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/permissionless-creation]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures the connection economy, tribe-led spread, permission and enrollment, and the idea that connected groups carry ideas farther than interruption-heavy mass marketing.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-how-to-get-your-ideas-to-spread]]
- [[wiki/sources/2026-04-12-seth-godin-how-to-get-your-ideas-to-spread]]
- [[wiki/concepts/business/connection-economy]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/permissionless-creation]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 00:46] ingest | Seth Godin Leadership vs. Management What It Means to Make a Difference

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-leadership-vs-management-what-it-means-to-make-a-difference]], a new leadership concept at [[wiki/concepts/leadership/leadership-vs-management]], and a new synthesis at [[wiki/syntheses/leadership/seth-godin-leadership-framework]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/leadership/leadership]], and [[wiki/syntheses/cross-source/high-performance-leadership-models]] so the leadership branch now captures responsibility without authority, the management-versus-leadership distinction, excellence beyond spec quality, and enrollment as a mode of change leadership.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-leadership-vs-management-what-it-means-to-make-a-difference]]
- [[wiki/sources/2026-04-12-seth-godin-leadership-vs-management-what-it-means-to-make-a-difference]]
- [[wiki/concepts/leadership/leadership-vs-management]]
- [[wiki/syntheses/leadership/seth-godin-leadership-framework]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/syntheses/cross-source/high-performance-leadership-models]]
- [[index]]

## [2026-04-12 00:59] ingest | Seth Godin The Secret Strategy To Success

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-the-secret-strategy-to-success]] and a new business concept at [[wiki/concepts/business/strategic-quitting]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/business-strategy]], [[wiki/syntheses/business/seth-godin-strategy-framework]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures dips versus lottery traps, gravity-aware strategy, fear as resistance, and quitting as a decision-quality skill rather than as generic failure.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-the-secret-strategy-to-success]]
- [[wiki/sources/2026-04-12-seth-godin-the-secret-strategy-to-success]]
- [[wiki/concepts/business/strategic-quitting]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/syntheses/business/seth-godin-strategy-framework]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 01:10] ingest | Seth Godin Marketing Strategies That Work

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-marketing-strategies-that-work]] and a new business concept at [[wiki/concepts/business/positioning-as-a-service]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/smallest-viable-audience]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures marketing as ethical change, positioning as a buyer service, the first ten as an early spread test, and price as story rather than as a race to the bottom.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-marketing-strategies-that-work]]
- [[wiki/sources/2026-04-12-seth-godin-marketing-strategies-that-work]]
- [[wiki/concepts/business/positioning-as-a-service]]
- [[wiki/entities/seth-godin]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 01:22] ingest | Purple Cow, How to Be Remarkable, and the Secrets of Marketing

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-purple-cow-how-to-be-remarkable-and-the-secrets-of-marketing]]. Also deepened [[wiki/entities/seth-godin]], [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]], [[wiki/syntheses/leadership/seth-godin-leadership-framework]], and [[wiki/concepts/ai/human-machine-collaboration]] so the branch now captures onlyness, customer-visible remarkability, surfing-style leadership under change, and AI adoption through small real-work pilots plus redesign from first principles.

Pages touched:

- [[raw/inbox/2026-04-12-purple-cow-how-to-be-remarkable-and-the-secrets-of-marketing]]
- [[wiki/sources/2026-04-12-purple-cow-how-to-be-remarkable-and-the-secrets-of-marketing]]
- [[wiki/entities/seth-godin]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[wiki/syntheses/leadership/seth-godin-leadership-framework]]
- [[wiki/concepts/ai/human-machine-collaboration]]
- [[index]]

## [2026-04-12 12:55] ingest | Seth Godin Reveals 5 Secrets For GREAT Brand Marketing

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-reveals-5-secrets-for-great-brand-marketing]] and deepened [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/psychographic-targeting]], [[wiki/concepts/business/success-metrics]], [[wiki/entities/seth-godin]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures brand-versus-direct scoreboard mismatch, vanity-metric distortion, psychographic core-audience logic, and symbolic campaigns that only work when they fit brand DNA.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-reveals-5-secrets-for-great-brand-marketing]]
- [[wiki/sources/2026-04-12-seth-godin-reveals-5-secrets-for-great-brand-marketing]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/psychographic-targeting]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/entities/seth-godin]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 13:05] ingest | Some of the Best Advice I've Received

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-seth-godin-some-of-the-best-advice-ive-received]] and deepened [[wiki/concepts/business/permissionless-creation]], [[wiki/concepts/leadership/locus-of-control]], [[wiki/entities/seth-godin]], and [[wiki/syntheses/leadership/seth-godin-leadership-framework]] so the Seth branch now captures self-picking, anti-rescue agency, victim-to-agent reframing, and the psychological layer behind permissionless action.

Pages touched:

- [[raw/inbox/2026-04-12-seth-godin-some-of-the-best-advice-ive-received]]
- [[wiki/sources/2026-04-12-seth-godin-some-of-the-best-advice-ive-received]]
- [[wiki/concepts/business/permissionless-creation]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/entities/seth-godin]]
- [[wiki/syntheses/leadership/seth-godin-leadership-framework]]
- [[index]]

## [2026-04-12 13:18] ingest | How To Build An Audience That Buys

Summary: Ingested a new English Seth Godin source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-how-to-build-an-audience-that-buys]] and deepened [[wiki/concepts/business/smallest-viable-audience]], [[wiki/concepts/business/connection-economy]], [[wiki/entities/seth-godin]], and [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]] so the Seth branch now captures a five-step audience-building sequence, worldview-aligned story design, word-of-mouth triggers built into social context, and the warning that platform reach can fail to produce buyers.

Pages touched:

- [[raw/inbox/2026-04-12-how-to-build-an-audience-that-buys]]
- [[wiki/sources/2026-04-12-how-to-build-an-audience-that-buys]]
- [[wiki/concepts/business/smallest-viable-audience]]
- [[wiki/concepts/business/connection-economy]]
- [[wiki/entities/seth-godin]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework]]
- [[index]]

## [2026-04-12 13:32] ingest | Unlocking Leadership with Simon Sinek The Infinite Mindset

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-unlocking-leadership-with-simon-sinek-the-infinite-mindset]] and deepened [[wiki/concepts/leadership/infinite-game-mindset]], [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/concepts/leadership/trust-performance-matrix]], [[wiki/entities/simon-sinek]], [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]], and [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]] so the Simon branch now captures leadership as a learnable service skill, people-first structure, vulnerable leadership, tailored feedback, micro-behavior culture design, and rewarding initiative beyond outcome-only logic.

Pages touched:

- [[raw/inbox/2026-04-12-unlocking-leadership-with-simon-sinek-the-infinite-mindset]]
- [[wiki/sources/2026-04-12-unlocking-leadership-with-simon-sinek-the-infinite-mindset]]
- [[wiki/concepts/leadership/infinite-game-mindset]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/trust-performance-matrix]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]
- [[index]]

## [2026-04-12 13:43] ingest | Why good leaders make you feel safe

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-why-good-leaders-make-you-feel-safe]] and deepened [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/concepts/leadership/leadership]], [[wiki/entities/simon-sinek]], and [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]] so the Simon branch now captures the circle of safety, sacrificial leadership, shared-sacrifice crisis design, and leadership as protective behavior rather than formal rank.

Pages touched:

- [[raw/inbox/2026-04-12-why-good-leaders-make-you-feel-safe]]
- [[wiki/sources/2026-04-12-why-good-leaders-make-you-feel-safe]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]
- [[index]]

## [2026-04-12 13:54] ingest | Leaders Eat Last Why Some Teams Pull Together and Others Don't

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-leaders-eat-last-why-some-teams-pull-together-and-others-dont]] and deepened [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/concepts/leadership/leadership]], [[wiki/entities/simon-sinek]], and [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]] so the Simon branch now captures the `leaders eat last` sacrifice standard, internal-versus-external threat design, dopamine/cortisol versus trust-oriented incentive framing, and the cultural damage caused by fear-heavy scoreboards.

Pages touched:

- [[raw/inbox/2026-04-12-leaders-eat-last-why-some-teams-pull-together-and-others-dont]]
- [[wiki/sources/2026-04-12-leaders-eat-last-why-some-teams-pull-together-and-others-dont]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework]]
- [[index]]

## [2026-04-12 14:07] ingest | How Great Leaders Inspire Action

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-how-great-leaders-inspire-action]] and deepened [[wiki/concepts/business/golden-circle]], [[wiki/concepts/leadership/leadership-communication]], [[wiki/entities/simon-sinek]], and [[wiki/syntheses/business/simon-sinek-golden-circle-framework]] so the Simon Golden Circle branch now captures stronger TED examples, clearer innovators-and-early-adopters diffusion logic, and a sharper distinction between formal leaders and `those who lead`.

Pages touched:

- [[raw/inbox/2026-04-12-how-great-leaders-inspire-action]]
- [[wiki/sources/2026-04-12-how-great-leaders-inspire-action]]
- [[wiki/concepts/business/golden-circle]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]
- [[index]]

## [2026-04-12 14:10] ingest | Engage and Inspire Simon Sinek's Guide to Starting with Why

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-engage-and-inspire-simon-sineks-guide-to-starting-with-why]] and deepened [[wiki/concepts/business/golden-circle]], [[wiki/concepts/business/brand-strategy]], [[wiki/entities/simon-sinek]], and [[wiki/syntheses/business/simon-sinek-golden-circle-framework]] so the Simon Golden Circle branch now captures belief-led introductions, worldview-based client qualification, early-adopter prioritization, and strategic refusal of low-alignment buyers.

Pages touched:

- [[raw/inbox/2026-04-12-engage-and-inspire-simon-sineks-guide-to-starting-with-why]]
- [[wiki/sources/2026-04-12-engage-and-inspire-simon-sineks-guide-to-starting-with-why]]
- [[wiki/concepts/business/golden-circle]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]
- [[index]]

## [2026-04-12 14:13] ingest | Authenticity Starts With Knowing Your WHY

Summary: Ingested a new English Simon Sinek source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-authenticity-starts-with-knowing-your-why]] and deepened [[wiki/concepts/business/golden-circle]], [[wiki/concepts/communication/authentic-communication]], [[wiki/concepts/leadership/values-driven-action]], [[wiki/entities/simon-sinek]], and [[wiki/syntheses/business/simon-sinek-golden-circle-framework]] so the Simon `why` branch now captures personal-purpose discovery, authenticity as alignment, the `friends exercise`, and emotional resonance as a clue for naming a core contribution.

Pages touched:

- [[raw/inbox/2026-04-12-authenticity-starts-with-knowing-your-why]]
- [[wiki/sources/2026-04-12-authenticity-starts-with-knowing-your-why]]
- [[wiki/concepts/business/golden-circle]]
- [[wiki/concepts/communication/authentic-communication]]
- [[wiki/concepts/leadership/values-driven-action]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework]]
- [[index]]

## [2026-04-12 01:33] ingest | What To Do To Be Successful Jordan B Peterson

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-what-to-do-to-be-successful-jordan-b-peterson]] plus a new concept page at [[wiki/concepts/productivity/conscientiousness]], and deepened [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/productivity/willpower]], and [[wiki/entities/jordan-peterson]] so the Peterson branch now captures conscientiousness as a reusable concept, multi-domain future design, negotiated scheduling, and a more operational self-management model.

Pages touched:

- [[raw/inbox/2026-04-12-what-to-do-to-be-successful-jordan-b-peterson]]
- [[wiki/sources/2026-04-12-what-to-do-to-be-successful-jordan-b-peterson]]
- [[wiki/concepts/productivity/conscientiousness]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/productivity/willpower]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[index]]

## [2026-04-12 02:28] ingest | Jordan Peterson Becoming Highly Efficient and Productive

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-jordan-peterson-becoming-highly-efficient-and-productive]] plus a new concept page at [[wiki/concepts/productivity/calibrated-challenge]], and deepened [[wiki/concepts/productivity/restorative-breaks]], [[wiki/concepts/leadership/meaning-through-responsibility]], [[wiki/entities/jordan-peterson]], [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]], and [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]] so the Peterson branch now captures calibrated challenge, planned recovery, and long-horizon productivity more explicitly.

Pages touched:

- [[raw/inbox/2026-04-12-jordan-peterson-becoming-highly-efficient-and-productive]]
- [[wiki/sources/2026-04-12-jordan-peterson-becoming-highly-efficient-and-productive]]
- [[wiki/concepts/productivity/calibrated-challenge]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]
- [[index]]

## [2026-04-12 21:10] ingest | Being Disciplined Will Make You Unstoppable

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-being-disciplined-will-make-you-unstoppable]] plus a new concept page at [[wiki/concepts/productivity/value-hierarchy]], and deepened [[wiki/concepts/productivity/conscientiousness]], [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/leadership/values-driven-action]], [[wiki/entities/jordan-peterson]], and [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]] so the Peterson productivity branch now captures discipline as internal governance under a ranked value structure rather than as brute-force suppression alone.

Pages touched:

- [[raw/inbox/2026-04-12-being-disciplined-will-make-you-unstoppable]]
- [[wiki/sources/2026-04-12-being-disciplined-will-make-you-unstoppable]]
- [[wiki/concepts/productivity/value-hierarchy]]
- [[wiki/concepts/productivity/conscientiousness]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/leadership/values-driven-action]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[index]]

## [2026-04-12 21:19] ingest | Jordan Peterson Daily Productivity Routine

Summary: Ingested a new English Jordan Peterson source and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-jordan-peterson-daily-productivity-routine]] plus a new concept page at [[wiki/concepts/productivity/workflow-redesign]], and deepened [[wiki/concepts/productivity/peak-hours]], [[wiki/concepts/productivity/restorative-breaks]], [[wiki/concepts/health/circadian-alignment]], [[wiki/entities/jordan-peterson]], and [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]] so the Peterson productivity branch now captures physiological stability, tactical naps, a capacity-aware view of deep work, and deliberate workflow redesign.

Pages touched:

- [[raw/inbox/2026-04-12-jordan-peterson-daily-productivity-routine]]
- [[wiki/sources/2026-04-12-jordan-peterson-daily-productivity-routine]]
- [[wiki/concepts/productivity/workflow-redesign]]
- [[wiki/concepts/productivity/peak-hours]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/concepts/health/circadian-alignment]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[index]]

## [2026-04-12 21:33] ingest | Jordan Peterson Sorting Your Life

Summary: Ingested a new English Jordan Peterson source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-jordan-peterson-sorting-your-life]] plus a new concept page at [[wiki/concepts/productivity/environmental-order]], and deepened [[wiki/concepts/leadership/meaning-through-responsibility]], [[wiki/concepts/productivity/value-hierarchy]], [[wiki/entities/jordan-peterson]], [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]], and [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]] so the Peterson branch now captures anti-hedonistic meaning, local order, and the leverage of repeated mundane routines.

Pages touched:

- [[raw/inbox/2026-04-12-jordan-peterson-sorting-your-life]]
- [[wiki/sources/2026-04-12-jordan-peterson-sorting-your-life]]
- [[wiki/concepts/productivity/environmental-order]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[wiki/concepts/productivity/value-hierarchy]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[index]]

## [2026-04-12 21:39] ingest | Jordan Peterson Guide to Leadership

Summary: Ingested a new English Jordan Peterson source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-jordan-peterson-guide-to-leadership]], a new concept page at [[wiki/concepts/leadership/voluntary-cooperation]], and a new synthesis at [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]]. Deepened [[wiki/concepts/leadership/leadership]], [[wiki/concepts/leadership/leadership-communication]], [[wiki/concepts/leadership/trust-based-collaboration]], and [[wiki/entities/jordan-peterson]] so the Peterson branch now captures ethical destination, narrative leadership, and voluntary cooperation more explicitly.

Pages touched:

- [[raw/inbox/2026-04-12-jordan-peterson-guide-to-leadership]]
- [[wiki/sources/2026-04-12-jordan-peterson-guide-to-leadership]]
- [[wiki/concepts/leadership/voluntary-cooperation]]
- [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/entities/jordan-peterson]]
- [[index]]

## [2026-04-12 21:44] ingest | The Importance of Character in Leadership Jordan Peterson

Summary: Ingested a new English Jordan Peterson source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-the-importance-of-character-in-leadership-jordan-peterson]] plus a new concept page at [[wiki/concepts/leadership/character-based-leadership]], and deepened [[wiki/concepts/leadership/leadership]], [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/concepts/productivity/conscientiousness]], [[wiki/entities/jordan-peterson]], and [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]] so the Peterson branch now captures characterological leadership, trustworthiness, and the distinction between style and reliability.

Pages touched:

- [[raw/inbox/2026-04-12-the-importance-of-character-in-leadership-jordan-peterson]]
- [[wiki/sources/2026-04-12-the-importance-of-character-in-leadership-jordan-peterson]]
- [[wiki/concepts/leadership/character-based-leadership]]
- [[wiki/concepts/leadership/leadership]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/productivity/conscientiousness]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]]
- [[index]]

## [2026-04-12 21:52] ingest | Your Job Is Not To Motivate People

Summary: Ingested a new English Jordan Peterson source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-your-job-is-not-to-motivate-people]] and deepened [[wiki/concepts/leadership/leadership-communication]], [[wiki/concepts/leadership/voluntary-cooperation]], [[wiki/entities/jordan-peterson]], and [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]] so the Peterson leadership branch now captures a sharper anti-`motivation` framing, explicit goal-role-mutual-benefit communication, and progress-based engagement.

Pages touched:

- [[raw/inbox/2026-04-12-your-job-is-not-to-motivate-people]]
- [[wiki/sources/2026-04-12-your-job-is-not-to-motivate-people]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/concepts/leadership/voluntary-cooperation]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/syntheses/leadership/jordan-peterson-leadership-framework]]
- [[index]]

## [2026-04-12 21:58] ingest | Focusing Is About Saying No Steve Jobs

Summary: Ingested a new English Steve Jobs source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-focusing-is-about-saying-no-steve-jobs]], a new concept page at [[wiki/concepts/business/strategic-focus]], and a new synthesis at [[wiki/syntheses/business/steve-jobs-focus-framework]]. Deepened [[wiki/concepts/business/business-strategy]] and [[wiki/entities/steve-jobs]] so the Steve Jobs branch now captures strategic focus as refusal, portfolio coherence, and the leadership cost of killing misaligned work.

Pages touched:

- [[raw/inbox/2026-04-12-focusing-is-about-saying-no-steve-jobs]]
- [[wiki/sources/2026-04-12-focusing-is-about-saying-no-steve-jobs]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/syntheses/business/steve-jobs-focus-framework]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/entities/steve-jobs]]
- [[index]]

## [2026-04-12 22:03] ingest | Steve Jobs MIT 1992

Summary: Ingested a new English Steve Jobs source from `raw/` and archived the canonical raw file under `raw/inbox/`. Created a new source page at [[wiki/sources/2026-04-12-steve-jobs-mit-1992]], a new concept page at [[wiki/concepts/business/operational-productivity]], and a new synthesis at [[wiki/syntheses/business/steve-jobs-next-framework]]. Deepened [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/business-strategy]], and [[wiki/entities/steve-jobs]] so the Steve Jobs branch now captures operational productivity, integrated company design, ownership, and long-window technology strategy.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-mit-1992]]
- [[wiki/sources/2026-04-12-steve-jobs-mit-1992]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/syntheses/business/steve-jobs-next-framework]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/entities/steve-jobs]]
- [[index]]

## [2026-04-12 22:06] ingest | Steve Jobs Think Different and Stanford Excerpts

Summary: Ingested a new English Steve Jobs composite source from `raw/` and archived the canonical raw file under [[raw/inbox/2026-04-12-steve-jobs-think-different-and-stanford-excerpts]]. Created a new source page at [[wiki/sources/2026-04-12-steve-jobs-think-different-and-stanford-excerpts]] and a new synthesis at [[wiki/syntheses/business/steve-jobs-think-different-framework]]. Deepened [[wiki/entities/steve-jobs]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/values-driven-companies]], [[wiki/concepts/business/strategic-focus]], [[wiki/concepts/business/brand-stewardship]], and [[wiki/concepts/business/business-systems]] so the Steve Jobs branch now captures values-first brand communication, customer-legible focus, and distribution speed as strategic feedback infrastructure.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-think-different-and-stanford-excerpts]]
- [[wiki/sources/2026-04-12-steve-jobs-think-different-and-stanford-excerpts]]
- [[wiki/syntheses/business/steve-jobs-think-different-framework]]
- [[wiki/entities/steve-jobs]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/values-driven-companies]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/business/brand-stewardship]]
- [[wiki/concepts/business/business-systems]]
- [[index]]

## [2026-04-12 22:11] ingest | Steve Jobs D8 Conference 2010

Summary: Ingested a new English Steve Jobs source from `raw/` and archived the canonical raw file under [[raw/inbox/2026-04-12-steve-jobs-d8-conference-2010]]. Created a new source page at [[wiki/sources/2026-04-12-steve-jobs-d8-conference-2010]]. Deepened [[wiki/entities/steve-jobs]], [[wiki/concepts/business/business-strategy]], [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/operational-productivity]], and [[wiki/syntheses/business/steve-jobs-next-framework]] so the Steve Jobs branch now includes a lower-confidence late-career restatement on platform transitions, integrated ecosystems, and the openness-versus-control tradeoff.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-d8-conference-2010]]
- [[wiki/sources/2026-04-12-steve-jobs-d8-conference-2010]]
- [[wiki/entities/steve-jobs]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/syntheses/business/steve-jobs-next-framework]]
- [[index]]

## [2026-04-12 22:14] ingest | Steve Jobs Signal to Noise Success Formula

Summary: Ingested a new English Steve Jobs-adjacent source from `raw/` and archived the canonical raw file under [[raw/inbox/2026-04-12-steve-jobs-signal-to-noise-success-formula]]. Created a new source page at [[wiki/sources/2026-04-12-steve-jobs-signal-to-noise-success-formula]] and a new concept page at [[wiki/concepts/productivity/signal-to-noise-ratio]]. Deepened [[wiki/entities/steve-jobs]], [[wiki/concepts/productivity/peak-hours]], [[wiki/concepts/business/strategic-focus]], and [[wiki/concepts/leadership/high-performance-mindset]] so the vault now has a named place for the daily `3 to 5 high-signal tasks` execution rule, with explicit caveats about anecdotal evidence, personality overreach, and the risk of mistaking harshness for disciplined focus.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-signal-to-noise-success-formula]]
- [[wiki/sources/2026-04-12-steve-jobs-signal-to-noise-success-formula]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/entities/steve-jobs]]
- [[wiki/concepts/productivity/peak-hours]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[index]]

## [2026-04-12 22:17] ingest | Steve Jobs D8 Conference 2010 Re-ingest

Summary: Re-ingested the D8 Steve Jobs source using a corrected raw note and replaced the archived raw file in place at [[raw/inbox/2026-04-12-steve-jobs-d8-conference-2010]]. Rewrote [[wiki/sources/2026-04-12-steve-jobs-d8-conference-2010]] to remove the earlier metadata-derived downgrade and deepen the source around `springtime` technologies, integrated ecosystem tradeoffs, aggressive pricing for volume, idea-driven leadership, and values-preserving decision-making under scrutiny. Updated [[wiki/entities/steve-jobs]], [[wiki/concepts/business/business-strategy]], [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/operational-productivity]], and [[wiki/syntheses/business/steve-jobs-next-framework]] so the D8 material now strengthens the Steve Jobs branch rather than serving mainly as a low-confidence confirmation layer.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-d8-conference-2010]]
- [[wiki/sources/2026-04-12-steve-jobs-d8-conference-2010]]
- [[wiki/entities/steve-jobs]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/syntheses/business/steve-jobs-next-framework]]
- [[index]]

## [2026-04-12 22:20] ingest | All You Need To Work Like Steve Jobs

Summary: Ingested a new English Steve Jobs-adjacent source from `raw/` and archived the canonical raw file under [[raw/inbox/2026-04-12-all-you-need-to-work-like-steve-jobs]]. Created a new source page at [[wiki/sources/2026-04-12-all-you-need-to-work-like-steve-jobs]]. Deepened [[wiki/concepts/productivity/signal-to-noise-ratio]], [[wiki/concepts/business/strategic-focus]], [[wiki/concepts/business/business-systems]], [[wiki/concepts/leadership/high-performance-mindset]], and [[wiki/entities/steve-jobs]] so the Steve Jobs branch now captures a stronger observer-side account of real-sacrifice focus, end-to-end experience control, and the difference between having ideas and finishing coherent products.

Pages touched:

- [[raw/inbox/2026-04-12-all-you-need-to-work-like-steve-jobs]]
- [[wiki/sources/2026-04-12-all-you-need-to-work-like-steve-jobs]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/entities/steve-jobs]]
- [[index]]

## [2026-04-12 22:31] ingest | Steve Jobs Get Much Simpler Be Really Clear

Summary: Ingested a new English Steve Jobs source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-steve-jobs-get-much-simpler-be-really-clear]]. Created [[wiki/sources/2026-04-12-steve-jobs-get-much-simpler-be-really-clear]] as a dedicated source page instead of collapsing it into an older composite, then deepened [[wiki/concepts/business/strategic-focus]], [[wiki/concepts/business/brand-strategy]], [[wiki/concepts/business/business-systems]], [[wiki/entities/steve-jobs]], and [[wiki/syntheses/business/steve-jobs-think-different-framework]] so the 1997 Steve Jobs branch now captures the product-marketing-distribution basics, morale effects of clearer strategy after cuts, and stronger brand-stewardship language about active care rather than legacy alone.

Pages touched:

- [[raw/inbox/2026-04-12-steve-jobs-get-much-simpler-be-really-clear]]
- [[wiki/sources/2026-04-12-steve-jobs-get-much-simpler-be-really-clear]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/entities/steve-jobs]]
- [[wiki/syntheses/business/steve-jobs-think-different-framework]]
- [[index]]

## [2026-04-12 22:40] ingest | The Secret to Elon Musk's Productivity

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-the-secret-to-elon-musks-productivity]]. Created [[wiki/sources/2026-04-12-the-secret-to-elon-musks-productivity]], added the new canonical concept [[wiki/concepts/productivity/serial-tasking]], created [[wiki/entities/elon-musk]], and distilled the branch into [[wiki/syntheses/productivity/elon-musk-serial-focus-framework]]. Updated [[wiki/concepts/productivity/restorative-breaks]], [[wiki/concepts/productivity/signal-to-noise-ratio]], and [[wiki/concepts/leadership/high-performance-mindset]] so the vault now captures clean-switch focus, bottleneck `surges`, support-system dependence, and the personal costs of extreme urgency without flattening the source into hero-model advice.

Pages touched:

- [[raw/inbox/2026-04-12-the-secret-to-elon-musks-productivity]]
- [[wiki/sources/2026-04-12-the-secret-to-elon-musks-productivity]]
- [[wiki/concepts/productivity/serial-tasking]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/entities/elon-musk]]
- [[wiki/syntheses/productivity/elon-musk-serial-focus-framework]]
- [[index]]

## [2026-04-12 22:49] ingest | Elon Musk's Approach to Problem-Solving

Summary: Ingested a new English Elon Musk source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-elon-musks-approach-to-problem-solving]]. Created [[wiki/sources/2026-04-12-elon-musks-approach-to-problem-solving]], added the new canonical concept [[wiki/concepts/business/first-principles-problem-solving]], and distilled the branch into [[wiki/syntheses/business/elon-musk-problem-solving-framework]]. Updated [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/operational-productivity]], [[wiki/concepts/productivity/workflow-redesign]], [[wiki/concepts/business/bottleneck-theory]], and [[wiki/entities/elon-musk]] so the Elon branch now captures requirement challenge, deletion-first redesign, late automation, frontline immersion, and the role of physical infrastructure constraints in advanced systems work.

Pages touched:

- [[raw/inbox/2026-04-12-elon-musks-approach-to-problem-solving]]
- [[wiki/sources/2026-04-12-elon-musks-approach-to-problem-solving]]
- [[wiki/concepts/business/first-principles-problem-solving]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/concepts/productivity/workflow-redesign]]
- [[wiki/concepts/business/bottleneck-theory]]
- [[wiki/entities/elon-musk]]
- [[wiki/syntheses/business/elon-musk-problem-solving-framework]]
- [[index]]

## [2026-04-12 22:58] ingest | Elon Musk on Time Management

Summary: Ingested a new English Elon Musk source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-elon-musk-on-time-management]]. Created [[wiki/sources/2026-04-12-elon-musk-on-time-management]] and used it to deepen [[wiki/entities/elon-musk]], [[wiki/concepts/business/operational-productivity]], [[wiki/concepts/productivity/serial-tasking]], and [[wiki/syntheses/productivity/elon-musk-serial-focus-framework]]. The Elon branch now captures an architect-CEO time model built around engineering-first allocation, delegated operations, factory-as-product thinking, and scheduled attention to secondary initiatives rather than purely ad hoc switching.

Pages touched:

- [[raw/inbox/2026-04-12-elon-musk-on-time-management]]
- [[wiki/sources/2026-04-12-elon-musk-on-time-management]]
- [[wiki/entities/elon-musk]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/concepts/productivity/serial-tasking]]
- [[wiki/syntheses/productivity/elon-musk-serial-focus-framework]]
- [[index]]

## [2026-04-12 23:05] ingest | Marc Andreessen Shares How Elon Musk Achieves Hyper Productivity

Summary: Ingested a new English Elon-adjacent source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-marc-andreessen-shares-how-elon-musk-achieves-hyper-productivity]]. Created [[wiki/sources/2026-04-12-marc-andreessen-shares-how-elon-musk-achieves-hyper-productivity]] and used it to deepen [[wiki/concepts/business/bottleneck-theory]], [[wiki/entities/elon-musk]], and [[wiki/syntheses/business/elon-musk-problem-solving-framework]]. The Elon branch now captures a sharper weekly cadence for one-bottleneck intervention, selective micromanagement of the main constraint, and a more explicit contrast between technical bottleneck-solving leadership and generic management education.

Pages touched:

- [[raw/inbox/2026-04-12-marc-andreessen-shares-how-elon-musk-achieves-hyper-productivity]]
- [[wiki/sources/2026-04-12-marc-andreessen-shares-how-elon-musk-achieves-hyper-productivity]]
- [[wiki/concepts/business/bottleneck-theory]]
- [[wiki/entities/elon-musk]]
- [[wiki/syntheses/business/elon-musk-problem-solving-framework]]
- [[index]]

## [2026-04-12 23:18] ingest | Why You Need To Put In 10,000 Hours

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-why-you-need-to-put-in-10000-hours]]. Created [[wiki/sources/2026-04-12-why-you-need-to-put-in-10000-hours]] and used it to add [[wiki/concepts/productivity/deliberate-practice]], deepen [[wiki/concepts/productivity/effective-practice]], [[wiki/entities/robert-greene]], and [[wiki/syntheses/productivity/robert-greene-mastery-framework]], and create [[wiki/syntheses/cross-source/competence-vs-mastery-learning-models]]. The learning branch now distinguishes more clearly between raw hours and qualified hours, early competence and long-horizon mastery, and technical drills versus live social exposure.

Pages touched:

- [[raw/inbox/2026-04-12-why-you-need-to-put-in-10000-hours]]
- [[wiki/sources/2026-04-12-why-you-need-to-put-in-10000-hours]]
- [[wiki/concepts/productivity/deliberate-practice]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[wiki/syntheses/cross-source/competence-vs-mastery-learning-models]]
- [[index]]

## [2026-04-12 23:27] ingest | Mastery Summarized in 8 Minutes by Robert Greene

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-12-mastery-summarized-in-8-minutes-by-robert-greene]]. Created [[wiki/sources/2026-04-12-mastery-summarized-in-8-minutes-by-robert-greene]] and used it to add [[wiki/concepts/business/mentorship]], deepen [[wiki/concepts/business/zone-of-genius]], [[wiki/concepts/leadership/emotional-intelligence]], [[wiki/entities/robert-greene]], and expand [[wiki/syntheses/productivity/robert-greene-mastery-framework]]. The Greene mastery branch now includes life's task, mentor-mediated acceleration, social intelligence as a compounding factor, and mastery as the fusion of intuition with rational analysis.

Pages touched:

- [[raw/inbox/2026-04-12-mastery-summarized-in-8-minutes-by-robert-greene]]
- [[wiki/sources/2026-04-12-mastery-summarized-in-8-minutes-by-robert-greene]]
- [[wiki/concepts/business/mentorship]]
- [[wiki/concepts/business/zone-of-genius]]
- [[wiki/concepts/leadership/emotional-intelligence]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[index]]

## [2026-04-13 00:41] ingest | The Best Path To Success - Robert Greene

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-best-path-to-success-robert-greene]]. Created [[wiki/sources/2026-04-13-the-best-path-to-success-robert-greene]] and used it to deepen [[wiki/concepts/business/strategic-focus]], [[wiki/concepts/business/career-blueprint]], [[wiki/entities/robert-greene]], and [[wiki/syntheses/productivity/robert-greene-mastery-framework]]. The Greene branch now captures one-vehicle focus, early resource accumulation before diversification, and envy-resistant judgment as part of the mastery path rather than as generic motivation advice.

Pages touched:

- [[raw/inbox/2026-04-13-the-best-path-to-success-robert-greene]]
- [[wiki/sources/2026-04-13-the-best-path-to-success-robert-greene]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[index]]

## [2026-04-13 00:52] ingest | Lessons on Mastery

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-lessons-on-mastery]]. Created [[wiki/sources/2026-04-13-lessons-on-mastery]] and used it to add [[wiki/concepts/productivity/alive-time]], deepen [[wiki/entities/robert-greene]], and expand [[wiki/syntheses/productivity/robert-greene-mastery-framework]]. The Greene mastery branch now explicitly includes alive-versus-dead time, discipline linked to deeper pleasure, and self-critique plus frustration tolerance as part of originality rather than as optional mindset garnish.

Pages touched:

- [[raw/inbox/2026-04-13-lessons-on-mastery]]
- [[wiki/sources/2026-04-13-lessons-on-mastery]]
- [[wiki/concepts/productivity/alive-time]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[index]]

## [2026-04-13 01:03] ingest | Master Psychology to Win Any Competition

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-master-psychology-to-win-any-competition]]. Created [[wiki/sources/2026-04-13-master-psychology-to-win-any-competition]] and used it to add [[wiki/concepts/communication/reputation]], deepen [[wiki/entities/robert-greene]], and expand [[wiki/syntheses/communication/robert-greene-power-framework]]. The Greene power branch now makes reputation, consistency, digital permanence, and credibility collapse explicit rather than leaving them as subpoints inside the older power summary.

Pages touched:

- [[raw/inbox/2026-04-13-master-psychology-to-win-any-competition]]
- [[wiki/sources/2026-04-13-master-psychology-to-win-any-competition]]
- [[wiki/concepts/communication/reputation]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/communication/robert-greene-power-framework]]
- [[index]]

## [2026-04-13 01:10] ingest | The Path To Power: Ambition, Status, Strength & Respect

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-path-to-power-ambition-status-strength-and-respect]]. Created [[wiki/sources/2026-04-13-the-path-to-power-ambition-status-strength-and-respect]] and used it to deepen [[wiki/concepts/communication/reputation]], [[wiki/concepts/communication/power-dynamics]], [[wiki/entities/robert-greene]], [[wiki/syntheses/communication/robert-greene-power-framework]], and [[wiki/syntheses/productivity/robert-greene-mastery-framework]]. The Greene branch now explicitly captures irreplaceability through cultivated weirdness, pressure and adversity as developmental inputs, scarcity rhythm in visibility, and ambition disciplined into contribution rather than vanity.

Pages touched:

- [[raw/inbox/2026-04-13-the-path-to-power-ambition-status-strength-and-respect]]
- [[wiki/sources/2026-04-13-the-path-to-power-ambition-status-strength-and-respect]]
- [[wiki/concepts/communication/reputation]]
- [[wiki/concepts/communication/power-dynamics]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/communication/robert-greene-power-framework]]
- [[wiki/syntheses/productivity/robert-greene-mastery-framework]]
- [[index]]

## [2026-04-13 01:22] ingest | How to DEFEAT Your BOSS Every Time

Summary: Ingested a new English Robert Greene source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-defeat-your-boss-every-time]]. Created [[wiki/sources/2026-04-13-how-to-defeat-your-boss-every-time]] and a new durable [[wiki/syntheses/communication/toxic-boss-response-framework]]. Used the source to deepen [[wiki/concepts/communication/assertiveness]], [[wiki/concepts/communication/boundary-language]], [[wiki/concepts/communication/power-dynamics]], [[wiki/entities/robert-greene]], [[wiki/syntheses/communication/assertiveness-agreeableness-and-self-advocacy]], and [[wiki/syntheses/communication/robert-greene-power-framework]]. The communication branch now captures toxic-authority handling as a distinct model built around depersonalization, emotional non-capture, calibrated self-advocacy, and preserved options rather than direct confrontation alone.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-defeat-your-boss-every-time]]
- [[wiki/sources/2026-04-13-how-to-defeat-your-boss-every-time]]
- [[wiki/syntheses/communication/toxic-boss-response-framework]]
- [[wiki/concepts/communication/assertiveness]]
- [[wiki/concepts/communication/boundary-language]]
- [[wiki/concepts/communication/power-dynamics]]
- [[wiki/entities/robert-greene]]
- [[wiki/syntheses/communication/assertiveness-agreeableness-and-self-advocacy]]
- [[wiki/syntheses/communication/robert-greene-power-framework]]
- [[index]]

## [2026-04-13 01:34] ingest | The Ultimate Sales Training for 2026

Summary: Ingested a new English sales source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-ultimate-sales-training-for-2026]]. Created [[wiki/sources/2026-04-13-the-ultimate-sales-training-for-2026]], added the new concept [[wiki/concepts/business/sales-operations]], and created [[wiki/syntheses/business/modern-sales-systems-framework]]. Used the source to deepen [[wiki/concepts/business/business-systems]] and [[wiki/syntheses/business/scalable-business-systems-framework]]. The business branch now captures a dedicated sales-ops layer built around speed-to-lead, calendar architecture, show-rate management, routing logic, training loops, and post-sale handoff rather than treating sales as conversation technique alone.

Pages touched:

- [[raw/inbox/2026-04-13-the-ultimate-sales-training-for-2026]]
- [[wiki/sources/2026-04-13-the-ultimate-sales-training-for-2026]]
- [[wiki/concepts/business/sales-operations]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/syntheses/business/modern-sales-systems-framework]]
- [[wiki/syntheses/business/scalable-business-systems-framework]]
- [[index]]

## [2026-04-13 01:46] ingest | How Elon Musk solves problems

Summary: Ingested a new English Elon Musk source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-elon-musk-solves-problems]]. Created [[wiki/sources/2026-04-13-how-elon-musk-solves-problems]] and added the new concept [[wiki/concepts/business/platonic-ideal-product]]. Used the source to deepen [[wiki/concepts/business/first-principles-problem-solving]], [[wiki/concepts/business/operational-productivity]], [[wiki/entities/elon-musk]], and [[wiki/syntheses/business/elon-musk-problem-solving-framework]]. The Musk branch now makes physics-first reasoning, limit testing, raw-material-floor cost logic, and ideal-product-first design explicit rather than leaving the branch centered only on deletion order and bottleneck clearing.

Pages touched:

- [[raw/inbox/2026-04-13-how-elon-musk-solves-problems]]
- [[wiki/sources/2026-04-13-how-elon-musk-solves-problems]]
- [[wiki/concepts/business/platonic-ideal-product]]
- [[wiki/concepts/business/first-principles-problem-solving]]
- [[wiki/concepts/business/operational-productivity]]
- [[wiki/entities/elon-musk]]
- [[wiki/syntheses/business/elon-musk-problem-solving-framework]]
- [[index]]

## [2026-04-13 01:10] ingest | First Principles: Elon Musk's Method of Thinking

Summary: Ingested a new English first-principles source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-first-principles-elon-musks-method-of-thinking]]. Created [[wiki/sources/2026-04-13-first-principles-elon-musks-method-of-thinking]] and used it to deepen [[wiki/concepts/business/first-principles-problem-solving]], [[wiki/entities/elon-musk]], and [[wiki/syntheses/business/elon-musk-problem-solving-framework]]. The Musk branch now captures the analogy-versus-first-principles distinction, a reusable four-step goal-to-redesign sequence, and a broader epistemic warning that authority and consensus can preserve bad assumptions.

Pages touched:

- [[raw/inbox/2026-04-13-first-principles-elon-musks-method-of-thinking]]
- [[wiki/sources/2026-04-13-first-principles-elon-musks-method-of-thinking]]
- [[wiki/concepts/business/first-principles-problem-solving]]
- [[wiki/entities/elon-musk]]
- [[wiki/syntheses/business/elon-musk-problem-solving-framework]]
- [[index]]

## [2026-04-13 01:13] ingest | Founder Mode Explained

Summary: Ingested a new English founder-scaling source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-founder-mode-explained]]. Created [[wiki/sources/2026-04-13-founder-mode-explained]], added the new concept [[wiki/concepts/business/founder-mode]], and created [[wiki/syntheses/business/founder-mode-framework]]. Used the source to deepen [[wiki/concepts/business/business-systems]] and [[wiki/concepts/leadership/leadership-vs-management]]. The business branch now captures founder mode as a calibrated alternative to bureaucratic manager mode, with craft-based promotions, task-relevant oversight, DRI-centered decision prep, and a scaling rule of turning duct-tape heroics into metal systems.

Pages touched:

- [[raw/inbox/2026-04-13-founder-mode-explained]]
- [[wiki/sources/2026-04-13-founder-mode-explained]]
- [[wiki/concepts/business/founder-mode]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/leadership/leadership-vs-management]]
- [[wiki/syntheses/business/founder-mode-framework]]
- [[index]]


## [2026-04-13 02:25] ingest | The Cheat Code for Controlling Conflict

Summary: Ingested a new English conflict-control source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-cheat-code-for-controlling-conflict]]. Created [[wiki/sources/2026-04-13-the-cheat-code-for-controlling-conflict]] and the new synthesis [[wiki/syntheses/communication/conflict-frame-control-framework]]. Used the source to deepen [[wiki/concepts/communication/frame-control]], [[wiki/concepts/communication/face-saving-de-escalation]], [[wiki/concepts/communication/boundary-language]], and [[wiki/concepts/communication/effective-communication]]. The communication branch now more clearly captures the ego triangle of identity, control, and safety, pre-framing as conflict prevention, anti-frame-attack rules, and procedural reframing that shifts blame fights back toward workable process.

Pages touched:

- [[raw/inbox/2026-04-13-the-cheat-code-for-controlling-conflict]]
- [[wiki/sources/2026-04-13-the-cheat-code-for-controlling-conflict]]
- [[wiki/syntheses/communication/conflict-frame-control-framework]]
- [[wiki/concepts/communication/frame-control]]
- [[wiki/concepts/communication/face-saving-de-escalation]]
- [[wiki/concepts/communication/boundary-language]]
- [[wiki/concepts/communication/effective-communication]]
- [[index]]

## [2026-04-13 02:21] ingest | How to Improve Your Attention & Focus

Summary: Ingested a new English Huberman-Groh productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-improve-your-attention-and-focus]]. Created [[wiki/sources/2026-04-13-how-to-improve-your-attention-and-focus]] and the new synthesis [[wiki/syntheses/productivity/attention-and-focus-framework]]. Used the source to deepen [[wiki/entities/andrew-huberman]], [[wiki/concepts/productivity/peak-hours]], and [[wiki/concepts/productivity/restorative-breaks]]. The productivity branch now more clearly captures focus as an attractor state shaped by sensory narrowing, interval-style effort, context shifts, and recovery rather than by brute-force willpower alone.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-improve-your-attention-and-focus]]
- [[wiki/sources/2026-04-13-how-to-improve-your-attention-and-focus]]
- [[wiki/syntheses/productivity/attention-and-focus-framework]]
- [[wiki/entities/andrew-huberman]]
- [[wiki/concepts/productivity/peak-hours]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[index]]

## [2026-04-13 02:18] ingest | The Secret Art of Micromanagement with Airbnb CEO Brian Chesky

Summary: Ingested a new English Brian Chesky leadership and founder-mode source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-secret-art-of-micromanagement-with-airbnb-ceo-brian-chesky]]. Created [[wiki/sources/2026-04-13-the-secret-art-of-micromanagement-with-airbnb-ceo-brian-chesky]] and used it to deepen [[wiki/entities/brian-chesky]], [[wiki/concepts/business/founder-mode]], [[wiki/syntheses/business/founder-mode-framework]], [[wiki/concepts/business/business-systems]], and [[wiki/concepts/business/values-driven-companies]]. The Chesky branch now more clearly captures `eyes on, hands off` leadership, standards-to-muscle-memory review, crisis psychology, customer love as a deeper business signal than boardroom abstraction, and values tested through hiring honesty and humane contraction.

Pages touched:

- [[raw/inbox/2026-04-13-the-secret-art-of-micromanagement-with-airbnb-ceo-brian-chesky]]
- [[wiki/sources/2026-04-13-the-secret-art-of-micromanagement-with-airbnb-ceo-brian-chesky]]
- [[wiki/entities/brian-chesky]]
- [[wiki/concepts/business/founder-mode]]
- [[wiki/syntheses/business/founder-mode-framework]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/values-driven-companies]]
- [[index]]

## [2026-04-13 02:13] ingest | Jim Keller: Most People Don't Think Simple Enough

Summary: Ingested a new English first-principles and systems-design source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-jim-keller-most-people-dont-think-simple-enough]]. Created [[wiki/sources/2026-04-13-jim-keller-most-people-dont-think-simple-enough]] and the new entity page [[wiki/entities/jim-keller]]. Used the source to deepen [[wiki/concepts/business/first-principles-problem-solving]] and added [[wiki/syntheses/business/architectural-redesign-from-first-principles]] so the vault now captures recipe-vs-understanding, decomposition failure, rewrite timing, the `two disasters` model, and redesign as a distribution-management problem rather than a guaranteed universal upgrade.

Pages touched:

- [[raw/inbox/2026-04-13-jim-keller-most-people-dont-think-simple-enough]]
- [[wiki/sources/2026-04-13-jim-keller-most-people-dont-think-simple-enough]]
- [[wiki/entities/jim-keller]]
- [[wiki/concepts/business/first-principles-problem-solving]]
- [[wiki/syntheses/business/architectural-redesign-from-first-principles]]
- [[index]]

## [2026-04-13 01:25] ingest | Brian Chesky Founder Mode and the Art of Hiring

Summary: Ingested a new English founder-mode and hiring source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-brian-chesky-founder-mode-and-the-art-of-hiring]]. Created [[wiki/sources/2026-04-13-brian-chesky-founder-mode-and-the-art-of-hiring]] and the new entity page [[wiki/entities/brian-chesky]]. Used the source to deepen [[wiki/concepts/business/founder-mode]], [[wiki/concepts/business/business-systems]], and [[wiki/syntheses/business/founder-mode-framework]]. The founder-mode branch now more clearly preserves functional expert-led org design, CEO review cadence, coordinated launch logic, heavy-reference evidence-based hiring, and Chesky's board-advice skepticism.

Pages touched:

- [[raw/inbox/2026-04-13-brian-chesky-founder-mode-and-the-art-of-hiring]]
- [[wiki/sources/2026-04-13-brian-chesky-founder-mode-and-the-art-of-hiring]]
- [[wiki/entities/brian-chesky]]
- [[wiki/concepts/business/founder-mode]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/syntheses/business/founder-mode-framework]]
- [[index]]

## [2026-04-13 01:17] ingest | We Need to Talk About Founder Mode

Summary: Ingested a new English founder-mode source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-we-need-to-talk-about-founder-mode]]. Created [[wiki/sources/2026-04-13-we-need-to-talk-about-founder-mode]] and used it to deepen [[wiki/concepts/business/founder-mode]], [[wiki/concepts/business/business-systems]], and [[wiki/syntheses/business/founder-mode-framework]]. The founder-mode branch now captures user proximity, bug-response trust, skip-level truth flow, the `don't hire to avoid` rule, and a more explicit warning about investor advice and politics-heavy `professional fakers`.

Pages touched:

- [[raw/inbox/2026-04-13-we-need-to-talk-about-founder-mode]]
- [[wiki/sources/2026-04-13-we-need-to-talk-about-founder-mode]]
- [[wiki/concepts/business/founder-mode]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/syntheses/business/founder-mode-framework]]
- [[index]]

## [2026-04-13 01:20] ingest | Founder Mode: A Summary of Paul Graham's Viral Essay

Summary: Ingested a new English founder-mode source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-founder-mode-a-summary-of-paul-grahams-viral-essay]]. Created [[wiki/sources/2026-04-13-founder-mode-a-summary-of-paul-grahams-viral-essay]] and used it to deepen [[wiki/concepts/business/founder-mode]], [[wiki/concepts/leadership/leadership-vs-management]], and [[wiki/syntheses/business/founder-mode-framework]]. The founder-mode branch now more clearly captures `manage the work, not the team`, coach-mode founder involvement, anti-popularity feedback culture, growth-mindset hiring over pedigree defaults, and `bureaucrat mode` as a concrete organizational failure pattern.

Pages touched:

- [[raw/inbox/2026-04-13-founder-mode-a-summary-of-paul-grahams-viral-essay]]
- [[wiki/sources/2026-04-13-founder-mode-a-summary-of-paul-grahams-viral-essay]]
- [[wiki/concepts/business/founder-mode]]
- [[wiki/concepts/leadership/leadership-vs-management]]
- [[wiki/syntheses/business/founder-mode-framework]]
- [[index]]

## [2026-04-13 02:29] ingest | Rory Sutherland Perspective is Everything

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-rory-sutherland-perspective-is-everything]]. Created [[wiki/sources/2026-04-13-rory-sutherland-perspective-is-everything]] and the new concept page [[wiki/concepts/business/psychological-leverage]]. Used the source to deepen [[wiki/concepts/business/perception-driven-value]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures control-and-uncertainty design, the technical-economic-psychological three-lens model, and low-cost experiential interventions that can outperform brute-force optimization.

Pages touched:

- [[raw/inbox/2026-04-13-rory-sutherland-perspective-is-everything]]
- [[wiki/sources/2026-04-13-rory-sutherland-perspective-is-everything]]
- [[wiki/concepts/business/psychological-leverage]]
- [[wiki/concepts/business/perception-driven-value]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 11:28] ingest | Psychology Hacks of the Worlds Best Advertisers

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-psychology-hacks-of-the-worlds-best-advertisers]]. Created [[wiki/sources/2026-04-13-psychology-hacks-of-the-worlds-best-advertisers]] and the new concept page [[wiki/concepts/business/fat-tailed-marketing]]. Used the source to deepen [[wiki/concepts/business/reverse-benchmarking]], [[wiki/concepts/business/advertising]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures fat-tailed marketing, stronger reverse-benchmarking cases, and explore-versus-exploit logic in creative markets.

Pages touched:

- [[raw/inbox/2026-04-13-psychology-hacks-of-the-worlds-best-advertisers]]
- [[wiki/sources/2026-04-13-psychology-hacks-of-the-worlds-best-advertisers]]
- [[wiki/concepts/business/fat-tailed-marketing]]
- [[wiki/concepts/business/reverse-benchmarking]]
- [[wiki/concepts/business/advertising]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 11:34] ingest | Rory Sutherland Soft Power in a Hard World

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-rory-sutherland-soft-power-in-a-hard-world]]. Created [[wiki/sources/2026-04-13-rory-sutherland-soft-power-in-a-hard-world]] and the new concept page [[wiki/concepts/business/paradigm-shifts]]. Used the source to deepen [[wiki/concepts/business/perception-driven-value]], [[wiki/concepts/business/fat-tailed-marketing]], [[wiki/concepts/business/business-strategy]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures paradigm shifts as soft power, separate explore-versus-exploit governance, and the strategic value of escaping false either/or frames.

Pages touched:

- [[raw/inbox/2026-04-13-rory-sutherland-soft-power-in-a-hard-world]]
- [[wiki/sources/2026-04-13-rory-sutherland-soft-power-in-a-hard-world]]
- [[wiki/concepts/business/paradigm-shifts]]
- [[wiki/concepts/business/perception-driven-value]]
- [[wiki/concepts/business/fat-tailed-marketing]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 11:20] ingest | The Playbook Behind Every Great Campaign

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-playbook-behind-every-great-campaign]]. Created [[wiki/sources/2026-04-13-the-playbook-behind-every-great-campaign]] and the new concept page [[wiki/concepts/business/transaction-utility]]. Used the source to deepen [[wiki/concepts/business/hidden-functions]], [[wiki/concepts/business/brand-strategy]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures transaction utility, doorman-fallacy hidden-value loss, service touchpoints as brand multipliers, and the cost of quantification bias.

Pages touched:

- [[raw/inbox/2026-04-13-the-playbook-behind-every-great-campaign]]
- [[wiki/sources/2026-04-13-the-playbook-behind-every-great-campaign]]
- [[wiki/concepts/business/transaction-utility]]
- [[wiki/concepts/business/hidden-functions]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 11:08] ingest | The Lost Genius of Irrationality Rory Sutherland

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-lost-genius-of-irrationality-rory-sutherland]]. Created [[wiki/sources/2026-04-13-the-lost-genius-of-irrationality-rory-sutherland]] and the new concept page [[wiki/concepts/business/social-heuristics]]. Used the source to deepen [[wiki/concepts/business/psychological-leverage]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures named social scripts, binary rules, network-shaped behavior, and the limits of over-rationalized behavioral models.

Pages touched:

- [[raw/inbox/2026-04-13-the-lost-genius-of-irrationality-rory-sutherland]]
- [[wiki/sources/2026-04-13-the-lost-genius-of-irrationality-rory-sutherland]]
- [[wiki/concepts/business/social-heuristics]]
- [[wiki/concepts/business/psychological-leverage]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 02:33] ingest | How Your Brain Gets Tricked By Clever Marketing

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-your-brain-gets-tricked-by-clever-marketing]]. Created [[wiki/sources/2026-04-13-how-your-brain-gets-tricked-by-clever-marketing]] and the new concept page [[wiki/concepts/business/experience-goods]]. Used the source to deepen [[wiki/concepts/business/psychological-leverage]], [[wiki/concepts/business/advertising]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures broken first-glance filters, costly signaling, trim-tab experimentation, and the difference between what looks good instantly and what proves valuable through use.

Pages touched:

- [[raw/inbox/2026-04-13-how-your-brain-gets-tricked-by-clever-marketing]]
- [[wiki/sources/2026-04-13-how-your-brain-gets-tricked-by-clever-marketing]]
- [[wiki/concepts/business/experience-goods]]
- [[wiki/concepts/business/psychological-leverage]]
- [[wiki/concepts/business/advertising]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 02:37] ingest | The Marketing Secrets Apple & Tesla Always Use

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-marketing-secrets-apple-and-tesla-always-use-rory-sutherland]]. Created [[wiki/sources/2026-04-13-the-marketing-secrets-apple-and-tesla-always-use-rory-sutherland]] and the new concept page [[wiki/concepts/business/costly-signaling]]. Used the source to deepen [[wiki/concepts/business/advertising]], [[wiki/concepts/business/brand-strategy]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures helpful versus harmful friction, signaling and counter-signaling, brand-versus-performance tradeoffs, and customer service as part of marketing rather than a separate cost center.

Pages touched:

- [[raw/inbox/2026-04-13-the-marketing-secrets-apple-and-tesla-always-use-rory-sutherland]]
- [[wiki/sources/2026-04-13-the-marketing-secrets-apple-and-tesla-always-use-rory-sutherland]]
- [[wiki/concepts/business/costly-signaling]]
- [[wiki/concepts/business/advertising]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 02:45] ingest | Rory Sutherland on the Magic of Original Thinking

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-rory-sutherland-on-the-magic-of-original-thinking]]. Created [[wiki/sources/2026-04-13-rory-sutherland-on-the-magic-of-original-thinking]] and the new concept page [[wiki/concepts/business/psychological-arbitrage]]. Used the source to deepen [[wiki/concepts/business/perception-driven-value]], [[wiki/concepts/business/psychological-leverage]], [[wiki/concepts/business/advertising]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures psychological arbitrage, experienced time versus clock time, protected explore-exploit space, and marketing as innovation through reframing.

Pages touched:

- [[raw/inbox/2026-04-13-rory-sutherland-on-the-magic-of-original-thinking]]
- [[wiki/sources/2026-04-13-rory-sutherland-on-the-magic-of-original-thinking]]
- [[wiki/concepts/business/psychological-arbitrage]]
- [[wiki/concepts/business/perception-driven-value]]
- [[wiki/concepts/business/psychological-leverage]]
- [[wiki/concepts/business/advertising]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 12:23] ingest | Think Fast Talk Smart Matt Abrahams

Summary: Ingested a new English Matt Abrahams communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-think-fast-talk-smart-matt-abrahams]]. Created [[wiki/sources/2026-04-13-think-fast-talk-smart-matt-abrahams]] and used it to deepen the existing spontaneous-speaking branch rather than create a parallel one. Updated [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/syntheses/communication/thinking-on-your-feet-framework]], and [[wiki/concepts/communication/effective-communication]] so the branch now makes the `approach-audience-context-structure` model explicit, including audience knowledge/expectations/attitudes, context-sensitive delivery, and `past-present-future` as another live-speaking structure.

Pages touched:

- [[raw/inbox/2026-04-13-think-fast-talk-smart-matt-abrahams]]
- [[wiki/sources/2026-04-13-think-fast-talk-smart-matt-abrahams]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[wiki/concepts/communication/effective-communication]]
- [[index]]

## [2026-04-13 12:16] ingest | Speaking Up Without Freaking Out Matt Abrahams

Summary: Ingested a new English Matt Abrahams communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-speaking-up-without-freaking-out-matt-abrahams]]. Created [[wiki/sources/2026-04-13-speaking-up-without-freaking-out-matt-abrahams]] and used it to deepen the existing spontaneous-speaking branch rather than create a parallel one. Updated [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/syntheses/communication/thinking-on-your-feet-framework]], and [[wiki/concepts/communication/effective-communication]] so the branch now carries a clearer anxiety-management layer around symptoms versus sources, greeting anxiety, audience-attention redirection, and `secondhand anxiety`.

Pages touched:

- [[raw/inbox/2026-04-13-speaking-up-without-freaking-out-matt-abrahams]]
- [[wiki/sources/2026-04-13-speaking-up-without-freaking-out-matt-abrahams]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[wiki/concepts/communication/effective-communication]]
- [[index]]

## [2026-04-13 12:13] ingest | Think Fast, Talk Smart Communication Techniques

Summary: Ingested a new English Matt Abrahams communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-think-fast-talk-smart-communication-techniques]]. Created [[wiki/sources/2026-04-13-think-fast-talk-smart-communication-techniques]] and used it to deepen the existing spontaneous-speaking branch rather than create a parallel one. Updated [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/syntheses/communication/thinking-on-your-feet-framework]], and [[wiki/concepts/communication/effective-communication]] so the branch now includes conversation-framing, `dare to be dull`, audience-comfort logic, hostile-question handling, and remote or cross-cultural adaptation.

Pages touched:

- [[raw/inbox/2026-04-13-think-fast-talk-smart-communication-techniques]]
- [[wiki/sources/2026-04-13-think-fast-talk-smart-communication-techniques]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[wiki/concepts/communication/effective-communication]]
- [[index]]

## [2026-04-13 12:08] ingest | Think Faster, Talk Smarter with Matt Abrahams

Summary: Ingested a new English communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-think-faster-talk-smarter-with-matt-abrahams]]. Created [[wiki/sources/2026-04-13-think-faster-talk-smarter-with-matt-abrahams]] and used it to deepen the existing live-speaking branch rather than create a duplicate one. Updated [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/syntheses/communication/thinking-on-your-feet-framework]], and [[wiki/concepts/communication/effective-communication]] so the branch now carries a fuller six-step Abrahams methodology with anxiety regulation, anti-perfectionism, deep listening, response structures, and outcome-focused brevity.

Pages touched:

- [[raw/inbox/2026-04-13-think-faster-talk-smarter-with-matt-abrahams]]
- [[wiki/sources/2026-04-13-think-faster-talk-smarter-with-matt-abrahams]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[wiki/concepts/communication/effective-communication]]
- [[index]]

## [2026-04-13 11:52] ingest | How to Think On Your Feet

Summary: Ingested a new English communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-think-on-your-feet]]. Created [[wiki/sources/2026-04-13-how-to-think-on-your-feet]], the new canonical concept [[wiki/concepts/communication/thinking-on-your-feet]], and the new synthesis [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. Updated [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/calibrated-questions]], and [[wiki/concepts/leadership/leadership-communication]] so the communication branch now has an explicit home for live-response skill under presentation and meeting pressure.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-think-on-your-feet]]
- [[wiki/sources/2026-04-13-how-to-think-on-your-feet]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/calibrated-questions]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]

## [2026-04-13 11:48] ingest | Duplicate Capture of The Practice Strategy That Could "Bulletproof" Your Memory Under Pressure

Summary: Processed a new raw-file arrival in `raw/` and determined it was a duplicate capture of an already ingested source rather than a materially new entry. Archived the recapture at [[raw/inbox/2026-04-13-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure-duplicate-capture]] and left the existing canonical source branch unchanged because the differences were limited to clipping noise near the title block rather than new reusable content.

Pages touched:

- [[raw/inbox/2026-04-13-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure-duplicate-capture]]

## [2026-04-13 11:44] ingest | The Practice Strategy That Could "Bulletproof" Your Memory Under Pressure

Summary: Ingested a new English raw source from `raw/` and archived the canonical raw file at [[raw/inbox/2016-12-18-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure]]. Created [[wiki/sources/2016-12-18-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure]] plus the new canonical concept [[wiki/concepts/productivity/retrieval-practice]] and the new synthesis [[wiki/syntheses/productivity/retrieval-practice-under-pressure-framework]]. Updated [[wiki/concepts/productivity/chunking]], [[wiki/concepts/productivity/effective-practice]], [[wiki/sources/2026-04-11-barbara-oakley-learning-how-to-learn]], and [[wiki/syntheses/productivity/barbara-oakley-learning-framework]] so the learning branch now distinguishes chunk-building from recall-testing and makes the pressure-resistance claim legible instead of leaving it trapped in a source-local note.

Pages touched:

- [[raw/inbox/2016-12-18-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure]]
- [[wiki/sources/2016-12-18-the-practice-strategy-that-could-bulletproof-your-memory-under-pressure]]
- [[wiki/concepts/productivity/retrieval-practice]]
- [[wiki/concepts/productivity/chunking]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/sources/2026-04-11-barbara-oakley-learning-how-to-learn]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]
- [[wiki/syntheses/productivity/retrieval-practice-under-pressure-framework]]
- [[index]]

## [2026-04-13 02:52] ingest | Rory Sutherland Why Logic Is Killing Your Business

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-rory-sutherland-why-logic-is-killing-your-business]]. Created [[wiki/sources/2026-04-13-rory-sutherland-why-logic-is-killing-your-business]] and used it to deepen [[wiki/concepts/business/bottleneck-theory]], [[wiki/concepts/business/brand-strategy]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures defensibility-versus-response logic, persuasion before compulsion, proxy-heavy opportunity bottlenecks, and the fact that B2B framing and service design are psychological too.

Pages touched:

- [[raw/inbox/2026-04-13-rory-sutherland-why-logic-is-killing-your-business]]
- [[wiki/sources/2026-04-13-rory-sutherland-why-logic-is-killing-your-business]]
- [[wiki/concepts/business/bottleneck-theory]]
- [[wiki/concepts/business/brand-strategy]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 03:00] ingest | Dirty Little Marketing Secrets That Always Work

Summary: Ingested a new English Rory Sutherland source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-dirty-little-marketing-secrets-that-always-work]]. Created [[wiki/sources/2026-04-13-dirty-little-marketing-secrets-that-always-work]] and the new concept page [[wiki/concepts/business/hidden-functions]]. Used the source to deepen [[wiki/concepts/business/experience-goods]], [[wiki/concepts/business/costly-signaling]], [[wiki/concepts/business/business-strategy]], [[wiki/entities/rory-sutherland]], and [[wiki/syntheses/business/rory-sutherland-marketing-framework]]. The Rory branch now more clearly captures slow-feedback underinvestment, no-going-back trial effects, and the tacit functions that get destroyed by reductionist cost cutting.

Pages touched:

- [[raw/inbox/2026-04-13-dirty-little-marketing-secrets-that-always-work]]
- [[wiki/sources/2026-04-13-dirty-little-marketing-secrets-that-always-work]]
- [[wiki/concepts/business/hidden-functions]]
- [[wiki/concepts/business/experience-goods]]
- [[wiki/concepts/business/costly-signaling]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/entities/rory-sutherland]]
- [[wiki/syntheses/business/rory-sutherland-marketing-framework]]
- [[index]]

## [2026-04-13 12:27] ingest | 3 Techniques for Managing Speaking Anxiety

Summary: Processed this raw source as a compact variant of the already-ingested Matt Abrahams speaking-anxiety material and archived it without creating new wiki pages, because its reusable structure is already represented in the existing spontaneous-speaking branch.

Pages touched:

- [[raw/inbox/2026-04-13-3-techniques-for-managing-speaking-anxiety]]
- [[log]]

## [2026-04-13 12:45] ingest | No Freaking Speaking Managing Public Speaking Anxiety

Summary: Ingested a new English speaking-anxiety source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-no-freaking-speaking-managing-public-speaking-anxiety]]. Created [[wiki/sources/2026-04-13-no-freaking-speaking-managing-public-speaking-anxiety]] and used it to deepen [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/communication/effective-communication]], and [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. The communication branch now more clearly captures situation-audience-goal anxiety diagnosis, audience-response visualization instead of word-perfect rehearsal, and present-focus rituals as pre-speech regulation rather than generic confidence advice.

Pages touched:

- [[raw/inbox/2026-04-13-no-freaking-speaking-managing-public-speaking-anxiety]]
- [[wiki/sources/2026-04-13-no-freaking-speaking-managing-public-speaking-anxiety]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]
- [[log]]

## [2026-04-13 12:58] ingest | Effective Body Language for Public Speaking

Summary: Ingested a new English public-speaking delivery source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-effective-body-language-for-public-speaking]]. Created [[wiki/sources/2026-04-13-effective-body-language-for-public-speaking]] and used it to deepen [[wiki/concepts/communication/charismatic-presence]], [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/communication/effective-communication]], and [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. The communication branch now more clearly captures anti-sway posture, open gesture mechanics, nonpatterned eye contact, purposeful movement, and seated or online delivery adaptations as reusable speaking infrastructure.

Pages touched:

- [[raw/inbox/2026-04-13-effective-body-language-for-public-speaking]]
- [[wiki/sources/2026-04-13-effective-body-language-for-public-speaking]]
- [[wiki/concepts/communication/charismatic-presence]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]
- [[log]]

## [2026-04-13 13:09] ingest | Think Faster Talk Smarter by Matt Abrahams Core Message

Summary: Ingested a new English Matt Abrahams source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-think-faster-talk-smarter-by-matt-abrahams-core-message]]. Created [[wiki/sources/2026-04-13-think-faster-talk-smarter-by-matt-abrahams-core-message]] and used it to deepen [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/communication/effective-communication]], and [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. This source overlapped heavily with the existing Abrahams branch, but it added durable mnemonic packaging: the `3S` anxiety plan, `stick your landings`, `brick not cathedral`, and a slightly broader library of reusable structures.

Pages touched:

- [[raw/inbox/2026-04-13-think-faster-talk-smarter-by-matt-abrahams-core-message]]
- [[wiki/sources/2026-04-13-think-faster-talk-smarter-by-matt-abrahams-core-message]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]
- [[log]]

## [2026-04-13 13:18] ingest | How to Manage Adrenaline in Public Speaking 3 Magic Words

Summary: Ingested a new English speaking-anxiety source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-manage-adrenaline-in-public-speaking-3-magic-words]]. Created [[wiki/sources/2026-04-13-how-to-manage-adrenaline-in-public-speaking-3-magic-words]] and used it to deepen [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/communication/effective-communication]], and [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. The branch now more clearly captures the secondary adrenaline spike, acceptance of symptoms through `and it's okay`, and the first minutes of speaking as the key window for preventing escalation.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-manage-adrenaline-in-public-speaking-3-magic-words]]
- [[wiki/sources/2026-04-13-how-to-manage-adrenaline-in-public-speaking-3-magic-words]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]
- [[log]]

## [2026-04-13 13:31] ingest | How to Win Friends and Influence People by Dale Carnegie

Summary: Ingested a new English Carnegie source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-win-friends-and-influence-people-by-dale-carnegie]]. Created [[wiki/sources/2026-04-13-how-to-win-friends-and-influence-people-by-dale-carnegie]] and the new entity page [[wiki/entities/dale-carnegie]]. Used the source to deepen [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/conversational-curiosity]], [[wiki/concepts/communication/persuasion]], and [[wiki/syntheses/communication/conversation-connection-framework]]. The communication branch now more clearly captures genuine interest as a compounding relationship strategy, appreciation as a primary behavior lever, and Carnegie as a humane counterweight to colder influence models.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-win-friends-and-influence-people-by-dale-carnegie]]
- [[wiki/sources/2026-04-13-how-to-win-friends-and-influence-people-by-dale-carnegie]]
- [[wiki/entities/dale-carnegie]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/conversational-curiosity]]
- [[wiki/concepts/communication/persuasion]]
- [[wiki/syntheses/communication/conversation-connection-framework]]
- [[index]]
- [[log]]

## [2026-04-13 13:43] ingest | The 4 Disciplines of Execution

Summary: Ingested a new English execution-system source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-4-disciplines-of-execution]]. Created [[wiki/sources/2026-04-13-the-4-disciplines-of-execution]] and the new synthesis [[wiki/syntheses/business/4dx-execution-framework]]. Used the source to deepen [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/strategic-focus]], [[wiki/concepts/business/success-metrics]], and [[wiki/syntheses/business/scalable-business-systems-framework]]. The business branch now more clearly captures the `Whirlwind`, wildly important goals, lead-versus-lag measurement, visible scoreboards, and weekly accountability as a recurring execution loop.

Pages touched:

- [[raw/inbox/2026-04-13-the-4-disciplines-of-execution]]
- [[wiki/sources/2026-04-13-the-4-disciplines-of-execution]]
- [[wiki/syntheses/business/4dx-execution-framework]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/syntheses/business/scalable-business-systems-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:00] ingest | Be Rare and Valuable: So Good They Can't Ignore You

Summary: Ingested a new English Cal Newport source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-be-rare-and-valuable-so-good-they-cant-ignore-you]]. Created [[wiki/sources/2026-04-13-be-rare-and-valuable-so-good-they-cant-ignore-you]], the new entity page [[wiki/entities/cal-newport]], the new concepts [[wiki/concepts/business/career-capital]] and [[wiki/concepts/business/craftsman-mindset]], and the new synthesis [[wiki/syntheses/business/cal-newport-career-capital-framework]]. Used the source to deepen [[wiki/concepts/business/career-blueprint]], [[wiki/concepts/business/zone-of-genius]], and [[wiki/concepts/productivity/deliberate-practice]]. The career branch now more clearly captures satisfying work as an earned combination of creativity, control, and impact built through scarce skill, stretch projects, and a craftsman orientation rather than passion-first drift.

Pages touched:

- [[raw/inbox/2026-04-13-be-rare-and-valuable-so-good-they-cant-ignore-you]]
- [[wiki/sources/2026-04-13-be-rare-and-valuable-so-good-they-cant-ignore-you]]
- [[wiki/entities/cal-newport]]
- [[wiki/concepts/business/career-capital]]
- [[wiki/concepts/business/craftsman-mindset]]
- [[wiki/concepts/business/career-blueprint]]
- [[wiki/concepts/business/zone-of-genius]]
- [[wiki/concepts/productivity/deliberate-practice]]
- [[wiki/syntheses/business/cal-newport-career-capital-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:10] ingest | Thinking, Fast and Slow by Daniel Kahneman

Summary: Ingested a new English Daniel Kahneman source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-thinking-fast-and-slow-by-daniel-kahneman]]. Created [[wiki/sources/2026-04-13-thinking-fast-and-slow-by-daniel-kahneman]] and the new concept pages [[wiki/concepts/others/mere-exposure-effect]], [[wiki/concepts/others/status-quo-bias]], and [[wiki/concepts/others/wysiati]]. Used the source to deepen [[wiki/concepts/others/two-systems-thinking]], [[wiki/entities/daniel-kahneman]], and [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]. The judgment branch now more clearly captures how familiarity, default-preservation, and incomplete visible evidence distort major choices even when the two-systems model is already understood.

Pages touched:

- [[raw/inbox/2026-04-13-thinking-fast-and-slow-by-daniel-kahneman]]
- [[wiki/sources/2026-04-13-thinking-fast-and-slow-by-daniel-kahneman]]
- [[wiki/concepts/others/mere-exposure-effect]]
- [[wiki/concepts/others/status-quo-bias]]
- [[wiki/concepts/others/wysiati]]
- [[wiki/concepts/others/two-systems-thinking]]
- [[wiki/entities/daniel-kahneman]]
- [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]
- [[index]]
- [[log]]

## [2026-04-13 14:15] ingest | Make the Competition Irrelevant: Blue Ocean Strategy

Summary: Ingested a new English strategy source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-make-the-competition-irrelevant-blue-ocean-strategy]]. Created [[wiki/sources/2026-04-13-make-the-competition-irrelevant-blue-ocean-strategy]], the new concepts [[wiki/concepts/business/blue-ocean-strategy]], [[wiki/concepts/business/value-innovation]], and [[wiki/concepts/business/errc-framework]], and the new synthesis [[wiki/syntheses/business/blue-ocean-strategy-framework]]. Used the source to deepen [[wiki/concepts/business/business-strategy]], [[wiki/concepts/business/jobs-to-be-done]], and [[wiki/syntheses/business/clayton-christensen-growth-framework]]. The business branch now more clearly captures category creation, non-customer insight, and redesign through elimination, reduction, raising, and creation rather than only head-to-head competition.

Pages touched:

- [[raw/inbox/2026-04-13-make-the-competition-irrelevant-blue-ocean-strategy]]
- [[wiki/sources/2026-04-13-make-the-competition-irrelevant-blue-ocean-strategy]]
- [[wiki/concepts/business/blue-ocean-strategy]]
- [[wiki/concepts/business/value-innovation]]
- [[wiki/concepts/business/errc-framework]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/business/jobs-to-be-done]]
- [[wiki/syntheses/business/blue-ocean-strategy-framework]]
- [[wiki/syntheses/business/clayton-christensen-growth-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:20] ingest | Measure What Matters by John Doerr

Summary: Ingested a new English execution-and-metrics source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-measure-what-matters-by-john-doerr]]. Created [[wiki/sources/2026-04-13-measure-what-matters-by-john-doerr]], the new concepts [[wiki/concepts/business/okrs]] and [[wiki/concepts/business/stretch-goals]], and the new synthesis [[wiki/syntheses/business/john-doerr-okr-framework]]. Used the source to deepen [[wiki/concepts/business/success-metrics]], [[wiki/concepts/business/business-systems]], [[wiki/concepts/business/strategic-focus]], and [[wiki/syntheses/business/4dx-execution-framework]]. The execution branch now more clearly captures ambition-calibrated objectives, mixed quality-and-quantity key results, traffic-light review loops, and the rule that easy 100 percent completion often signals timid target-setting rather than strong performance.

Pages touched:

- [[raw/inbox/2026-04-13-measure-what-matters-by-john-doerr]]
- [[wiki/sources/2026-04-13-measure-what-matters-by-john-doerr]]
- [[wiki/concepts/business/okrs]]
- [[wiki/concepts/business/stretch-goals]]
- [[wiki/concepts/business/success-metrics]]
- [[wiki/concepts/business/business-systems]]
- [[wiki/concepts/business/strategic-focus]]
- [[wiki/syntheses/business/john-doerr-okr-framework]]
- [[wiki/syntheses/business/4dx-execution-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:49] ingest | 12 Rules for Life by Jordan Peterson

Summary: Ingested a new English Jordan Peterson source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-12-rules-for-life-by-jordan-peterson]]. Created [[wiki/sources/2026-04-13-12-rules-for-life-by-jordan-peterson]] and the new concept [[wiki/concepts/productivity/progress-against-yesterday]]. Used the source to deepen [[wiki/entities/jordan-peterson]], [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/communication/assertiveness]], [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]], and [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]. The Peterson branch now more clearly captures progress-against-yesterday as an anti-comparison scoreboard, plus truth-telling and early difficult conversations as part of daily anti-chaos maintenance rather than only as abstract moral advice.

Pages touched:

- [[raw/inbox/2026-04-13-12-rules-for-life-by-jordan-peterson]]
- [[wiki/sources/2026-04-13-12-rules-for-life-by-jordan-peterson]]
- [[wiki/concepts/productivity/progress-against-yesterday]]
- [[wiki/entities/jordan-peterson]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/communication/assertiveness]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:51] ingest | Stress-free productivity: Getting Things Done by David Allen

Summary: Ingested a new English David Allen source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-stress-free-productivity-getting-things-done-by-david-allen]]. Created [[wiki/sources/2026-04-13-stress-free-productivity-getting-things-done-by-david-allen]], the new entity page [[wiki/entities/david-allen]], the new concept [[wiki/concepts/productivity/trusted-external-system]], and the new synthesis [[wiki/syntheses/productivity/david-allen-gtd-framework]]. Used the source to deepen [[wiki/concepts/productivity/behavior-journaling]], [[wiki/concepts/productivity/future-self-prioritization]], [[wiki/concepts/productivity/signal-to-noise-ratio]], and [[wiki/syntheses/productivity/daniel-pink-sustainable-productivity-framework]]. The productivity branch now more clearly captures GTD as anti-overwhelm infrastructure: uncaptured open loops consume attention, while capture, clarification, trusted containers, and review cadence reduce stress by externalizing commitments rather than repeatedly renegotiating them mentally.

Pages touched:

- [[raw/inbox/2026-04-13-stress-free-productivity-getting-things-done-by-david-allen]]
- [[wiki/sources/2026-04-13-stress-free-productivity-getting-things-done-by-david-allen]]
- [[wiki/entities/david-allen]]
- [[wiki/concepts/productivity/trusted-external-system]]
- [[wiki/concepts/productivity/behavior-journaling]]
- [[wiki/concepts/productivity/future-self-prioritization]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/syntheses/productivity/david-allen-gtd-framework]]
- [[wiki/syntheses/productivity/daniel-pink-sustainable-productivity-framework]]
- [[index]]
- [[log]]

## [2026-04-13 14:59] ingest | The Only Skill That Matters by Jonathan Levi

Summary: Ingested a new English Jonathan Levi source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-only-skill-that-matters-by-jonathan-levi]]. Created [[wiki/sources/2026-04-13-the-only-skill-that-matters-by-jonathan-levi]], the new entity page [[wiki/entities/jonathan-levi]], the new concept [[wiki/concepts/productivity/learning-pyramid]], and the new synthesis [[wiki/syntheses/productivity/jonathan-levi-superlearning-framework]]. Used the source to deepen [[wiki/concepts/productivity/effective-practice]], [[wiki/concepts/productivity/rapid-skill-acquisition]], [[wiki/concepts/productivity/retrieval-practice]], and [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]. The learning branch now more clearly captures plateau-breaking through paired-skill transfer, multi-source explanation hunting, and climbing from understanding to recall, explanation, application, analysis, and creation instead of stopping at familiarity.

Pages touched:

- [[raw/inbox/2026-04-13-the-only-skill-that-matters-by-jonathan-levi]]
- [[wiki/sources/2026-04-13-the-only-skill-that-matters-by-jonathan-levi]]
- [[wiki/entities/jonathan-levi]]
- [[wiki/concepts/productivity/learning-pyramid]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/concepts/productivity/rapid-skill-acquisition]]
- [[wiki/concepts/productivity/retrieval-practice]]
- [[wiki/syntheses/productivity/jonathan-levi-superlearning-framework]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]
- [[index]]
- [[log]]

## [2026-04-15 01:57] ingest | The Optimizer Productive, But Miserable

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-the-optimizer-productive-but-miserable]]. Created [[wiki/sources/2026-04-15-the-optimizer-productive-but-miserable]], the new concept [[wiki/concepts/productivity/optimization-as-avoidance]], and the new synthesis [[wiki/syntheses/productivity/optimizer-trap-framework]]. Used the source to deepen [[wiki/concepts/productivity/strategic-underachievement]], [[wiki/concepts/productivity/signal-to-noise-ratio]], [[wiki/concepts/leadership/inner-excellence]], and [[wiki/syntheses/productivity/oliver-burkeman-four-thousand-weeks-framework]]. The anti-overwhelm branch now more clearly distinguishes structural overload from fear-driven optimization, adds three optimizer archetypes, and makes the difference between productive appearance and real fulfillment easier to see.

Pages touched:

- [[raw/inbox/2026-04-15-the-optimizer-productive-but-miserable]]
- [[wiki/sources/2026-04-15-the-optimizer-productive-but-miserable]]
- [[wiki/concepts/productivity/optimization-as-avoidance]]
- [[wiki/syntheses/productivity/optimizer-trap-framework]]
- [[wiki/concepts/productivity/strategic-underachievement]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/concepts/leadership/inner-excellence]]
- [[wiki/syntheses/productivity/oliver-burkeman-four-thousand-weeks-framework]]
- [[index]]
- [[log]]

## [2026-04-13 15:03] ingest | The 4 Fs of Flow

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-the-4-fs-of-flow]]. Created [[wiki/sources/2026-04-13-the-4-fs-of-flow]], the new concept [[wiki/concepts/productivity/flow]], and the new synthesis [[wiki/syntheses/productivity/four-fs-of-flow-framework]]. Used the source to deepen [[wiki/concepts/productivity/calibrated-challenge]] and [[wiki/syntheses/productivity/attention-and-focus-framework]]. The productivity branch now more clearly captures flow as a designable work state, `permission timers` as a way to separate performance from critique, and the `4 percent challenge` idea as a slight-stretch heuristic rather than a precise law.

Pages touched:

- [[raw/inbox/2026-04-13-the-4-fs-of-flow]]
- [[wiki/sources/2026-04-13-the-4-fs-of-flow]]
- [[wiki/concepts/productivity/flow]]
- [[wiki/concepts/productivity/calibrated-challenge]]
- [[wiki/syntheses/productivity/four-fs-of-flow-framework]]
- [[wiki/syntheses/productivity/attention-and-focus-framework]]
- [[index]]
- [[log]]

## [2026-04-13 15:13] ingest | Flow by Mihaly Csikszentmihalyi

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-flow-by-mihaly-csikszentmihalyi]]. Created [[wiki/sources/2026-04-13-flow-by-mihaly-csikszentmihalyi]], the new entity page [[wiki/entities/mihaly-csikszentmihalyi]], and the new synthesis [[wiki/syntheses/productivity/mihaly-csikszentmihalyi-flow-framework]]. Used the source to deepen [[wiki/concepts/productivity/flow]] and [[wiki/concepts/productivity/dopamine-regulation]]. The flow branch now more clearly captures happiness as consciousness design, the challenge-skill channel as a state map, and the risk that passive comfort drifts into apathy rather than deep fulfillment.

Pages touched:

- [[raw/inbox/2026-04-13-flow-by-mihaly-csikszentmihalyi]]
- [[wiki/sources/2026-04-13-flow-by-mihaly-csikszentmihalyi]]
- [[wiki/entities/mihaly-csikszentmihalyi]]
- [[wiki/concepts/productivity/flow]]
- [[wiki/concepts/productivity/dopamine-regulation]]
- [[wiki/syntheses/productivity/mihaly-csikszentmihalyi-flow-framework]]
- [[index]]
- [[log]]

## [2026-04-13 15:18] ingest | Four Thousand Weeks by Oliver Burkeman

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-four-thousand-weeks-by-oliver-burkeman]]. Created [[wiki/sources/2026-04-13-four-thousand-weeks-by-oliver-burkeman]], the new concept [[wiki/concepts/productivity/strategic-underachievement]], and the new synthesis [[wiki/syntheses/productivity/oliver-burkeman-four-thousand-weeks-framework]]. Used the source to deepen [[wiki/concepts/productivity/signal-to-noise-ratio]]. The Burkeman branch now more clearly captures open versus closed lists, deliberate good-enough standards for low-value work, and last-time reflection as a presence practice built on finitude rather than as another optimization tactic.

Pages touched:

- [[raw/inbox/2026-04-13-four-thousand-weeks-by-oliver-burkeman]]
- [[wiki/sources/2026-04-13-four-thousand-weeks-by-oliver-burkeman]]
- [[wiki/concepts/productivity/strategic-underachievement]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/syntheses/productivity/oliver-burkeman-four-thousand-weeks-framework]]
- [[index]]
- [[log]]

## [2026-04-13 17:38] ingest | How Decision Making is Actually Science: Game Theory Explained

Summary: Ingested a new English game-theory source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-decision-making-is-actually-science-game-theory-explained]]. Created [[wiki/sources/2026-04-13-how-decision-making-is-actually-science-game-theory-explained]], the new concepts [[wiki/concepts/business/game-theory]] and [[wiki/concepts/business/shapley-value]], and the new synthesis [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. Used the source to deepen [[wiki/concepts/business/business-strategy]], [[wiki/concepts/communication/negotiation-and-mediation]], and [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]. The decision branch now more clearly separates cognitive failure from incentive-structure failure and adds a coalition-fairness layer through marginal-contribution logic.

Pages touched:

- [[raw/inbox/2026-04-13-how-decision-making-is-actually-science-game-theory-explained]]
- [[wiki/sources/2026-04-13-how-decision-making-is-actually-science-game-theory-explained]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/concepts/business/shapley-value]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[wiki/syntheses/cross-source/decision-making-under-cognitive-strain]]
- [[index]]
- [[log]]

## [2026-04-13 17:44] ingest | What Game Theory Teaches Us About War

Summary: Ingested a new English Simon Sinek source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-what-game-theory-teaches-us-about-war]]. Created [[wiki/sources/2026-04-13-what-game-theory-teaches-us-about-war]] and used it to deepen [[wiki/concepts/business/game-theory]], [[wiki/concepts/leadership/infinite-game-mindset]], and [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]. The Sinek branch now more clearly captures finite-versus-infinite conflict mismatch, quagmire through endurance asymmetry, adversary replacement in ongoing contests, and value-first consistency as a source of strategic predictability and alliance trust.

Pages touched:

- [[raw/inbox/2026-04-13-what-game-theory-teaches-us-about-war]]
- [[wiki/sources/2026-04-13-what-game-theory-teaches-us-about-war]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/concepts/leadership/infinite-game-mindset]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]
- [[index]]
- [[log]]

## [2026-04-13 18:26] ingest | What Actually Is Game Theory?

Summary: Ingested a new English introductory game-theory source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-what-actually-is-game-theory]]. Created [[wiki/sources/2026-04-13-what-actually-is-game-theory]] and the new concept [[wiki/concepts/business/zero-sum-games]]. Used the source to deepen [[wiki/concepts/business/game-theory]] and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The game-theory branch now more clearly captures the players-strategies-payoffs modeling lens, the limits of zero-sum framing, the distinction between dominant strategy and Nash equilibrium, and the tension between clean rational models and real human behavior.

Pages touched:

- [[raw/inbox/2026-04-13-what-actually-is-game-theory]]
- [[wiki/sources/2026-04-13-what-actually-is-game-theory]]
- [[wiki/concepts/business/zero-sum-games]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-13 22:12] ingest | Game Theory: A Simple Strategy That Will Change Your Life Forever

Summary: Ingested a new English repeated-games source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-game-theory-a-simple-strategy-that-will-change-your-life-forever]]. Created [[wiki/sources/2026-04-13-game-theory-a-simple-strategy-that-will-change-your-life-forever]] and the new concept [[wiki/concepts/business/tit-for-tat]]. Used the source to deepen [[wiki/concepts/business/game-theory]], [[wiki/concepts/communication/negotiation-and-mediation]], and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The game-theory branch now more clearly captures one-shot versus repeated-game logic, Axelrod-style tournament evidence, and the four-part repeated-strategy profile of cooperating first, retaliating proportionally, forgiving quickly, and staying clear.

Pages touched:

- [[raw/inbox/2026-04-13-game-theory-a-simple-strategy-that-will-change-your-life-forever]]
- [[wiki/sources/2026-04-13-game-theory-a-simple-strategy-that-will-change-your-life-forever]]
- [[wiki/concepts/business/tit-for-tat]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-13 22:26] ingest | Game Theory (Yale University - Ben Polak)

Summary: Ingested a new English course-style game-theory source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-game-theory-yale-university-ben-polak]]. Created [[wiki/sources/2026-04-13-game-theory-yale-university-ben-polak]] and the new concept [[wiki/concepts/business/backward-induction]]. Used the source to deepen [[wiki/concepts/business/game-theory]], [[wiki/concepts/business/business-strategy]], and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The game-theory branch now more clearly captures timing games, the distinction between robust dominance arguments and more fragile backward-induction logic, and proactive-bias errors where acting early feels bold but worsens the odds.

Pages touched:

- [[raw/inbox/2026-04-13-game-theory-yale-university-ben-polak]]
- [[wiki/sources/2026-04-13-game-theory-yale-university-ben-polak]]
- [[wiki/concepts/business/backward-induction]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/concepts/business/business-strategy]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-13 22:40] ingest | Game Theory and Negotiation

Summary: Ingested a new English negotiation-focused game-theory source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-game-theory-and-negotiation]]. Created [[wiki/sources/2026-04-13-game-theory-and-negotiation]] and the new concept [[wiki/concepts/communication/batna]]. Used the source to deepen [[wiki/concepts/business/game-theory]], [[wiki/concepts/communication/negotiation-and-mediation]], and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The branch now captures outside-option logic, BATNA, signaling and screening under incomplete information, and credible commitment as a bridge between abstract game structure and live negotiation practice.

Pages touched:

- [[raw/inbox/2026-04-13-game-theory-and-negotiation]]
- [[wiki/sources/2026-04-13-game-theory-and-negotiation]]
- [[wiki/concepts/communication/batna]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/concepts/communication/negotiation-and-mediation]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-13 22:47] ingest | Speed Reading by Kam Knight

Summary: Ingested a new English productivity-and-learning source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-speed-reading-by-kam-knight]]. Created [[wiki/sources/2026-04-13-speed-reading-by-kam-knight]], the new concept [[wiki/concepts/productivity/speed-reading]], and the new synthesis [[wiki/syntheses/productivity/speed-reading-framework]]. Used the source to deepen [[wiki/concepts/productivity/effective-practice]] and [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]. The learning branch now captures purpose-first reading, T.H.I.E.V.E.S. previewing, peripheral-vision intake, and the caution that speed only counts when comprehension survives.

Pages touched:

- [[raw/inbox/2026-04-13-speed-reading-by-kam-knight]]
- [[wiki/sources/2026-04-13-speed-reading-by-kam-knight]]
- [[wiki/concepts/productivity/speed-reading]]
- [[wiki/syntheses/productivity/speed-reading-framework]]
- [[wiki/concepts/productivity/effective-practice]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]
- [[index]]
- [[log]]

## [2026-04-13 22:55] ingest | This Game Theory Problem Will Change the Way You See the World

Summary: Ingested a new English repeated-games source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-this-game-theory-problem-will-change-the-way-you-see-the-world]]. Created [[wiki/sources/2026-04-13-this-game-theory-problem-will-change-the-way-you-see-the-world]] and used it to deepen [[wiki/concepts/business/tit-for-tat]], [[wiki/concepts/business/zero-sum-games]], [[wiki/concepts/business/game-theory]], and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The branch now more clearly captures the four Axelrod strategy traits, cooperation as an ecological phenomenon, generous reciprocity under noise, and the claim that many domains reward total value from the environment rather than direct opponent defeat.

Pages touched:

- [[raw/inbox/2026-04-13-this-game-theory-problem-will-change-the-way-you-see-the-world]]
- [[wiki/sources/2026-04-13-this-game-theory-problem-will-change-the-way-you-see-the-world]]
- [[wiki/concepts/business/tit-for-tat]]
- [[wiki/concepts/business/zero-sum-games]]
- [[wiki/concepts/business/game-theory]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-13 23:02] ingest | Be Wealthy Without Getting Lucky The Almanack of Naval Ravikant

Summary: Ingested a new English business-and-career source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-be-wealthy-without-getting-lucky-the-almanack-of-naval-ravikant]]. Created [[wiki/sources/2026-04-13-be-wealthy-without-getting-lucky-the-almanack-of-naval-ravikant]], the new entity [[wiki/entities/naval-ravikant]], the new concept [[wiki/concepts/business/specific-knowledge.md|Specific Knowledge]], and the new synthesis [[wiki/syntheses/business/naval-ravikant-wealth-framework]]. Used the source to deepen [[wiki/concepts/business/career-capital]] and [[wiki/concepts/business/permissionless-creation]]. The business branch now more clearly captures wealth as freedom, specific knowledge as anti-competition, accountability as ownership of outcomes, and leverage through code and media.

Pages touched:

- [[raw/inbox/2026-04-13-be-wealthy-without-getting-lucky-the-almanack-of-naval-ravikant]]
- [[wiki/sources/2026-04-13-be-wealthy-without-getting-lucky-the-almanack-of-naval-ravikant]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/concepts/business/specific-knowledge.md|Specific Knowledge]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/concepts/business/career-capital]]
- [[wiki/concepts/business/permissionless-creation]]
- [[index]]
- [[log]]

## [2026-04-13 23:03] ingest | How to Think On Your Feet (Harvey Specter Edition)

Summary: Ingested a new English communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-13-how-to-think-on-your-feet-harvey-specter-edition]]. Created [[wiki/sources/2026-04-13-how-to-think-on-your-feet-harvey-specter-edition]] and used it to deepen [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/communication/frame-control]], and [[wiki/syntheses/communication/thinking-on-your-feet-framework]]. The communication branch now more clearly captures composure tests, expectation management under pressure, body language as cognitive time-buying, and the bounded use of playful non-literal replies in mildly adversarial settings.

Pages touched:

- [[raw/inbox/2026-04-13-how-to-think-on-your-feet-harvey-specter-edition]]
- [[wiki/sources/2026-04-13-how-to-think-on-your-feet-harvey-specter-edition]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/communication/frame-control]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework]]
- [[index]]
- [[log]]

## [2026-04-14 00:41] ingest | 44 Harsh Truths About The Game Of Life

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-44-harsh-truths-about-the-game-of-life]]. Created [[wiki/sources/2026-04-14-44-harsh-truths-about-the-game-of-life]], the new concept [[wiki/concepts/business/mimetic-desire]], and the new synthesis [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. Used the source to deepen [[wiki/entities/naval-ravikant]], [[wiki/concepts/business/specific-knowledge]], [[wiki/concepts/business/zero-sum-games]], [[wiki/concepts/productivity/signal-to-noise-ratio]], and [[wiki/syntheses/business/naval-ravikant-wealth-framework]]. The Naval branch now more clearly captures copied desire, wealth-versus-status games, self-respect as internal reputation, time freedom, selective problem ownership, and the claim that wealth should serve life quality rather than replace it.

Pages touched:

- [[raw/inbox/2026-04-14-44-harsh-truths-about-the-game-of-life]]
- [[wiki/sources/2026-04-14-44-harsh-truths-about-the-game-of-life]]
- [[wiki/concepts/business/mimetic-desire]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/concepts/business/specific-knowledge]]
- [[wiki/concepts/business/zero-sum-games]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[index]]
- [[log]]

## [2026-04-14 00:58] ingest | Imagine Life If You Didn't Overthink Everything

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-imagine-life-if-you-didnt-overthink-everything]]. Created [[wiki/sources/2026-04-14-imagine-life-if-you-didnt-overthink-everything]] and the new concept [[wiki/concepts/health/overthinking]]. Used the source to deepen [[wiki/concepts/productivity/alive-time]], [[wiki/syntheses/business/naval-ravikant-life-design-framework]], and [[wiki/entities/naval-ravikant]]. The Naval branch now more clearly captures stress as conflicting desires, anxiety as unlabeled accumulated stress, the difference between clarifying self-observation and ego-driven rumination, wasted time as absence from the present, and the bounded use of gut judgment in hard ambiguous decisions.

Pages touched:

- [[raw/inbox/2026-04-14-imagine-life-if-you-didnt-overthink-everything]]
- [[wiki/sources/2026-04-14-imagine-life-if-you-didnt-overthink-everything]]
- [[wiki/concepts/health/overthinking]]
- [[wiki/concepts/productivity/alive-time]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[wiki/entities/naval-ravikant]]
- [[index]]
- [[log]]

## [2026-04-14 01:16] ingest | Naval Ravikant on Happiness, Anxiety, and More

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]]. Created [[wiki/sources/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]] and used it to deepen [[wiki/concepts/productivity/dopamine-regulation]], [[wiki/concepts/health/mindfulness]], [[wiki/concepts/health/overthinking]], [[wiki/entities/naval-ravikant]], [[wiki/syntheses/business/naval-ravikant-wealth-framework]], and [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. The Naval branch now more clearly captures long-term games with long-term people, meditation as destructive self-examination, calm as a performance advantage, cleaner alternatives to cheap dopamine, and low-conflict self-aware relationship selection.

Pages touched:

- [[raw/inbox/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]]
- [[wiki/sources/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]]
- [[wiki/concepts/productivity/dopamine-regulation]]
- [[wiki/concepts/health/mindfulness]]
- [[wiki/concepts/health/overthinking]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[index]]
- [[log]]

## [2026-04-14 15:27] ingest | There Is Infinite Opportunity In The Modern World

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-there-is-infinite-opportunity-in-the-modern-world]]. Created [[wiki/sources/2026-04-14-there-is-infinite-opportunity-in-the-modern-world]] and used it to deepen [[wiki/concepts/business/specific-knowledge]], [[wiki/concepts/productivity/signal-to-noise-ratio]], [[wiki/entities/naval-ravikant]], [[wiki/syntheses/business/naval-ravikant-wealth-framework]], and [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. The Naval branch now more clearly captures explore-versus-exploit timing, premature commitment as a path error, authenticity as anti-competition, and media-fed `mimetic viruses` as copied problems rather than only copied desires.

Pages touched:

- [[raw/inbox/2026-04-14-there-is-infinite-opportunity-in-the-modern-world]]
- [[wiki/sources/2026-04-14-there-is-infinite-opportunity-in-the-modern-world]]
- [[wiki/concepts/business/specific-knowledge]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[index]]
- [[log]]

## [2026-04-14 12:47] ingest | See Their Core Shame Instantly

Summary: Ingested a new English Chase Hughes source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-see-their-core-shame-instantly-chase-hughes]]. Created [[wiki/sources/2026-04-14-see-their-core-shame-instantly-chase-hughes]] and the new concept [[wiki/concepts/others/core-shame]]. Used the source to deepen [[wiki/concepts/others/mask-behavior]], [[wiki/concepts/others/projection-as-self-signal]], [[wiki/concepts/communication/face-saving-de-escalation]], [[wiki/entities/chase-hughes]], [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]], and [[wiki/syntheses/cross-source/hidden-motives-and-social-behavior]]. The hidden-motives branch now more clearly captures shame as survival architecture, insults as identity boundary markers, four recurring judgment domains, and the ethical use of empathy as accurate vision without contempt.

Pages touched:

- [[raw/inbox/2026-04-14-see-their-core-shame-instantly-chase-hughes]]
- [[wiki/sources/2026-04-14-see-their-core-shame-instantly-chase-hughes]]
- [[wiki/concepts/others/core-shame]]
- [[wiki/concepts/others/mask-behavior]]
- [[wiki/concepts/others/projection-as-self-signal]]
- [[wiki/concepts/communication/face-saving-de-escalation]]
- [[wiki/entities/chase-hughes]]
- [[wiki/syntheses/others/chase-hughes-mask-and-compassion-framework]]
- [[wiki/syntheses/cross-source/hidden-motives-and-social-behavior]]
- [[index]]
- [[log]]

## [2026-04-14 15:19] ingest | Naval Ravikant on Happiness, Anxiety, and More (Second Capture)

Summary: Ingested a second English capture of the same Naval Ravikant conversation from `raw/` and archived it at [[raw/inbox/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more-second-capture]]. Instead of creating a duplicate wiki source page, used the new capture to deepen [[wiki/sources/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]], [[wiki/entities/naval-ravikant]], [[wiki/syntheses/business/naval-ravikant-wealth-framework]], and [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. The Naval branch now more clearly captures `define enough` as a stopping rule, `10,000 iterations` over blunt hours-counting, and independence plus peer-level relationships as part of the endpoint rather than as side effects of wealth.

Pages touched:

- [[raw/inbox/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more-second-capture]]
- [[wiki/sources/2026-04-14-naval-ravikant-on-happiness-anxiety-and-more]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[index]]
- [[log]]

## [2026-04-14 15:28] ingest | These Are The 2 Paths To Happiness Naval Ravikant

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-these-are-the-2-paths-to-happiness-naval-ravikant]]. Created [[wiki/sources/2026-04-14-these-are-the-2-paths-to-happiness-naval-ravikant]] and used it to deepen [[wiki/concepts/business/mimetic-desire]], [[wiki/concepts/business/process-over-outcomes]], [[wiki/concepts/productivity/dopamine-regulation]], [[wiki/entities/naval-ravikant]], and [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. The Naval branch now more clearly captures the two-path happiness model, optional suffering versus necessary effort, desire-loop reset dynamics, journey quality as part of the result, and fame as a fragile byproduct rather than a stable endpoint.

Pages touched:

- [[raw/inbox/2026-04-14-these-are-the-2-paths-to-happiness-naval-ravikant]]
- [[wiki/sources/2026-04-14-these-are-the-2-paths-to-happiness-naval-ravikant]]
- [[wiki/concepts/business/mimetic-desire]]
- [[wiki/concepts/business/process-over-outcomes]]
- [[wiki/concepts/productivity/dopamine-regulation]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[index]]
- [[log]]

## [2026-04-14 15:30] ingest | The 4 Secrets To Be Great At Anything

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-the-4-secrets-to-be-great-at-anything]]. Created [[wiki/sources/2026-04-14-the-4-secrets-to-be-great-at-anything]] and used it to deepen [[wiki/concepts/business/specific-knowledge]], [[wiki/concepts/business/zone-of-genius]], [[wiki/entities/naval-ravikant]], and [[wiki/syntheses/business/naval-ravikant-life-design-framework]]. The Naval branch now more clearly captures anti-prescription greatness, goal selection as part of intelligence, assigned meaning as a practical stance, and solitude as infrastructure for self-authored direction rather than mere withdrawal.

Pages touched:

- [[raw/inbox/2026-04-14-the-4-secrets-to-be-great-at-anything]]
- [[wiki/sources/2026-04-14-the-4-secrets-to-be-great-at-anything]]
- [[wiki/concepts/business/specific-knowledge]]
- [[wiki/concepts/business/zone-of-genius]]
- [[wiki/entities/naval-ravikant]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[index]]
- [[log]]

## [2026-04-14 15:35] ingest | 11 Rules For Life Genius Rules

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-11-rules-for-life-genius-rules]]. Created [[wiki/sources/2026-04-14-11-rules-for-life-genius-rules]] and used it to deepen [[wiki/syntheses/business/naval-ravikant-life-design-framework]], [[wiki/syntheses/business/naval-ravikant-wealth-framework]], [[wiki/concepts/productivity/signal-to-noise-ratio]], and [[wiki/entities/naval-ravikant]]. The Naval branch now more clearly captures strategic restarting, impatient action with patient result horizons, play-work fit, single-desire narrowing, reading and basics as durable edge, explicit escape from time-renting through ownership and permissionless leverage, blank-space thinking, and anti-validation independence.

Pages touched:

- [[raw/inbox/2026-04-14-11-rules-for-life-genius-rules]]
- [[wiki/sources/2026-04-14-11-rules-for-life-genius-rules]]
- [[wiki/syntheses/business/naval-ravikant-life-design-framework]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/concepts/productivity/signal-to-noise-ratio]]
- [[wiki/entities/naval-ravikant]]
- [[index]]
- [[log]]

## [2026-04-14 15:39] ingest | Were Living Through A Crisis Of Meaning Simon Sinek

Summary: Ingested a new English Simon Sinek source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-were-living-through-a-crisis-of-meaning-simon-sinek]]. Created [[wiki/sources/2026-04-14-were-living-through-a-crisis-of-meaning-simon-sinek]] and the new concept [[wiki/concepts/leadership/friendship-as-growth-pact]]. Used the source to deepen [[wiki/entities/simon-sinek]], [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]], [[wiki/concepts/leadership/trust-based-collaboration]], and [[wiki/concepts/leadership/meaning-through-responsibility]]. The Simon branch now more clearly captures the crisis-of-meaning diagnosis, purpose versus goals, friendship as relational infrastructure, accountability without helplessness, and `sit in the mud` emotional accompaniment before advice.

Pages touched:

- [[raw/inbox/2026-04-14-were-living-through-a-crisis-of-meaning-simon-sinek]]
- [[wiki/sources/2026-04-14-were-living-through-a-crisis-of-meaning-simon-sinek]]
- [[wiki/concepts/leadership/friendship-as-growth-pact]]
- [[wiki/entities/simon-sinek]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[index]]
- [[log]]

## [2026-04-14 15:48] ingest | Naval Ravikant How To Go from Employee To Financially Independent

Summary: Ingested a new English Naval Ravikant source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-naval-ravikant-how-to-go-from-employee-to-financially-independent]]. Created [[wiki/sources/2026-04-14-naval-ravikant-how-to-go-from-employee-to-financially-independent]] and the new concept [[wiki/concepts/business/ownership-ladder]]. Used the source to deepen [[wiki/syntheses/business/naval-ravikant-wealth-framework]] and [[wiki/entities/naval-ravikant]]. The Naval wealth branch now more clearly preserves a concrete employee-to-owner progression from selling hours to managing labor, taking asset-level risk, allocating capital, and adding code-enabled platform leverage on top.

Pages touched:

- [[raw/inbox/2026-04-14-naval-ravikant-how-to-go-from-employee-to-financially-independent]]
- [[wiki/sources/2026-04-14-naval-ravikant-how-to-go-from-employee-to-financially-independent]]
- [[wiki/concepts/business/ownership-ladder]]
- [[wiki/syntheses/business/naval-ravikant-wealth-framework]]
- [[wiki/entities/naval-ravikant]]
- [[index]]
- [[log]]

## [2026-04-14 20:47] ingest | Increase Performance AND Fulfillment at the Same Time

Summary: Ingested a new English Jim Murphy source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-increase-performance-and-fulfillment-at-the-same-time]]. Created [[wiki/sources/2026-04-14-increase-performance-and-fulfillment-at-the-same-time]], the new concept [[wiki/concepts/leadership/inner-excellence]], and the new synthesis [[wiki/syntheses/leadership/jim-murphy-inner-excellence-framework]]. Used the source to deepen [[wiki/concepts/leadership/high-performance-mindset]] and [[wiki/concepts/leadership/meaning-through-responsibility]]. The leadership branch now more clearly captures a performance model built around self-belief, gratitude-based present focus, anti-hurry execution, failure without identity collapse, and service as an antidote to ego-driven choking.

Pages touched:

- [[raw/inbox/2026-04-14-increase-performance-and-fulfillment-at-the-same-time]]
- [[wiki/sources/2026-04-14-increase-performance-and-fulfillment-at-the-same-time]]
- [[wiki/concepts/leadership/inner-excellence]]
- [[wiki/syntheses/leadership/jim-murphy-inner-excellence-framework]]
- [[wiki/concepts/leadership/high-performance-mindset]]
- [[wiki/concepts/leadership/meaning-through-responsibility]]
- [[index]]
- [[log]]

## [2026-04-14 20:55] ingest | Game Theory 3 Rich Dad Poor Dad

Summary: Ingested a new English structural-success source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-14-game-theory-3-rich-dad-poor-dad]]. Created [[wiki/sources/2026-04-14-game-theory-3-rich-dad-poor-dad]] and the new concept [[wiki/concepts/business/social-mobility]]. Used the source to deepen [[wiki/concepts/leadership/growth-mindset]], [[wiki/concepts/leadership/locus-of-control]], and [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]. The business and leadership branches now more clearly distinguish trait-based explanations of success from structural ones by adding trust-rich versus trust-poor environments, class-conditioned parenting games, social mobility as game openness, and the risk of elites re-rigging institutions until the system becomes reset-prone.

Pages touched:

- [[raw/inbox/2026-04-14-game-theory-3-rich-dad-poor-dad]]
- [[wiki/sources/2026-04-14-game-theory-3-rich-dad-poor-dad]]
- [[wiki/concepts/business/social-mobility]]
- [[wiki/concepts/leadership/growth-mindset]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/syntheses/business/game-theory-cooperation-and-competition-framework]]
- [[index]]
- [[log]]

## [2026-04-14 22:23] admin | Query routing upgrade for second-brain answers

Summary: Audited the vault for readiness as a question-answering second brain. Confirmed that the wiki layer already contains substantial concept and synthesis coverage, that the raw root is currently clear, and that internal linking is broadly healthy. Updated [[AGENTS]] and [[index]] so future query work now routes through compiled concept and synthesis pages before falling back to source inventory, making life and business questions easier to answer from durable pages instead of archive scans.

Pages touched:

- [[AGENTS]]
- [[index]]
- [[log]]

## [2026-04-14 22:33] query | Supporting a newly promoted lead under impostor pressure

Summary: Answered a practical leadership question about how to support a newly promoted team lead with impostor syndrome by compiling a new synthesis that bridges tactical empathy, growth mindset, character-based leadership, inner excellence, trust-centered leadership, and Klopp's confidence-protective coaching logic. Added a reusable page so future coaching questions can route through a durable model instead of reconstructing the advice from adjacent branches.

Pages touched:

- [[wiki/syntheses/leadership/supporting-a-new-team-lead-under-impostor-pressure]]
- [[index]]
- [[log]]

## [2026-04-14 22:33] admin | Create dedicated query-answer folder

Summary: Updated the schema so durable answers created from user questions now live in `wiki/queries/` instead of being mixed into `wiki/syntheses/`. Added a dedicated `Queries` section to [[index]], noted that chat responses should use Codex-compatible absolute file links, and migrated the existing impostor-pressure answer into the new query-answer folder.

Pages touched:

- [[AGENTS]]
- [[index]]
- [[wiki/queries/supporting-a-new-team-lead-under-impostor-pressure]]
- [[log]]

## [2026-04-15 00:25] query | Three-day performance crunch plan

Summary: Answered a practical high-pressure work question by compiling a query page on how to handle too many important tasks across the next three days. The resulting model combines 4DX-style priority protection, GTD-style capture and next-action clarity, peak-hour defense, signal-to-noise filtering, interval-based focus, and anti-panic performance framing.

Pages touched:

- [[wiki/queries/three-day-performance-crunch-plan]]
- [[index]]
- [[log]]

## [2026-04-15 01:48] ingest | How To Defuse Procrastination And Be Productive

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-how-to-defuse-procrastination-and-be-productive]]. Created [[wiki/sources/2026-04-15-how-to-defuse-procrastination-and-be-productive]], the new concept [[wiki/concepts/productivity/procrastination]], and the new synthesis [[wiki/syntheses/productivity/procrastination-defusing-framework]]. Used the source to deepen [[wiki/concepts/productivity/willpower]], [[wiki/concepts/productivity/restorative-breaks]], and [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]. The productivity branch now more clearly captures working-memory narrowing, anti-binary action choice, `next best thing` task sizing, and doorway-style context shifts as a way to break stuck avoidance loops without reducing the whole problem to weak discipline.

Pages touched:

- [[raw/inbox/2026-04-15-how-to-defuse-procrastination-and-be-productive]]
- [[wiki/sources/2026-04-15-how-to-defuse-procrastination-and-be-productive]]
- [[wiki/concepts/productivity/procrastination]]
- [[wiki/syntheses/productivity/procrastination-defusing-framework]]
- [[wiki/concepts/productivity/willpower]]
- [[wiki/concepts/productivity/restorative-breaks]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework]]
- [[index]]
- [[log]]

## [2026-04-15 02:06] ingest | How To Always Stay Motivated

Summary: Ingested a new English motivation source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-how-to-always-stay-motivated]]. Created [[wiki/sources/2026-04-15-how-to-always-stay-motivated]], the new concept [[wiki/concepts/leadership/identity-based-motivation]], the new synthesis [[wiki/syntheses/leadership/identity-based-motivation-framework]], and the new entity page [[wiki/entities/alok-kanojia]]. Used the source to deepen [[wiki/concepts/leadership/locus-of-control]], [[wiki/concepts/productivity/calibrated-challenge]], and [[wiki/syntheses/leadership/locus-of-control-motivation-framework]]. The motivation branch now more clearly distinguishes causal agency from identity-shaped task appraisal and preserves boredom and overwhelm as two self-concept-driven failures of usable effort.

Pages touched:

- [[raw/inbox/2026-04-15-how-to-always-stay-motivated]]
- [[wiki/sources/2026-04-15-how-to-always-stay-motivated]]
- [[wiki/concepts/leadership/identity-based-motivation]]
- [[wiki/syntheses/leadership/identity-based-motivation-framework]]
- [[wiki/entities/alok-kanojia]]
- [[wiki/concepts/leadership/locus-of-control]]
- [[wiki/concepts/productivity/calibrated-challenge]]
- [[wiki/syntheses/leadership/locus-of-control-motivation-framework]]
- [[index]]
- [[log]]

## [2026-04-15 21:26] ingest | 5 Habits that Destroy Your Productivity

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-5-habits-that-destroy-your-productivity]]. Created [[wiki/sources/2026-04-15-5-habits-that-destroy-your-productivity]] and the new synthesis [[wiki/syntheses/productivity/anti-productivity-myths-framework]]. Used the source to deepen [[wiki/concepts/productivity/serial-tasking]], [[wiki/concepts/productivity/calibrated-challenge]], [[wiki/concepts/business/career-capital]], [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/syntheses/business/cal-newport-career-capital-framework]], and [[wiki/entities/alok-kanojia]]. The branch now more clearly distinguishes application from passive self-improvement, serial focus from multitasking, main-career compounding from side-hustle dilution, calibrated challenge from hustle theater, and reciprocity from self-first extraction.

Pages touched:

- [[raw/inbox/2026-04-15-5-habits-that-destroy-your-productivity]]
- [[wiki/sources/2026-04-15-5-habits-that-destroy-your-productivity]]
- [[wiki/syntheses/productivity/anti-productivity-myths-framework]]
- [[wiki/concepts/productivity/serial-tasking]]
- [[wiki/concepts/productivity/calibrated-challenge]]
- [[wiki/concepts/business/career-capital]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/syntheses/business/cal-newport-career-capital-framework]]
- [[wiki/entities/alok-kanojia]]
- [[index]]
- [[log]]

## [2026-04-15 21:52] ingest | How to Become More Mentally Efficient & Conscientious

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-how-to-become-more-mentally-efficient-and-conscientious]]. Created [[wiki/sources/2026-04-15-how-to-become-more-mentally-efficient-and-conscientious]] and the new synthesis [[wiki/syntheses/productivity/conscientiousness-training-framework]]. Used the source to deepen [[wiki/concepts/productivity/conscientiousness]], [[wiki/concepts/productivity/willpower]], [[wiki/concepts/leadership/trust-based-collaboration]], [[wiki/syntheses/leadership/identity-based-motivation-framework]], [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]], and [[wiki/entities/alok-kanojia]]. The branch now more clearly models conscientiousness as partly trainable through costly prosocial action, distinguishes empathy from chosen altruism, and preserves `do it for someone else` as a possible bridge from motivation into disciplined follow-through.

Pages touched:

- [[raw/inbox/2026-04-15-how-to-become-more-mentally-efficient-and-conscientious]]
- [[wiki/sources/2026-04-15-how-to-become-more-mentally-efficient-and-conscientious]]
- [[wiki/syntheses/productivity/conscientiousness-training-framework]]
- [[wiki/concepts/productivity/conscientiousness]]
- [[wiki/concepts/productivity/willpower]]
- [[wiki/concepts/leadership/trust-based-collaboration]]
- [[wiki/syntheses/leadership/identity-based-motivation-framework]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework]]
- [[wiki/entities/alok-kanojia]]
- [[index]]
- [[log]]

## [2026-04-15 21:57] ingest | Procrastination Holds You Back

Summary: Ingested a new English productivity source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-15-procrastination-holds-you-back]]. Created [[wiki/sources/2026-04-15-procrastination-holds-you-back]] and the new synthesis [[wiki/syntheses/productivity/mind-training-procrastination-framework]]. Used the source to deepen [[wiki/concepts/productivity/procrastination]], [[wiki/syntheses/productivity/procrastination-defusing-framework]], [[wiki/concepts/productivity/willpower]], [[wiki/concepts/health/mindfulness]], [[wiki/concepts/leadership/identity-based-motivation]], [[wiki/syntheses/leadership/identity-based-motivation-framework]], and [[wiki/entities/alok-kanojia]]. The procrastination branch now more clearly captures false inner struggle, anti-bargaining mind-training, `do the task or do nothing`, and the claim that action often improves when thoughts are treated as mind activity rather than as authoritative self-definition.

Pages touched:

- [[raw/inbox/2026-04-15-procrastination-holds-you-back]]
- [[wiki/sources/2026-04-15-procrastination-holds-you-back]]
- [[wiki/syntheses/productivity/mind-training-procrastination-framework]]
- [[wiki/concepts/productivity/procrastination]]
- [[wiki/syntheses/productivity/procrastination-defusing-framework]]
- [[wiki/concepts/productivity/willpower]]
- [[wiki/concepts/health/mindfulness]]
- [[wiki/concepts/leadership/identity-based-motivation]]
- [[wiki/syntheses/leadership/identity-based-motivation-framework]]
- [[wiki/entities/alok-kanojia]]
- [[index]]
- [[log]]

## [2026-04-16 20:59] ingest | Why Introverts Struggle With Charisma

Summary: Ingested a new English communication source from `raw/` and archived the canonical raw file at [[raw/inbox/2026-04-16-why-introverts-struggle-with-charisma]]. Created [[wiki/sources/2026-04-16-why-introverts-struggle-with-charisma]] and the new synthesis [[wiki/syntheses/communication/introvert-charisma-framework]]. Used the source to deepen [[wiki/concepts/communication/charismatic-presence]], [[wiki/concepts/communication/effective-communication]], [[wiki/concepts/communication/thinking-on-your-feet]], [[wiki/concepts/leadership/leadership-communication]], and [[wiki/entities/alok-kanojia]]. The communication branch now more clearly models charisma for introverts as trainable through prepared communication, visibility tolerance, eye-contact exposure, and reduced self-referential embarrassment rather than as extrovert-only essence.

Pages touched:

- [[raw/inbox/2026-04-16-why-introverts-struggle-with-charisma]]
- [[wiki/sources/2026-04-16-why-introverts-struggle-with-charisma]]
- [[wiki/syntheses/communication/introvert-charisma-framework]]
- [[wiki/concepts/communication/charismatic-presence]]
- [[wiki/concepts/communication/effective-communication]]
- [[wiki/concepts/communication/thinking-on-your-feet]]
- [[wiki/concepts/leadership/leadership-communication]]
- [[wiki/entities/alok-kanojia]]
- [[index]]
- [[log]]
## [2026-04-16 21:05] ingest | What High Performers Know That You Don't

Pages touched:
- [[wiki/sources/2026-04-16-what-high-performers-know-that-you-dont|What High Performers Know That You Don't]]
- [[wiki/syntheses/productivity/high-performer-coping-framework|High-Performer Coping Framework]]
- [[wiki/concepts/leadership/high-performance-mindset|High-Performance Mindset]]
- [[wiki/concepts/health/experiential-avoidance|Experiential Avoidance]]
- [[wiki/concepts/productivity/conscientiousness|Conscientiousness]]
- [[wiki/entities/alok-kanojia|Alok Kanojia]]
- [[index|index]]

Summary:
- Ingested a new Alok Kanojia source on long-term versus short-term compassion, selective refusal, action-oriented coping, and the performance costs of `toxic fuel`.
- Added a durable synthesis page that separates useful pressure-conversion from passive coping and from romanticized self-sacrifice.
- Updated nearby canonical concepts so the source now sharpens the vault's treatment of conscientiousness boundaries, experiential avoidance, and high-performance tradeoffs.
## [2026-04-16 21:12] ingest | How To Succeed At Anything

Pages touched:
- [[wiki/sources/2026-04-16-how-to-succeed-at-anything|How To Succeed At Anything]]
- [[wiki/concepts/leadership/values-driven-action|Values-Driven Action]]
- [[wiki/syntheses/leadership/values-driven-motivation-framework|Values-Driven Motivation Framework]]
- [[wiki/concepts/leadership/high-performance-mindset|High-Performance Mindset]]
- [[wiki/entities/alok-kanojia|Alok Kanojia]]
- [[index|index]]

Summary:
- Ingested a new Alok Kanojia source on anti-comparison motivation, values as stable fuel, the `human element` bottleneck in success formulas, and early imperfect application as reinforcement.
- Folded the source into the existing values-driven branch instead of creating a duplicate framework page.
- Strengthened the vault's treatment of values-driven action by making shame, prestige fantasy, and reinforcement loops more explicit.
## [2026-04-16 21:15] ingest | Imposter Syndrome Is Holding You Back In Life

Pages touched:
- [[wiki/sources/2026-04-16-imposter-syndrome-is-holding-you-back-in-life|Imposter Syndrome Is Holding You Back In Life]]
- [[wiki/concepts/health/imposter-syndrome|Imposter Syndrome]]
- [[wiki/concepts/leadership/identity-based-motivation|Identity-Based Motivation]]
- [[wiki/syntheses/leadership/identity-based-motivation-framework|Identity-Based Motivation Framework]]
- [[wiki/entities/alok-kanojia|Alok Kanojia]]
- [[index|index]]

Summary:
- Ingested a new Alok Kanojia source on imposter syndrome as an achievement-linked shame adaptation maintained by effort devaluation, asymmetric attribution, and externalized validation.
- Created a canonical health concept page for imposter syndrome rather than leaving the pattern trapped inside one source summary.
- Updated the identity-based motivation branch so the vault now covers both identity friction before action and failure to internalize success afterward.
## [2026-04-16 21:19] ingest | Jordan Peterson Overcoming Imposter Syndrome

Pages touched:
- [[wiki/sources/2026-04-16-jordan-peterson-overcoming-imposter-syndrome|Jordan Peterson Overcoming Imposter Syndrome]]
- [[wiki/concepts/health/imposter-syndrome|Imposter Syndrome]]
- [[wiki/syntheses/leadership/identity-based-motivation-framework|Identity-Based Motivation Framework]]
- [[wiki/entities/jordan-peterson|Jordan Peterson]]
- [[index|index]]

Summary:
- Ingested a Jordan Peterson source that reframes some imposter feelings as normal status-transition stress rather than automatic pathology.
- Updated the canonical imposter-syndrome page with the distinction between beginner anxiety and evidence-resistant `imposter adaptation`, plus the role of question-asking, honest `acting as if`, and exposure.
- Kept the new material integrated into the existing identity branch instead of creating a redundant second imposter framework.
## [2026-04-16 21:30] ingest | Why You're Struggling With Discipline

Pages touched:
- [[raw/inbox/2026-04-16-why-youre-struggling-with-discipline|Why You're Struggling With Discipline]]
- [[wiki/sources/2026-04-16-why-youre-struggling-with-discipline|Why You're Struggling With Discipline]]
- [[wiki/syntheses/productivity/authentic-discipline-framework|Authentic Discipline Framework]]
- [[wiki/concepts/productivity/willpower|Willpower]]
- [[wiki/concepts/productivity/dopamine-regulation|Dopamine Regulation]]
- [[wiki/concepts/productivity/procrastination|Procrastination]]
- [[index|index]]

Summary:
- Ingested a new productivity source on why discipline often fails when present comfort beats the future being promised.
- Added a new synthesis page around authentic discipline so the source's distinctive contribution stays visible as motive selection, `competing interest`, and all-or-nothing resistance rather than collapsing into generic willpower advice.
- Updated the canonical willpower, dopamine-regulation, and procrastination pages so the productivity branch now distinguishes resistance-capacity problems from value-conflict problems more clearly.
## [2026-04-16 21:38] ingest | Should You Follow Your Passion Solved

Pages touched:
- [[raw/inbox/2026-04-16-should-you-follow-your-passion-solved|Should You Follow Your Passion Solved]]
- [[wiki/sources/2026-04-16-should-you-follow-your-passion-solved|Should You Follow Your Passion Solved]]
- [[wiki/syntheses/business/passion-and-practicality-framework|Passion and Practicality Framework]]
- [[wiki/concepts/business/career-capital|Career Capital]]
- [[wiki/concepts/business/craftsman-mindset|Craftsman Mindset]]
- [[wiki/concepts/business/zone-of-genius|Zone of Genius]]
- [[wiki/concepts/business/career-blueprint|Career Blueprint]]
- [[index|index]]

Summary:
- Ingested a new business-career source that rejects the `passion versus practicality` binary and reframes passion as something developed under constraints rather than discovered in pure form.
- Added a new synthesis around passion and practicality so the source's distinctive contribution remains visible as harmonious versus obsessive passion, power-law realism, adjacent-path testing, and runway-aware career design.
- Updated the canonical career-capital, craftsman-mindset, zone-of-genius, and career-blueprint pages so the business branch now treats passion as developmental, risk-adjusted, and constraint-sensitive rather than as either naive destiny or something to ignore.
## [2026-04-16 22:45] ingest | How You Keep Yourself Suffering

Pages touched:
- [[raw/inbox/2026-04-16-how-you-keep-yourself-suffering|How You Keep Yourself Suffering]]
- [[wiki/sources/2026-04-16-how-you-keep-yourself-suffering|How You Keep Yourself Suffering]]
- [[wiki/syntheses/health/involvement-over-identity-suffering-framework|Involvement Over Identity-Suffering Framework]]
- [[wiki/concepts/health/experiential-avoidance|Experiential Avoidance]]
- [[wiki/concepts/health/overthinking|Overthinking]]
- [[wiki/concepts/leadership/identity-based-motivation|Identity-Based Motivation]]
- [[wiki/concepts/leadership/high-performance-mindset|High-Performance Mindset]]
- [[wiki/entities/alok-kanojia|Alok Kanojia]]
- [[index|index]]

Summary:
- Ingested a new health-psychology source on high-functioning suffering maintained by identity-preserving overachievement, emotional amputation, congruent depression, and timeline shame.
- Added a new health synthesis around involvement over identity so the source's distinctive contribution stays visible as a model of defended success that still produces emptiness.
- Updated the canonical experiential-avoidance, overthinking, identity-based-motivation, high-performance-mindset, and Alok Kanojia pages so the vault now tracks how achievement itself can become an avoidance structure rather than evidence of wellbeing.
## [2026-04-16 22:53] ingest | 9 Habits for Clearer Speaking I Wish I Knew Sooner

Pages touched:
- [[raw/inbox/2026-04-16-9-habits-for-clearer-speaking-i-wish-i-knew-sooner|9 Habits for Clearer Speaking I Wish I Knew Sooner]]
- [[wiki/sources/2026-04-16-9-habits-for-clearer-speaking-i-wish-i-knew-sooner|9 Habits for Clearer Speaking I Wish I Knew Sooner]]
- [[wiki/syntheses/communication/clear-speaking-habits-framework|Clear Speaking Habits Framework]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/thinking-on-your-feet|Thinking on Your Feet]]
- [[index|index]]

Summary:
- Ingested a new communication source on speaking clarity as a trainable system of delivery, vocal, and cognitive habits rather than as vague charisma.
- Added a new communication synthesis so the source's distinctive contribution stays visible as pause control, declarative phrasing, vocal setup, `CCC`, and analogy-based explanation.
- Updated the canonical effective-communication and thinking-on-your-feet pages so the communication branch now includes a more mechanical model of speech legibility alongside its existing pressure-management and audience-design layers.
## [2026-04-16 22:54] ingest | The 3-2-1 Speaking Trick That Forces You To Stop Rambling

Pages touched:
- [[raw/inbox/2026-04-16-the-3-2-1-speaking-trick-that-forces-you-to-stop-rambling|The 3-2-1 Speaking Trick That Forces You To Stop Rambling]]
- [[wiki/sources/2026-04-16-the-3-2-1-speaking-trick-that-forces-you-to-stop-rambling|The 3-2-1 Speaking Trick That Forces You To Stop Rambling]]
- [[wiki/concepts/communication/thinking-on-your-feet|Thinking on Your Feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework|Thinking on Your Feet Framework]]
- [[index|index]]

Summary:
- Ingested a new communication source that treats rambling as a structure failure and contributes `3-2-1` as a minimal fallback for spontaneous speaking.
- Added a source page so the note's distinctive value remains legible as `three steps`, `two types`, `one thing`, signposting, and random-topic pressure drills.
- Updated the canonical thinking-on-your-feet branch so the vault now includes an emergency-use answer scaffold alongside its existing deeper live-speaking frameworks.
## [2026-04-16 22:50] ingest | Doing This (Almost) GUARANTEES You Get Hired In A Job Interview

Pages touched:
- [[raw/inbox/2026-04-16-doing-this-almost-guarantees-you-get-hired-in-a-job-interview|Doing This (Almost) GUARANTEES You Get Hired In A Job Interview]]
- [[wiki/sources/2026-04-16-doing-this-almost-guarantees-you-get-hired-in-a-job-interview|Doing This (Almost) GUARANTEES You Get Hired In A Job Interview]]
- [[wiki/syntheses/business/job-interview-storytelling-framework|Job Interview Storytelling Framework]]
- [[wiki/concepts/business/career-blueprint|Career Blueprint]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/thinking-on-your-feet|Thinking on Your Feet]]
- [[index|index]]

Summary:
- Ingested a new business-career source that reframes interview success as preparation plus role-relevant narrative rather than spontaneous self-description.
- Added a dedicated interview synthesis so the source's distinctive contribution stays visible as origin-story design, evidence over adjectives, explicit role-bridging, and rapport as a functional part of hiring conversations.
- Updated the canonical career-blueprint, effective-communication, and thinking-on-your-feet pages so the vault now covers how a coherent career story gets translated into a prepared interview performance.
## [2026-04-16 22:54] ingest | Give me 14 minutes and I'll help you think & speak faster

Pages touched:
- [[raw/inbox/2026-04-16-give-me-14-minutes-and-ill-help-you-think-and-speak-faster|Give me 14 minutes and I'll help you think & speak faster]]
- [[wiki/sources/2026-04-16-give-me-14-minutes-and-ill-help-you-think-and-speak-faster|Give me 14 minutes and I'll help you think & speak faster]]
- [[wiki/syntheses/communication/clear-speaking-habits-framework|Clear Speaking Habits Framework]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/thinking-on-your-feet|Thinking on Your Feet]]
- [[index|index]]

Summary:
- Ingested a new communication source that treats faster speaking as a trainable hardware-and-software system rather than a fixed trait.
- Added a source page so the note's distinctive value remains legible as articulation drills, WPM baselining, breath-efficiency practice, domain-depth logic, and `3-2-1` as a constraint tool for broad answers.
- Updated the clear-speaking, effective-communication, and thinking-on-your-feet branches so the vault now includes a more measurable model of speech-speed training and faster explanation under pressure.
## [2026-04-16 23:01] ingest | How to Remember Everything You Read

Pages touched:
- [[raw/inbox/2026-04-16-how-to-remember-everything-you-read|How to Remember Everything You Read]]
- [[wiki/sources/2026-04-16-how-to-remember-everything-you-read|How to Remember Everything You Read]]
- [[wiki/syntheses/productivity/pacer-reading-and-retention-framework|PACER Reading and Retention Framework]]
- [[wiki/concepts/productivity/retrieval-practice|Retrieval Practice]]
- [[wiki/concepts/productivity/speed-reading|Speed Reading]]
- [[wiki/syntheses/productivity/barbara-oakley-learning-framework|Barbara Oakley Learning Framework]]
- [[index|index]]

Summary:
- Ingested a new productivity-learning source that reframes forgetting after reading as a digestion failure and adds the PACER classification system for routing different information types into different processing methods.
- Added a dedicated PACER synthesis so the source's distinctive contribution stays visible as consumption-versus-digestion, the `big three` knowledge types, conceptual mapping, external storage of specifics, and selective retention over indiscriminate memory.
- Updated the retrieval-practice, speed-reading, and Barbara Oakley learning branches so the vault now links reading efficiency more explicitly to post-reading processing rather than treating intake speed as the main learning lever.
## [2026-04-16 23:10] ingest | Jesse Cole fans-first experience source

Pages touched:
- [[wiki/sources/2026-04-16-why-this-baseball-team-has-a-4-2-million-person-waitlist-with-jesse-cole|Why This Baseball Team Has a 4.2 Million Person Waitlist With Jesse Cole]]
- [[wiki/concepts/business/experience-design|Experience Design]]
- [[wiki/syntheses/business/jesse-cole-fans-first-experience-framework|Jesse Cole Fans-First Experience Framework]]
- [[wiki/concepts/business/brand-strategy|Brand Strategy]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[index|index]]

Summary:
- Ingested a new Jesse Cole source on the Savannah Bananas and extracted a reusable business model centered on end-to-end experience design, `upper deck` empathy, generosity as strategy, and structured experimentation.
- Added a new canonical concept page for [[wiki/concepts/business/experience-design|Experience Design]] so the source's strongest reusable idea is not trapped in the source summary.
- Updated [[wiki/concepts/business/brand-strategy|Brand Strategy]] and [[wiki/concepts/business/success-metrics|Success Metrics]] to incorporate the source's operational brand embodiment and anti-extraction scoreboard logic.
## [2026-04-16 23:15] ingest | Quiet ego source

Pages touched:
- [[wiki/sources/2026-04-16-how-to-quiet-your-ego|How to Quiet Your Ego]]
- [[wiki/concepts/health/quiet-ego|Quiet Ego]]
- [[wiki/syntheses/health/quiet-ego-framework|Quiet Ego Framework]]
- [[wiki/concepts/health/mindfulness|Mindfulness]]
- [[wiki/concepts/leadership/identity-based-motivation|Identity-Based Motivation]]
- [[wiki/concepts/leadership/high-performance-mindset|High-Performance Mindset]]
- [[index|index]]

Summary:
- Ingested a new psychology source on ego rigidity versus flexibility and extracted its strongest reusable contribution as a `quiet ego` model built from detached awareness, inclusive identity, perspective-taking, and growth-mindedness.
- Added a new canonical health concept page for [[wiki/concepts/health/quiet-ego|Quiet Ego]] and a matching synthesis so the source's self-structure model is available outside the source page.
- Updated [[wiki/concepts/health/mindfulness|Mindfulness]], [[wiki/concepts/leadership/identity-based-motivation|Identity-Based Motivation]], and [[wiki/concepts/leadership/high-performance-mindset|High-Performance Mindset]] to connect mindfulness, motivation, and performance more explicitly to ego flexibility rather than only to calm, effort, or intensity.
## [2026-04-17 00:52] ingest | Mark Manson resilience expansion source

Pages touched:
- [[wiki/sources/2026-04-17-how-to-become-resilient|How to Become Resilient]]
- [[wiki/concepts/health/stress-inoculation|Stress Inoculation]]
- [[wiki/concepts/health/stress-mindset|Stress Mindset]]
- [[wiki/concepts/leadership/mental-toughness|Mental Toughness]]
- [[wiki/syntheses/leadership/mark-manson-resilience-framework|Mark Manson Resilience Framework]]
- [[index|index]]

Summary:
- Ingested a new Mark Manson resilience source that expands the branch from challenge appraisal alone into biological reserve, Goldilocks-zone stress inoculation, social buffering, humor, and the hidden costs of overdeveloped resilience.
- Added a canonical concept page for [[wiki/concepts/health/stress-inoculation|Stress Inoculation]] so the source's main training method is explicit and reusable across the vault.
- Updated [[wiki/concepts/health/stress-mindset|Stress Mindset]], [[wiki/concepts/leadership/mental-toughness|Mental Toughness]], and [[wiki/syntheses/leadership/mark-manson-resilience-framework|Mark Manson Resilience Framework]] so the resilience branch now shows both psychophysiological reserve and relationship-level resilience more clearly.
## [2026-04-17 01:10] ingest | How to Stop Procrastinating

Pages touched:
- [[raw/inbox/2026-04-17-how-to-stop-procrastinating|How to Stop Procrastinating]]
- [[wiki/sources/2026-04-17-how-to-stop-procrastinating|How to Stop Procrastinating]]
- [[wiki/concepts/productivity/procrastination|Procrastination]]
- [[wiki/syntheses/productivity/procrastination-defusing-framework|Procrastination Defusing Framework]]
- [[wiki/entities/mark-manson|Mark Manson]]
- [[index|index]]

Summary:
- Ingested a new Mark Manson productivity source that reframes procrastination as emotional avoidance and short-term mood repair rather than a character defect or a pure scheduling problem.
- Added a dedicated source page so the note's durable value remains explicit as shame and perfectionism loops, Temporal Motivation Theory, RAIN, minimum viable action, identity stakes, and system-tinkering as respectable avoidance.
- Updated the canonical procrastination branch and Mark Manson entity so the vault now links working-memory, anti-bargaining, authentic desire, and emotional-regulation models instead of leaving them as parallel fragments.
## [2026-04-17 01:17] ingest | Savannah Bananas 5 E's source

Pages touched:
- [[raw/inbox/2026-04-17-savannah-bananas-the-5-es-to-creating-raving-fans|Savannah Bananas The 5 E's To Creating Raving Fans]]
- [[wiki/sources/2026-04-17-savannah-bananas-the-5-es-to-creating-raving-fans|Savannah Bananas The 5 E's To Creating Raving Fans]]
- [[wiki/concepts/business/experience-design|Experience Design]]
- [[wiki/syntheses/business/jesse-cole-fans-first-experience-framework|Jesse Cole Fans-First Experience Framework]]
- [[index|index]]

Summary:
- Ingested a second Jesse Cole business source that turns the Savannah Bananas story into an explicit `5 E's` operating model for fan-first growth.
- Added a dedicated source page so the note's durable value remains visible as friction removal, touchpoint entertainment, rapid experimentation, deep participation, and fan-and-staff empowerment.
- Updated the canonical Jesse Cole experience branch so the vault now combines the earlier waitlist, generosity, and `upper deck` material with a clearer transferable operating sequence rather than leaving them as separate adjacent summaries.
## [2026-04-17 01:21] ingest | Jesse Cole bankrupt-to-breathtaking interview

Pages touched:
- [[raw/inbox/2026-04-17-savannah-bananas-jesse-cole-from-bankrupt-to-breathtaking|Savannah Bananas Jesse Cole From Bankrupt to Breathtaking]]
- [[wiki/sources/2026-04-17-savannah-bananas-jesse-cole-from-bankrupt-to-breathtaking|Savannah Bananas Jesse Cole From Bankrupt to Breathtaking]]
- [[wiki/entities/jesse-cole|Jesse Cole]]
- [[wiki/concepts/leadership/organizational-culture|Organizational Culture]]
- [[wiki/syntheses/business/jesse-cole-fans-first-experience-framework|Jesse Cole Fans-First Experience Framework]]
- [[index|index]]

Summary:
- Ingested a third Jesse Cole source that expands the branch from fan-first experience into founder psychology, product redesign, creative operations, and belonging-driven leadership.
- Added a canonical Jesse Cole entity page so the repeated Bananas material now has a stable person-level home linking experience design, culture, metrics, and founder operating logic.
- Updated the Jesse Cole synthesis and organizational-culture concept so the vault now captures the `attention plan`, Banana Ball as product innovation, weekly creative cadence, explicit expectation-setting, and the tension between founder intensity and scalable culture.
## [2026-04-17 01:31] ingest | Modern Day Disney Jesse Cole source

Pages touched:
- [[raw/inbox/2026-04-17-modern-day-disney-the-key-to-making-a-dream-a-reality|Modern Day Disney The Key To Making A Dream A Reality]]
- [[wiki/sources/2026-04-17-modern-day-disney-the-key-to-making-a-dream-a-reality|Modern Day Disney The Key To Making A Dream A Reality]]
- [[wiki/entities/jesse-cole|Jesse Cole]]
- [[wiki/concepts/leadership/organizational-culture|Organizational Culture]]
- [[wiki/syntheses/business/jesse-cole-fans-first-experience-framework|Jesse Cole Fans-First Experience Framework]]
- [[index|index]]

Summary:
- Ingested another Jesse Cole source that clarifies belief before proof, the `messy phase` of early experience design, and internal-external culture symmetry.
- Added a dedicated source page so the note's durable value remains visible as friction-first design, gratitude rituals, employee-as-fan logic, and Disney-style tolerance for chaotic first versions.
- Updated the Jesse Cole entity, organizational-culture concept, and Jesse Cole synthesis so the branch now reflects belief-signaling, backstage-to-frontstage alignment, and the risk that visionary conviction can drift into magical thinking if operational truth gets lost.
## [2026-04-17 01:36] ingest | Jefferson Fisher conflict-composure source

Pages touched:
- [[raw/inbox/2026-04-17-phrases-you-must-use-to-sound-confident-and-undisturbed-during-conflict|Phrases You Must Use to Sound Confident and Undisturbed During Conflict]]
- [[wiki/sources/2026-04-17-phrases-you-must-use-to-sound-confident-and-undisturbed-during-conflict|Phrases You Must Use to Sound Confident and Undisturbed During Conflict]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/concepts/communication/frame-control|Frame Control]]
- [[wiki/concepts/communication/interactional-authority|Interactional Authority]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher communication source that extends the branch from apology and manipulation handling into live conflict composure and de-escalation.
- Added a dedicated source page so the note's durable value remains visible as voice control, time as regulator, no-oriented questions, perspective-validation, and the three-part frame formula for difficult conversations.
- Updated the Jefferson Fisher synthesis plus frame-control and interactional-authority concepts so the vault now links boundary language with vocal pacing, pause discipline, and process-framing under pressure.
## [2026-04-17 01:56] ingest | Jefferson Fisher emotional-responsibility source

Pages touched:
- [[raw/inbox/2026-04-17-youre-not-responsible-for-their-emotions|You're Not Responsible for Their Emotions]]
- [[wiki/sources/2026-04-17-youre-not-responsible-for-their-emotions|You're Not Responsible for Their Emotions]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source centered on refusing emotional outsourcing, self-regulation before reply, and staying out of the `easy target` role during conflict.
- Added a dedicated source page so the note's durable value remains visible as breath-first response, `does not threaten me` relabeling, reflective questions about rude intent, and the distinction between ordinary disrespect and unsafe dynamics.
- Updated Boundary Language, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now ties accountability phrasing more explicitly to internal regulation, emotional non-capture, and reflective confrontation.
## [2026-04-17 01:59] ingest | Belittling-response conflict source

Pages touched:
- [[raw/inbox/2026-04-17-how-to-respond-when-someone-belittles-you-confidence-tips|How to Respond When Someone Belittles You Confidence Tips]]
- [[wiki/sources/2026-04-17-how-to-respond-when-someone-belittles-you-confidence-tips|How to Respond When Someone Belittles You Confidence Tips]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new conflict-response source focused on belittling remarks, public put-downs, and protecting integrity without escalating into reactive combat.
- Added a dedicated source page so the note's durable value remains visible as the three-step `repeat / ask intent / use silence` sequence, contempt as provocation for emotional payoff, and the distinction between ordinary belittlement and unsafe hierarchy.
- Updated Boundary Language, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now captures repetition requests, more specific intent questions, and silence as an active respect-threshold move.
## [2026-04-17 02:04] ingest | Jefferson Fisher rude-comments source

Pages touched:
- [[raw/inbox/2026-04-17-responding-to-rude-comments-without-losing-your-cool|Responding To Rude Comments Without Losing Your Cool]]
- [[wiki/sources/2026-04-17-responding-to-rude-comments-without-losing-your-cool|Responding To Rude Comments Without Losing Your Cool]]
- [[wiki/concepts/communication/dynamic-silence|Dynamic Silence]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source on moderate rude comments and passive aggression that expands the branch beyond belittling into a broader anti-escalation model.
- Added a dedicated source page so the note's durable value remains visible as the `rudeness card game` metaphor, `Did you mean...?` clarification, `It sounds like...` passive-aggression checks, 4-second deliberate silence, and digital tone-repair through short clarifying questions.
- Updated Dynamic Silence, Boundary Language, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now distinguishes overt rudeness from passive aggression, links silence to non-participation in escalation, and carries the model into email and text.
## [2026-04-17 02:12] ingest | Jefferson Fisher defensiveness source

Pages touched:
- [[raw/inbox/2026-04-17-how-to-handle-defensiveness-in-communication|How to Handle Defensiveness in Communication]]
- [[wiki/sources/2026-04-17-how-to-handle-defensiveness-in-communication|How to Handle Defensiveness in Communication]]
- [[wiki/concepts/communication/face-saving-de-escalation|Face-Saving De-Escalation]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source focused on defensiveness as a threat response in ordinary communication, feedback, and leadership.
- Added a dedicated source page so the note's durable value remains visible as the `ignition vs cooling` model, `let the words fall to the ground` self-regulation metaphor, `I` statements over `you` accusations, and `what/how/can we` replacements for `why` and `you need to`.
- Updated Face-Saving De-Escalation, Effective Communication, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now captures autonomy-sensitive phrasing and a clearer distinction between lowering defensiveness and weakening accountability.
## [2026-04-17 11:23] ingest | Being Nice Won't Save You in Difficult Conversations

Pages touched:
- [[raw/inbox/2026-04-17-being-nice-wont-save-you-in-difficult-conversations|Being Nice Won't Save You in Difficult Conversations]]
- [[wiki/sources/2026-04-17-being-nice-wont-save-you-in-difficult-conversations|Being Nice Won't Save You in Difficult Conversations]]
- [[wiki/concepts/communication/assertiveness|Assertiveness]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/concepts/communication/authentic-communication|Authentic Communication]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source that reframes chronic niceness as a self-erasing conflict strategy rather than as genuine kindness.
- Added a dedicated source page so the note's durable value remains visible as the `nice versus kind` distinction, `decision first, phrasing second`, `no first` refusal, realness openers, and values-based boundary framing.
- Updated Assertiveness, Boundary Language, Authentic Communication, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now links honesty under pressure to anti-people-pleasing, internal decision clarity, and the psychological cost of pleasant falsehood.
## [2026-04-17 11:31] ingest | Turn Dismissiveness Around Words that Command Respect

Pages touched:
- [[raw/inbox/2026-04-17-turn-dismissiveness-around-words-that-command-respect|Turn Dismissiveness Around Words that Command Respect]]
- [[wiki/sources/2026-04-17-turn-dismissiveness-around-words-that-command-respect|Turn Dismissiveness Around Words that Command Respect]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/concepts/communication/intention-and-impact|Intention and Impact]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source focused on dismissive phrases that minimize impact while trying to control how the listener is allowed to interpret the exchange.
- Added a dedicated source page so the note's durable value remains visible as invalidation-through-humor and minimization, `I get to decide that`, `I'm sensing...`, and `I'm surprised...` as compact non-defensive boundary replies.
- Updated Boundary Language, Intention and Impact, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now treats dismissiveness as a specific accountability failure rather than only as generic rudeness or belittlement.
## [2026-04-17 11:39] ingest | Respond with Confidence Tips to Improve Your Communication Skills

Pages touched:
- [[raw/inbox/2026-04-17-respond-with-confidence-tips-to-improve-your-communication-skills|Respond with Confidence Tips to Improve Your Communication Skills]]
- [[wiki/sources/2026-04-17-respond-with-confidence-tips-to-improve-your-communication-skills|Respond with Confidence Tips to Improve Your Communication Skills]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/interactional-authority|Interactional Authority]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source on sounding more confident in professional communication through delivery choices rather than personality change.
- Added a dedicated source page so the note's durable value remains visible as `breath first` silence, anti-filler cleanup, uptalk reduction, stronger replacement phrases for `Does that make sense?`, and a confident structure for answering unknowns.
- Updated Effective Communication, Interactional Authority, and the Jefferson Fisher entity so the communication branch now captures professional-delivery confidence as a reusable pattern alongside the existing conflict-focused Fisher material.
## [2026-04-17 11:44] ingest | Outsmarting Narcissists The Praise or Provoke Trap

Pages touched:
- [[raw/inbox/2026-04-17-outsmarting-narcissists-the-praise-or-provoke-trap|Outsmarting Narcissists The Praise or Provoke Trap]]
- [[wiki/sources/2026-04-17-outsmarting-narcissists-the-praise-or-provoke-trap|Outsmarting Narcissists The Praise or Provoke Trap]]
- [[wiki/concepts/communication/boundary-language|Boundary Language]]
- [[wiki/syntheses/communication/toxic-boss-response-framework|Toxic Boss Response Framework]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source on dealing with strong narcissistic behaviors by recognizing the interaction as a rigged `praise or provoke` game rather than as a normal repairable conflict.
- Added a dedicated source page so the note's durable value remains visible as flat neutral replies, brief-contact strategy, optics-sensitive `audience` reframing, and the distinction between functioning under unavoidable contact and trying to fix the person.
- Updated Boundary Language, Toxic Boss Response Framework, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now captures a clearer no-win-manipulation model for high-control personalities and constrained-contact situations.

## [2026-04-17 11:52] ingest | 3 Courtroom Tricks That Work in Everyday Conversations

Pages touched:
- [[raw/inbox/2026-04-17-3-courtroom-tricks-that-work-in-everyday-conversations|3 Courtroom Tricks That Work in Everyday Conversations]]
- [[wiki/sources/2026-04-17-3-courtroom-tricks-that-work-in-everyday-conversations|3 Courtroom Tricks That Work in Everyday Conversations]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/interactional-authority|Interactional Authority]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source that translates courtroom-tested communication habits into ordinary disagreement and repair.
- Added a dedicated source page so the note's durable value remains visible as the `but` versus `and` distinction, moving from detail-level fighting to higher-order shared concerns, and slow deliberate delivery as a way to preserve connection.
- Updated Effective Communication, Interactional Authority, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now captures bridge wording and macro-level de-escalation rather than only conflict defense, manipulation handling, and professional confidence mechanics.

## [2026-04-17 11:58] ingest | 3 Communication Truths That Will Change Every Conversation

Pages touched:
- [[raw/inbox/2026-04-17-3-communication-truths-that-will-change-every-conversation|3 Communication Truths That Will Change Every Conversation]]
- [[wiki/sources/2026-04-17-3-communication-truths-that-will-change-every-conversation|3 Communication Truths That Will Change Every Conversation]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/conversational-curiosity|Conversational Curiosity]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source focused less on tactical wording and more on the core philosophy beneath his communication advice.
- Added a dedicated source page so the note's durable value remains visible as `unravel the knot` instead of `win the argument`, `something to learn` instead of `something to prove`, the `full pitcher` metaphor, and the claim that the visible person is not the whole person.
- Updated Effective Communication, Conversational Curiosity, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the branch now captures Fisher's deeper learner-mode and depth-aware-empathy layer rather than only his conflict-response tactics.

## [2026-04-17 12:02] ingest | How to Sound Assertive Tips for Confident Communication

Pages touched:
- [[raw/inbox/2026-04-17-how-to-sound-assertive-tips-for-confident-communication|How to Sound Assertive Tips for Confident Communication]]
- [[wiki/sources/2026-04-17-how-to-sound-assertive-tips-for-confident-communication|How to Sound Assertive Tips for Confident Communication]]
- [[wiki/concepts/communication/assertiveness|Assertiveness]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source focused on assertive language cleanup in ordinary professional and interpersonal communication.
- Added a dedicated source page so the note's durable value remains visible as gratitude over unnecessary apology, removing self-undermining disclaimers, additive contribution phrasing, and `no` as a complete sentence.
- Updated Assertiveness, Effective Communication, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the branch now captures self-minimizing language habits as a practical assertiveness problem rather than only a confidence or niceness issue.

## [2026-04-17 12:06] ingest | Erin McGoff How to be Instantly More Confident at Work

Pages touched:
- [[raw/inbox/2026-04-17-erin-mcgoff-how-to-be-instantly-more-confident-at-work|Erin McGoff How to be Instantly More Confident at Work]]
- [[wiki/sources/2026-04-17-erin-mcgoff-how-to-be-instantly-more-confident-at-work|Erin McGoff How to be Instantly More Confident at Work]]
- [[wiki/entities/erin-mcgoff|Erin McGoff]]
- [[wiki/syntheses/business/erin-mcgoff-workplace-confidence-framework|Erin McGoff Workplace Confidence Framework]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/syntheses/business/job-interview-storytelling-framework|Job Interview Storytelling Framework]]
- [[index|index]]

Summary:
- Ingested a new Erin McGoff and Jefferson Fisher workplace-confidence source broad enough that its main value needed to be compiled into a dedicated business synthesis rather than left in a source page.
- Added a source page and a new Erin McGoff entity so the vault now has a stable home for her career-oriented communication material.
- Created [[wiki/syntheses/business/erin-mcgoff-workplace-confidence-framework|Erin McGoff Workplace Confidence Framework]] and updated Effective Communication plus Job Interview Storytelling Framework so the branch now captures self-talk as confidence substrate, the `10/90 rule` for weakness questions, issue-behind-the-issue framing, graceful quitting, and collaborative raise conversations.

## [2026-04-17 12:04] ingest | Why Nice People Lose Power & How To Fix It

Pages touched:
- [[raw/inbox/2026-04-17-why-nice-people-lose-power-and-how-to-fix-it|Why Nice People Lose Power & How To Fix It]]
- [[wiki/sources/2026-04-17-why-nice-people-lose-power-and-how-to-fix-it|Why Nice People Lose Power & How To Fix It]]
- [[wiki/concepts/communication/power-dynamics|Power Dynamics]]
- [[wiki/syntheses/communication/robert-greene-power-framework|Robert Greene Power Framework]]
- [[wiki/syntheses/communication/assertiveness-agreeableness-and-self-advocacy|Assertiveness, Agreeableness, and Self-Advocacy]]
- [[wiki/entities/robert-greene|Robert Greene]]
- [[index|index]]

Summary:
- Ingested a new Robert Greene source focused on why politically naive `nice` behavior loses power in real social and workplace environments.
- Added a dedicated source page so the note's durable value remains visible as power as neutral self-mastery, influence through self-interest, ethical asymmetry, early character-reading, and self-love as a defense against manipulation.
- Updated Power Dynamics, Robert Greene Power Framework, Assertiveness, Agreeableness, and Self-Advocacy, plus the Robert Greene entity so the communication branch now captures the difference between under-assertiveness as a trait problem and `niceness` as a political-literacy problem.

## [2026-04-17 12:09] ingest | Best Argument Responses Top 3 Ways to Stay Calm and Assertive

Pages touched:
- [[raw/inbox/2026-04-17-best-argument-responses-top-3-ways-to-stay-calm-and-assertive|Best Argument Responses Top 3 Ways to Stay Calm and Assertive]]
- [[wiki/sources/2026-04-17-best-argument-responses-top-3-ways-to-stay-calm-and-assertive|Best Argument Responses Top 3 Ways to Stay Calm and Assertive]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/face-saving-de-escalation|Face-Saving De-Escalation]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[index|index]]

Summary:
- Ingested a new Jefferson Fisher source focused on preventing defensiveness in ordinary arguments and workplace friction before the conversation locks up.
- Added a dedicated source page so the note's durable value remains visible as macro-level agreement, learner-mode reflection, `helpful to know` acknowledgment, and emotional validation without full factual concession.
- Updated Effective Communication, Face-Saving De-Escalation, the Jefferson Fisher synthesis, and the Jefferson Fisher entity so the communication branch now captures acknowledgment structure as a distinct de-escalation tool rather than only trigger-avoidance, boundary language, or conflict philosophy.

## [2026-04-19 21:43] ingest | Over 100 Years of Leadership Advice in 97 Minutes

Pages touched:
- [[raw/inbox/2026-04-19-over-100-years-of-leadership-advice-in-97-minutes|Over 100 Years of Leadership Advice in 97 Minutes]]
- [[wiki/sources/2026-04-19-over-100-years-of-leadership-advice-in-97-minutes|Over 100 Years of Leadership Advice in 97 Minutes]]
- [[wiki/concepts/leadership/character-based-leadership|Character-Based Leadership]]
- [[wiki/concepts/leadership/trust-based-collaboration|Trust-Based Collaboration]]
- [[wiki/concepts/leadership/leadership-vs-management|Leadership vs. Management]]
- [[wiki/concepts/leadership/leadership-communication|Leadership Communication]]
- [[index|index]]

Summary:
- Ingested a new leadership source built around John Maxwell, Patrick Lencioni, and Dave Ramsey on service, trust, communication clarity, role fit, and grounded definitions of success.
- Added a dedicated source page so the note's durable value remains visible as leadership-versus-specialist fit, the `like me / help me / trust me` follower sequence, truth-and-grace communication, `good miss` versus excuse-bound failure, and private integrity as a leadership test.
- Updated Character-Based Leadership, Trust-Based Collaboration, Leadership vs. Management, and Leadership Communication so the leadership branch now captures anti-default-promotion logic, trust sequencing, the moral case for clarity, and approval-independence as a condition of honest leadership.

## [2026-04-21 14:41] ingest | How Casinos Are Able to Predict Human Behavior

Pages touched:
- [[raw/inbox/2026-04-21-how-casinos-are-able-to-predict-human-behavior|How Casinos Are Able to Predict Human Behavior]]
- [[wiki/sources/2026-04-21-how-casinos-are-able-to-predict-human-behavior|How Casinos Are Able to Predict Human Behavior]]
- [[wiki/concepts/health/scarcity-loop|Scarcity Loop]]
- [[wiki/concepts/health/reward-based-habit-loops|Reward-Based Habit Loops]]
- [[wiki/concepts/productivity/dopamine-regulation|Dopamine Regulation]]
- [[wiki/concepts/business/psychological-leverage|Psychological Leverage]]
- [[wiki/syntheses/productivity/difficult-but-rewarding-behaviors-framework|Difficult but Rewarding Behaviors Framework]]
- [[index|index]]

Summary:
- Ingested a behavioral-design source explaining casino and app engagement through the scarcity loop: opportunity, unpredictable reward, and quick repeatability.
- Added a dedicated source page and a new Scarcity Loop concept under health so the mechanism is available beyond the casino example.
- Updated reward-based habit loops, dopamine regulation, psychological leverage, and the difficult-but-rewarding-behaviors framework so the vault now distinguishes generic fast-reward language from engineered variable-reward loops and emphasizes friction plus environmental richness as interventions.

## [2026-04-21 14:37] ingest | Trusting Teams The 5 Practices

Pages touched:
- [[raw/inbox/2026-04-21-trusting-teams-the-5-practices|Trusting Teams The 5 Practices]]
- [[wiki/sources/2026-04-21-trusting-teams-the-5-practices|Trusting Teams The 5 Practices]]
- [[wiki/concepts/leadership/trust-based-collaboration|Trust-Based Collaboration]]
- [[wiki/concepts/leadership/organizational-culture|Organizational Culture]]
- [[wiki/concepts/leadership/high-performance-team-culture|High-Performance Team Culture]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[index|index]]

Summary:
- Ingested a reinforcing Simon Sinek source on trusting teams, vulnerability safety, fear-based cultures, same-person/different-culture service behavior, and leadership as daily trust-maintenance practice.
- Added a dedicated source page so the Noah/Four Seasons versus Caesars example, United/Virgin contrast, and leadership-fitness analogy remain visible rather than being folded invisibly into the older Sinek trust source.
- Updated the trust, culture, team-performance, leadership, Sinek entity, and Sinek trust-framework pages so the leadership branch now treats hidden mistakes, rigid rule enforcement, and head-down compliance as environmental fear signals.

## [2026-04-21 14:35] ingest | Why Every Johnny Harris Video Goes Viral

Pages touched:
- [[raw/inbox/2026-04-21-why-every-johnny-harris-video-goes-viral|Why Every Johnny Harris Video Goes Viral]]
- [[wiki/sources/2026-04-21-why-every-johnny-harris-video-goes-viral|Why Every Johnny Harris Video Goes Viral]]
- [[wiki/concepts/communication/anchor-bridge-structure|Anchor-Bridge Structure]]
- [[wiki/syntheses/communication/johnny-harris-explainer-framework|Johnny Harris Explainer Framework]]
- [[wiki/entities/johnny-harris|Johnny Harris]]
- [[index|index]]

Summary:
- Ingested a reinforcing Johnny Harris analysis that overlaps with the older explainer-storytelling source but adds the `experience it, understand it` shorthand, the timeline labeling audit, the musical rhythm metaphor, and recurring visual anchors as callbacks.
- Added a dedicated source page so the new note's operational editor-facing value is preserved rather than folded invisibly into the older source.
- Updated the Anchor-Bridge Structure concept, Johnny Harris entity, and Johnny Harris Explainer Framework so the branch now captures visual-anchor density, short contextual bridges, rhythm diagnosis, and the caveat that vivid anchors can mislead when they are not representative.

## [2026-04-20 21:43] ingest | Are you an ideal team player?

Pages touched:
- [[raw/inbox/2026-04-20-are-you-an-ideal-team-player|Are you an ideal team player?]]
- [[wiki/sources/2026-04-20-are-you-an-ideal-team-player|Are you an ideal team player?]]
- [[wiki/concepts/leadership/high-performance-team-culture|High-Performance Team Culture]]
- [[wiki/concepts/leadership/emotional-intelligence|Emotional Intelligence]]
- [[wiki/concepts/leadership/trust-performance-matrix|Trust-Performance Matrix]]
- [[index|index]]

Summary:
- Ingested the first of the two new Patrick Lencioni raw entries and left the second raw file untouched for the next pass.
- Added a dedicated source page so the note's durable value remains visible as the `humble / hungry / smart` team-player model, the `accidental mess maker`, `lovable slacker`, and `skillful politician` profiles, and the self-ranking plus coaching exercise for team development.
- Updated High-Performance Team Culture, Emotional Intelligence, and Trust-Performance Matrix so the leadership branch now captures team-player composition, people-smarts as everyday coordination skill, and a sharper subtype view of trust-versus-output tradeoffs.

## [2026-04-20 21:43] ingest | The Ideal Team Player by Patrick Lencioni

Pages touched:
- [[raw/inbox/2026-04-20-the-ideal-team-player-by-patrick-lencioni|The Ideal Team Player by Patrick Lencioni]]
- [[wiki/sources/2026-04-20-the-ideal-team-player-by-patrick-lencioni|The Ideal Team Player by Patrick Lencioni]]
- [[wiki/concepts/leadership/high-performance-team-culture|High-Performance Team Culture]]
- [[wiki/concepts/leadership/trust-performance-matrix|Trust-Performance Matrix]]
- [[index|index]]

Summary:
- Ingested the second Patrick Lencioni raw entry as a reinforcing but still distinct companion to the first `ideal team player` source.
- Added a dedicated source page so the note's durable value remains visible as the model's origin story, the rule to coach the missing virtue rather than label the person, and the idea that steady expectations often produce either development or self-selection out.
- Updated High-Performance Team Culture and Trust-Performance Matrix so the leadership branch now captures virtue language as an operating system for reviews and coaching, not only as a one-time diagnostic or hiring filter.

## [2026-04-21 14:19] ingest | The 5 Step Playbook for 10x Your AI Productivity

Pages touched:
- [[raw/inbox/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity|The 5 Step Playbook for 10x Your AI Productivity]]
- [[wiki/sources/2026-04-21-the-5-step-playbook-for-10x-your-ai-productivity|The 5 Step Playbook for 10x Your AI Productivity]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/ai/ai-roleplay-simulation|AI Roleplay Simulation]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/few-shot-prompting|Few-Shot Prompting]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[index|index]]

Summary:
- Ingested a richer Jeremy Utley AI productivity source that overlaps with the older 2026-04-09 Utley note but adds clearer reusable structure.
- Added a dedicated source page plus two new AI concept pages for AI as a critical-thinking partner and AI roleplay simulation.
- Updated the existing Utley synthesis, prompt workflow, prompting concepts, human-machine collaboration, and Jeremy Utley entity so the AI branch now captures the yes-man failure mode, human-colleague context test, few-shot greatest-hits library, roleplay conversation simulator, and current caveat around chain-of-thought-style prompting.

## [2026-04-21 14:27] ingest | How To Become A Master Storyteller

Pages touched:
- [[raw/inbox/2026-04-21-how-to-become-a-master-storyteller|How To Become A Master Storyteller]]
- [[wiki/sources/2026-04-21-how-to-become-a-master-storyteller|How To Become A Master Storyteller]]
- [[wiki/syntheses/filmmaking/short-form-storytelling-framework|Short-Form Storytelling Framework]]
- [[wiki/concepts/filmmaking/story-lenses|Story Lenses]]
- [[wiki/concepts/filmmaking/story-propulsion|Story Propulsion]]
- [[wiki/concepts/filmmaking/dialogue-as-music|Dialogue as Music]]
- [[wiki/concepts/filmmaking/visual-storytelling-first|Visual Storytelling First]]
- [[wiki/concepts/communication/authentic-communication|Authentic Communication]]
- [[wiki/syntheses/communication/johnny-harris-explainer-framework|Johnny Harris Explainer Framework]]
- [[index|index]]

Summary:
- Ingested a new short-form storytelling source organized around dance, rhythm, tone, direction, story lenses, and hooks.
- Added a dedicated source page, a new Story Lenses concept, and a Short-Form Storytelling Framework synthesis so the source's platform-specific craft model is accessible beyond the raw note.
- Updated Story Propulsion, Dialogue as Music, Visual Storytelling First, Authentic Communication, and the Johnny Harris Explainer Framework so the filmmaking and communication branches now capture context/conflict loops, the `but` / `therefore` test, sentence-rhythm diagnostics, one-person conversational tone, ending-first direction, distinctive angles, and visual-first hooks.

## [2026-04-21 15:05] ingest | The 48 Laws of Power in Under 30 Minutes

Pages touched:
- [[raw/inbox/2026-04-21-the-48-laws-of-power-in-under-30-minutes|The 48 Laws of Power in Under 30 Minutes]]
- [[wiki/sources/2026-04-21-the-48-laws-of-power-in-under-30-minutes|The 48 Laws of Power in Under 30 Minutes]]
- [[wiki/concepts/communication/power-dynamics|Power Dynamics]]
- [[wiki/syntheses/communication/robert-greene-power-framework|Robert Greene Power Framework]]
- [[wiki/entities/robert-greene|Robert Greene]]
- [[index|index]]

Summary:
- Ingested a rapid Robert Greene summary that heavily overlaps with the existing Greene power branch but adds a clearer cluster map of the 48 laws.
- Added a dedicated source page so the note remains discoverable as a tactical grouping of perception, relationship leverage, concealment, option control, timing, conformity, and fantasy/belief tactics.
- Updated Power Dynamics, Robert Greene Power Framework, and the Robert Greene entity so the branch now makes the laws' internal contradictions and belief-management layer more explicit.

## [2026-04-21 15:12] ingest | STORYWORTHY by Matthew Dicks Core Message

Pages touched:
- [[raw/inbox/2026-04-21-storyworthy-by-matthew-dicks-core-message|STORYWORTHY by Matthew Dicks Core Message]]
- [[wiki/sources/2026-04-21-storyworthy-by-matthew-dicks-core-message|STORYWORTHY by Matthew Dicks Core Message]]
- [[wiki/entities/matthew-dicks|Matthew Dicks]]
- [[wiki/syntheses/filmmaking/matthew-dicks-personal-storytelling-framework|Matthew Dicks Personal Storytelling Framework]]
- [[wiki/concepts/filmmaking/transformation-in-storytelling|Transformation in Storytelling]]
- [[wiki/concepts/filmmaking/story-propulsion|Story Propulsion]]
- [[wiki/concepts/filmmaking/character-driven-storytelling|Character-Driven Storytelling]]
- [[wiki/concepts/communication/authentic-communication|Authentic Communication]]
- [[index|index]]

Summary:
- Ingested a Matthew Dicks source centered on the `five-second moment` as the core of powerful personal storytelling.
- Added a dedicated source page, a new Matthew Dicks entity, and a personal-storytelling framework synthesis.
- Updated transformation, propulsion, character-driven storytelling, and authentic communication so the branch now captures before/after contrast, action-first openings, misdirection, delayed reveals, and vulnerability as structured connection.

## [2026-04-21 15:18] ingest | THE 48 LAWS OF POWER by Robert Greene Core Message

Pages touched:
- [[raw/inbox/2026-04-21-the-48-laws-of-power-by-robert-greene-core-message|THE 48 LAWS OF POWER by Robert Greene Core Message]]
- [[wiki/sources/2026-04-21-the-48-laws-of-power-by-robert-greene-core-message|THE 48 LAWS OF POWER by Robert Greene Core Message]]
- [[wiki/concepts/communication/power-dynamics|Power Dynamics]]
- [[wiki/syntheses/communication/robert-greene-power-framework|Robert Greene Power Framework]]
- [[wiki/entities/robert-greene|Robert Greene]]
- [[index|index]]

Summary:
- Ingested a reinforcing 48 Laws source that compresses Greene's power model into three meta-laws: say little, be audacious, and be formless.
- Added a dedicated source page so this compact mental model remains visible rather than being absorbed into the prior 48 Laws source pages.
- Updated Power Dynamics, Robert Greene Power Framework, and the Robert Greene entity so the branch now captures strategic silence, status-making audacity, formless adaptation, and the `iron hand inside a velvet glove` caveat around visible power hunger.

## [2026-04-21 15:20] ingest | Ted Lasso Leadership Lessons That Work

Pages touched:
- [[raw/inbox/2026-04-21-ted-lasso-leadership-lessons-that-work|Ted Lasso Leadership Lessons That Work]]
- [[wiki/sources/2026-04-21-ted-lasso-leadership-lessons-that-work|Ted Lasso Leadership Lessons That Work]]
- [[wiki/entities/ted-lasso|Ted Lasso]]
- [[wiki/syntheses/leadership/ted-lasso-leadership-framework|Ted Lasso Leadership Framework]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/leadership/individualized-leadership|Individualized Leadership]]
- [[wiki/concepts/leadership/trust-based-collaboration|Trust-Based Collaboration]]
- [[wiki/concepts/leadership/high-performance-team-culture|High-Performance Team Culture]]
- [[wiki/concepts/leadership/leadership-communication|Leadership Communication]]
- [[wiki/syntheses/cross-source/high-performance-leadership-models|High-Performance Leadership Models]]
- [[index|index]]

Summary:
- Ingested a case-based leadership source using Ted Lasso to model recognition across status, self-interest-to-team alignment, distributed credit, blind-spot feedback, individualized motivation, and grounded optimism.
- Added a dedicated source page, Ted Lasso entity page, and reusable leadership synthesis.
- Updated core leadership concept pages and the high-performance leadership cross-source synthesis so the new source strengthens the compiled model rather than remaining isolated.

## [2026-04-21 15:23] ingest | Why You've Been Lied to About Where to Put Your Time, Energy, and Focus

Pages touched:
- [[raw/inbox/2026-04-21-why-youve-been-lied-to-about-where-to-put-your-time-energy-and-focus|Why You've Been Lied to About Where to Put Your Time, Energy, and Focus]]
- [[wiki/sources/2026-04-21-why-youve-been-lied-to-about-where-to-put-your-time-energy-and-focus|Why You've Been Lied to About Where to Put Your Time, Energy, and Focus]]
- [[wiki/entities/seth-godin|Seth Godin]]
- [[wiki/syntheses/business/seth-godin-practice-framework|Seth Godin Practice Framework]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework|Seth Godin Remarkable Marketing Framework]]
- [[wiki/concepts/business/process-over-outcomes|Process Over Outcomes]]
- [[wiki/concepts/business/smallest-viable-audience|Smallest Viable Audience]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[wiki/concepts/business/permissionless-creation|Permissionless Creation]]
- [[wiki/concepts/leadership/identity-based-motivation|Identity-Based Motivation]]
- [[index|index]]

Summary:
- Ingested a Seth Godin Impact Theory source centered on practice as the controllable output, audience-specific intention, generous shipping, behavior-first identity, chosen passion, taste-building, curated feedback, and anti-vanity metrics.
- Added a dedicated source page and a new Seth Godin Practice Framework synthesis.
- Updated the existing Godin branch and related concepts so the new source strengthens process-over-outcomes, smallest viable audience, success metrics, permissionless creation, and identity-based motivation rather than remaining isolated.

## [2026-04-21 15:28] ingest | Your Job is to Make Art - Seth Godin at ConvertKit Craft & Commerce 2017

Pages touched:
- [[raw/inbox/2026-04-21-your-job-is-to-make-art-seth-godin-craft-commerce-2017|Your Job is to Make Art - Seth Godin at ConvertKit Craft & Commerce 2017]]
- [[wiki/sources/2026-04-21-your-job-is-to-make-art-seth-godin-craft-commerce-2017|Your Job is to Make Art - Seth Godin at ConvertKit Craft & Commerce 2017]]
- [[wiki/entities/seth-godin|Seth Godin]]
- [[wiki/syntheses/business/seth-godin-remarkable-marketing-framework|Seth Godin Remarkable Marketing Framework]]
- [[wiki/syntheses/leadership/seth-godin-leadership-framework|Seth Godin Leadership Framework]]
- [[wiki/concepts/business/connection-economy|Connection Economy]]
- [[wiki/concepts/business/smallest-viable-audience|Smallest Viable Audience]]
- [[wiki/concepts/business/permissionless-creation|Permissionless Creation]]
- [[wiki/concepts/creativity/art-making|Art Making]]
- [[wiki/concepts/leadership/leadership-vs-management|Leadership vs. Management]]
- [[index|index]]

Summary:
- Ingested a Seth Godin Craft & Commerce source defining art as generous human work that might not work and tying that posture to audience choice, permission, tribe identity, and leadership under uncertainty.
- Added a dedicated source page and moved the normalized raw source into `raw/inbox/`.
- Updated the existing Godin branch and related concept pages so the source strengthens art/plumbing, prepared-versus-ready action, shipwreck-aware experimentation, permission as being missed, and customer-benefiting network effects rather than remaining isolated.

## [2026-04-21 15:38] ingest | Jordan Peterson on Goals, Scheduling, Negotiating & Friendship

Pages touched:
- [[raw/inbox/2026-04-21-jordan-peterson-on-goals-scheduling-negotiating-and-friendship|Jordan Peterson on Goals, Scheduling, Negotiating & Friendship]]
- [[wiki/sources/2026-04-21-jordan-peterson-on-goals-scheduling-negotiating-and-friendship|Jordan Peterson on Goals, Scheduling, Negotiating & Friendship]]
- [[wiki/entities/jordan-peterson|Jordan Peterson]]
- [[wiki/syntheses/productivity/jordan-peterson-self-management-framework|Jordan Peterson Self-Management Framework]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework|Jordan Peterson Responsibility Framework]]
- [[wiki/concepts/communication/negotiation-and-mediation|Negotiation and Mediation]]
- [[wiki/concepts/leadership/friendship-as-growth-pact|Friendship as Growth Pact]]
- [[index|index]]

Summary:
- Ingested a Jordan Peterson source connecting life vision, best-day schedule design, self-negotiation, incremental schedule adherence, time valuation, resentment-aware negotiation, competent networks, and friendship tests.
- Added a dedicated source page and moved the normalized raw source into `raw/inbox/`.
- Updated the Peterson branch and related communication/friendship pages so the new material strengthens negotiated self-management, resentment as an articulation signal, and friendship as a relationship that can hold both bad news and success.

## [2026-04-21 15:40] ingest | Jordan Peterson Secrets to Life and Relationships

Pages touched:
- [[raw/inbox/2026-04-21-jordan-peterson-secrets-to-life-and-relationships|Jordan Peterson Secrets to Life and Relationships]]
- [[wiki/sources/2026-04-21-jordan-peterson-secrets-to-life-and-relationships|Jordan Peterson Secrets to Life and Relationships]]
- [[wiki/entities/jordan-peterson|Jordan Peterson]]
- [[wiki/syntheses/leadership/jordan-peterson-responsibility-framework|Jordan Peterson Responsibility Framework]]
- [[wiki/concepts/leadership/meaning-through-responsibility|Meaning Through Responsibility]]
- [[wiki/concepts/leadership/owners-mentality|Owner's Mentality]]
- [[wiki/concepts/leadership/better-problems|Better Problems]]
- [[wiki/concepts/leadership/values-driven-action|Values-Driven Action]]
- [[index|index]]

Summary:
- Ingested a Jordan Peterson source centered on meaning as calibration, love and truth commitments, voluntary acceptance of suffering, responsibility as chosen game, all-in commitment, individual integrity, and unrealized human potential.
- Added a dedicated source page and moved the normalized raw source into `raw/inbox/`.
- Updated the Peterson branch and related meaning/commitment pages so the source strengthens highest-good orientation, all-in games, and the caveat that commitment requires safeguards against coercion, abuse, or sunk-cost rigidity.

## [2026-04-21 15:53] ingest | Jordan Belfort Straight Line Strategy

Pages touched:
- [[raw/inbox/2026-04-21-jordan-belfort-straight-line-strategy|Jordan Belfort Straight Line Strategy]]
- [[wiki/sources/2026-04-21-jordan-belfort-straight-line-strategy|Jordan Belfort Straight Line Strategy]]
- [[wiki/entities/jordan-belfort|Jordan Belfort]]
- [[wiki/concepts/business/sales-conversation-control|Sales Conversation Control]]
- [[wiki/syntheses/business/jordan-belfort-straight-line-sales-framework|Jordan Belfort Straight Line Sales Framework]]
- [[wiki/syntheses/business/modern-sales-systems-framework|Modern Sales Systems Framework]]
- [[wiki/concepts/business/sales-operations|Sales Operations]]
- [[wiki/concepts/communication/persuasion|Persuasion]]
- [[index|index]]

Summary:
- Ingested a Jordan Belfort sales source centered on Straight Line selling, certainty transfer, first-four-second authority, conversation control, tonality, body language, state management, scripting, and objection reframing.
- Added a dedicated source page, Belfort entity page, call-level sales synthesis, and Sales Conversation Control concept.
- Updated the broader sales and persuasion branches so the source strengthens live-call mechanics while preserving the ethical caveat that `no` can mean poor fit or legitimate refusal, not only unresolved uncertainty.

## [2026-04-21 15:59] ingest | How to be a creative thinker - Carnegie Mellon University Po-Shen Loh

Pages touched:
- [[raw/inbox/2026-04-21-how-to-be-a-creative-thinker-carnegie-mellon-university-po-shen-loh|How to be a creative thinker - Carnegie Mellon University Po-Shen Loh]]
- [[wiki/sources/2026-04-21-how-to-be-a-creative-thinker-carnegie-mellon-university-po-shen-loh|How to be a creative thinker - Carnegie Mellon University Po-Shen Loh]]
- [[wiki/entities/po-shen-loh|Po-Shen Loh]]
- [[wiki/concepts/creativity/creative-problem-solving|Creative Problem Solving]]
- [[wiki/syntheses/creativity/po-shen-loh-creative-thinking-framework|Po-Shen Loh Creative Thinking Framework]]
- [[wiki/concepts/creativity/idea-development|Idea Development]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/productivity/effective-practice|Effective Practice]]
- [[index|index]]

Summary:
- Ingested a Po-Shen Loh source on creative thinking in the AI era, centered on grading generated answers, preserving novelty through unfamiliar math problems, and treating real-world interaction as creative discovery.
- Added a dedicated source page, Po-Shen Loh entity page, Creative Problem Solving concept, and Loh creative-thinking synthesis.
- Updated the AI collaboration, critical-thinking, idea-development, and effective-practice branches so the source strengthens judgment-preserving AI use, anti-drill practice design, and social pain-point discovery rather than remaining isolated.

## [2026-04-21 16:09] ingest | How to Master AI Powered Creativity in Just 13 Minutes - Jeremy Utley

Pages touched:
- [[raw/inbox/2026-04-21-how-to-master-ai-powered-creativity-in-just-13-minutes-jeremy-utley|How to Master AI Powered Creativity in Just 13 Minutes - Jeremy Utley]]
- [[wiki/sources/2026-04-21-how-to-master-ai-powered-creativity-in-just-13-minutes-jeremy-utley|How to Master AI Powered Creativity in Just 13 Minutes - Jeremy Utley]]
- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[wiki/concepts/ai/ai-powered-creativity|AI-Powered Creativity]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/context-engineering|Context Engineering]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/ai/prompt-engineering|Prompt Engineering]]
- [[wiki/concepts/creativity/creative-problem-solving|Creative Problem Solving]]
- [[index|index]]

Summary:
- Ingested a Jeremy Utley source on AI-powered creativity, centered on treating AI as a teammate, having AI interview the user about workflows and objectives, targeting dreaded tasks, and using volume/variation to move beyond first-pass adequacy.
- Added a dedicated source page and a new AI-Powered Creativity concept page.
- Updated the existing Utley, prompt-design, reverse-prompting, context-engineering, human-machine collaboration, critical-thinking, prompt-engineering, and creative problem-solving branches so the new source strengthens workflow discovery, inspiration discipline, teammate framing, and anti-satisficing creative practice.

## [2026-04-21 16:15] ingest | The Only Trait for Success in the AI Era - How to Build It - Po-Shen Loh

Pages touched:
- [[raw/inbox/2026-04-21-the-only-trait-for-success-in-the-ai-era-how-to-build-it-po-shen-loh|The Only Trait for Success in the AI Era - How to Build It - Po-Shen Loh]]
- [[wiki/sources/2026-04-21-the-only-trait-for-success-in-the-ai-era-how-to-build-it-po-shen-loh|The Only Trait for Success in the AI Era - How to Build It - Po-Shen Loh]]
- [[wiki/entities/po-shen-loh|Po-Shen Loh]]
- [[wiki/concepts/ai/ai-era-thoughtfulness|AI-Era Thoughtfulness]]
- [[wiki/concepts/business/social-entrepreneurship|Social Entrepreneurship]]
- [[wiki/syntheses/ai/po-shen-loh-ai-era-thoughtfulness-framework|Po-Shen Loh AI-Era Thoughtfulness Framework]]
- [[wiki/syntheses/creativity/po-shen-loh-creative-thinking-framework|Po-Shen Loh Creative Thinking Framework]]
- [[wiki/concepts/creativity/creative-problem-solving|Creative Problem Solving]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/concepts/productivity/effective-practice|Effective Practice]]
- [[index|index]]

Summary:
- Ingested a Po-Shen Loh source on the AI-era trait of thoughtfulness: mental fitness, empathy, world simulation, bias-aware perspective gathering, value creation, social entrepreneurship, and generate-destroy-refine idea discipline.
- Added a dedicated source page, AI-Era Thoughtfulness concept, Social Entrepreneurship concept, and a Po-Shen Loh AI-Era Thoughtfulness Framework synthesis.
- Updated the existing Loh, creative problem-solving, AI critical-thinking, human-machine collaboration, and effective-practice branches so the source strengthens the distinction between AI as training partner and AI as cognitive crutch.

## [2026-04-21 16:24] ingest | Jeremy Utley - AI Ignites Human Creativity

Pages touched:
- [[raw/inbox/2026-04-21-jeremy-utley-ai-ignites-human-creativity|Jeremy Utley - AI Ignites Human Creativity]]
- [[wiki/sources/2026-04-21-jeremy-utley-ai-ignites-human-creativity|Jeremy Utley - AI Ignites Human Creativity]]
- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[wiki/concepts/creativity/idea-flow|Idea Flow]]
- [[wiki/concepts/ai/ai-powered-creativity|AI-Powered Creativity]]
- [[wiki/concepts/ai/human-machine-collaboration|Human-Machine Collaboration]]
- [[wiki/concepts/ai/reverse-prompting|Reverse Prompting]]
- [[wiki/concepts/ai/ai-critical-thinking-partner|AI Critical Thinking Partner]]
- [[wiki/concepts/creativity/creative-problem-solving|Creative Problem Solving]]
- [[wiki/concepts/creativity/idea-development|Idea Development]]
- [[wiki/syntheses/ai/jeremy-utley-ai-collaboration-framework|Jeremy Utley AI Collaboration Framework]]
- [[wiki/syntheses/ai/prompt-design-workflow|Prompt Design Workflow]]
- [[index|index]]

Summary:
- Ingested a Jeremy Utley source on AI as an ignition layer for human creativity, centered on idea flow, quantity-driven quality, bad-idea tolerance, voice-first thought capture, regeneration, feedback loops, and AI adoption as a people-skills transformation.
- Added a dedicated source page and a new Idea Flow concept so the quantity-and-variation model is reusable beyond the Utley source page.
- Updated the Utley, AI-powered creativity, human-machine collaboration, reverse-prompting, critical-thinking, creative-problem-solving, idea-development, and prompt-workflow branches so the source strengthens the distinction between AI as an answer oracle and AI as a conversational sampling partner.

## [2026-04-21 16:31] ingest | The Habit That Built Every Genius

Pages touched:
- [[raw/inbox/2026-04-21-the-habit-that-built-every-genius|The Habit That Built Every Genius]]
- [[wiki/sources/2026-04-21-the-habit-that-built-every-genius|The Habit That Built Every Genius]]
- [[wiki/entities/jeremy-utley|Jeremy Utley]]
- [[wiki/concepts/creativity/inspiration-discipline|Inspiration Discipline]]
- [[wiki/concepts/creativity/creative-white-space|Creative White Space]]
- [[wiki/concepts/creativity/idea-flow|Idea Flow]]
- [[wiki/concepts/creativity/idea-development|Idea Development]]
- [[wiki/concepts/creativity/creative-incubation|Creative Incubation]]
- [[wiki/concepts/creativity/creative-problem-solving|Creative Problem Solving]]
- [[wiki/concepts/ai/ai-powered-creativity|AI-Powered Creativity]]
- [[wiki/concepts/productivity/focused-and-diffuse-learning-modes|Focused and Diffuse Learning Modes]]
- [[wiki/syntheses/productivity/attention-and-focus-framework|Attention and Focus Framework]]
- [[wiki/syntheses/creativity/jeremy-utley-genius-habits-framework|Jeremy Utley Genius Habits Framework]]
- [[index|index]]

Summary:
- Ingested a Jeremy Utley creativity source centered on genius as trainable habits rather than IQ: disciplined inspiration, constant idea capture, bug lists, protected white space, ambiguity tolerance, and quantity-first idea generation.
- Added dedicated Inspiration Discipline and Creative White Space concept pages plus a Jeremy Utley Genius Habits Framework synthesis so the four-habit model is reusable beyond the source page.
- Updated the Utley, idea-flow, idea-development, creative-incubation, creative-problem-solving, AI-powered creativity, focused/diffuse learning, and attention/focus branches so the source strengthens input design, capture systems, delayed closure, and AI as a force multiplier rather than a replacement for creative habits.

## [2026-04-21 16:40] ingest | Beyond Public Speaking - Elevate Your Impromptu Speaking Skills with Matt Abrahams

Pages touched:
- [[raw/inbox/2026-04-21-beyond-public-speaking-impromptu-speaking-matt-abrahams|Beyond Public Speaking - Elevate Your Impromptu Speaking Skills with Matt Abrahams]]
- [[wiki/sources/2026-04-21-beyond-public-speaking-impromptu-speaking-matt-abrahams|Beyond Public Speaking - Elevate Your Impromptu Speaking Skills with Matt Abrahams]]
- [[wiki/entities/matt-abrahams|Matt Abrahams]]
- [[wiki/concepts/communication/thinking-on-your-feet|Thinking on Your Feet]]
- [[wiki/syntheses/communication/thinking-on-your-feet-framework|Thinking on Your Feet Framework]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/concepts/communication/conversational-curiosity|Conversational Curiosity]]
- [[index|index]]

Summary:
- Ingested a Matt Abrahams source on impromptu speaking as a trainable skill, centered on anxiety reframing, rule-of-lung breathing, service orientation, anti-perfectionism, heuristic audits, empathy, apology repair, `brick not cathedral`, and `miss-take` practice.
- Added a dedicated source page and a Matt Abrahams entity page because the vault already had several Abrahams sources without a stable entity.
- Updated the thinking-on-your-feet, effective-communication, and conversational-curiosity branches so the source strengthens everyday spontaneous communication beyond formal public speaking.

## [2026-04-21 16:44] ingest | Just Cause - The 5 Practices (Simon Sinek)

Pages touched:
- [[raw/inbox/2026-04-21-just-cause-the-5-practices-simon-sinek|Just Cause - The 5 Practices (Simon Sinek)]]
- [[wiki/sources/2026-04-21-just-cause-the-5-practices-simon-sinek|Just Cause - The 5 Practices (Simon Sinek)]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/just-cause|Just Cause]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/concepts/business/golden-circle|Golden Circle]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek source defining Just Cause as an ideal future state, independent of products and finite wins, that is meaningful enough for aligned people to accept sacrifice.
- Added a dedicated source page and a new Just Cause concept page so the infinite-game branch has a clear cause-substance layer rather than only general purpose language.
- Updated the Sinek entity, Infinite-Game Mindset, Sinek Infinite Game Framework, and Golden Circle pages so the source clarifies the relationship between cause, product, sacrifice, finite victories, and belief-led communication.

## [2026-04-21 16:50] ingest | Worthy Rival - The 5 Practices (Simon Sinek)

Pages touched:
- [[raw/inbox/2026-04-21-worthy-rival-the-5-practices-simon-sinek|Worthy Rival - The 5 Practices (Simon Sinek)]]
- [[wiki/sources/2026-04-21-worthy-rival-the-5-practices-simon-sinek|Worthy Rival - The 5 Practices (Simon Sinek)]]
- [[wiki/concepts/leadership/worthy-rival|Worthy Rival]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/just-cause|Just Cause]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek source on worthy rivals as respected comparison points whose strengths expose one's weaknesses and turn competition into infinite-game calibration.
- Added a dedicated source page and a new Worthy Rival concept page so the competition practice is not trapped inside the source summary.
- Updated the Sinek entity, Infinite-Game Mindset, Just Cause, and Simon Sinek Infinite Game Framework pages so rivalry now functions as a calibration layer alongside cause, trust, self-competition, and long-horizon purpose.

## [2026-04-21 16:55] ingest | Existential Flexibility - The 5 Practices (Simon Sinek)

Pages touched:
- [[raw/inbox/2026-04-21-existential-flexibility-the-5-practices-simon-sinek|Existential Flexibility - The 5 Practices (Simon Sinek)]]
- [[wiki/sources/2026-04-21-existential-flexibility-the-5-practices-simon-sinek|Existential Flexibility - The 5 Practices (Simon Sinek)]]
- [[wiki/concepts/leadership/existential-flexibility|Existential Flexibility]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/just-cause|Just Cause]]
- [[wiki/concepts/business/self-disruption|Self-Disruption]]
- [[wiki/concepts/business/business-strategy|Business Strategy]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek source defining existential flexibility as the capacity to make profound strategic shifts when a new model better advances the Just Cause.
- Added a dedicated source page and a new Existential Flexibility concept page so the radical-change practice is reusable beyond the source summary.
- Updated the Sinek entity, Infinite-Game Mindset, Just Cause, Self-Disruption, Business Strategy, and Sinek Infinite Game Framework pages so the branch now connects cause, trust, cannibalization, short-term pain, and long-term relevance.

## [2026-04-21 17:00] ingest | Courage to Lead - The 5 Practices (Simon Sinek)

Pages touched:
- [[raw/inbox/2026-04-21-courage-to-lead-the-5-practices-simon-sinek|Courage to Lead - The 5 Practices (Simon Sinek)]]
- [[wiki/sources/2026-04-21-courage-to-lead-the-5-practices-simon-sinek|Courage to Lead - The 5 Practices (Simon Sinek)]]
- [[wiki/concepts/leadership/courage-to-lead|Courage to Lead]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/business/values-driven-companies|Values-Driven Companies]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek source defining courage as the pressure-bearing practice that keeps Just Cause, trusting teams, worthy rivals, and existential flexibility from collapsing under short-term incentives.
- Added a dedicated source page and a new Courage to Lead concept page so the ethical-tradeoff layer is reusable beyond the source summary.
- Updated the Sinek entity, Infinite-Game Mindset, Leadership, Values-Driven Companies, Success Metrics, and both Sinek framework syntheses so the branch now captures legal-minimum versus ethical leadership, shareholder-pressure critique, CVS-style values tradeoffs, layoffs/rank-and-yank trust damage, and legacy through human impact.

## [2026-04-21 17:06] ingest | The Infinite Game - How to Lead in the 21st Century

Pages touched:
- [[raw/inbox/2026-04-21-the-infinite-game-how-to-lead-in-the-21st-century|The Infinite Game - How to Lead in the 21st Century]]
- [[wiki/sources/2026-04-21-the-infinite-game-how-to-lead-in-the-21st-century|The Infinite Game - How to Lead in the 21st Century]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/just-cause|Just Cause]]
- [[wiki/concepts/leadership/courage-to-lead|Courage to Lead]]
- [[wiki/concepts/leadership/existential-flexibility|Existential Flexibility]]
- [[wiki/concepts/leadership/trust-based-collaboration|Trust-Based Collaboration]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek overview that integrates the finite-versus-infinite game distinction with Just Cause, Trusting Teams, Worthy Rival, Existential Flexibility, and Courage to Lead.
- Added a dedicated source page rather than a new concept page because the source primarily consolidates and sharpens the existing five-practices branch.
- Updated the Sinek entity, Infinite-Game Mindset, Just Cause, Courage to Lead, Existential Flexibility, Trust-Based Collaboration, and both Sinek framework syntheses with the Carse game distinction, Just Cause versus `why`, courage as a social net, consistency over intensity, small-scale existential flexibility, and legacy as human impact beyond tenure.

## [2026-04-21 17:14] ingest | Simon Sinek Explains What Almost Every Leader Gets Wrong

Pages touched:
- [[raw/inbox/2026-04-21-simon-sinek-explains-what-almost-every-leader-gets-wrong|Simon Sinek Explains What Almost Every Leader Gets Wrong]]
- [[wiki/sources/2026-04-21-simon-sinek-explains-what-almost-every-leader-gets-wrong|Simon Sinek Explains What Almost Every Leader Gets Wrong]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[wiki/concepts/business/self-disruption|Self-Disruption]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested an Inc. Simon Sinek video summary that reinforces the infinite-game branch while sharpening the critique of shareholder primacy, arbitrary annual and quarterly targets, legal-minimum ethics, mass layoffs, rank-and-yank systems, and incumbent revenue traps.
- Added a dedicated source page and integrated the source into existing Sinek, infinite-game, trust-centered leadership, success-metrics, leadership, and self-disruption pages rather than creating duplicate concept pages.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-21 17:14] ingest | Simon Sinek How to Make Your Life A Success

Pages touched:
- [[raw/inbox/2026-04-21-simon-sinek-how-to-make-your-life-a-success|Simon Sinek How to Make Your Life A Success]]
- [[wiki/sources/2026-04-21-simon-sinek-how-to-make-your-life-a-success|Simon Sinek How to Make Your Life A Success]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/business/golden-circle|Golden Circle]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[wiki/syntheses/business/simon-sinek-golden-circle-framework|Simon Sinek Golden Circle Framework]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested an Inc. Simon Sinek video summary that uses Sinek's own career path to connect personal `why`, the Golden Circle's origin, scientific testing of ideas, organic spread before TEDx scale, and success as momentum beyond the individual.
- Added a dedicated source page and integrated the reusable claims into existing Golden Circle, infinite-game, trust-centered leadership, success-metrics, leadership, and Simon Sinek pages rather than creating a duplicate life-success page.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-21 17:16] ingest | Business is an INFINITE GAME Full Speech (Simon Sinek)

Pages touched:
- [[raw/inbox/2026-04-21-business-is-an-infinite-game-full-speech-simon-sinek|Business is an INFINITE GAME Full Speech (Simon Sinek)]]
- [[wiki/sources/2026-04-21-business-is-an-infinite-game-full-speech-simon-sinek|Business is an INFINITE GAME Full Speech (Simon Sinek)]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/leadership/human-skills|Human Skills]]
- [[wiki/concepts/leadership/trust-performance-matrix|Trust-Performance Matrix]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/business/success-metrics|Success Metrics]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested a full-speech Simon Sinek source that restates the five infinite-game practices while adding stronger implementation detail around trust-performance measurement, goals as adjustable dials, human-skills training, difficult-conversation scripts, command-and-control as trust-dependent crisis mode, and the Great Resignation as a correction against disposable treatment of workers.
- Added a dedicated source page and a new Human Skills concept page, then integrated the reusable material into the Sinek entity, Infinite-Game Mindset, Trust-Performance Matrix, Leadership, Success Metrics, and both Sinek leadership syntheses.
- Updated the index and moved the canonical raw source into the inbox archive.
## [2026-04-21 17:25] ingest | You're Losing Respect Every Time You Say This

Pages touched:
- [[raw/inbox/2026-04-21-youre-losing-respect-every-time-you-say-this|You're Losing Respect Every Time You Say This]]
- [[wiki/sources/2026-04-21-youre-losing-respect-every-time-you-say-this|You're Losing Respect Every Time You Say This]]
- [[wiki/entities/jefferson-fisher|Jefferson Fisher]]
- [[wiki/concepts/communication/assertiveness|Assertiveness]]
- [[wiki/concepts/communication/effective-communication|Effective Communication]]
- [[wiki/syntheses/communication/jefferson-fisher-conflict-response-framework|Jefferson Fisher Conflict Response Framework]]
- [[wiki/syntheses/communication/conflict-frame-control-framework|Conflict Frame Control Framework]]
- [[index|index]]

Summary:
- Ingested a communication source on three respect-eroding habits: absolute language, overexplaining, and poorly framed first seconds of a conversation.
- Added a dedicated source page and integrated the reusable material into the existing assertiveness, effective communication, Jefferson Fisher, and conflict-frame-control branches rather than creating a near-duplicate concept page.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-21 20:50] ingest | The Leadership Advice Nobody Follows But Everyone Should

Pages touched:
- [[raw/inbox/2026-04-21-the-leadership-advice-nobody-follows-but-everyone-should|The Leadership Advice Nobody Follows But Everyone Should]]
- [[wiki/sources/2026-04-21-the-leadership-advice-nobody-follows-but-everyone-should|The Leadership Advice Nobody Follows But Everyone Should]]
- [[wiki/entities/simon-sinek|Simon Sinek]]
- [[wiki/entities/don-yaeger|Don Yaeger]]
- [[wiki/entities/john-wooden|John Wooden]]
- [[wiki/concepts/leadership/standards-of-being|Standards of Being]]
- [[wiki/concepts/leadership/leadership|Leadership]]
- [[wiki/concepts/leadership/high-performance-team-culture|High-Performance Team Culture]]
- [[wiki/concepts/leadership/trust-based-collaboration|Trust-Based Collaboration]]
- [[wiki/concepts/leadership/infinite-game-mindset|Infinite-Game Mindset]]
- [[wiki/concepts/business/mentorship|Mentorship]]
- [[wiki/syntheses/leadership/simon-sinek-infinite-game-framework|Simon Sinek Infinite Game Framework]]
- [[wiki/syntheses/leadership/simon-sinek-trust-centered-leadership-framework|Simon Sinek Trust-Centered Leadership Framework]]
- [[index|index]]

Summary:
- Ingested a Simon Sinek and Don Yaeger leadership conversation centered on John Wooden, standards of being, appreciation rituals, employee-first virtuous cycles, mentorship as time-giving, and family presence as a values constraint.
- Added a dedicated source page, new Don Yaeger and John Wooden entity pages, and a new Standards of Being concept page.
- Integrated the reusable material into existing Sinek, leadership, high-performance team culture, trust-based collaboration, infinite-game, mentorship, and Sinek framework pages rather than leaving the ideas trapped in a source summary.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-22 02:03] query | How Many Index Cards For A Full Screenplay

Pages touched:
- [[wiki/queries/how-many-index-cards-for-a-full-screenplay|How Many Index Cards For A Full Screenplay]]
- [[index|index]]

Summary:
- Added a durable query answer clarifying that the vault's Sorkin summaries record index cards on a cork board but do not preserve a fixed full-script card count.
- Preserved the practical screenplay scale heuristic as roughly `40-50` cards while distinguishing it from Sorkin's source-grounded process notes and linking the relevant scene-card, outlining, and Sorkin entries.

## [2026-04-22 02:08] admin | Query Workflow Is Wiki-Only

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/queries/how-many-index-cards-for-a-full-screenplay|How Many Index Cards For A Full Screenplay]]
- [[log|log]]

Summary:
- Updated the query workflow to explicitly forbid web search, internet browsing, external live lookup, or non-vault sources during query mode unless the user explicitly overrides the rule for that request.
- Added the required fallback behavior: if the answer is not found in local vault files, return that no answer was found within the wiki/vault instead of filling the gap externally.
- Removed the external Screenwriting.io citation from the preserved screenplay index-card query page so the page is grounded only in local vault material.

## [2026-04-23 01:47] ingest | How to Write Vividly Well - Michael Connelly

Pages touched:
- [[raw/inbox/2026-04-23-how-to-write-vividly-well-michael-connelly|How to Write Vividly Well - Michael Connelly]]
- [[wiki/sources/2026-04-23-how-to-write-vividly-well-michael-connelly|How to Write Vividly Well - Michael Connelly]]
- [[wiki/entities/michael-connelly|Michael Connelly]]
- [[wiki/concepts/filmmaking/telling-details|Telling Details]]
- [[wiki/concepts/filmmaking/fiction-writing|Fiction Writing]]
- [[wiki/concepts/filmmaking/thriller-writing|Thriller Writing]]
- [[wiki/concepts/filmmaking/character-driven-storytelling|Character-Driven Storytelling]]
- [[wiki/concepts/filmmaking/setting-as-character|Setting as Character]]
- [[wiki/concepts/filmmaking/writing-process-and-revision|Writing Process and Revision]]
- [[wiki/concepts/filmmaking/text-and-subtext|Text and Subtext]]
- [[wiki/concepts/filmmaking/dialogue-as-music|Dialogue as Music]]
- [[wiki/concepts/filmmaking/immersive-research|Immersive Research]]
- [[wiki/syntheses/filmmaking/michael-connelly-crime-fiction-framework|Michael Connelly Crime Fiction Framework]]
- [[wiki/syntheses/filmmaking/baldacci-thriller-framework|Baldacci Thriller Framework]]
- [[index|index]]

Summary:
- Ingested a Michael Connelly craft source on vivid crime fiction through telling details, daily paper rewriting, character-first investigation, Los Angeles as social map, compressed dialogue, and the moral cost of confronting darkness.
- Added a dedicated source page, a Michael Connelly entity page, a Telling Details concept page, and a Michael Connelly Crime Fiction Framework synthesis.
- Integrated the reusable material into the existing fiction, thriller, character, setting, revision, dialogue, subtext, research, and Baldacci comparison branches.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-23 15:14] ingest | Large Language Models Explained Briefly

Pages touched:
- [[raw/inbox/2026-04-23-large-language-models-explained-briefly|Large Language Models Explained Briefly]]
- [[wiki/sources/2026-04-23-large-language-models-explained-briefly|Large Language Models Explained Briefly]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]]
- [[index|index]]

Summary:
- Ingested a beginner-oriented AI source that explains LLMs through next-token prediction, backpropagation over large corpora, transformer attention, RLHF-style post-training, stochastic decoding, and model opacity.
- Added a dedicated source page and a compiled AI synthesis page so the vault can now answer not only where LLMs sit in the stack, but also how their training and inference loop works at a mechanistic overview level.
- Updated the canonical [[wiki/concepts/ai/large-language-models|Large Language Models]] page with the source's new evidence and adjusted the branch's open questions toward tokenization, context limits, retrieval, evaluation, and tool use.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-23 15:18] ingest | How Large Language Models Work

Pages touched:
- [[raw/inbox/2026-04-23-how-large-language-models-work|How Large Language Models Work]]
- [[wiki/sources/2026-04-23-how-large-language-models-work|How Large Language Models Work]]
- [[wiki/concepts/ai/foundation-models|Foundation Models]]
- [[wiki/concepts/ai/generative-ai|Generative AI]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/concepts/ai/fine-tuning|Fine-Tuning]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
- [[index|index]]

Summary:
- Ingested a second beginner LLM overview that overlaps with the prior mechanistic explainer but adds a clearer `foundation model -> LLM -> GPT-style instance` hierarchy and a more explicit business-use layer.
- Added a new [[wiki/concepts/ai/foundation-models|Foundation Models]] concept page so the AI branch can now distinguish broad reusable base models from the narrower LLM branch rather than leaving that distinction implicit.
- Updated the generative-AI, large-language-models, fine-tuning, and AI-stack-overview pages so the branch now records self-supervised pre-training, foundation-model framing, and concrete organizational use cases like support automation, drafting, and code assistance.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-23 15:46] ingest | Most Devs Don't Understand How LLM Tokens Work

Pages touched:
- [[raw/inbox/2026-04-23-most-devs-dont-understand-how-llm-tokens-work|Most Devs Don't Understand How LLM Tokens Work]]
- [[wiki/sources/2026-04-23-most-devs-dont-understand-how-llm-tokens-work|Most Devs Don't Understand How LLM Tokens Work]]
- [[wiki/concepts/ai/tokenization|Tokenization]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]]
- [[wiki/syntheses/ai/llm-tokenization-and-cost-overview|LLM Tokenization and Cost Overview]]
- [[index|index]]

Summary:
- Ingested an AI source focused on tokenization as the hidden layer between text and LLM computation, including provider-specific token counts, encoding/decoding, vocabulary-size tradeoffs, token billing, and the token penalty imposed on rarer languages or codebases.
- Added a new [[wiki/concepts/ai/tokenization|Tokenization]] concept page and a new [[wiki/syntheses/ai/llm-tokenization-and-cost-overview|LLM Tokenization and Cost Overview]] synthesis so the branch now preserves token economics and tokenizer behavior as first-class compiled knowledge.
- Updated the canonical [[wiki/concepts/ai/large-language-models|Large Language Models]] page and the existing [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]] page so tokenization is no longer only an open gap in the AI branch.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-23 16:26] ingest | How Modern LLMs Work - Lex Fridman Podcast (Lex Clips)

Pages touched:
- [[raw/inbox/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips|How Modern LLMs Work - Lex Fridman Podcast (Lex Clips)]]
- [[wiki/sources/2026-04-23-how-modern-llms-work-lex-fridman-podcast-lex-clips|How Modern LLMs Work - Lex Fridman Podcast (Lex Clips)]]
- [[wiki/concepts/ai/open-weight-models|Open-Weight Models]]
- [[wiki/concepts/ai/foundation-models|Foundation Models]]
- [[wiki/concepts/ai/large-language-models|Large Language Models]]
- [[wiki/syntheses/ai/llm-training-and-inference-overview|LLM Training and Inference Overview]]
- [[wiki/syntheses/ai/ai-stack-overview|AI Stack Overview]]
- [[index|index]]

Summary:
- Ingested a modern LLM landscape source that shifts the AI branch from beginner mechanics toward current practice: open-weight ecosystems, GPT-lineage continuity, tool-use training, sparse MoE scaling, pre/mid/post-training, and systems-level efficiency work.
- Added a new [[wiki/concepts/ai/open-weight-models|Open-Weight Models]] concept page so the branch now has a canonical place for local inference, customization, licensing flexibility, and model-availability strategy.
- Updated the foundation-models, large-language-models, llm-training-and-inference-overview, and ai-stack-overview pages so the branch now captures architecture continuity, tool use, and the claim that recent progress is driven at least as much by training and systems engineering as by radical architectural replacement.
- Updated the index and moved the canonical raw source into the inbox archive.

## [2026-04-24 15:23] admin | Add AI Prompt Library Workflow

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/ai/README|AI Prompt Library]]
- [[wiki/prompts/ai/agents/README|Agents Prompts]]
- [[wiki/prompts/ai/coding/README|Coding Prompts]]
- [[wiki/prompts/ai/research/README|Research Prompts]]
- [[wiki/prompts/ai/writing/README|Writing Prompts]]
- [[wiki/prompts/ai/creativity/README|Creativity Prompts]]
- [[wiki/prompts/ai/business/README|Business Prompts]]
- [[wiki/prompts/ai/productivity/README|Productivity Prompts]]
- [[wiki/prompts/ai/image-video/README|Image Video Prompts]]
- [[wiki/prompts/ai/other/README|Other Prompts]]
- [[index|index]]

Summary:
- Added a special prompt-ingest workflow for saving pasted AI prompts verbatim under `wiki/prompts/ai/` without normal source synthesis, frontmatter, or formatting changes.
- Created category folders and README rules for agents, coding, research, writing, creativity, business, productivity, image-video, and other prompts.
- Updated the index so the prompt library is visible from the vault's main navigation.

## [2026-04-24 15:23] admin | Flatten Prompt Library Structure

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- [[index|index]]

Summary:
- Flattened the prompt library from `wiki/prompts/ai/<category>/` to `wiki/prompts/<category>/`.
- Removed per-category README files; category routing now lives in `AGENTS.md` and the single top-level prompt-library README.
- Updated index references so future prompt-ingest captures use the simplified folder structure.

## [2026-04-24 15:32] prompt-ingest | Coding Assistant Operating Prompt

Pages touched:
- [[wiki/prompts/agents/2026-04-24-coding-assistant-operating-prompt|Coding Assistant Operating Prompt]]
- [[log|log]]

Summary:
- Saved the pasted coding-assistant operating prompt verbatim under `wiki/prompts/agents/`.
- Chose `agents/` because the prompt primarily defines assistant role, communication style, judgment, instruction priority, coding integrity, scope, and verification behavior.

## [2026-04-24 15:35] admin | Add Tags To Prompt Ingests

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- [[wiki/prompts/agents/2026-04-24-coding-assistant-operating-prompt|Coding Assistant Operating Prompt]]
- [[log|log]]

Summary:
- Updated the prompt-ingest schema so prompt files use minimal YAML frontmatter with `type: prompt`, `category`, and `tags`.
- Preserved the prompt payload convention by placing the unchanged pasted prompt under a `# Prompt` heading.
- Retrofitted the existing coding-assistant operating prompt with tags for agent behavior, coding assistance, code review, coding standards, verification, and instruction priority.

## [2026-04-24 15:37] prompt-ingest | Project Manager Task Breakdown Prompt

Pages touched:
- [[wiki/prompts/productivity/2026-04-24-project-manager-task-breakdown-prompt|Project Manager Task Breakdown Prompt]]
- [[log|log]]

Summary:
- Saved the pasted project-manager task breakdown prompt under `wiki/prompts/productivity/`.
- Added tags for productivity, project management, task breakdown, planning, checklists, and pitfalls.

## [2026-04-24 15:39] admin | Make Prompt Files Copy-Friendly

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- [[wiki/prompts/agents/2026-04-24-coding-assistant-operating-prompt|Coding Assistant Operating Prompt]]
- [[wiki/prompts/productivity/2026-04-24-project-manager-task-breakdown-prompt|Project Manager Task Breakdown Prompt]]
- [[log|log]]

Summary:
- Updated prompt-ingest rules so prompt payloads are stored inside fenced code blocks under `# Prompt` for easier copying in Obsidian.
- Added the fence-length rule for prompts that already contain triple backticks.
- Retrofitted existing prompt files to use copy-friendly fenced prompt blocks.

## [2026-04-24 15:41] prompt-ingest | Council Of Ghosts Ethical Dilemma Prompt

Pages touched:
- [[wiki/prompts/agents/2026-04-24-council-of-ghosts-ethical-dilemma-prompt|Council Of Ghosts Ethical Dilemma Prompt]]
- [[log|log]]

Summary:
- Saved the pasted Council of Ghosts ethical dilemma prompt under `wiki/prompts/agents/`.
- Added tags for agents, roleplay, council-of-ghosts, ethical dilemmas, decision-making, masculine models, and persona prompts.

## [2026-04-24 15:42] admin | Wrap Prompt Code Blocks In Obsidian

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- `.obsidian/snippets/prompt-code-wrap.css`
- `.obsidian/appearance.json`
- [[log|log]]

Summary:
- Added an Obsidian CSS snippet to visually wrap fenced code blocks in `wiki/prompts/` notes without hard-wrapping the saved prompt payload.
- Enabled the `prompt-code-wrap` snippet in Obsidian appearance settings.
- Updated prompt-ingest rules to keep prompt text unchanged and rely on the snippet for display wrapping.

## [2026-04-24 15:42] admin | Strengthen Prompt Code Wrap Selectors

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- [[wiki/prompts/agents/2026-04-24-coding-assistant-operating-prompt|Coding Assistant Operating Prompt]]
- [[wiki/prompts/agents/2026-04-24-council-of-ghosts-ethical-dilemma-prompt|Council Of Ghosts Ethical Dilemma Prompt]]
- [[wiki/prompts/productivity/2026-04-24-project-manager-task-breakdown-prompt|Project Manager Task Breakdown Prompt]]
- `.obsidian/snippets/prompt-code-wrap.css`
- [[log|log]]

Summary:
- Broadened the prompt code-wrap CSS selectors to target Obsidian's workspace-leaf `data-path` structure, rendered markdown, reading view, and Live Preview codeblock lines.
- Added `cssclasses: prompt` to prompt frontmatter as a fallback targeting hook for prompt notes.
- Updated prompt-ingest rules so future prompt files include the `prompt` CSS class automatically.

## [2026-04-24 15:48] admin | Simplify Prompt Code Wrap CSS

Pages touched:
- [[AGENTS|AGENTS]]
- [[wiki/prompts/README|Prompt Library]]
- [[wiki/prompts/agents/2026-04-24-coding-assistant-operating-prompt|Coding Assistant Operating Prompt]]
- [[wiki/prompts/agents/2026-04-24-council-of-ghosts-ethical-dilemma-prompt|Council Of Ghosts Ethical Dilemma Prompt]]
- [[wiki/prompts/productivity/2026-04-24-project-manager-task-breakdown-prompt|Project Manager Task Breakdown Prompt]]
- `.obsidian/snippets/prompt-code-wrap.css`
- [[log|log]]

Summary:
- Replaced the broader path-based prompt wrapping CSS with a dedicated `prompt-note` class to avoid unintended layout side effects.
- Corrected the Obsidian CSS class targeting model by using `.prompt-note` rather than the non-working `.cssclass-prompt` fallback.
- Updated existing prompt notes and future prompt-ingest rules to use `cssclasses: prompt-note`.

## [2026-04-24 15:48] admin | Fix Prompt Code Wrap Specificity

Pages touched:
- `.obsidian/snippets/prompt-code-wrap.css`
- [[log|log]]

Summary:
- Updated the prompt code-wrap snippet to use Obsidian's known `pre > code[class*="language-"]` selector pattern for fenced code blocks.
- Kept the rule scoped to `cssclasses: prompt-note` notes.
- Hid the large rendered properties panel on prompt notes so the copyable prompt block is visible immediately.

## [2026-04-24 15:55] prompt-ingest | 80 20 Strategy Prompt Pack

Pages touched:
- [[wiki/prompts/productivity/2026-04-24-80-20-strategy-prompt-pack|80 20 Strategy Prompt Pack]]
- [[log|log]]

Summary:
- Saved a productivity prompt pack covering fast skill acquisition, contrarian strategy, reverse-engineering success, minimalist execution, and 80/20 analysis.
- Preserved the prompt payload verbatim in a copy-friendly fenced text block with `cssclasses: prompt-note`.

## [2026-04-24 16:30] prompt-ingest | Cognitive Advisory Council Simulation Prompt

Pages touched:
- [[wiki/prompts/agents/2026-04-24-cognitive-advisory-council-simulation-prompt|Cognitive Advisory Council Simulation Prompt]]
- [[log|log]]

Summary:
- Saved an agent prompt for simulating a five-person advisory council around a user-provided dilemma.
- Preserved the prompt payload verbatim in a copy-friendly fenced text block with `cssclasses: prompt-note`.

## [2026-04-24 16:35] prompt-ingest | AI Automation Specialist Prompt

Pages touched:
- [[wiki/prompts/agents/2026-04-24-ai-automation-specialist-prompt|AI Automation Specialist Prompt]]
- [[log|log]]

Summary:
- Saved an agent prompt for identifying routine tasks suitable for AI automation and setting up practical low-skill automations.
- Preserved the prompt payload verbatim in a copy-friendly fenced text block with `cssclasses: prompt-note`.
