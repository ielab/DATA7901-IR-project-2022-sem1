# Subproject 6 - Multi-Modal Vector-PRF (Rocchio)

## Overview
Pseudo-relevance feedback (PRF) aims to reduce the effect of query-passage vocabulary mismatch and thus improve search effectiveness by modifying the original query using information from top-ranked passages.
Instead of using texts to perform PRF in the classic way, a new research has proposed the Vector-PRF, which utilises the embeddings produced by Dense Retrievers, then fuse the top-k result vectors for each query from the initial retrieval results with the query vectors together to form a new query vector. This approach has shown great improvements on several datasets with a high efficiency. For the image retrieval task, images are also represented as embeddings, therefore, it is interesting to apply the Vector-PRF in this task and analyze the performance.


## Core Tasks

- obtain code and FAISS index for Vector PRF on TREC DL; reproduce results, make sure it works
- obtain code etc for CLIP, reproduce results, make sure it works
- bundle CLIP with Vector PRF; run it evaluate it, analyse results — how do parameters influence performance?
- [extension] could try more datasets or models, such as [X-VLM](https://arxiv.org/pdf/2111.08276v2.pdf)


## Code
1. [CLIP](https://github.com/openai/CLIP)
2. [Vector-PRF](https://github.com/hanglics/Neural-Relevance-Feedback-Public)


## Key Papers

1. Li, H., Mourad, A., Zhuang, S., Koopman, B., & Zuccon, G. (2022) [Pseudo Relevance Feedback with Deep Language Models and Dense Retrievers: Successes and Pitfalls](https://hangli.me/files/li-tois-2021.pdf). Accepted at ACM Transactions on Information Systems (TOIS).

