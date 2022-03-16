# Subproject 2 - Investigate the Robustness of DRs on Queries with Typos

## Overview
Dense retrievers (DRs) are effective methods for retrieval; however, they are sensitive to noisy input data. For example, previous work has shown that a single query term containing a typo can dramatically decrese the retrieval effectivness of DRs. This project aims to replicate the previous work, extend their analysis, re-cast the investigation to different typo-settings or typo-settings for another language, such as Chinese or Japanese. 

## Core Tasks

- Obtain code and FAISS index, re-run the original pipelines, evaluate the results accuracy to form the original table.
- Apply different types of typo-queries in addition to the original settings and investigate the robustness of other exsiting BERT-based Dense/Sparse retrievers on typo queries.	
- investigate other datasets, including multi-lingual datasets.
- [extension] Adopt the original typos-aware trainig to the state-of-the-art DRs: this requires understand how the the state-of-the-art DRs to be trained.



## Key Papers

1. Shengyao Zhuang and Guido Zuccon. (2021, November). [Dealing with Typos for BERT-based Passage Retrieval and Ranking.](https://aclanthology.org/2021.emnlp-main.225/) In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing.

