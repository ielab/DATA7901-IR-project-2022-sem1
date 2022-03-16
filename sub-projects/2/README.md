# Subproject 2 - Investigate the robustness of DRs with typo queries

## Overview
Dense retrievers (DRs) are effective methods for the document retireval task, however, they are sensitive to noisy input data. For example, previous works have shown that a single typo word presented in user query will dramatically decrese the retreival effectivness of DRs. This project aims to replicate the previous work, extend their analysis, re-cast the investigation to a other different typo settings or typo settings in another lanugage, such as Chinese or Japeness. 

## Core Tasks

- Obtain code and FAISS index, re-run their pipelines, evaluate the results accuracy to form the original table.
- Apply different types of typo queries in addition to the original settings and investigate the robustness of other exsiting BERT-based Dense/Sparse retrievers on typo queries.	
- [extension] Adopt the original typos-aware trainig to the state-of-the-art DRs: this requires understand how the the state-of-the-art DRs to be trained.



## Key Papers

1. Shengyao Zhuang and Guido Zuccon. (2021, November). [Dealing with Typos for BERT-based Passage Retrieval and Ranking.](https://aclanthology.org/2021.emnlp-main.225/) In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing.

