# Subproject 6 - Multi-Modal Vector-PRF (Rocchio)

## Overview
Pseudo-relevance feedback (PRF) aims to reduce the effect of query-passage vocabulary mismatch and thus improve search effectiveness by modifying the original query using information from top-ranked passages. PRF has been widely investigated in the context of traditional bag-of-words retrieval models. The use of the PRF process in the context of dense retrievers has seen some initial work.
This project will focus in particular on the Vector-PRF method for dense retrievers, which utilises the embeddings produced by dense retrievers, then fuses the top-k result vectors for each query from the initial retrieval results with the query vectors to form a new query vector. This approach has shown improvements on several tetx-based datasets with a high efficiency. This project will investigate this method on multimodal datasets, and in particular on datasets that contain images and are queried with text -- both represented as dense vectors.


## Core Tasks

- obtain code and FAISS index for Vector PRF on TREC DL; reproduce results, make sure it works
- obtain code and resources for CLIP, reproduce results, make sure it works
- bundle CLIP with Vector PRF; run it evaluate it, analyse results — how do parameters influence performance?
- [extension] could try more datasets or models, such as [X-VLM](https://arxiv.org/pdf/2111.08276v2.pdf)


## Code
1. [CLIP](https://github.com/openai/CLIP)
2. [Vector-PRF](https://github.com/hanglics/Neural-Relevance-Feedback-Public)


## Key Papers

1. Li, H., Mourad, A., Zhuang, S., Koopman, B., & Zuccon, G. (2022) [Pseudo Relevance Feedback with Deep Language Models and Dense Retrievers: Successes and Pitfalls](https://hangli.me/files/li-tois-2021.pdf). Accepted at ACM Transactions on Information Systems (TOIS).

