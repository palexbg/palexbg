## Hi there 👋

<!--
**palexbg/palexbg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Selected projects in AI Systems and Information Retrieval

- **LLM-based Fusion of Multi-modal Features for Commercial Memorability Prediction** (2025)
  - Paper (in progress) | [Code](https://github.com/dsgt-arc/mediaeval-2025-memorability) (in progress) 
  - Proposed a multimodal fusion system using a Gemma-3 LLM, fine-tuned with LoRA, to predict commercial and brand memorability scores for the [Mediaeval 2025 challenge](https://multimediaeval.github.io/editions/2025/tasks/memorability/).
  - The system fuses pre-computed visual (ViT) and textual (E5) features via trainable linear projections and guided by novel LLM-generated rationales that provide expert-like qualitative analysis of the video's content.

- **Multilingual Claim-Normalisation RAG** (2025)
  - [Paper](https://arxiv.org/abs/2508.17402) | [Code](https://github.com/dsgt-arc/checkthat-2025-claims)
  - Published for [CLEF CheckThat! 2025 (Task 2)](https://checkthat.gitlab.io/clef2025/task2/).
  - We propose a retrieval-first, LLM-backed pipeline for claim normalization, a critical second step in automated fact-checking systems that follows claim retrieval. 
  - By dynamically prompting GPT-4o-mini or retrieving close matches in the training data, the system achieved first place in 7 out of 13 monolingual language tracks.

- **Numerical Claim Veracity Classifier** (2025)
  - [Paper](https://arxiv.org/pdf/2507.06195) | [Code](https://github.com/dsgt-arc/checkthat-2025-numerical)
  - Published for [CLEF CheckThat! 2025 (Task 3)](https://checkthat.gitlab.io/clef2025/task3/), and presented at [CLEF 2025 conference](https://clef2025.clef-initiative.eu/).
  - This study evaluated modeling strategies for veracity prediction of numerical and temporal claims using a hybrid BM25 sparse retriever, transformer reranker, and a long-context BERT-based veracity classifier (ModernBERT). 
  - The system achieved a 4/11 position in the English language track.

- **Temporal Performance Analysis in Web Search** (2025) 
  - [Paper](https://arxiv.org/pdf/2507.08360) | [Code](https://github.com/dsgt-arc/longeval-2025)
  - Published for [CLEF LongEval 2025 (Task 1)](https://clef-longeval.github.io/tasks/).
  - We propose a two-phase information retrieval pipeline (sparse retrieval & reranking) to assess temporal performance in web search systems, employing sparse keyword searches, query expansion, and document reranking
  - We also perform topic modeling of the underlying web searches over time.

- **Quantum Annealing for Machine Learning Research** (2025)
  - [Paper](https://arxiv.org/pdf/2507.15063?) | [Code (Task 1)](https://github.com/dsgt-arc/qclef-2025-feature) | [Code (Task 2)](https://github.com/dsgt-arc/qclef-2025-instance) | [Code (Task 3)](https://github.com/dsgt-arc/qclef-2025-clustering)
  - Published for [QuantumCLEF 2025](https://qclef.dei.unipd.it/clef2025-lab) and presented at [CLEF 2025 conference](https://clef2025.clef-initiative.eu/).
  - Our work explored Quantum Annealing approaches in 3 classical ML problems: Feature Selection, Instance Selection and Clustering. Quantum Annealing needs to express the ML problem in a Quadratic Unconstrained Binary Optimization (QUBO) form.
  - We explore various such QUBO formulations for the 3 tasks and evaluate the results using D-Wave quantum annealing system. We benchmark our results with a classical Simulated Annealing evaluation. 
  - Our proposed systems achieved good performance and ranking across all tasks. 
