---
aliases:
  - How modern LLMs work | Lex Fridman Podcast (Lex Clips)
---
- Title of Video: How modern LLMs work | Lex Fridman Podcast (Lex Clips) [youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

---

## 📝 Executive Summary

This clip explains how modern large language models (LLMs) have evolved from GPT‑2–style transformers, focusing on open‑weight models, architectural tweaks (like mixture of experts and new attention variants), and the growing Chinese and Western open‑source ecosystems. It emphasizes that most recent progress comes less from radical new architectures and more from scaling, systems engineering, and post‑training methods such as supervised fine‑tuning and RLHF, often combined with tool use (web search, code execution) to reduce hallucinations and unlock new capabilities.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

---

## 🎯 Key Takeaways

- The open‑weight LLM landscape has exploded, with both Chinese and Western labs releasing increasingly strong models, often with very permissive licenses that encourage local use and customization.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Architecturally, state‑of‑the‑art models are still autoregressive transformers in the GPT‑2 lineage; new ideas are mostly incremental tweaks (mixture of experts, attention variants, normalization changes) rather than wholesale replacements.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- A major conceptual shift is training models explicitly for **tool** use (web search, Python, etc.), which offers a practical path to reducing hallucinations and extending knowledge beyond what is stored in parameters.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Progress today is dominated by training regimes (pre/mid/post‑training), data quality, and systems‑level optimizations (low‑precision formats like FP8/FP4) that enable faster, larger‑scale experimentation.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Open‑weight and locally runnable models matter for sovereignty, privacy, and commercial flexibility, and Chinese models in particular often combine high performance with very permissive licensing and large parameter counts.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

---

## 💡 Core Concepts

## 1. Open‑weight LLM Ecosystem

The guests list a long array of open models: DeepSeek, Qwen, Kimi, MiniMax, Zhipu (Z.AI), Mistral, Gemma, GPT‑OSS (OpenAI’s open‑weight model), Nvidia’s NeMo/“Neotron” series, Hugging Face’s SmolLM, K2 models from the LLM360 initiative, and Stanford’s Marin community project, among others. The key point is that since roughly 2024–2026 the open ecosystem has become dense and competitive: many actors now release weights, data, and training code such that others can reproduce or extend their systems.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

Chinese open‑weight models are highlighted as especially large and high‑performing, often exceeding 100B parameters and pushing toward 400B‑parameter releases around early 2026. In contrast, many US/EU open models (e.g., Gemma, some NeMo variants) tend to be smaller but more resource‑efficient, though this balance is starting to change as Western labs also scale up parameter counts.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

Licensing is a crucial differentiator: Chinese open‑weight models often use genuinely permissive open‑source licenses, while Western models like Llama or Gemma include usage caps or reporting obligations (e.g., user‑count or revenue thresholds requiring disclosure to Meta/Google). This makes Chinese models very attractive to companies that want maximal freedom with minimal legal “strings attached.”[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 2. Why Open Models Matter

From a **use** perspective, open‑weight models enable:

- Local inference without sending data to a cloud provider or foreign entity.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Custom fine‑tuning and domain specialization (e.g., law, medical, internal knowledge bases).[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Deployment by third‑party startups who host Chinese models and “sell tokens” as an API, decoupling model origin from where it is served.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

From the provider’s perspective (e.g., OpenAI with GPT‑OSS), releasing open weights can offload GPU cost to the community: users run the models on their own hardware while the originating lab still benefits from ecosystem adoption and distribution. This is especially relevant when big labs are “GPU‑constrained” and every new proprietary feature competes for limited accelerator capacity.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 3. Tool Use as a Paradigm Shift

GPT‑OSS is described as one of the first open‑weight models trained with **tool use** as a first‑class capability. “Tool use” here means the model can:[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

- Call web search (e.g., Google) to fetch up‑to‑date information.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Invoke a Python interpreter or calculator for math and data manipulation.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

This shifts how we attack hallucinations: instead of relying solely on memorized facts, the model delegates factual lookup or exact computation to external systems. For example, to answer “Who won the 1998 soccer World Cup?” the model can call a search tool, fetch a reliable source (like FIFA), and then answer “France” based on retrieved evidence rather than parameter memory.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

Despite its power, tool use is underutilized in open‑source practice because:

- Users may not trust giving a model broad system access (fears of destructive commands, data exfiltration, etc.), so they need containerization and proper sandboxing.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Tool‑calling modes are more complex to integrate into applications, and many devs still default to pure chat‑completion APIs.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

## 4. Transformer Architecture Lineage

The clip explicitly roots modern LLMs in the original “Attention Is All You Need” transformer, which had encoder and decoder parts. GPT‑style models keep only the **decoder** and operate as autoregressive transformers: tokens are embedded, passed through stacked transformer blocks (attention + feed‑forward + normalization), and one token is predicted at a time.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

Key architectural tweaks since GPT‑2 include:

- **Mixture of Experts (MoE):** Instead of a single fully connected feed‑forward layer, you have many parallel feed‑forward “experts” and a router chooses a small subset per token. This makes the effective parameter count much larger without paying full compute cost each forward pass. It is a **sparse** architecture, as only a few experts are active per token.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Attention variants:
    
    - Grouped Query Attention (GQA), which reduces the cost of multi‑head attention by sharing key/value projections among query heads.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Multi‑Head Latent Attention (MHLA) in DeepSeek, a tweak aimed at making long‑context inference more efficient and reducing KV‑cache size.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Sliding‑window attention and related schemes that limit which past tokens are attended to, lowering memory and latency while still supporting long contexts.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
- Normalization and activations: swaps like LayerNorm → RMSNorm and different nonlinearities change training stability and efficiency but not the fundamental architecture.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

The guests emphasize that these changes are real but incremental: you can conceptually start from a GPT‑2 codebase and, by layering in MoE, new attention, norms, and activations, morph it into Gemma‑3‑like or Qwen‑like models. The “family resemblance” is very strong—modern LLMs are still fundamentally autoregressive transformers.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 5. Dense vs Sparse Models

They distinguish **dense** models (standard feed‑forward layers used for every token) from **sparse** MoE models (many experts, few active per token). Dense models are simpler, generally easier to train, and remain dominant in some state‑of‑the‑art models because MoE training can suffer from issues like expert collapse or poor routing balance. Sparse MoE models, however, offer a way to scale parameter count and represent more “knowledge” while keeping per‑token compute manageable.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 6. Training Regimes: Pre‑, Mid‑, and Post‑training

The development pipeline for modern LLMs is broken into three **stages**:[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

- Pre‑training: large‑scale unsupervised next‑token prediction on massive corpora. Scaling data quality and quantity still yields core capability gains.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Mid‑training: additional training phases that adjust the model for particular distributions or capabilities before the final alignment step (the clip doesn’t deeply detail this but notes it as a distinct phase).[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Post‑training: supervised fine‑tuning plus Reinforcement Learning from Human Feedback (RLHF), which transformed GPT‑3 into ChatGPT and unlocked conversational and instruction‑following behavior.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

The key insight is that many “capability unlocks” we associate with ChatGPT‑like systems come from post‑training methods rather than architectural revolutions.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 7. Systems‑Level Advances

Nvidia and others continuously push new low‑precision formats (FP8, FP4) and training optimizations. These reduce memory per parameter and communication overhead, increasing tokens‑per‑second‑per‑GPU and making it feasible to train larger models or run more experiments in the same wall‑clock time.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

While these do not by themselves create new cognitive capabilities, they accelerate the iterative loop over data curation, hyperparameter tuning, and algorithmic innovation. In practice, much of the rapid pace in AI comes from these systems improvements, even though a diagram of the architecture still “looks like GPT‑2.”[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

## 8. Alternatives to Transformers

There are emerging alternatives such as:

- Text diffusion models (which may still use transformers internally but are not autoregressive in the same sense).[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Mamba and related state‑space models, which offer different trade‑offs (e.g., potential efficiency gains) but have not displaced transformers at the high‑end.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

For now, the **state of the art** in language remains autoregressive transformers; alternatives live mostly in the “cheaper end” of the trade‑off space or niche applications.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)

---

## 🔨 Actionable Tips

These are practical implications you can apply if you work with or around LLMs.

1. **Prioritize tool integration over bigger base models**
    
    - If hallucinations or up‑to‑dateness are major problems, focus on reliably integrating web search and code execution, rather than only chasing larger parameter counts.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Containerize tool calls and restrict capabilities to build trust and safety into your system from day one.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
2. **Leverage permissive open‑weight licenses for products**
    
    - For commercial or privacy‑sensitive use cases, evaluate Chinese and other permissively licensed open‑weight models that you can run locally and fine‑tune without heavy legal constraints.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Check license terms on models like Llama/Gemma carefully if you expect to exceed user or revenue thresholds.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
3. **Treat architecture as stable, focus on training and data**
    
    - When designing your own models or selecting vendors, spend more effort on data pipelines, post‑training (SFT/RLHF), and evaluation setups than on exotic architectural tweaks.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Use “simple but well‑tuned” transformer baselines as your reference, adding complexity like MoE only when you can justify the operational cost.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
4. **Optimize for hardware and precision early**
    
    - If you control training or inference, adopt hardware‑friendly tricks—like quantization or low‑precision formats—early in your stack to improve throughput and reduce cost.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Monitor practical metrics like tokens/s/GPU as first‑class KPIs; they directly determine how fast you can iterate on algorithms and data.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
5. **Exploit local models for customization and privacy**
    
    - For enterprise applications (e.g., law, medicine, internal knowledge bases), design around a locally hosted open‑weight model that you fine‑tune with proprietary data.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        
    - Combine this with retrieval and tool use for a system that is both private and capable, without constant cloud calls.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
        

---

## 🔍 Additional Insights

- There is a subtle but important cultural and economic dynamic: many users worldwide will not pay for SaaS AI, but they will run models locally if given the weights, which incentivizes countries like China to push open‑weight releases for global influence.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- The ecosystem is sensitive to **perceived** data routing: people care whether their data is going “to China” or “to Silicon Valley,” so a lot of value is created by American or European startups that host foreign models domestically.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Model “quirks” (e.g., Kimi K2’s reputation for strong creative writing or specific coding strengths) lead practitioners to treat models as personalities and choose them task‑by‑task, rather than assuming one monolithic best model.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Despite heavy marketing around “new architectures,” the guests argue that the real story of the last few years is architectural continuity plus better training regimes and infrastructure, so claims of radical novelty should be treated skeptically unless tied to clear empirical gains.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- Alternatives like Mamba or diffusion‑based text models are worth watching, but the bar for displacing autoregressive transformers at the top end remains very high; any such replacement would need to show not just efficiency, but clear, consistent capability advantages.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    

**Ambiguities / unclear points:**

- Exact technical details of DeepSeek’s multi‑head latent attention and some newer linear‑scaling attention variants are only sketched at a high level here, not fully derived.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)
    
- The clip references mid‑training as distinct from pre‑ and post‑training but does not rigorously define how different labs operationalize this phase, so specifics may vary by organization.[youtube](https://www.youtube.com/watch?v=44mKM4WxSOA&list=WL&index=7)