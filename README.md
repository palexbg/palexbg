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
## Current projects

- **Memorability: Predicting movie and commercial memorability**
  - Working on subtask 2 (Commercial/Ad memorability) as part of the [Mediaeval 2025 challenge](https://multimediaeval.github.io/editions/2025/tasks/memorability/)

## Selected projects on Information Retrieval

- **Multilingual Claim-Normalisation RAG**
  - Research submitted to [CLEF CheckThat! 2025 (Task 2)](https://checkthat.gitlab.io/clef2025/task2/) and accepted for publication.
  - We propose a retrieval-first, LLM-backed pipeline for claim normalization, a critical second step in automated fact-checking systems that follows claim retrieval. 
  - By dynamically prompting GPT-4o-mini or retrieving close matches in the training data, the system achieved first place in 7 out of 13 monolingual language tracks.

- **Numerical Claim Veracity Classifier** 
  - [Paper](https://arxiv.org/pdf/2507.06195) | [Code](https://github.com/dsgt-arc/checkthat-2025-numerical)
  - Another research submission to [CLEF CheckThat! 2025 (Task 3)](https://checkthat.gitlab.io/clef2025/task3/), accepted for publication and oral presentation at the [CLEF 2025 conference](https://clef2025.clef-initiative.eu/).
  - This study evaluated modeling strategies for veracity prediction of numerical and temporal claims using a hybrid BM25 sparse retriever, transformer reranker, and a long-context BERT-based veracity classifier (ModernBERT). 
  - The system achieved a 4/11 position in the English language track.

- **Temporal Performance Analysis in Web Search** 
  - [Paper](https://arxiv.org/pdf/2507.08360) | [Code](https://github.com/dsgt-arc/longeval-2025)
  - Submitted to [CLEF LongEval 2025 (Task 1)](https://clef-longeval.github.io/tasks/)  and accepted for publication.
  - We propose a two-phase information retrieval pipeline (sparse retrieval & reranking) to assess temporal performance in web search systems, employing sparse keyword searches, query expansion, and document reranking
  - We also perform topic modeling of the underlying web searches over time.

- **Quantum Annealing for Machine Learning Research**
  - [Paper](https://arxiv.org/pdf/2507.15063?) | [Code (Task 1)](https://github.com/dsgt-arc/qclef-2025-feature) | [Code (Task 2)](https://github.com/dsgt-arc/qclef-2025-instance) | [Code (Task 3)](https://github.com/dsgt-arc/qclef-2025-clustering)
  - Submitted to [QuantumCLEF 2025](https://qclef.dei.unipd.it/clef2025-lab) and accepted for publication and oral presentation.  
  - Our work explored Quantum Annealing approaches in 3 classical ML problems: Feature Selection, Instance Selection and Clustering.
  - Quantum Annealing needs to express the ML problem in a Quadratic Unconstrained Binary Optimization (QUBO) form.
  - We explore various such QUBO formulations for the aforementioned problems and evaluate results using D-Wave quantum annealing system. We benchmark our results with a classical Simulated Annealing evaluation. 
  - Our proposed systems achieved good performance and ranking across all 3 tasks. 