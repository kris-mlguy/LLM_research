# LLM_research

### Frameworks and model releases
Paper | Description | Other links | Release      
-- | -- | -- | --  
[DeepSeek-R1](https://arxiv.org/pdf/2501.12948) | A reasoning model trained on RL without SFT, demonstrating reduction of data and compute requirements | [Github](https://github.com/deepseek-ai/DeepSeek-R1) | Jan'25  
[DeepSeek-V3 Technical Report](https://arxiv.org/pdf/2412.19437) | A Mixture-of-Experts model achieving efficient inference | [Github](https://github.com/deepseek-ai/DeepSeek-V3) | Dec'24
[DeepSeek-V2](https://arxiv.org/pdf/2405.04434) | A Strong, Economical, and Efficient Mixture-of-Experts Language Model using innovative architectures such as Multi-head Latent Attention (MLA) and DeepSeekMoE | | May'24
[OLMo - Accelerating the science of Language Models](https://arxiv.org/pdf/2402.00838v2.pdf) | First release of a truly open language model with access to data, training code, models and evaluation code | [Model weights](https://huggingface.co/allenai/OLMo-7B) <br> [Code](https://github.com/allenai/OLMo) <br> [Data](https://huggingface.co/datasets/allenai/dolma) <br> [Evaluation](https://github.com/allenai/OLMo-Eval) <br> [Instruction tuning](https://github.com/allenai/open-instruct) | Feb'24 
[RewriteLM: An Instruction-tuned Large Language Model for text rewriting](https://arxiv.org/pdf/2305.15685.pdf) | New strategies for instruction tuning and reinforcement learning to better align LLMs for cross-sentence rewriting tasks | [Github](https://github.com/google-research/google-research/tree/master/rewritelm) | May'23
 

### Foundation  
Paper | Description | Other links | Release      
-- | -- | -- | --  
[Retentive Network: A Successor to Transformer for Large Language Models](https://arxiv.org/pdf/2307.08621v4.pdf) | Alternative foundation architecture for training parallelism and low-cost inference | [Github](https://github.com/microsoft/unilm/tree/master/retnet) | Jul'23   

### Fine tuning  
Paper | Description | Other links | Release    
-- | -- | -- | --  
[QLORA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/pdf/2305.14314v1.pdf) | An efficient fine tuning apporach backpropagates gradients through a frozen, 4-bit quantized pretrained language model into Low Rank Adapters (LoRA) | [Github](https://github.com/artidoro/qlora) <br> [bitsandbytes](https://github.com/TimDettmers/bitsandbytes) | May'23  
[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685v2.pdf) | First alternative to full fine tuning freezing pretrained model weights and injecting trainable rank decomposition matrices  | [Github](https://github.com/microsoft/LoRA) | Oct'21

### Datasets  
Paper | Description | Other links | Release 
-- | -- | -- | --  
[Improving Wikipedia Verifiability with AI](https://openreview.net/pdf?id=qfTqRtkDbWZ) | WAFER - a large scale dataset to improve citations, SIDE - an AI based wikipedia citation verifier | [Demo](https://verifier.sideeditor.com/) <br> [Github](https://github.com/facebookresearch/side) | Jul'22  
[Understanding Iterative Revision from Human-Written Text (IteraTeR)](https://aclanthology.org/2022.acl-long.250.pdf) | The first largescale, multi-domain, edit-intention annotated corpus of iteratively revised text (GEC, coherence, clarity, style) | [Github](https://github.com/vipulraheja/IteraTeR) | May'22 
[JFLEG: A Fluency Corpus and Benchmark for Grammatical Error Correction](https://arxiv.org/pdf/1702.04066v1.pdf) | JHU FLuency-Extended GUG corpus (JFLEG) for developing and evaluating grammatical error correction (GEC) | [Dataset](https://huggingface.co/datasets/jfleg) | Feb'17  

### Evaluation benchmarks   
Paper | Description | Other links | Release 
-- | -- | -- | -- 
[EDITEVAL: An Instruction-Based Benchmark for Text Improvements](https://arxiv.org/pdf/2209.13331.pdf) | An instruction-based, benchmark and evaluation suite that leverages high-quality existing and new datasets for automatic evaluation of editing capabilities in areas such as fluency, coherence, clarity, simplification, paraphrasing, neutralization and updating | [Github](https://github.com/facebookresearch/EditEval) <br> [Leaderboard](https://eval.ai/web/challenges/challenge-page/1866/overview) | Sep'22  

### Noteworthy 
Blog | Description | Other links | Release 
-- | -- | -- | -- 
[Retrieval Augmented Generation or Long-Context LLMs?](https://arxiv.org/pdf/2407.16833) | Comparison between RAG and long-context (LC) LLMs and proposal of a hybrid approach for LC applications | | Jul'24
[The Hallucinations Leaderboard, an Open Effort to Measure Hallucinations in Large Language Models](https://huggingface.co/blog/leaderboards-on-the-hub-hallucinations) | The Hallucinations Leaderboard aims to track, rank and evaluate hallucinations in LLMs | [Leaderboard](https://huggingface.co/spaces/hallucinations-leaderboard/leaderboard) | Jan'24  
[Lost in the middle](https://cs.stanford.edu/~nfliu/papers/lost-in-the-middle.arxiv2023.pdf) | A study on how LLM performance degrades while changing the position of relevant information in the input context  | | Jul'23 
