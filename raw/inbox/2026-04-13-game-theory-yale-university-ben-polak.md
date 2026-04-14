- Title of Video: Game Theory (Yale University – Ben Polak)[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

📝 Executive Summary  
The lecture introduces game theory as a systematic way to analyze **strategic** situations where outcomes depend on the actions of multiple decision-makers, not just one’s own choices. Through a sponge-throwing duel game, Ben Polak demonstrates how tools like dominance reasoning and backward induction can determine optimal strategies in timing-based conflicts, from duels and product launches to bike racing and negotiations. He also highlights psychological biases—especially overconfidence and a cultural “proactive bias”—that cause real people to deviate from theoretically optimal play.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)

🎯 Key Takeaways

- Game theory studies situations where payoffs depend on others’ actions, covering both competition (e.g., firms) and cooperation (e.g., teams, university leadership).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- In timing games (like a duel or product launch), the key strategic question is often _when_ to act, not _what_ to do, and optimal timing can be solved mathematically.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Two core analytical tools are dominance (doing the same action regardless of others’ choices) and backward induction (solving from the end of the game backwards).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Even if opponents are irrational or “crazy,” dominance arguments remain robust, while backward induction is more fragile and depends on assumptions about others’ rationality.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Real-world behavior systematically deviates from game-theoretic predictions due to overconfidence and a cultural bias toward “going down swinging” instead of waiting.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

💡 Core Concepts

1. What Game Theory Analyzes
    

- Game theory is defined as the analysis of strategic situations where your outcome depends on both your own actions and those of others.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Examples include: duopolistic competition (Apple vs. Samsung in smartphones), cooperative settings (teams, university deans “herding cats”), and broader social interactions.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- It is used to understand both competitive behavior (pricing, innovation, litigation) and cooperative behavior (coordination within organizations).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. The Sponge Duel Game Structure
    

- Two players stand several steps apart, each with one wet sponge; on their turn, they either step forward or throw the sponge at the opponent.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- If a throw hits, the thrower wins; if it misses, the thrower has no sponge left and must continue stepping, eventually allowing the opponent an easy win.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Each player’s probability of hitting depends on distance DDD: at distance zero the probability is 1, and as distance increases, the probability of hitting decreases.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Let P1(D)P_1(D)P1​(D) and P2(D)P_2(D)P2​(D) denote the respective hit probabilities for player 1 and player 2 at distance DDD; the curves slope downward, and one player may be the better shot at all distances.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Information Assumption and Common Knowledge
    

