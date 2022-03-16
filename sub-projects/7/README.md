# Subproject 7 - Reproduce ColBERT PRF

## Overview
Pseudo-relevance feedback mechanisms, from Rocchio to the relevance models, have shown the usefulness of expanding and reweighting the users’ initial queries using information occurring in an initial set of retrieved documents. Two different dense retrieval families have emerged: the use of single embedded representations for each passage and query (e.g. using BERT’s [CLS] token), or via multiple representations (e.g. using an embedding for each token of the query and document). Previous work have been studying the single embedded representations with PRF, but the ColBERT-PRF is the first work that studies the multiple representations with PRF, therefore, it would be very interesting to reproduce their work and conduct more deeper experiments and analysis.


## Core Tasks

- read the ColBERT PRF paper understand the workflow as well as the mechanism
- implement the pipeline
- obtain ColBERT index on TREC DL and other datasets
- reproduce results
- Try with other multi-representation Dense retrievers and analyze the results
- [extension] might be interesting to devise a method to improve the efficiency without significantly degrade the effectiveness


## Key Papers

1. Wang, X., Macdonald, C., Tonellotto, N., & Ounis, I. [Pseudo-Relevance Feedback for Multiple Representation Dense Retrieval](https://arxiv.org/pdf/2106.11251.pdf) In Proceedings of SIGIR 2021.

