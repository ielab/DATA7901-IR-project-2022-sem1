# Subproject 5 - Effectiveness/Efficiency/Space Trade-Off of Pseudo-Relevance Feedback

## Overview
Pseudo-relevance feedback (PRF) aims to reduce the effect of query-passage vocabulary mismatch and thus improve search eectiveness by modifying the original query using information from top-ranked passages. PRF has been widely investigated in the context of traditional bag-of-words retrieval models. The use of the PRF process in the context of dense retrievers has seen some initial work. Common drawbacks of these PRF methods are that: (1) the encoder used for the PRF signal is based on large pre-trained language models like BERT (for ColBERT-PRF, RepBERT-PRF) and RoBERTa (for ANCE-PRF), rendering this encoder quite large in size (e.g., 503.4 MB for ANCE-PRF); and (2) the PRF signal given as input to the PRF encoder is often represented as text and thus requires expensive BERT inference operations to perform the PRF process, especially if CPUs, rather than GPUs, are used. The computational cost of a BERT inference grows as the size of the input grows. Thus the encoding of the query text plus the text of several passages is far more time consuming than the encoding the query alone. Therefore, a thorough analysis of the effectiveness/efficiency/space trade-off of PRF methods with deep language models is necessary, this is useful in a resource constrained environment such as that of cheap cloud instances or embedded systems (e.g., smartphones and smartwatches), where memory and CPU are limited and GPUs are not present.


## Core Tasks

- obtain code and FAISS index of ANCE-PRF, x_PRF (From Hang's Reproducibility Paper), re-run their pipelines, evaluate the effectiveness, efficiency, and space to form the original table
- perform deeper investigations of the trade-offs of these models
- [extension] investigate methods to reduce size/latency of trained PRF methods (e.g. Knowledge Distillation, Negative Sampling, etc.) 


## Key Papers

1. Yu, H., Xiong, C., & Callan, J. (2021, August). [Improving Query Representations for Dense Retrieval with Pseudo Relevance Feedback.](https://arxiv.org/abs/2108.13454) In Proceedings of CIKM 2021.
2. Li, H., Zhuang, S., Mourad, A., Ma, X., Lin, J., & Zuccon, G. (2021, December). [Improving Query Representations for Dense Retrieval with Pseudo Relevance Feedback: A Reproducibility Study.](https://arxiv.org/abs/2112.06400) In Proceedings of ECIR 2021.
3. Wang, X., Macdonald, C., Tonellotto, N., & Ounis, I. [Pseudo-Relevance Feedback for Multiple Representation Dense Retrieval](https://arxiv.org/pdf/2106.11251.pdf) In Proceedings of SIGIR 2021.
4. Gou, J., Yu, B., Maybank, S., & Tao, D. [Knowledge Distillation: A Survey](https://arxiv.org/abs/2006.05525) In International Journal of Computer Vision (2021).
5. Zhan, J., Mao, J., Liu, Y., Guo, J., Zhang, M., & Ma, S. (2021, July). [Optimizing dense retrieval model training with hard negatives.](https://arxiv.org/abs/2104.08051) In Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 1503-1512).