- The simplifying (unrealistic) assumption: each player knows their own hit probability function and the opponent’s function, and this is common knowledge (they know that the other knows, etc.).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- This assumption allows formal solution in a single lecture, even though in real life players do not precisely know these probabilities.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Two Local “Building Block” Problems  
    Polak breaks the complex problem into two simpler conditional questions:[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

- Building Block A (Opponent will not shoot next turn):
    
    - If at distance DDD, player III _knows_ opponent JJJ will not shoot next turn, then the best response is **not** to shoot now.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
    - Rationale: moving closer increases your hit probability, so waiting for “the day after tomorrow” strictly improves your chance compared to shooting today.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
- Building Block B (Opponent will shoot next turn):
    
    - If at distance DDD, player III _knows_ opponent JJJ will shoot next turn if III doesn’t shoot now, then III should compare:
        
        - Probability of winning by shooting now: PI(D)P_I(D)PI​(D).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
            
        - Probability of winning by waiting: probability opponent misses tomorrow, 1−PJ(D−1)1 - P_J(D-1)1−PJ​(D−1), because they will be one step closer.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
            
    - So III should shoot now if and only if
        
        PI(D)≥1−PJ(D−1)P_I(D) \ge 1 - P_J(D-1)PI​(D)≥1−PJ​(D−1)
        
        which can be rearranged to
        
        PI(D)+PJ(D−1)≥1.P_I(D) + P_J(D-1) \ge 1.PI​(D)+PJ​(D−1)≥1.
        
        [youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        

1. Critical Distance D∗D^*D∗ and Optimal Strategy
    

- As distance decreases, both players’ hit probabilities increase; thus the sum P1(D)+P2(D−1)P_1(D) + P_2(D-1)P1​(D)+P2​(D−1) is small at large distances and eventually exceeds 1 when they are closer.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- There exists a critical distance D∗D^*D∗ where for the _first_ time the inequality PI(D)+PJ(D−1)≥1P_I(D) + P_J(D-1) \ge 1PI​(D)+PJ​(D−1)≥1 becomes true (for the player whose turn it is).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Polak claims and then shows:
    
    - Nobody should throw before reaching distance D∗D^*D∗.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
    - At D∗D^*D∗, whoever’s turn it is should throw; if they failed to throw, the opponent should throw on the next turn at distance D∗−1D^*-1D∗−1.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        

1. Dominance Reasoning (Key Tool #1)
    

- A **dominant** action is one that is optimal regardless of what you believe the opponent will do.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- For early stages (distances greater than D∗D^*D∗), Polak shows:
    
    - If you think opponent won’t throw next turn, Building Block A implies you should step (not throw).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
    - If you think opponent will throw next turn, Building Block B implies you should step, because at those distances PI(D)+PJ(D−1)<1P_I(D) + P_J(D-1) < 1PI​(D)+PJ​(D−1)<1.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
- Since “step” is optimal whether the opponent throws or not, stepping is a dominant action before D∗D^*D∗.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Backward Induction (Key Tool #2)
    

- At distance D∗D^*D∗, dominance no longer resolves the choice because the two conditional recommendations conflict:
    
    - If you believe opponent will not throw next turn, Building Block A says “step”.
        
    - If you believe opponent will throw, Building Block B (with equality close to binding) says “throw”.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
- To resolve this, Polak uses **backward induction**:
    
    - Analyze the very last possible position (distance 0): if it’s your turn there, you throw because hit probability is 1.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
    - Step one position back: if at distance 1 it’s the other player’s turn, they know you will certainly throw at distance 0, so by Building Block B they should throw at 1.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
    - Step back again: at distance 2, you know they will throw at 1, so you should throw at 2, and so on.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
        
- Iterating this logic backward identifies that at D∗D^*D∗ the player whose turn it is must throw, resolving the earlier dilemma.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Robustness to Irrationality
    

- The dominance-based part of the argument (no one should throw before D∗D^*D∗) does not rely on assumptions that others are rational, sophisticated, or well-trained in game theory—it holds even against “crazy” or unsophisticated opponents.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- By contrast, the backward induction part (what happens exactly at and after D∗D^*D∗) does depend on beliefs that others will reason similarly and understand that you reason similarly.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- This asymmetry shows that some game-theoretic predictions are very robust, while others are fragile to bounded rationality, limited cognition, or misperceptions.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Applications of the Duel Timing Logic
    

- Duels in 19th-century Russian literature: Polak references Tolstoy’s “War and Peace” (Pierre vs. Dolokhov) and Pushkin’s “Eugene Onegin,” noting that the key lesson is “don’t duel,” but if you do, timing matters.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Tour de France breakaways: a cyclist must decide when to break from the peloton; going too early guarantees being reeled in, while going too late means someone else wins—mathematically analogous to deciding when to throw the sponge.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Product launches and network-effect markets: two firms developing a new technology must decide when to launch; too early risks failure and reputational damage, but too late lets the rival establish a standard and dominate the market.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- In each case, the structure is: everyone knows the action to take (throw, launch, attack), but the strategic problem is to pick the optimal _moment_.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Psychological and Cultural Biases
    

- Overconfidence bias: people overestimate their own abilities and sometimes their opponents’ abilities; this is widely documented in psychology and behavioral economics.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Proactive bias (especially in American culture, per Polak): people are socialized to value “taking control,” “seizing the bull by the horns,” and “controlling their own destiny.”[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- When applying the sponge game in classes (undergrads, MBAs, alumni, deans), Polak empirically observes far fewer hits than the roughly 50% rate implied by the model at D∗D^*D∗, suggesting players throw too early.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- He argues that cultural glorification of “going down swinging” leads players to act prematurely rather than wait for better odds, even when theory says waiting is superior.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Game Theory Beyond Economics
    

- Game theory is now heavily used in biology, especially in evolutionary game theory and the analysis of evolutionary stable strategies (ESS).[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Biologists can infer payoff structures from observed behavior in populations, e.g., rock–paper–scissors dynamics in lizard mating strategies, where cyclical patterns in population frequencies reveal underlying game payoffs.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Polak emphasizes that biological applications sometimes use game-theoretic ideas more creatively than economists, and they illustrate how the same formal tools can apply to genes and species, not just rational individuals.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

1. Limits, Assumptions, and Interdisciplinary Dialogue
    

- Mathematical social science clarifies which conclusions depend on which assumptions; dropping or changing assumptions (e.g., knowledge of skill curves, rationality, payoff structure) can alter predictions.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Polak stresses that the goal is not to produce perfectly accurate predictions of behavior but to perform disciplined thought experiments and see exactly where an argument breaks if an assumption is relaxed.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- He encourages constructive dialogue between formal modelers and humanists or sociologists: rather than dismissing models as unrealistic, one can ask which assumptions are crucial and which results remain robust when assumptions change.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

🔨 Actionable Tips

- When facing a timing decision (e.g., launching a campaign, making a career move, attacking in a negotiation), first clarify whether the key strategic variable is _when_ to act rather than _what_ to do.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Before acting, ask: “If I knew my counterpart would _not_ act next round, would waiting strictly improve my chance?”; if yes, resist acting now and wait for a better position.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Use dominance reasoning: if an action is better regardless of what you believe the other side will do, treat it as your default and avoid overcomplicating the decision.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- For finite-horizon interactions (clear end points), practice backward induction: think from the last possible move, figure out optimal play there, then walk your reasoning step by step back to the present.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Actively check your own **overconfidence** and the urge to “be proactive” for its own sake; ensure that the impulse to move first is backed by better probabilities, not just by cultural norms or ego.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

🔍 Additional Insights

- The lecture uses live participation with deans as players, which serves both as a teaching device and as implicit data on how real people deviate from theoretical predictions.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- The mathematical step of transforming PI(D)≥1−PJ(D−1)P_I(D) \ge 1 - P_J(D-1)PI​(D)≥1−PJ​(D−1) into PI(D)+PJ(D−1)≥1P_I(D) + P_J(D-1) \ge 1PI​(D)+PJ​(D−1)≥1 is simple algebraically but conceptually powerful, framing the decision in terms of whether the combined hit chances across two turns exceed certainty.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Theoretically, if abilities are randomly distributed and players follow the model’s logic, hits at the optimal distance should occur around 50% of the time; Polak’s much lower observed hit rate is strong empirical evidence of systematic bias.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- The assumption of full knowledge of skill curves is flagged by Polak himself as unrealistic; in more realistic settings, players must reason under uncertainty about opponent abilities, requiring expectations and Bayesian updating over possible skill distributions.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- Polak distinguishes robust insights (like dominance-based “don’t shoot early”) from more fragile ones (like exact timing under backward induction), showing where game theory is most reliable and where human psychology likely dominates.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    

Ambiguities / Unclear Points (Flagged)

- The lecture does not specify an explicit functional form for P1(D)P_1(D)P1​(D) or P2(D)P_2(D)P2​(D); the argument relies only on monotonicity and boundedness, so numerical predictions for specific distances remain abstract.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- The exact statistical basis for the “10% hits” empirical claim is informal (Polak’s classroom observations), with no sample sizes or controlled conditions provided.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)
    
- The discussion of proactive bias is partly anecdotal and culturally focused on the U.S.; its generalizability to other cultures is suggested but not empirically demonstrated within the lecture.[youtube](https://www.youtube.com/watch?v=M3oWYHYoBvk&list=WL&index=8)