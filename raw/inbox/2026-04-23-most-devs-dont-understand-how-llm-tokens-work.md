- Title of Video: Most devs don't understand how LLM tokens work[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

---

📝 Executive Summary  
This video explains what LLM tokens are, how they relate to billing, and why different providers count tokens differently for the same text. It walks through how tokenizers are trained, how text is encoded and decoded as tokens, and what trade-offs exist between vocabulary size, efficiency, and model complexity.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)

---

🎯 Key Takeaways

- Tokens are the basic “currency” of LLMs, and you are billed per input and output token, often at different rates.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Each model provider uses its own tokenizer and vocabulary, so the same prompt can produce very different token counts and costs.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Tokenization turns text into sequences of numbers (tokens) using a learned vocabulary of characters and subwords, and all LLM computation happens on these numbers, not on raw text.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Larger vocabularies can represent common words in fewer tokens (more efficient) but require bigger, more memory‑hungry models, so providers must balance vocabulary size vs. efficiency.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Unusual words or low‑resource languages get split into more tokens, increasing cost and sometimes reducing effectiveness, whereas common languages and coding languages enjoy more efficient tokenization.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

---

💡 Core Concepts

1. What tokens are and how billing works
    

- A token is a unit from a model’s vocabulary (word, subword, or character) that gets mapped to a number.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- When you send “hello world” to an LLM, it is split into the largest known chunks (e.g., “hello”, space, “world”, “!”), each mapped to a numeric token ID.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Providers charge per 1,000 input and output tokens, often with different rates; total cost is computed by summing input and output tokens, dividing by 1,000, and multiplying by the per‑1K price.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Example: using an SDK with “hello world” to Anthropic’s Claude 3.5 Haiku shows 11 input tokens and 20 output tokens, even though the literal prompt is only two words.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Differences between model providers
    

- The same prompt sent to two providers (Anthropic vs. Google Gemini 2.0 Flash) yields different token counts (e.g., 11/20 vs. 4/11) because each uses a different tokenizer and vocabulary.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- There is no universal mapping between “words” and “tokens”; the relationship depends entirely on the tokenizer’s learned subword segmentation and vocabulary design.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Encoding, decoding, and the LLM process
    

- Encoding: input text is split into the largest possible tokens found in the vocabulary, then each token is replaced by its numeric ID to form a sequence of numbers.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- The LLM does all its internal “thinking” (matrix multiplications, neural network operations) on these token IDs, not on text.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Decoding: the output token IDs are mapped back to subwords/characters via the vocabulary, concatenated, and returned as text.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- In code, this is demonstrated with OpenAI’s `tiktoken` (via the JS implementation `js-tiktoken` using the `o200k_base` tokenizer for GPT‑4.0), showing that a long English sentence (≈2,300 characters) may be fewer than 500 tokens, while “hello world” is 3 tokens vs 12 characters.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Building token vocabularies
    

- Tokenizers are trained on a large corpus (often the same data used to train the model), learning which character sequences occur frequently and should be merged into subwords.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- A simple character‑level tokenizer uses unique characters as tokens; for an input like “cats sat mat”, the number of tokens equals the number of characters, which is inefficient.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- In a TypeScript example, a character‑level tokenizer over “the cat sat on the mat” yields a vocabulary with only 10 tokens, but any input’s token count matches its character length, increasing computational cost.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Vocabulary size and subword tokenization
    

- Vocabulary size matters: with 1,000 tokens, a word like “understanding” might be split into 5 tokens (“under”, “st”, “and”, “ing”, etc.); with 50,000 tokens, it might be 3 tokens (“under”, “standing”, maybe something else); with 200,000 tokens, it might become just 2 tokens.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Fewer tokens per word mean less computational work per prompt, but larger vocabularies require larger models and more memory to store and operate on embedding matrices.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- A subword‑level tokenizer improves efficiency by identifying frequent bigrams or groups (e.g., “th”, “he”, “ a”) and using them as single tokens, reducing token count on typical text.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- The demo subword tokenizer (described as “vibe coded”) shows that for “cats sat mat” the input length is 11 characters but only 8 tokens, with a richer 15‑token vocabulary that includes subwords like “th”, “he”, and combinations with spaces.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Handling unusual words and low‑frequency patterns
    

