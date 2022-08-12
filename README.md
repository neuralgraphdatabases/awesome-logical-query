# awesome-logical-query-answering
A collection of resources on the topic of Complex Logical Query Answering

TODO: Insert an image from the paper


## :scroll: Categorization of papers

#### Modalities

- Triple-based KGs
- Hyper-relational KGs
- Hyper-graphs

#### Reasoning Domain

- Discrete (Entities only)
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

#### Modeling

- Pure Neural
- Neural + Geometric
- Neuro-symbolic
- Symbolic

#### Query Patterns

- Fixed patterns from specific datasets
- Arbitrary query DAGs

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

## :wrench: Implementations

- [KGReasoning](https://github.com/snap-stanford/KGReasoning): GQE, Query2Box, BetaE
- [CQD](https://github.com/pminervini/KGReasoning): GQE, Query2Box, BetaE, CQD
- [StarQE](https://github.com/DimitrisAlivas/StarQE): StarQE
- [SMORE](https://github.com/google-research/smore): GQE, Query2Box, BetaE + Very Large Datasets
- [GNN-QE](https://github.com/DeepGraphLearning/GNN-QE): GNN-QE
- [TAR](https://github.com/lilv98/TAR): Former ABIN
- 


