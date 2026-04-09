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
- [[.obsidian/workspace.json]]
