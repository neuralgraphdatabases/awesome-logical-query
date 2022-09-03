# awesome-logical-query-answering
A collection of resources on the topic of Complex Logical Query Answering

TODO: Insert an image from the paper


## :scroll: Categorization of papers

#### Modalities

- Triple-based KGs
  - <details>
        <summary>Expand the list</summary>

        - some text
        - [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
        - [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
        - [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
        - [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf)  
  
    </details> 

- Hyper-relational KGs
  - [StarQE](https://arxiv.org/abs/2106.08166)
- Hyper-graphs and Multi-modal graphs
  - None as of Sept 2022

#### Reasoning Domain

- Discrete (Entities only)
    - predict qualifiers
- Discrete Temporal (Entities + Dates)
- Discrete + Continuous (Entities + string/numerical Literals)


#### Logical Expressiveness

- EPFO
- EPFO + Negation queries
- OWL profiles (+ class / relation axioms)

#### Learning

- Transductive
- Inductive (limited)
- Inductive
    - Only target inductive
    - Any node on the reasoning path inductive

#### Modeling

- Pure Neural
- Neural + Geometric
- Neuro-symbolic
- Symbolic

#### Query Patterns

- Fixed patterns from specific datasets
- Arbitrary query DAGs
- Extended query DAGs (e.g., mpqe/StarQE extensions)
- Allowing cycles
- Arbitrary query shapes

### Query Operators

- JOIN (intersection)
- UNION 
- NOT (negation)
- FILTER over discrete outputs (filtering entities)
- FILTER over discrete + continuous outputs (+ filtering literals)
- AGGREGATIONS (GROUP BY, ORDER BY, etc)

#### Return Type (Projections)

- Final node only
- Arbitrary non-anchor nodes

#### Training

- End-to-end trainable
- Inference-only (decoders)

#### Metrics

- Generalization: predicting hard answers (MRR / Hits@k)
- Generalization: from ranking to binary classification
- Entailment: faithfulness - ability to recover easy answers (no link prediction) (MRR / Hits@k)
- Estimating the cardinality of answer set size (Spearman's rank correlation, MAPE)
- Predicting easy answers before hard answers (ROC-AUC)


## 📈 Datasets and Benchmarking

### BetaE Datasets

- FB15k
- FB15k237
- NELL995

### Query2Box Datasets

- FB15k
- FB15k237
- NELL995

### Type-Aware Datasets

- TODO
- TODO
- YAGO 4 (Abductive), introduced in [TAR](https://github.com/lilv98/TAR)
- DBpedia (Abductive), introduced in [TAR](https://github.com/lilv98/TAR)

### Inductive Datasets

### Very Large Datasets

### Dataset tools

- [Graph Query Sampler](https://github.com/miselico/graph_query_sampler): Not a method, rather a dataset generator


## :wrench: Implementations

- [KGReasoning](https://github.com/snap-stanford/KGReasoning): GQE, Query2Box, BetaE
- [CQD](https://github.com/pminervini/KGReasoning): GQE, Query2Box, BetaE, CQD
- [StarQE](https://github.com/DimitrisAlivas/StarQE): StarQE
- [SMORE](https://github.com/google-research/smore): GQE, Query2Box, BetaE + Very Large Datasets
- [GNN-QE](https://github.com/DeepGraphLearning/GNN-QE): GNN-QE
- [TAR](https://github.com/lilv98/TAR): Former ABIN


