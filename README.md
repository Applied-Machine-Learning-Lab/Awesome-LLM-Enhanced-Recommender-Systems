# Awesome LLM-Enhanced Recommender Systems

This is the collection of the papers on __LLM__-__E__nhanced __R__ecommender __S__ystems (__LLMERS__). 

Due to the latency requirements by the online recommenders, LLMERS has gained considerable attention recently. We would like to give the definition of the LLMERS in our survey.

:bulb: __Definition__: The conventional recommender systems are enhanced by large language models via assistance in training or supplementary for data, while no need for LLM inference during the service

:star: __Category__: LLMERS augments the conventional RS from its basic components, i.e., interaction data and recommendation model, so that  we categorize them into three lines: Knowledge Enhancement, Interaction Enhancement and Model Enhancement.



<img src="./Taxonomy.png" style="zoom:80%;" />

## 1. Knowledge Enhancement

| Date / Venue       | Model     | Paper                                                                                                                                                               | Knowledge Type            | Foundation Model (Finetuned/Non-finetuned)     | Code                                                                           |
| ------------------ | :-------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------ |
| 2023.5 / WSDM'24   | ONCE      | [ONCE: Boosting Content-based Recommendation with Both Open- and Closed-source Large Language Models](https://dl.acm.org/doi/pdf/10.1145/3616855.3635845)              | Summarization & Reasoning | LLaMA-7B (F) + GPT-3.5 (N)                     | [Link](https://github.com/Jyonn/ONCE)                                             |
| 2023.6 / RecSys'24 | KAR       | [Towards Open-World Recommendation with Knowledge Augmentation from Large Language Models](https://arxiv.org/pdf/2306.10933)                                           | Summarization & Reasoning | ChatGLM (N)                                    | [Link](https://github.com/YunjiaXi/Open-World-Knowledge-Augmented-Recommendation) |
| 2023.8 / AAAI'24   | LLMRG     | [LLMRG: Improving Recommendations through Large Language Model Reasoning Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/29887/31548)                         | Knowledge Graph           | GPT-4 (N) / GPT-3.5 (N)                        | N/A                                                                            |
| 2023.12 / arXiv'23 | SAGCN     | [Understanding Before Recommendation: Semantic Aspect-Aware Review Exploitation via Large Language Models](https://arxiv.org/pdf/2312.16275)                           | Knowledge Graph           | Vicuna-13B (N)                                 | N/A                                                                            |
| 2024.1 / arXiv'24  | LLMHG     | [LLM-Guided Multi-View Hypergraph Learning for Human-Centric Explainable Recommendation](https://arxiv.org/pdf/2401.08217)                                             | Knowledge Graph           | GPT-4 (N) / GPT-3.5 (N)                        | N/A                                                                            |
| 2024.2 / arXiv'24  | LLM-KERec | [Breaking the Barrier: Utilizing Large Language Models for Industrial Recommendation Systems through an Inferential Knowledge Graph](https://arxiv.org/pdf/2402.13750) | Knowledge Graph           | GPT-3.5 (N) / ChatGLM2 (N)                     | N/A                                                                            |
| 2024.2 / arXiv'24  | GaCLLM    | [Large Language Model with Graph Convolution for Recommendation](https://arxiv.org/pdf/2402.08859)                                                                     | Summarization & Reasoning | ChatGLM2-6B (F)                                | N/A                                                                            |
| 2024.3 / arXiv'24  | CSRec     | [Common Sense Enhanced Knowledge-based Recommendation with Large Language Model](https://arxiv.org/pdf/2403.18325)                                                     | Knowledge Graph           | GPT-3.5 (N)                                    | [Link](https://github.com/ysh-1998/CSRec)                                         |
| 2024.3 / arXiv'24  | KELLMRec  | [KELLMRec: Knowledge-Enhanced Large Language Models for Recommendation](https://arxiv.org/pdf/2403.06642)                                                              | Both                      | InternLM-7B (N)                                | N/A                                                                            |
| 2024.4 / ICASSP'24 | LAMAR     | [Large Language Models Augmented Rating Prediction in Recommender System](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10447514)                           | Summarization & Reasoning | LLaMA (N)                                      | [Link](https://github.com/sichunluo/LAMAR)                                        |
| 2024.5 / arXiv'24  |           | [News Recommendation with Category Description by a Large Language Model](https://arxiv.org/pdf/2405.13007)                                                            | Summarization & Reasoning | GPT-4 (N)                                      | [Link](https://github.com/yamanalab/gpt-augmented-news-recommendation)            |
| 2024.5 / SIGIRW'24 | LLM-BRec  | [LLM-BRec: Personalizing Session-based Social Recommendation with LLM-BERT Fusion Framework](https://openreview.net/pdf?id=gwHVlTNKsG)                                 | Summarization & Reasoning | LLaMA2-7B (N)                                  | N/A                                                                            |
| 2024.5 / arXiv'24  | SKarREC   | [Learning Structure and Knowledge Aware Representation with Large Language Models for Concept Recommendation](https://arxiv.org/pdf/2405.12442)                        | Both                      | GPT-3.5 (N)                                    | N/A                                                                            |
| 2024.7 / arXiv'24  | LANE      | [LANE: Logic Alignment of Non-tuning Large Language Models and Online Recommendation Systems for Explainable Reason Generation](https://arxiv.org/pdf/2407.02833)      | Summarization & Reasoning | GPT-3.5 (N)                                    | N/A                                                                            |
| 2024.7 / SIGIR'24  | SeRALM    | [Enhancing Sequential Recommenders with Augmented Knowledge from Aligned Large Language Models](https://dl.acm.org/doi/pdf/10.1145/3626772.3657782)                    | Summarization & Reasoning | LLaMA2-7B (F)                                  | N/A                                                                            |
| 2024.8 / ACLW'24   | HRGraph   | [HRGraph: Leveraging LLMs for HR Data Knowledge Graphs with Information Propagation-based Job Recommendation](https://aclanthology.org/2024.kallm-1.6.pdf)             | Knowledge Graph           | unknown                                        | [Link](https://github.com/azminewasi/HRGraph)                                     |
| 2024.8 / arXiv'24  | MMRec     | [MMREC: LLM Based Multi-Modal Recommender System](https://arxiv.org/pdf/2408.04211)                                                                                    | Summarization & Reasoning | GPT-3.5 (N)                                    | N/A                                                                            |
| 2024.8 / arXiv'24  | REKI      | [Efficient and Deployable Knowledge Infusion for Open-World Recommendations via Large Language Models](https://www.arxiv.org/pdf/2408.10520)                           | Summarization & Reasoning | GPT-3.5 (N)                                    | [Link](https://github.com/YunjiaXi/REKI?tab=readme-ov-file)                       |
| 2024.8 / arXiv'24  | X-REFLECT | [X-REFLECT: Cross-Reflection Prompting for Multimodal Recommendation](https://www.arxiv.org/pdf/2408.15172)                                                            | Summarization & Reasoning | GPT-4V (N) / LLaVA1.5-7B (N) / InternLM-7B (N) | N/A                                                                            |

