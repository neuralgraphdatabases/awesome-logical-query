# awesome-logical-query-answering
A collection of resources on the topic of Complex Logical Query Answering

TODO: Insert an image from the paper


## :scroll: Categorization of papers

#### Modalities


<details>
  <summary>Triple-based KGs (28)</summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  4. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  14. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  15. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  19. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  20. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  21. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  22. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  23. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  24. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  25. [Joint Abductive and Inductive Neural Logical Reasoning](https://arxiv.org/abs/2205.14591), arxiv 2022
  26. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  27. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  28. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

  </details> 

<details>
  <summary>Hyper-relational KGs (1)</summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022

</details>

<details>
  <summary>Hyper-graphs and Multi-modal graphs (0)</summary>

  0. None as of Sept 2022
  
</details>


#### Reasoning Domain


- <details>
    <summary>Discrete (Entities only) (28) </summary>

    - [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
    - [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
    - [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
    - [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
    - [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
    - [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
    - [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
    - [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
    - [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
    - [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
    - [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
    - [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
    - [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
    - [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
    - [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
    - [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
    - [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
    - [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
    - [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
    - [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
    - [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
    - [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
    - [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
    - [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
    - [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
    - [Joint Abductive and Inductive Neural Logical Reasoning](https://arxiv.org/abs/2205.14591), arxiv 2022
    - [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
    - [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  </details>
  - Predict Qualifier Entities for Hyper-Relational KGs (0)
    - None as of Sept 2022
- Discrete Temporal (Entities + Dates) (1)
  - [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
- Discrete + Continuous (Entities + string/numerical Literals) (0)
  - None as of Sept 2022


#### Logical Expressiveness


- <details>
    <summary>EPFO (15) </summary>

    - [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
    - [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
    - [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
    - [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
    - [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
    - [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
    - [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
    - [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
    - [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
    - [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
    - [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
    - [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
    - [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
    - [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
    - [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022

  </details>
- <details>
    <summary>EPFO + Negation queries (11) </summary>

    - [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
    - [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
    - [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
    - [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
    - [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
    - [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
    - [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
    - [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
    - [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
    - [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
    - [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  </details>
- <details>
    <summary>Class / relation axioms (3) </summary>

    - [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
    - [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
    - [Joint Abductive and Inductive Neural Logical Reasoning](https://arxiv.org/abs/2205.14591), arxiv 2022
  </details>


#### Learning

- Transductive
- Inductive (limited)
- Inductive
    - Only target inductive (0)
    - Any node on the reasoning path inductive (2)

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


