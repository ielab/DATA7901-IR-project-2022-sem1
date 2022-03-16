# Subproject 4 - Multi-lingual DRs

## Overview
Dense retrieval has shown great success for passage ranking in English or monolingual tasks. This still remains a largely unexplored area in a multi-lingual setting. However, recently published datasets, including Mr TyDo and mMarco have given opportunities to test the effectiveness of multi-lingual models. In this project, we aim to replicate previous works, investigate the effectiveness and generalization of different multi-lingual DR models on Mr. TyDi datasets.

## Core Tasks

- Using index from Mr Tydi dataset, replicate their results of bm25, mDPR and hybrid using pyserini
- Redo their analysis, investigate (1) Can you result in the same findings with them? (2) is there more findings you want to show?
- Using mColbert in mMarco, test its effectiveness in Mr. Tydi. What's the difference or similarity in findings with (1)Mr TyDi mDPR (2) mMarco mColbert
- [extension] With more recent works on multi-lingual models (papers 3 and 4), show effectiveness and findings on Mr Tydi Dataset.



## Key Papers

1. Xinyu Zhang, Xueguang Ma, Peng Shi, and Jimmy Lin (2021, November).  [Mr. TYDI: A Multi-lingual Benchmark for Dense Retrieval](https://arxiv.org/abs/2108.08787) In Proceedings of the 1st Workshop on multi-lingual Representation Learning 2021.
2. Luiz Henrique Bonifacio, Vitor Jeronymo, Hugo Queiroz Abonizio, Israel Campiotti, Marzieh Fadaee, Roberto Lotufo and Rodrigo Nogueira (2022 January).  [mMARCO: A multi-lingual Version of the MS MARCO Passage Ranking Dataset](https://arxiv.org/abs/2108.13897)
3. Peng Shi, Rui Zhang, He Bai, and Jimmy Lin (2021, September). [Cross-Lingual Training with Dense Retrieval for Document Retrieval](https://arxiv.org/abs/2109.01628) In Proceedings of the 1st Workshop on multi-lingual Representation Learning 2021.
4. Akari Asai, Xinyan Yu, Jungo Kasai and Hannaneh Hajishirzi (2021, October). [One Question Answering Model for Many Languages with Cross-lingual Dense Passage Retrieval](https://arxiv.org/abs/2107.11976) In Proceedings of NeurIPS 2021.