## 2. Interaction Enhancement

| Date / Venue      | Model    | Paper                                                        | Generation Method | Foundation Model (Finetuned/Non-finetuned) | Code                                    |
| ----------------- | -------- | ------------------------------------------------------------ | ----------------- | ------------------------------------------ | --------------------------------------- |
| 2023.6 / WSDM'24  | LLMRec   | [LLMRec: Large Language Models with Graph Augmentation for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3616855.3635853) | Text-based        | GPT-3.5 + text-embedding-ada-002 (N)       | [Link](https://github.com/HKUDS/LLMRec) |
| 2024.1 / arXiv'24 | LlamaRec | [Integrating Large Language Models into Recommendation via Mutual Augmentation and Adaptive Aggregation](https://arxiv.org/pdf/2401.13870) | Text-based        | LLaMA2-7B (F)                              | N/A                                     |
| 2024.2 / arXiv'24 | LLM-InS  | [Large Language Model Interaction Simulator for Cold-Start Item Recommendation](https://arxiv.org/pdf/2402.09176) | Score-based       | LLaMA2 (F)                                 | N/A                                     |
| 2024.2 / WWW'24   | ColdAug  | [Large Language Models as Data Augmenters for Cold-Start Item Recommendation](https://dl.acm.org/doi/pdf/10.1145/3589335.3651532) | Text-based        | PaLM2 (N)                                  | N/A                                     |
| 2024.8 / arXiv'24 | LLMDSR   | [LLM4DSR: Leveraing Large Language Model for Denoising Sequential Recommendation](https://arxiv.org/pdf/2408.08208) | Score-based       | LLaMA3-8B (F)                              | N/A                                     |
| 2024.9 / arXiv'24 | LLMHD    | [Large Language Model Enhanced Hard Sample Identification for Denoising Recommendation](https://arxiv.org/pdf/2409.10343) | Text-based        | GPT-3.5 (N)                                | N/A                                     |

