# Subproject 1 - DRs have problems with Entities

## Overview
Dense retrievers (DRs) are effective methods for searching large indexes. Previous work has however identified DRs fail on a specific type of queries: queries that contain entities. This project aims to replicate the previous work, extend their analysis, re-cast the investigation to a more streamlined and common ad-hoc search task on MS MARCO/TREC DL, and investigate whether this finding generalises across different DR methods.


## Core Tasks

- obtain code and FAISS index, re-run their pipelines, evaluate the results accuracy to form the original table
- for a subset of queries, analyse the retrieved passages to identify: (1) are these relevant? (2) do they really mention/not-mention the entity?	
- [extension] extend the original experiments to DRs other than DPR: this requires understand how the DPR index of Wikidata was created, and process this data with other DRs.



## Key Papers

1. Sciavolino, C., Zhong, Z., Lee, J., & Chen, D. (2021, November). [Simple Entity-Centric Questions Challenge Dense Retrievers.](https://arxiv.org/pdf/2109.08535.pdf) In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing (pp. 6138-6148).