- When a tokenizer encounters an unusual or invented word (e.g., “frabjous” from Lewis Carroll), a tokenizer like `o200k_base` splits it into multiple subword tokens (four in this example) because it rarely appears in the training data.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- The same happens for languages or coding languages that are underrepresented in the training corpus: they get segmented into more tokens for the same number of characters.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- This gives popular human languages and widely used programming languages (e.g., JavaScript) an efficiency advantage: 20 lines of JavaScript cost fewer tokens than 20 lines of Haskell, all else equal.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

1. Summary of token workflow
    

- Tokens are the units that LLMs think in and that providers bill for; encoding transforms text into tokens, the model reasons on tokens, and decoding transforms tokens back to text.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Differences in how tokenizers are trained and how vocabularies are constructed explain the variation in token counts and pricing across providers.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    

---

🔨 Actionable Tips

- Monitor token usage per provider
    
    - Use your SDK’s usage reporting (like the example with an AI SDK logging `usage`) to track input and output tokens per call, and correlate them with cost.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
    - Pay attention to how different models (e.g., Anthropic vs. Gemini) tokenize the same prompts; this can directly affect your per‑request spend, especially at scale.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
- Design prompts with tokenization in mind
    
    - Recognize that long or verbose prompts increase both input tokens and cost; trim boilerplate and avoid unnecessary repetition.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
    - For languages or code that you know tokenize poorly (rare languages, esoteric languages), consider whether you can switch to more common languages or representations to reduce token count.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
- Choose models and tokenizers strategically
    
    - When modeling cost, test multiple providers with the same workload to see who gives the most efficient tokenization (fewest tokens for similar quality output).[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
    - For applications with significant traffic, prioritize models whose tokenizer handles your dominant language or codebase efficiently, rather than choosing solely on per‑1K‑token list price.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
- Understand vocabulary trade‑offs in design decisions
    
    - When evaluating or building systems around custom models or tokenizers, consider the balance between vocabulary size, per‑prompt token count, and required model/memory size.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
    - Favor subword‑level approaches (like BPE‑style tokenization) over naive character‑level tokenization to avoid one‑token‑per‑character inefficiency.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
- Educate your team on token fundamentals
    
    - Share mental models from this video (tokens as “numbers representing chunks of text”, encoding/decoding diagram) to improve cost awareness and debugging across devs.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        
    - Use small code demos (like the TypeScript `tiktoken` examples or simple custom tokenizers) in internal workshops to make tokenization behavior concrete.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
        

---

🔍 Additional Insights

- The presenter emphasizes using TypeScript for building AI‑powered applications, reserving Python primarily for model‑level work, reflecting a preference for strong typing and modern JS tooling in app development.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- The examples show that “token” is not reliably approximated by “word”: short phrases can have surprisingly high token counts due to system prompts, metadata, and provider‑specific encoding schemes, even though those extra pieces are not shown in the simple example code.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- There is a structural bias in tokenizers towards common patterns in the training corpus, which has downstream implications: languages, domains, or coding ecosystems that are underrepresented pay an implicit “token tax” in both cost and sometimes latency.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- The talk implicitly highlights a strategic angle for AI economics: understanding and optimizing tokenization is as important as model selection for teams that care about large‑scale cost, latency, and throughput.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)
    
- Ambiguity: the internal details of the “vibe coded” subword tokenizer are not rigorously explained, and the exact training algorithm (e.g., BPE vs. unigram LM) is abstracted away, so its behavior should be treated as illustrative rather than a faithful reproduction of production tokenizers.[youtube](https://www.youtube.com/watch?v=nKSk_TiR8YA&list=WL&index=6)