## 3. Model Enhancement

| Date / Venue        | Model     | Paper                                                        | Integration Type                           | Foundation Model (Finetuned/Non-finetuned)      | Code                                                         |
| ------------------- | --------- | ------------------------------------------------------------ | ------------------------------------------ | ----------------------------------------------- | ------------------------------------------------------------ |
| 2023.8 / arXiv'23   | CTRL      | [CTRL: Connect Collaborative and Language Model for CTR Prediction](https://arxiv.org/pdf/2306.02841v4) | Model Initialization                       | ChatGLM-6B (F)                                  | N/A                                                          |
| 2023.9 / RecSys'23  | LLM       | [Leveraging Large Language Models for Sequential Recommendation](https://dl.acm.org/doi/pdf/10.1145/3604915.3610639) | Model Initialization                       | text-embedding-ada-002 (N)                      | [Link](https://github.com/dh-r/LLM-Sequential-Recommendation) |
| 2023.10 / RecSys'24 | FLIP      | [FLIP: Towards Fine-grained Alignment between ID-based Models and Pretrained Language Models for CTR Prediction](https://arxiv.org/pdf/2310.19453) | Model Initialization                       | TinyBERT                                        | [Link](https://github.com/justarter/FLIP)                    |
| 2023.10 / WWW'24    | RLMRec    | [Representation Learning with Large Language Models for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3589334.3645458) | Embedding Guidance                         | text-embedding-ada-002 (N) + GPT-3.5 (N)        | [Link](https://github.com/HKUDS/RLMRec)                      |
| 2023.11 / WWW'24    | SINGLE    | [Modeling User Viewing Flow using Large Language Models for Article Recommendation](https://dl.acm.org/doi/pdf/10.1145/3589335.3648305) | Embedding Utilization                      | ChatGLM-6B (F)                                  | N/A                                                          |
| 2024.2 / arXiv'24   | LEADER    | [Large Language Model Distilling Medication Recommendation Model](https://arxiv.org/pdf/2402.02803) | Model Distillation                         | LLaMA-7B (F)                                    | [Link](https://github.com/liuqidong07/LEADER-pytorch)        |
| 2024.2 / arXiv'24   | LLM2X     | [Improving Sequential Recommendations with LLMs](https://arxiv.org/pdf/2402.01339) | Model Initialization                       | text-embedding-ada-002 (N)                      | [Link](https://github.com/dh-r/LLM-Sequential-Recommendation) |
| 2024.2 / arXiv'24   | LLM4SBR   | [LLM4SBR: A Lightweight and Effective Framework for Integrating Large Language Models in Session-based Recommendation](https://arxiv.org/pdf/2402.13840) | Embedding Guidance                         | QWen-7B (N)                                     | N/A                                                          |
| 2024.2 / arXiv'24   | TedRec    | [Sequence-level Semantic Representation Fusion for Recommender Systems](https://arxiv.org/pdf/2402.18166) | Embedding Utilization                      | LLaMA2-7B (N), T5 (N)                           | [Link](https://github.com/RUCAIBox/TedRec)                   |
| 2024.3 / CIKM'24    | LLM-CF    | [Large Language Models Enhanced Collaborative Filtering](https://arxiv.org/pdf/2403.17688) | Embedding Utilization                      | LLaMA2-7B (F)                                   | [Link](https://anonymous.4open.science/r/LLM-CF-AD78/readme.md) |
| 2024.3 / CIKM'24    | LoID      | [Enhancing Content-based Recommendation via Large Language Model](https://arxiv.org/pdf/2404.00236) | Embedding Utilization                      | BERT (F)                                        | [Link](https://github.com/cjx96/LoID)                        |
| 2024.3 / arXiv'24   | LSVCR     | [A Large Language Model Enhanced Sequential Recommender for Joint Video and Comment Recommendation](https://arxiv.org/pdf/2403.13574) | Embedding Utilization                      | ChatGLM3-6B (F)                                 | [Link](https://github.com/RUCAIBox/LSVCR/)                   |
| 2024.3 / SIGIR'24   | BAHE      | [Breaking the Length Barrier: LLM-Enhanced CTR Prediction in Long Textual User Behaviors](https://dl.acm.org/doi/pdf/10.1145/3626772.3657974) | Embedding Utilization                      | QWen-8B (F)                                     | N/A                                                          |
| 2024.3 / SIGIR'24   | LRD       | [Sequential Recommendation with Latent Relations based on Large Language Model](https://dl.acm.org/doi/pdf/10.1145/3626772.3657762) | Embedding Utilization                      | text-embedding-ada-002 (N)                      | [Link](https://github.com/ysh-1998/LRD)                      |
| 2024.3 / WWW'24     | SLIM      | [Can Small Language Models be Good Reasoners for Sequential Recommendation?](https://dl.acm.org/doi/pdf/10.1145/3589334.3645671) | Model Initialization                       | LLaMA2-7B (F)                                   | N/A                                                          |
| 2024.3 / WWW'24     | NoteLLM   | [NoteLLM: A Retrievable Large Language Model for Note Recommendation](https://dl.acm.org/doi/pdf/10.1145/3589335.3648314) | Embedding Utilization                      | LLaMA2-7B (F)                                   | N/A                                                          |
| 2024.5 / NeurIPS'24 | LLM-ESR   | [LLMESR: Large Language Models Enhancement for Long-tailed Sequential Recommendation](https://arxiv.org/pdf/2405.20646) | Embedding Utilization / Embedding Guidance | text-embedding-ada-002 (N)                      | [Link](https://github.com/liuqidong07/LLM-ESR)               |
| 2024.5 / WWW'24     | SAID      | [Enhancing sequential recommendation via LLM-based item semantic embedding learning](https://dl.acm.org/doi/pdf/10.1145/3589335.3648307) | Model Initialization                       | LLaMA2-7B (F)                                   | N/A                                                          |
| 2024.5 / arXiv'24   | CELA      | [CELA: Cost-Efficient Language Model Alignment for CTR Prediction](https://arxiv.org/pdf/2405.10596) | Embedding Utilization                      | OPT-1.3B (F)                                    | N/A                                                          |
| 2024.5 / arXiv'24   | DLLM2Rec  | [Distillation Matters: Empowering Sequential Recommenders to Match the Performance of Large Language Models](https://arxiv.org/pdf/2405.00338) | Model Distillation                         | LLaMA2-7B (F)                                   | N/A                                                          |
| 2024.5 / arXiv'24   | DynLLM    | [DynLLM: When Large Language Models Meet Dynamic Graph Recommendation](https://arxiv.org/pdf/2405.07580) | Embedding Utilization                      | QWen-max-1201 (N) + text-embedding-v2 (N)       | N/A                                                          |
| 2024.5 / RecSys'24  | EmbSum    | [EmbSum: Leveraging the Summarization Capabilities of Large Language Models for Content-Based Recommendations](https://arxiv.org/pdf/2405.11441) | Embedding Utilization                      | T5-small (F) + Mistral-8*22B (N)                | N/A                                                          |
| 2024.5 / arXiv'24   | LEARN     | [Knowledge Adaptation from Large Language Model to Recommendation for Practical Industrial Application](https://arxiv.org/pdf/2405.03988) | Model Initialization                       | Baichuan2-7B (N)                                | N/A                                                          |
| 2024.5 / arXiv'24   | NoteLLM-2 | [NoteLLM-2: Multimodal Large Representation Models for Recommendation](https://arxiv.org/pdf/2405.16789) | Embedding Utilization                      | LLaMA2 (F) / QWen (F)                           | N/A                                                          |
| 2024.5 / arXiv'24   | SLMRec    | [SLMRec: Empowering Small Language Models for Sequential Recommendation](https://arxiv.org/pdf/2405.17890) | Model Distillation                         | LLaMA-7B (F)                                    | N/A                                                          |
| 2024.6 / FCS'24     | Laser     | [Large Language Models Make Sample-Efficient Recommender Systems](https://arxiv.org/pdf/2406.02368) | Embedding Utilization                      | Mistral-7B (F) / Vicuna-7B (F) / Vicuna-13B (F) | N/A                                                          |
| 2024.6 / CIKM'24    | LLM4MSR   | [LLM4MSR: An LLM-Enhanced Paradigm for Multi-Scenario Recommendation](https://arxiv.org/pdf/2406.12529) | Embedding Guidance                         | ChatGLM-6B (N)                                  | [Link](https://anonymous.4open.science/r/LLM4MSR/)           |
| 2024.6 / arXiv'24   | TSLRec    | [A Practice-Friendly Two-Stage LLM-Enhanced Paradigm in Sequential Recommendation](https://arxiv.org/pdf/2406.00333) | Model Initialization                       | LLaMA-13B (F)                                   | N/A                                                          |
| 2024.7 / arXiv'24   | AlphaRec  | [Language Models Encode Collaborative Signals in Recommendation](https://arxiv.org/pdf/2407.05441) | Embedding Utilization                      | text-embedding-3-large (N)                      | [Link](https://github.com/LehengTHU/AlphaRec)                |
| 2024.8 / arXiv'24   | DaRec     | [DaRec: A Disentangled Alignment Framework for Large Language Model and Recommender System](https://arxiv.org/pdf/2408.08231) | Embedding Guidance                         | GPT-3.5 (N) + text-embedding-ada-002 (F)        | N/A                                                          |
| 2024.8 / RecSys'24  | LARR      | [LARR: Large Language Model Aided Real-time Scene Recommendation with Semantic Understanding](https://arxiv.org/pdf/2408.11523) | Embedding Utilization / Embedding Guidance | Baichuan-7B (F)                                 | N/A                                                          |
| 2024.9 / arXiv'24   | Flare     | [FLARE: Fusing Language Models and Collaborative Architectures for Recommender Enhancement](https://arxiv.org/pdf/2409.11699) | Embedding Utilization                      | mT5 (N)                                         | N/A                                                          |
| 2024.9 / arXiv'24   | HLLM      | [HLLM: Enhancing Sequential Recommendations via Hierarchical Large Language Models for Item and User Modeling](https://arxiv.org/pdf/2409.12740) | Embedding Utilization                      | TinyLLaMA-1.1B (F) / Baichuan2-7B (F)           | [Link](https://github.com/bytedance/HLLM)                    |
| 2024.9 / arXiv'24   | LLMEmb    | [Large Language Model Empowered Embedding Generator for Sequential Recommendation](https://arxiv.org/pdf/2409.19925) | Embedding Initialization                   | LLaMA-7B (F)                                    | [Link](https://github.com/liuqidong07/LLMEmb)                |



