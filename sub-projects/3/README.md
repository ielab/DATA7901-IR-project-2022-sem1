# Subproject 3 - Converting Sparse Re-rankers to Retrievers. 

## Overview
This project aims to investigate the adaptation of two BERT-based sparse passage re-rankers proposed by our research group, namely TILDE and TILDEv2, to the passage retrieval setting. Both models have been originally implemented as passage re-rankers, i.e. used to re-rank a pool of candidate passages for a given query. Your task in this project is to convert them into passage retrievers, i.e. retrieve a passage through searching the whole passage sparse index, and evaluate the ranking effectiveness and efficiency.

## Core Tasks

- Obtain code and model checkpoints, re-run our pipelines, evaluate the results accuracy to form the original table.
- Convert the original passage re-ranking setting to passage retrieval setting. Analyse the results and identify errors.
- [extension] Retrain TILDE with more advanced sparsity loss functions and re-evaluate newly trained model on passage retrieval task.



## Key Papers

1. Links to papers can be found in our [TILDE/TILDEv2 github repo](https://github.com/ielab/TILDE).
2. Another sparse passage retriever example [code](https://github.com/luyug/COIL/tree/main/uniCOIL).

