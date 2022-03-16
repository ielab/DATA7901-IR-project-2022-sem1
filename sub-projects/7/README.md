# Subproject 7 - Reproduce ColBERT PRF

## Overview
Pseudo-relevance feedback (PRF) mechanisms expand and reweight the users’ initial query using information occurring in an initial set of retrieved documents. Two different methods for PRF with dense retrievers have emerged in the literature: (1) the use of single embedded representations for each passage and query (e.g. using BERT’s [CLS] token), (2) the use of multiple representations (e.g. using an embedding for each token of the query and document, as in ColBERT-PRF). Approach 1 has attracted the lionshare of attention, while approaches such as ColBERT-PRF has seen only initial investigation. This project will revisit the ColBERT-PRF approach, reproduce the relevant intial work and conduct additional experimentation and analysis.


## Core Tasks

- examine the ColBERT PRF paper to understand the workflow as well as the mechanisms of the method
- implement the pipeline
- create the ColBERT index on TREC DL and other datasets (this is a computationally extensive process)
- reproduce results from the original paper
- Identify and examine other multi-representation Dense retrievers and analyze the results
- [extension] might be interesting to devise a method to improve the efficiency of multi-reprsentation PRF without significantly degrade its effectiveness


## Key Papers

1. Wang, X., Macdonald, C., Tonellotto, N., & Ounis, I. [Pseudo-Relevance Feedback for Multiple Representation Dense Retrieval](https://arxiv.org/pdf/2106.11251.pdf) In Proceedings of SIGIR 2021.