Beside, we also conclude existing surveys about Large Language Model for Recommender Systems as follows.

## LLM4RS Survey

| Date / Venue       | Paper                                                        | Institution                                 | Repo                                                       |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------- | ---------------------------------------------------------- |
| 2023.6 / WWWJ'24   | [A Survey on Large Language Models for Recommendation](https://arxiv.org/pdf/2305.19860) | USTC, BOSS, HKUST                           | [Link](https://github.com/WLiK/LLM4Rec-Awesome-Papers)     |
| 2023.6 / TOIS'24   | [How Can Recommender Systems Benefit from Large Language Models: A Survey](https://arxiv.org/pdf/2306.05817) | SJTU, Noah's Ark                            | [Link](https://github.com/CHIANGEL/Awesome-LLM-for-RecSys) |
| 2023.7 / TKDE'24   | [Recommender Systems in the Era of Large Language Models (LLMs)](https://ieeexplore.ieee.org/abstract/document/10506571) | PolyU, NUDT, Amazon, CityU, MSU             | N/A                                                        |
| 2023.7 / WWWJ'24   | [When Large Language Models Meet Personalization: Perspectives of Challenges and Opportunities](https://link.springer.com/content/pdf/10.1007/s11280-024-01276-1.pdf) | HKUST, BAAI, USTC, UESTC                    | N/A                                                        |
| 2024.9 / COLING'24 | [Large Language Models for Generative Recommendation: A Survey and Visionary Discussions](https://arxiv.org/pdf/2309.01157) | HKBU, Rutgers                               | N/A                                                        |
| 2024.2 / arXiv'24  | [Foundation Models for Recommender Systems: A Survey and New Perspectives](https://arxiv.org/pdf/2402.11143) | UNSW, Adobe, Gatech, ETH, CSIRO, UCSD       | N/A                                                        |
| 2024.3 / arXiv'24  | [Exploring the Impact of Large Language Models on Recommender Systems: An Extensive Review](https://arxiv.org/pdf/2402.18590) | SCU, Stanford, CMU                          | N/A                                                        |
| 2024.4 / arXiv'24  | [A Survey of Generative Search and Recommendation in the Era of Large Language Models](https://arxiv.org/pdf/2404.16924) | PolyU, NUS, USTC, CAS, HIT                  | N/A                                                        |
| 2024.6 / arXiv'24  | [Survey for Landing Generative AI in Social and E-commerce Recsys – the Industry Perspectives](https://arxiv.org/pdf/2406.06475) | Linkdin, Amazon, Tiktok, Rutgers, Microsoft | N/A                                                        |
| 2024.7 / arXiv'24  | [All Roads Lead to Rome: Unveiling the Trajectory of Recommender Systems Across the LLM Era](https://arxiv.org/pdf/2407.10081) | Noah's Ark                                  | N/A                                                        |

