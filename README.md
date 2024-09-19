# Awesome LLM-Enhanced Recommender Systems

## 1. Knowledge Enhancement

| Date / Venue | Model (Paper Link) | Knowledge Type        | Foundation Model (Finetuned/Non-finetuned) | Code |
| ------------ | ------------------ | --------------------- | ------------------------------------------ | ---- |
|              |                    | Summarize / KG / Both |                                            |      |
|              |                    |                       |                                            |      |
|              |                    |                       |                                            |      |

## 2. Interaction Enhancement

| Date / Venue      | Model    | Paper                                                                                                                                                 | Generation Method | Foundation Model (Finetuned/Non-finetuned) | Code                                 |
| ----------------- | -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------ | ------------------------------------ |
| 2023.6 / WSDM'24  | LLMRec   | [LLMRec: Large Language Models with Graph Augmentation for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3616855.3635853)                           | Text-based        | GPT-3.5 + text-embedding-ada-002 (N)       | [Link](https://github.com/HKUDS/LLMRec) |
| 2024.1 / arXiv'24 | LlamaRec | [Integrating Large Language Models into Recommendation via Mutual Augmentation and Adaptive Aggregation](https://arxiv.org/pdf/2401.13870)               | Text-based        | LLaMA2-7B (F)                              | N/A                                  |
| 2024.2 / arXiv'24 | LLM-InS  | [Large Language Model Interaction Simulator for Cold-Start Item Recommendation](https://arxiv.org/pdf/2402.09176)                                        | Score-based       | LLaMA2 (F)                                 | N/A                                  |
| 2024.2 / WWW'24   |          | [Large Language Models as Data Augmenters for Cold-Start Item Recommendation](https://dl.acm.org/doi/pdf/10.1145/3589335.3651532)                        | Text-based        | PaLM2 (N)                                  | N/A                                  |
| 2024.8 / arXiv'24 | LLMDSR   | [LLM4DSR: Leveraing Large Language Model for Denoising Sequential Recommendation](https://arxiv.org/pdf/2408.08208)                                      | Score-based       | LLaMA3-8B (F)                              | N/A                                  |
| 2024.8 / KDD'24   |          | [Optimizing Novelty of Top-k Recommendations using Large Language Models and Reinforcement Learning](https://dl.acm.org/doi/pdf/10.1145/3637528.3671618) | Text-based        | GPT-3.5 (N)                                | N/A                                  |
| 2024.9 / arXiv'24 | LLMHD    | [Large Language Model Enhanced Hard Sample Identification for Denoising Recommendation](https://arxiv.org/pdf/2409.10343)                                | Text-based        | GPT-3.5 (N)                                | N/A                                  |

## 3. Model Enhancement

| Date / Venue | Model (Paper Link) | Integration Type | Foundation Model (Finetuned/Non-finetuned) | Code |
| ------------ | ------------------ | ---------------- | ------------------------------------------ | ---- |
|              |                    |                  |                                            |      |
|              |                    |                  |                                            |      |
|              |                    |                  |                                            |      |

### The weaknesses of existing LLM4Rec Surveys

1. Most current surveys focus on investigating how to use the LLM as RS, while ignoring the aspect of enhancement.
2. The surveys do not include most up-to-date papers, because this field is developing fastly.
3. We categorize the LLM enhanced RS papers from technical view, which may be more practical.

华为的两篇survey和我们的稍微有重合，但是很少。他们还是从LLM本身出发，但是我们需要提

All Roads Lead to Rome: Unveiling the Trajectory of Recommender Systems Across the LLM Era

How Can Recommender Systems Benefit from Large Language Models: A Survey
