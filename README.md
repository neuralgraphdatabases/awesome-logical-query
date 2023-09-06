# Complex Logical Query Answering & Neural Graph Databases #

<p align="center">
  <a href="https://arxiv.org/abs/2303.14617"><img src="http://img.shields.io/badge/Paper-PDF-red.svg"></a>
  <a href="https://mgalkin.medium.com/neural-graph-databases-cc35c9e1d04f"><img src="https://img.shields.io/badge/Blog-Medium-03a87c"></a>
  <a href="https://www.ngdb.org/">
      <img src="https://img.shields.io/badge/Project-website-blue"></a>
</p>

A collection of resources on the topic of Complex Logical Query Answering accompanying the paper [Neural Graph Reasoning: Complex Logical Query Answering Meets Graph Databases](https://arxiv.org/abs/2303.14617). 
Feel free to open PRs and issues to add new papers, datasets, and implementations!

This repo follows the Neural Query Engine taxonomy proposed in the paper (Figure 9).

![hierarchy](asset/tree.png)

## :scroll: Categorization of papers

### Graphs | Modalities


<details>
  <summary>Triple-based KGs (43)</summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019
  4. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  5. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  6. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  7. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  8. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  9. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021
  10. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  11. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  12. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  13. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  14. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  15. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  16. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  17. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  18. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  19. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  20. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  21. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  22. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  23. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  24. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  25. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  26. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
  27. [TeMP](https://arxiv.org/abs/2205.00782), arxiv 2022
  28. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  29. [TFLEX](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  30. [GNNQ](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022
  31. [ENeSy](https://arxiv.org/pdf/2209.08779.pdf), NeurIPS 2022
  32. [NodePiece-QE](https://arxiv.org/abs/2210.08008), NeurIPS 2022
  33. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  34. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022
  35. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  36. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022
  37. [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l), ICLR 2023
  38. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  39. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  40. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  41. [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
  42. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  43. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023


  </details> 

<details>
  <summary>Hyper-relational KGs (2)</summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  2. [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023

</details>

<details>
  <summary>Hyper-graphs and Multi-modal graphs (0)</summary>

  0. None as of March 2023
  
</details>


### Graphs | Reasoning Domain


<details>
  <summary>Discrete (Entities only) (45) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019
  4. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  5. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  6. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  7. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  8. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  9. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021
  10. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  11. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  12. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  13. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  14. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  15. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  16. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  17. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  18. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  19. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  20. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  21. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  22. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  23. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  24. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  25. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  26. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  27. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  28. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
  29. [TeMP](https://arxiv.org/abs/2205.00782), arxiv 2022
  30. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  31. [GNNQ](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022
  32. [ENeSy](https://arxiv.org/pdf/2209.08779.pdf), NeurIPS 2022
  33. [NodePiece-QE](https://arxiv.org/abs/2210.08008), NeurIPS 2022
  34. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  35. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022
  36. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  37. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022
  38. [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l), ICLR 2023
  39. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  40. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  41. [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  42. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  43. [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
  44. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  45. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023

</details>
  
<details>
  <summary>Discrete Temporal (Entities + Dates) (1)</summary>

  1. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  
</details>

<details>
  <summary>Discrete + Continuous (Entities + string/numerical Literals) (0)</summary>

  0. None as of March 2023
  
</details>



### Graphs | Background Semantics

<details>
  <summary>Facts-only (ABOX) (41) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  8. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021
  9.  [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  11. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  12. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  13. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  14. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  15. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  19. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  20. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  21. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  22. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  23. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  24. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  25. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  26. [TFLEX](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  27. [GNNQ](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022
  28. [ENesy](https://arxiv.org/pdf/2209.08779.pdf), NeurIPS 2022
  29. [NodePiece-QE](https://arxiv.org/abs/2210.08008), NeurIPS 2022
  30. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  31. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022
  32. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  33. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022
  34. [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l), ICLR 2023
  35. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  36. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  37. [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  38. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  39. [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
  40. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  41. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023
</details>

<details>
  <summary>Class Hierarchy (3) </summary>

  1. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019
  2. [TeMP](https://arxiv.org/abs/2205.00782), arxiv 2022
  3. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
</details>

<details>
  <summary>Complex axioms (TBOX) (1) </summary>

  1. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
</details>



### Modeling | Encoder 

<details>
  <summary>Shallow Embedding (32) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019 
  3. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019 
  4. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020 
  5. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  6. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  7. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  8. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  9. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021
  10. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  14. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  15. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  18. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  19. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  20. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
  21. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  22. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  23. [TFLEX](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  24. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  25. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022
  26. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  27. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022
  28. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  29. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  30. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  31. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  32. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023

</details>

<details>
  <summary>Transductive Encoder (9) </summary>

  1. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  2. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  3. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  4.  [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  5.  [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  6.  [ENeSy](https://arxiv.org/pdf/2209.08779.pdf) NeurIPS 2022
  7.  [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l) ICLR 2023
  8.  [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  9.  [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
</details>

<details>
  <summary>Inductive Encoder (4) </summary>

  1. (TeMP) [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  2. (GNN-QE) [Neural-Symbolic Models for Logical Queries on Knowledge Graphs](https://arxiv.org/abs/2205.10128), ICML 2022
  3. (GNNQ) [GNNQ: A Neuro-Symbolic Approach for Query Answering over Incomplete Knowledge Graphs](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022
  4. (NodePiece-QE) [Inductive Logical Query Answering in Knowledge Graphs](https://arxiv.org/abs/2210.08008), NeurIPS 2022

</details>


### Modeling | Processor

<details>
  <summary>Any Processor (2) </summary>

  1. [TeMP](https://arxiv.org/abs/2205.00782), arxiv 2022 
  2. [NodePiece-QE](https://arxiv.org/abs/2210.08008), NeurIPS 2022

</details>

<details>
  <summary>End-to-end Neural (15) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019
  4. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  5. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  6. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  7. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  8. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  9. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  10. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  11. [GNNQ](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022
  12. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  13. [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l) ICLR 2023
  14. [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
  15. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023

</details>

<details>
  <summary>Neuro-Symbolic | Geometric (8) </summary>

  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  3. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  4. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021
  5. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  6. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  7. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  8. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022
   
</details>


<details>
  <summary>Neuro-Symbolic | Probabilistic (5) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  3. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  4. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  5. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022

</details>

<details>
  <summary>Neuro-Symbolic | Fuzzy Logic (16) </summary>

  1. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  2. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020   
  3. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  4. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  5. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  6. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
  7. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  8. [TFLEX](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  9. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  10. [ENeSy](https://arxiv.org/pdf/2209.08779.pdf) NeurIPS 2022
  11. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  12. [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  13. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  14. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  15. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023
  16. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023

</details>

### Modeling | Decoder

<details>
  <summary>Non-Parametric (all) </summary>

  All existing models up to March 2023

</details>

<details>
  <summary>Parametric (0) </summary>

  1. None as of March 2023

</details>

### Queries | Query Operators

Progressive scale of supported operators. That is, all models listed under the "NOT" category also support JOIN and UNION.

<details>
  <summary>PROJECTION + JOIN (intersection) (10) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019 
  4. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020
  5. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  6. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  7. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  8. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  9. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  10. [GNNQ](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c), ISWC 2022

</details>

<details>
  <summary> + UNION (9) </summary>

  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  3. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  4. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  5. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  6. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  7. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  8. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  9. [Query2Geom](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), AICS 2022

</details>

<details>
  <summary> + NOT (negation) (22) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  3. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  4. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  5. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  6. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  7. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  8. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  9. [GammaE](https://arxiv.org/pdf/2210.15578.pdf), EMNLP 2022
  10. [NMP-QEM](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022
  11. [TAR](https://arxiv.org/abs/2205.14591), arxiv 2022
  12. [FLEX](https://arxiv.org/abs/2205.11039), arxiv 2022
  13. [TFLEX](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  14. [ENeSy](https://arxiv.org/pdf/2209.08779.pdf), NeurIPS 2022
  15. [SignalE](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM 2022
  16. [QTO](https://arxiv.org/pdf/2212.09567.pdf), arxiv 2023
  17. [LMPNN](https://openreview.net/pdf?id=SoyOsp7i_l), ICLR 2023
  18. [NQE](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  19. [Var2Vec](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI 2023
  20. [CQD A](https://arxiv.org/pdf/2301.12313.pdf), arxiv 2023
  21. [SQE](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023
  22. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  23. [WFRE](https://arxiv.org/pdf/2305.04034.pdf), ACL 2023

</details>

<details>
  <summary> Kleene Plus (1) </summary>

  1. [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021

</details>

<details>
  <summary> FILTER (0) </summary>

  0. None as of March 2023

</details>

<details>
  <summary> AGGREGATIONS (GROUP BY, ORDER BY, etc) (0) </summary>

  0. None as of March 2023

</details>

### Queries | Query Patterns

<details>
  <summary>Tree-structured (47) </summary>

  1. All existing processors as of March 2023

</details>

<details>
  <summary>Arbitrary DAGs (1) </summary>

  1. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023

</details>

<details>
  <summary>Cyclic Queries (1) </summary>

  1. [FIT](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023

</details>


### Queries | Projected Variables

<details>
  <summary> Zero Projected Vars (ASK queries) (0) </summary>

  0. None as of March 2023

</details>

<details>
  <summary> One Projected Variable (all) </summary>

  1. All processors as of March 2023

</details>

<details>
  <summary> Multiple Projected Variables (1) </summary>
 
  1. (EFOk-CQA) [EFOk-CQA: Towards Knowledge Graph Complex Query Answering beyond Set Operation](https://arxiv.org/abs/2307.13701) arxiv 2023

</details>



### Metrics

- Original metrics: ROC AUC and Average Percentile Rank over 1000 negative samples. 
  - Proposed by original [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) (NeurIPS 2018), used by [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), [CGA](https://arxiv.org/pdf/1910.00084.pdf), and [TractOR](https://arxiv.org/pdf/2002.10029.pdf). **Not used after**.
- Generalization: predicting hard answers (MRR / Hits@k).
  - Introduced by [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS) (ICLR 2020). **Standard metric**.
- Generalization: from ranking to binary classification
  - Proposed in [Approximate knowledge graph query answering: from ranking to binary classification](https://arxiv.org/abs/2102.11389)
- Entailment: faithfulness - ability to recover easy answers (no link prediction) (MRR / Hits@k)
  - Proposed by [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) (NeurIPS 2020)
- Estimating the cardinality of answer set size (Spearman's rank correlation, MAPE)
  - Used in [GNN-QE](https://arxiv.org/abs/2205.10128), [QTO](https://arxiv.org/pdf/2212.09567.pdf)
- Predicting easy answers before hard answers (ROC-AUC)
  - Used in [NodePiece-QE](https://arxiv.org/abs/2210.08008)
- Multiple variable queries, (multiply / marginal / joint) x (MRR/ HITs@k)
  - Proposed in [EFOk-CQA](https://arxiv.org/abs/2307.13701) arxiv 2023


## 📈 Datasets and Benchmarking

### Inference (datasets)

<details>
  <summary>Transductive datasets (14) </summary>

  1. (GQE datasets) [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018
  2. (Query2Box datasets) [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  3. (BetaE datasets) [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  4. (Regex datasets) [Regex Queries](https://arxiv.org/abs/2005.00480), AKBC 2021
  5. (BiQE dataset) [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  6. (Query2Onto datasets) [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  7. (EFO-1 dataset) [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925), NeurIPS 2021 (Datasets and Benchmarks)
  8. (Real EFO-1) [On Existential First Order Queries Inference on Knowledge Graphs](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023
  9. (SMORE datasets) [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890), KDD 2022
  10. (StarQE dataset) [Query Embedding on Hyper-relational Knowledge Graphs](https://arxiv.org/abs/2106.08166) ICLR 2022,
  11. (TFLEX dataset) [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  12. (WD50K-NFOL dataset) [NQE: N-ary Query Embedding for Complex Query Answering over Hyper-relational Knowledge Graphs](https://arxiv.org/pdf/2211.13469.pdf), AAAI 2023
  13. (SQE dataset) [Sequential Query Encoding For Complex Query Answering on Knowledge Graphs](https://arxiv.org/pdf/2302.13114.pdf)
  14. (EFOk-CQA) [EFOk-CQA: Towards Knowledge Graph Complex Query Answering beyond Set Operation](https://arxiv.org/abs/2307.13701) arxiv 2023
</details>

<details>
  <summary>Inductive datasets (3) </summary>

  1. (TeMP datasets) [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  2. (InductiveQE datasets) [Inductive Logical Query Answering in Knowledge Graphs](https://arxiv.org/abs/2210.08008) NeurIPS 2022
  3. (GNNQ dataset) [GNNQ: A Neuro-Symbolic Approach for Query Answering over Incomplete Knowledge Graphs](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c) ISWC 2022

</details>

### GQE Datasets

Are Bio and Reddit available at all? Introduced in GQE, used in 4 papers overall (GQE, GQE+hashing, CGA, TractOR).

### BetaE Datasets

The main difference with Query2Box datasets: queries in the BetaE datasets have less than 100 answers. Has queries with negation.

Introduced in [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 2in/3in/inp/pin/pni  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 27,371 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 14,968 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 10,798 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 2in | 3in | inp | pin | pni |
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|---:|----:|---:|---:|---:|
  | FB15k   | 1.7 | 19.6 | 24.4 | 8.0 | 5.2 | 18.3 | 12.5 | 18.9 | 23.8 | 15.9 | 14.6 | 19.8 | 21.6 | 16.9 |
  | FB15k237 | 1.7 | 17.3 | 24.3 | 6.9 | 4.5 | 17.7 | 10.4 | 19.6 | 24.3 | 16.3 | 13.4 | 19.5 | 21.7 | 18.2 |
  | NELL995 | 1.6 | 14.9 | 17.5 | 5.7 | 6.0 | 17.4 | 11.9 | 14.9 | 19.0 | 12.9 | 11.1 | 12.9 | 16.0 | 13.0 | 
  
</details>

### Query2Box Datasets

Introduced in [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020. 

EPFO queries are considered **easier** than BetaE datasets. Doesn't have queries with negations.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p  | others  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 273,710 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 149,689 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 107,982 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|
  | FB15k   | 10.8 | 255.6 | 250.0 | 90.3 | 64.1 | 593.8 | 190.1 | 27.8 | 227.0 | 
  | FB15k237 | 13.3 | 131.4 | 215.3 | 69.0 | 48.9 | 593.8 | 257.7 | 35.6 | 127.7 | 
  | NELL995 | 8.5 | 56.6 | 65.3 | 30.3 | 15.9 | 310.0 | 144.9 | 14.4 | 62.5 | 
  
</details>

### CGA Datasets

GQE-like patterns mined on subsets of DBpedia and Wikidata. The datasets are DB18 and WikiGeo19, introduced in [CGA](https://arxiv.org/pdf/1910.00084.pdf), K-CAP 2019.

**As of Sept 2022: not available**.

### Regex Queries

Queries emulating property paths in SPARQL with variable length of relation paths (up to length 5). Queries are EPFO queries, i.e., no negation.
New operators over relations resemble those from SPARQL:
* $r_1 / r_2 / \dots$ - relational path, aka classic projection queries
* $r_1 \lor r_2$ - a union of decomposed patterns $(e, r_1, ?) \lor (e, r_2, ?)$
* Kleene plus $r^{+}$ - one or more occurence of relation $r$, eg, $r_1/r_2^{+}$ corresponds to $r_1 / r_2$, $r_1 / r_2 / r_2$, $r_1 / r_2 / r_2 / r_2 / \dots$ up to some final depth. Those *can* be cyclic patterns. 

Two datasets:

* FB15k-Regex is based on Freebase, queries have less than 50 answers, 21 query types
* Wiki100-Regex is based on query logs from the official Wikidata SPARQL endpoint, 5 query types. 

Introduced in [RotatE-Box](https://arxiv.org/abs/2005.00480), AKBC 2021.

Repo: [GitHub](https://github.com/dair-iitd/kbi-regex) - no actual data dumps are present :(

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | Wiki100 | 41,291 | 100   | 389,795 | 21,655 | 21,656 | 433,106 |


</details>

<details>
  <summary> Queries </summary>

  #### FB15k-Regex

  | Query type | Train | Valid | Test |
  |-----------:|------:|------:|-----:|
  |  $(e_1, r_1^+, ?)$    | 24,476 | 4,614 | 8,405 |
  |  $(e_1, r_1/r_2, ?)$  | 25,378 | 4,927  | 8,844 |
  | $(e_1, r_1^+/r_2^+, ?)$  | 26,391  | 4,978  | 9,028 |
  | $(e_1, r_1^+/r_2^+/r_3^+, ?)$ | 25,470  | 4,878 | 8,816 |
  | $(e_1, r_1/r_2^+, ?)$  | 26,335 | 5,007 | 9,062 |
  | $(e_1, r_1^+/r_2, ?)$  | 27,614 | 5,229 | 9,429 |
  | $(e_1, r_1^+/r_2^+/r_3, ?)$ | 27,865 | 5,283 | 9,509 |
  | $(e_1, r_1^+/r_2/r_3^+, ?)$ | 26,366 | 5,058 | 9,159 |
  | $(e_1, r_1/r_2^+/r_3^+, ?)$ | 26,366 | 5,045 | 9,099 |
  | $(e_1, r_1/r_2/r_3^+, ?)$   | 26,703 | 5,155 | 9,313 |
  | $(e_1, r_1/r_2^+/r_3, ?)$   | 28,005 | 5,380 | 9,688 |
  | $(e_1, r_1^+/r_2/r_3, ?)$   | 27,884 | 5,338 | 9,632 |
  | $(e_1, r_1\lor r_2, ?)$ | 30,080 | 5,828 | 9,664 |
  | $(e_1, (r_1\lor r_2)/r_3, ?)$ | 31,559 | 6,606 | 10,974 |
  | $(e_1, r_1/(r_2\lor r_3), ?)$ | 41,886 | 7,755 | 13,611 |
  | $(e_1, r_1^+\lor r_2^+, ?)$   | 23,109 | 4,469 | 8,367  |
  | $(e_1, (r_1\lor r_2)/r_3^+, ?)$ | 27,658 | 5,738 | 9,711 |
  | $(e_1, (r_1^+\lor r_2^+)/r_3, ?)$ | 24,462 | 4,865 | 8,863 |
  | $(e_1, r_1^+/(r_2\lor r_3), ?)$ | 27,676 | 5,340 | 9,267 |
  | $(e_1, r_1/(r_2^+\lor r_3^+), ?)$ | 28,542 | 5,475 | 9,436 |
  | $(e_1, (r_1\lor r_2)^+, ?)$  | 26,260 | 5,523 | 10,360 |
  |  **Total**                   | 580,085 | 112,491 | 200,237 |


  #### Wiki100-Regex

  | Query type | Train | Valid | Test |
  |-----------:|------:|------:|-----:|
  |  $(e_1, r_1^+, ?)$    | 490,562 | 24,878 | 23,443 |
  | $(e_1, r_1^+/r_2^+, ?)$  | 6,945  | 620  | 772 |
  | $(e_1, r_1/r_2^+, ?)$  | 85,253 | 10,013 | 8,377 |
  | $(e_1, r_1\lor r_2, ?)$ | 274,012 | 14,900 | 14,915 |
  | $(e_1, (r_1\lor r_2)^+, ?)$  | 348,274 | 15,720 | 15,311 |
  |  **Total**                   | 1,205,046 | 66,131 | 62,818 |

</details>

### DAG Queries

Conjunctive queries (w/o union) not limited to 9 patterns from Query2Box/BetaE datasets. The task is to predict *all* intermediate entities, not just final leaf nodes. Query depth: 2-5; max 3 intersecting branches.

Introduced in [Answering complex queries in knowledge graphs with bidirectional sequence encoders](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021.

New FB15K-237-CQ and WN18RR-CQ datasets have two variations:
* CQ (conjunctive queries) - Training on triples + paths + DAGs, Validation/Test on **DAGs only**;
* Paths - Training on triples + paths, Validation/Test on **paths only**

**Sept 2022: the datasets are not publicly available.**

<details>
  <summary> Graphs </summary>
  
  | Dataset | FB15K-237-CQ | FB15K-237-CQ | FB15K-237-CQ | WN18RR-CQ | WN18RR-CQ | WN18RR-CQ |
  |-----|----:|----:|----:|----:|----:|----:|
  | Dataset | Train | Validation | Test | Train | Validation | Test |
  | Entities | 14,505 | - | - | 40,943 | - | - |
  | Relations | 237 | 237 | 237 | 11 | 11 | 11 |
  | Triples  | 272,115 | - | - | 86,835 | - | - |
  | Paths | 50,000 | - | - | 10,000 | - | - |
  | DAGs | 48,865 | 2,785 | 2,599 | 9,465 | 112 | 95 |
  | Avg Masks | 1.86 | 5.91 | 6.05 | 1.84 | 5.13 | 4.91 |
  | Avg Query Len (Tokens) | 152 | 460 | 479 | 71 | 198 | 199 |   


</details>

<details>
  <summary> Queries </summary>
  
  No detailed breakdown by query type is available, only the DAGs stats from the main table.

  | Dataset | FB15K-237-CQ | FB15K-237-CQ | FB15K-237-CQ | WN18RR-CQ | WN18RR-CQ | WN18RR-CQ |
  |-----|----:|----:|----:|----:|----:|----:|
  | Dataset | Train | Validation | Test | Train | Validation | Test |
  | Paths | 50,000 | - | - | 10,000 | - | - |
  | DAGs | 48,865 | 2,785 | 2,599 | 9,465 | 112 | 95 |
  | Avg Masks | 1.86 | 5.91 | 6.05 | 1.84 | 5.13 | 4.91 |
  | Avg Query Len (Tokens) | 152 | 460 | 479 | 71 | 198 | 199 | 

</details>

###  EFO-1 Queries

Existential First-Order queries  with Single Free Variable, extended from BetaE. The goal is to evaluate the combinatorial generalizability. 

Introduced in [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925), NeurIPS 2021 (Datasets and Benchmarks)

<details>
  <summary> Graphs </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 2in/3in/inp/pin/pni  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 27,371 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 14,968 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 10,798 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Queries </summary>

Cannot list all the 301 query types. Details can be found in a summarization excel file [here](https://docs.google.com/spreadsheets/d/18RJL1puHpbGZJKLkffqKEbzRmRFdSnGFQvekApFWc3Q/edit?usp=sharing).

</details>

### Real EFO-1 dataset

Rethinking the EFO-1 formulation by introducing leaf nodes, multi edge, and cycle.
For standard FB15k, FB15k-237, and NELL - 9 new query types (10 with reworked `pni` type) including:
-  `l` - queries with existentially quantified variables as leaf nodes (2il, 3il)
-  `m` - queries with multiple relation projection edges from one variable to another (2m, 2nm, 3mp, 3pm, im)
-  `c` - queries with cycles (3c, cm)

All new query have 5000 instances in three KGs. Introduced in [On Existential First Order Queries Inference on Knowledge Graphs](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023. The dataset can be downloaded from [here](https://drive.google.com/drive/folders/17bPr6_ESqh5D0LgWNgpE4mY8gpg2iC5o?usp=sharing).

#### EPFO queries with Literals

Based on a variation of the FB15k-237 dataset with entity attributes (12,390 entities, 237 relations, 115 attributes, 29,229 (?) triples).
Literals are restricted to numerical values, three additional filter functions (less than, equal, greater then).

The dataset includes standard 9 EPFO query types and adds 8 more variations of those patterns enriched with literals:
- 5 query types where literals are in queries, but the answer is an entity (ai, 2ai, pai, aip, au)
- 3 query types where literals are in queries, and the answer is a mean of relevant literal values (1ap, 2ap, 3ap)

Introduced in [LitCQD: Multi-Hop Reasoning in Incomplete Knowledge Graphs with Numeric Literals](https://arxiv.org/pdf/2304.14742.pdf), arxiv 2023

###  SQE Queries

Existential First-Order queries aimed at evaluating compositional generalization to OOD query patterns (29 in-distribution types, 29 out-of-distribution). In contrast to BetaE datasets, does **not** have restrictions on the number of answers per query, long tails are possible.  

Introduced in [Sequential Query Encoding For Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2302.13114)

<details>
  <summary> Graphs </summary>

  | Queries | Training | Training |  Validation | Test |
  |---------|---------:|-----------:|-----:|---------:|
  | Dataset | 1p | others  | all | all |
  | FB15k    | 273,710 | 821,130 | 8,000 | 8,000 |
  | FB15k237 | 149,689 | 449,067 | 5,000 | 5,000 |
  | NELL995  | 107,982 | 323,946 | 4,000 | 4,000 | 

</details>

<details>
  <summary> Queries </summary>

58 query types, refer to Appendix A in the paper for the full list of patterns.

</details>

### EFOk queries

Introduced by (EFOk-CQA) [EFOk-CQA: Towards Knowledge Graph Complex Query Answering beyond Set Operation](https://arxiv.org/abs/2307.13701) with 741 query types in total.

Featured by:
- existential first-order queries with more than multiple variables.
- combinatorial space with multi-edge and cyclic queries


### Type-Aware Datasets

In addition to a normal graph of entities (instances) a-la BetaE datasets, the type-aware datasets offer an additional set of classes, classes hierarchy (from a pre-existing ontology), and `instanceOf` links between entities and classes.

Those datasets might include an additional task of predicting types of answer entities (Concept Retrieval).

- LUBM, introduced in [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm), OpenReview 2021
- NELL, introduced in [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm), OpenReview 2021. The base graph is the same as in the BetaE datasets, but a few ontological axioms were added.
- YAGO 4, introduced in [TAR: Neural Logical Reasoning across TBox and ABox](https://github.com/lilv98/TAR)
- DBpedia, introduced in [TAR: Neural Logical Reasoning across TBox and ABox](https://github.com/lilv98/TAR)

LUBM and NELL employ ontological axioms of the DL-Lite (R) family of Description Logics.

<details>
  <summary> Graphs </summary>

  **TODO** Figure out Concept Retrieval edges in TAR 
  
  | Dataset | Entities | Relations | Axioms | Base Graph | Materialized Graph | 
  |-----|----:|----:|----:|----:|----:|
  | LUBM | 55,684 | 28 | 68 | 284k | 565k | 
  | NELL | 63,361 | 400 | 307 | 285k | 497k | 

  Axioms breakdown in ontologies for LUBM and NELL

  | Rules | LUBM | NELL | 
  |------:|-----:|-----:|
  | $\mathcal{O}$ (Total) |  68  | 307  |
  | $A \sqsubseteq A'$ (Subclass) | 13 | - |
  | $p \sqsubseteq s$ | 5 | 92 |
  | $p^{-} \sqsubseteq s$ | 28 | 215 |
  | $\exists p \sqsubseteq A$ | 11 | - |
  | $\exists p^{-} \sqsubseteq A$ | 11 | - |



  | Dataset | Entities | Relations | Classes | Training Edges | Validation Edges | Test Edges | Entity-Class Edges | Class Hierarchy Edges | Total Edges |
  |-----|----:|----:|----:|----:|----:|----:|---:|---:|---:|
  | YAGO 4 | 32,465 | 75 | 8,382 | 101,417 | 1,000 | 1,000 | 83,291 | 16,644 | 184,708 |
  | DBpedia | 28,824 | 327 | 981 | 136,821 | 1,000 | 1,000 | 225,436 | 2,582 | 362,257 |
  


</details>

<details>
  <summary> Queries </summary>
  
  | Dataset | Train / Test | 1p | 2p | 3p | 2i | 3i | ip | pi | 2u | up |
  |--------:|-------------:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
  | LUBM    | Plain (**Train**)| 110,000 | 110,000 | 110,000 | 110,000 | 110,000 | - | - | - | - |
  | LUBM    | Generalized (**Train**)| 117,124 | 136,731 | 150,653 | 181,234 | 208,710 | - | - | - | - | 
  | LUBM    | Specialized (**Train**)| 117,780 | 154,851 | 173,678 | 271,532 | 230,085 | - | - | - | - | 
  | LUBM    | Ontological (**Train**)| 116,893 | 166,159 | 333,406 | 212,718 | 491,707 | - | - | - | - |
  | LUBM    | Induction (w/ missing links in queries) (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 
  | LUBM    | Deduction (w/o missing link in training) (**Val/Test**)| 1,241 | 4,701 | 6,472 | 3,829 | 4,746 | 7,393 | 7,557 | 4,986 | 7,122 |
  | LUBM    | Induction + Deduction (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 7,986 | 8,000 |
  | NELL    | Plain (**Train**)| 107,982 | 107,982 | 107,982 | 107,982 | 107,982 | - | - | - | - |
  | NELL    | Generalized (**Train**)| 174,310 | 408,842 | 864,268 | 398,412 | 930,787 | - | - | - | - | 
  | NELL    | Specialized (**Train**)| 174,310 | 419,664 | 906,609 | 401,954 | 936,537 | - | - | - | - | 
  | NELL    | Ontological (**Train**)| 114,614 | 542,923 | 864,268 | 629,144 | 930,787 | - | - | - | - |
  | NELL    | Induction (w/ missing links in queries) (**Val/Test**)| 15,688 | 3,910 | 3,918 | 3,828 | 3,786 | 3,932 | 3,895 |3,940 | 3,966 | 
  | NELL    | Deduction (w/o missing link in training) (**Val/Test**)| 346 | 4,461 | 4,294 | 4,842 | 5,996 | 7,295 | 5,862 | 5,646 | 6,894 |
  | NELL    | Induction + Deduction (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 7,990 | 8,000 |


  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p  | others  | 1p | others | 1p | others |
  | YAGO 4 (Concept Retrieval)    | 189,338 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | YAGO 4 (Entity Only)    | 101,417 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | YAGO 4 (Entity + Instantiations)    | 184,708 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Concept Retrieval)    | 473,924 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Entity Only)    | 136,821 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Entity + Instantiations)    | 362,257 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |



</details>

### Very Large Datasets

Introduced in [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890), KDD 2022.

Training queries are sampled on-the-fly during training due to the huge size of underlying graphs. 

The underlying graphs are FB400k (400K nodes), WikiKG 2 (2.5M nodes) [(from OGB)](https://ogb.stanford.edu/docs/linkprop/#ogbl-wikikg2), and full Freebase (86M nodes)
TODO: confirm with Hongyu the number of validation / test queries.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB400k    | 409,829 | 918 | 1,075,837 | 537,917 | 537,917 | 2,151,671 |
  | WikiKG2 | 2,500,604 | 535   | 16,109,182 | 429,456 | 598,543 | 17,137,181 |
  | Freebase  | 86,054,361 | 14,824  | 304,727,650 | 16,929,318 | 16,929,308 | 338,586,276 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries |  Validation | Validation |  Test | Test |
  |---------|------------:|-----------:|------:|-----:|
  | Dataset |  1p | others | 1p | others |
  | FB400k    | TODO | TODO | TODO | TODO |
  | WikiKG2 | TODO | TODO | TODO | TODO |
  | Freebase  | TODO | TODO | TODO | TODO |

</details>

### Hyper-Relational Datasets

The main difference of hyper-relational datasets is that edges are no longer plain triples $(h, r, t)$ but *statements* (in terms of Wikidata or RDF-Star) $\Big(h, r, t, (q\_{ri}, q\_{ei})\_i\Big)$ with key-value (relation:entity) qualifiers $(q\_{r}, q\_{e})$ over the *main* triple. 
For example, in the statment `(Albert Einstein, educated at, ETH Zurich, (degree, Bachelor))`, the main triple is `Albert Einstein, educated at, ETH Zurich` and its unique qualifier is `(degree, Bachelor)`. 
Qualifiers provide an additional context to the edge - the tail node might change with another qualifier, e.g., `(Albert Einstein, educated at, University of Zurich, (degree, Doctorate))`.

Entities and relations in qualifiers are still legit entities and relations which could be present in main triples. Some entities and relations can be found *only* in qualifiers.

The WD50K dataset has only conjunctive queries (projection + intersection), neither union nor negation.

Introduced in [Query Embedding on Hyper-Relational Knowledge Graphs](https://openreview.net/pdf?id=4rLw09TgRw9), ICLR 2022

The WD50K-NFOL dataset introduced in [NQE: N-ary Query Embedding for Complex Query Answering over Hyper-relational Knowledge Graphs](https://arxiv.org/pdf/2211.13469.pdf)adds unions and negations, as well as possibility of variables at qualifier entity positions. **As of Nov 2022, not openly available)

<details>
  <summary> Graph </summary>

  The original WD50K graph from the [StarE paper](https://aclanthology.org/2020.emnlp-main.596.pdf) by Galkin et al.


  | Dataset | Entities | Relations | Qualifier-only Entities | Qualifier-only Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|----:|----:|
  | WD50K    | 47,156 | 532 | 5460 | 45 | 166,435 | 23,913 | 46,159 | 236,508 |

  32,167 edges have at least one key-value (relation:entity) qualifier.
 

</details>

<details>
  <summary> Queries </summary>

  | Split | 1p | 2p | 3p | 2i | 3i | ip | pi |
  |-----|----:|----:|----:|----:|----:|----:|----:|
  | train | 24,819 | 313,088 | 5,950,990 | 48,513 | 318,735 | 306,022 | 1,088,539 |
  | validation | 4,100 | 100,706 | 2,968,315 | 15,648 | 169,195 | 169,438 | 569,957 |
  | test  | 7,716 | 202,045 | 6,433,476 | 38,207 | 547,272 | 445,007 | 1,267,452 |

  WD50K-NFOL stats are not yet available

</details>

### Inductive Datasets

As of March 2023, there are no existing purely inductive datasets such that the training and validation/test graphs are different (validation and test containing new unseen entities) and predictions should only rely on the graph structure w/o external data.

#### Type-based Inductive

As a bridge between shallow transductive models and inductive inference, [Type-aware Embeddings for Multi-Hop Reasoning over Knowledge Graphs](https://arxiv.org/pdf/2205.00782.pdf) propose to mine entity types as the invariant that remains the same at training and inference.

As a result, the following datasets assume an existing and known in advance class hierarchy (or a graph of classes). Technically, those can be put in the [Type-Aware Datasets](#type-aware-datasets) category. The query datasets only have EPFO queries (no negation).

Inductive splits have been published, see the [GitHub issue](https://github.com/zhiweihu1103/QE-TEMP/issues/2)

<details>
  <summary> Graphs </summary>
  
  The underlying graphs are FB15k-237-V2 and NELL995-V3 from [Inductive relation prediction by subgraph reasoning](https://arxiv.org/abs/1911.06962) by Teru et al, ICML 2020. The original repo and other datasets are [here](https://github.com/kkteru/grail).

  Training is performed on the Train Graph, but at validation/test time the model is fed with a new Inference Graph with completely new nodes. The Inference Graph has missing edges that have to be predicted at validation or test time.


  | Dataset | Relations | Types | Train Graph | Train Graph | Inference Graph | Inference Graph | Inference Graph | Inference Graph |
  |-----|----:|----:|----:|----:|----:|----:|----:|----:|
  |  |  |  |  Train Entities | Train Edges | Inference Entities | Inference Edges | Validation Edges | Test Edges |
  | FB15k-237-V2 | 203 | 3851 | 3,000 | 4,245 | 2,000 | 4,145 | 469 | 478 |
  | NELL995-V3 | 142 | 267 | 4,647 | 16,393 | 4,921 | 8.048 | 811 | 809 |

  The type hierarchy created for those datasets remains unknown.

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 1p | others | 1p | others |
  | FB15k-237-V2  | 9,964 | 1,738 | 2,000 | 791 | 1,000 |
  | NELL995-V3 | 12,010 | 2,197 | 2,000 | 1,167 | 1,500 |

</details> 

#### Tree-like Conjunctive Inductive

The dataset proposed in [GNNQ](https://github.com/KRR-Oxford/GNNQ) frames query answering as node classification. The dataset has 9 tree-like conjunctive queries (6 synthetic from WatDiv and 3 from FB15k237), no unions nor negations. For each query, there are **P** KGs with an answer entity satisfying a query and **N** KGs with negative samplies where an answer does not satisfy a query. 
Test splits have graphs with new entities (but the same query shapes).

<details>
  <summary> Graphs </summary>
    Many - each WatDiv query has 2K positive GRAPHS and 700K negative GRAPHS (each of about 100K triples); each FB15k237 query has about 1K positive GRAPHS and 1K negative GRAPHS (each of about 10K triples)
</details>

<details>
  <summary> Queries </summary>

  Each query in the table has many associated graphs where one node is an answer (positive graph sample) and where nodes are not answers (negative graph samples)
  
  | Query | Relations | Num atoms / tree depth |  Train: pos/neg | Test: pos/neg | 
  |---------|---------:|-----:|---------:|-----------:|
  | WatDiv-Q1 | 158  | 8 / 4 | 2114 / 699699 | 1085 / 349877 |
  | WatDiv-Q2 | 158  | 8 / 3 | 3258 / 698396 | 1769 / 349119 |
  | WatDiv-Q3 | 158  | 8 / 3 | 1520 / 700276 | 798 / 350165 | 
  | WatDiv-Q4 | 158  | 10 / 4 | 2397 / 698986 | 1226 / 349546 | 
  | WatDiv-Q5 | 158  | 10 / 4 | 6338 / 693988 | 2866 / 347570 | 
  | WatDiv-Q6 | 158  | 10 / 4 | 7545 / 692439 | 3744 / 346290 | 
  | FB15k237-Q1 | 237  | 7 / 4 | 1185 / 1180 | 395 / 395 | 
  | FB15k237-Q2 | 237  | 7 / 4 | 650 / 660 | 220 / 220 | 
  | FB15k237-Q3 | 237  | 5 / 4 | 860 / 870 | 290 / 290 | 
</details>

### Temporal Datasets

Introduced in [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/abs/2205.14307), KDD 2022.

Based on FOL operators, the dataset focuses on temporal reasoning, which includes `after`, `before` and `between` on any timestamp set.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Timestamps | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|----:|
  | ICEWS14 | 7,128 | 230 | 365 | 72,826 | 8,941 | 8,963 | 90,730 |
  | ICEWS05-15 | 10,488 | 251 | 4,017 | 386,962 | 46,275 | 46,092 | 479,329 |
  | GDELT-500  | 500 | 20 | 366 | 2,735,685 | 341,961 | 341,961 | 3,419,607 |

</details>

<details>
  <summary> Queries </summary>
  
| Query Name | ICEWS14-Train | Validation | Test | ICES05-15-Train | Validation | Test  | GDELT-500-Train | Validation | Test  |
|------------|---------------|------------|------|-----------------|------------|-------|-----------------|------------|-------|
| Pe2        | 72826         | 3482       | 4037 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| Pe3        | 72826         | 3492       | 4083 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| Pe_Pt      | 7282          | 3385       | 3638 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i        | 72826         | 3305       | 3655 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| e3i        | 72826         | 2966       | 3023 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| e2i_Pe     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_e2i     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_t2i     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| e2i_NPe       | 7282          | 3061       | 3192 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i_peN       | 7282          | 2971       | 3031 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_e2i_Pe_NPe | 7282          | 2968       | 3012 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i_N         | 7282          | 2949       | 2975 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e3i_N         | 7282          | 2913       | 2914 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2u           | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_e2u        | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pt_lPe     | 7282          | 4976       | 5608 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pt_rPe     | 7282          | 3321       | 3621 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i        | 72826         | 5112       | 6631 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| t3i        | 72826         | 3094       | 3296 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| t2i_Pe     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pt_le2i    | 7282          | 3226       | 3466 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pt_re2i    | 7282          | 3236       | 3485 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_NPt         | 7282          | 4873       | 5464 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_PtN         | 7282          | 3300       | 3609 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_t2i_PtPe_NPt | 7282          | 3031       | 3127 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_N           | 7282          | 3135       | 3328 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t3i_N           | 7282          | 2924       | 2944 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2u        | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_t2u     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_aPt     | 7282          | 4134       | 4733 | 68262           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_bPt     | 7282          | 3970       | 4565 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_at2i    | 7282          | 4607       | 5338 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_bt2i    | 7282          | 4583       | 5386 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| between    | 7282          | 2913       | 2913 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |

</details>

### Dataset tools

- [Graph Query Sampler](https://github.com/miselico/graph_query_sampler): Not a method, rather a dataset generator
- [EFO-1-QA-benchmark](https://github.com/HKUST-KnowComp/EFO-1-QA-benchmark): Generating combiantorial tree-formed query types and sampling the data.
- [EFOk-CQA](https://github.com/HKUST-KnowComp/EFOK-CQA): Generating combinatorial existential first order query types with multiple (k) variables and sampling the data.

## :wrench: Implementations

- [KGReasoning](https://github.com/snap-stanford/KGReasoning): GQE, Query2Box, BetaE
- [CQD](https://github.com/pminervini/KGReasoning): GQE, Query2Box, BetaE, CQD
- [EFO-1-QA-benchmark](https://github.com/HKUST-KnowComp/EFO-1-QA-benchmark): Query2Box, BetaE, LogicE, NewLook, ConE, FuzzQE
- [Query2particles](https://github.com/HKUST-KnowComp/query2particles)
- [StarQE](https://github.com/DimitrisAlivas/StarQE): StarQE
- [SMORE](https://github.com/google-research/smore): GQE, Query2Box, BetaE + Very Large Datasets
- [GNN-QE](https://github.com/DeepGraphLearning/GNN-QE): GNN-QE
- [InductiveQE](https://github.com/DeepGraphLearning/InductiveQE): Inductive QE with NodePiece and GNN-QE
- [TAR](https://github.com/lilv98/TAR): TAR
- [QE-TeMP](https://github.com/zhiweihu1103/QE-TEMP): TeMP (based on KGReasoning)
- [GNNQ](https://github.com/KRR-Oxford/GNNQ): GNNQ
- [SE-KGE](https://github.com/gengchenmai/se-kge): GQE, CGA, and geospatial model
- [LARK](https://github.com/Akirato/LLM-KG-Reasoning/): LARK (uses Huggingface LLMs)
- [WFRE](https://github.com/HKUST-KnowComp/WFRE): WFRE
- [FIT](https://github.com/HKUST-KnowComp/FIT): FIT
- [EFOk-CQA](https://github.com/HKUST-KnowComp/EFOK-CQA): EFOk


## All Papers on Complex Logical Query Answering (53)

<details>
  <summary>Click to expand </summary>

  1. (GQE) [Embedding Logical Queries on Knowledge Graphs](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) NeurIPS 2018
  2. (GQE + hashing) [Learning to Hash for Efficient Search over Incomplete Knowledge Graphs](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA) ICDM 2019
  3. (CGA) [Contextual Graph Attention for Answering Logical Queries over Incomplete Knowledge Graphs](https://arxiv.org/pdf/1910.00084.pdf) K-CAP 2019, GQE + self-attention instead of DeepSet
  4. (TractOR) [Symbolic querying of vector spaces: Probabilistic databases meets relational embeddings](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020
  5. (Query2Box) [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS) ICLR 2020
  6. (BetaE) [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf) NeurIPS 2020
  7. (EmQL) [Faithful embeddings for knowledge base queries](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) NeurIPS 2020
  8. (MPQE) [Message Passing Query Embedding](https://grlplus.github.io/papers/26.pdf) ICML’20 Workshop
  9. (RotatE-Box)[Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480) AKBC’21
  10. (BiQE) [Answering complex queries in knowledge graphs with bidirectional sequence encoders](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI’21 
  11. [Approximate knowledge graph query answering: from ranking to binary classification](https://arxiv.org/abs/2102.11389)
  12. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf) arxiv, 2021
  13. (ConE) [Cone: Cone embeddings for multi-hop reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html) NeurIPS’21
  14. (PERM) [Probabilistic entity representation model for reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html) (improv over BetaE) NeurIPS’21
  15. (CQD) [Complex Query Answering with Neural Link Predictors](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  16. (HypE) [Self-Supervised Hyperboloid Representations from Logical Queries over Knowledge Graphs](https://arxiv.org/pdf/2012.13023.pdf), WWW 2021
  17. (NewLook) [Neural-Answering Logical Queries on Knowledge Graphs](http://tonghanghang.org/pdfs/kdd21_newlook.pdf) (KDD’21) 
  18. [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925), NeurIPS 2021 (Datasets and Benchmarks)
  19. [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm) OpenReview 2021
  20. (LogicE) [Logic Embeddings for Complex Query Answering](https://arxiv.org/pdf/2103.00418.pdf) arxiv 2021
  21. (StarQE) [Query Embedding on Hyper-relational Knowledge Graphs](https://arxiv.org/abs/2106.08166) ICLR 2022, 
  22. (MLPMix) [Neural Methods for Logical Reasoning over Knowledge Graphs](https://openreview.net/forum?id=tgcAoUVHRIB) ICLR 2022
  23. (FuzzQE) [Fuzzy Logic Based Logical Query Answering on Knowledge Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  24. (GNN-QE)  [Neural-Symbolic Models for Logical Queries on Knowledge Graphs](https://arxiv.org/abs/2205.10128), ICML 2022
  25. (SMORE) [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890) KDD 2022 
  26. (kgTransformer) [Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries](https://dl.acm.org/doi/pdf/10.1145/3534678.3539472?casa_token=c_fD5BwP0MoAAAAA:eYO12-vcXophXPFSYro_6go4b2sQRkCTcEYRZRcVgDT6SiDpKa0AvGhqS8spvhn8-y_H0ZmCz72E) KDD 2022
  27. (Query2Particles) [Query2Particles: Knowledge Graph Reasoning with Particle Embeddings](https://arxiv.org/abs/2204.12847), Findings NAACL’22
  28. (TAR) [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591) (arxiv, 2022) 
  29. (TeMP) [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782) (IJCAI-ECAI 2022) 
  30. (FLEX) [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039) (arxiv 2022)
  31. (TFLEX) [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf) (arxiv, 2022)
  32. (LinE) [LinE: Logical Query Reasoning over Hierarchical Knowledge Graphs](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw) KDD 2022
  33. [GNNQ: A Neuro-Symbolic Approach for Query Answering over Incomplete Knowledge Graphs](https://scholar.archive.org/work/sswyx3mbc5danaxosfnyr45cw4/access/wayback/https://s3-eu-west-1.amazonaws.com/pstorage-oxford-0703704596/36647646/GNNQ_full.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA3OGA3B5WHKHW6LWV/20220814/eu-west-1/s3/aws4_request&X-Amz-Date=20220814T213541Z&X-Amz-Expires=10&X-Amz-SignedHeaders=host&X-Amz-Signature=1bf627735fbce377c2478f514fbac1dfcf49423980d372cc71e2bed732d6ae2c) ISWC 2022
  34. (ENeSy) [Neural-Symbolic Entangled Framework for Complex Query Answering](https://arxiv.org/pdf/2209.08779.pdf) NeurIPS 2022  
  35. (NodePiece-QE, InductiveQE) [Inductive Logical Query Answering in Knowledge Graphs](https://arxiv.org/abs/2210.08008) NeurIPS 2022  
  36. (RoMA) [Reasoning over Multi-view Knowledge Graphs](https://arxiv.org/pdf/2209.13702.pdf) arxiv 2022, some new datasets, but no code/data published  
  37. (LMPNN) [Logical Message Passing Networks With One-Hop Inference On Atomic Formulas](https://openreview.net/pdf?id=SoyOsp7i_l) ICLR'23  
  38. (GammaE) [GammaE: Gamma Embeddings for Logical Queries on Knowledge Graphs](https://arxiv.org/pdf/2210.15578.pdf) EMNLP 2022  
  39. (NMP-QEM) [Neural-based Mixture Probabilistic Query Embedding for Answering FOL queries on Knowledge Graphs](https://aclanthology.org/2022.emnlp-main.194.pdf), EMNLP 2022  
  40. (NQE) [NQE: N-ary Query Embedding for Complex Query Answering over Hyper-relational Knowledge Graphs](https://arxiv.org/pdf/2211.13469.pdf) AAAI 2023  
  41. (QTO) [Answering Complex Logical Queries on Knowledge Graphs via Query Computation Tree Optimization](https://arxiv.org/pdf/2212.09567.pdf), ICML'23 submission  
  42. (SignalE) [Signal Embeddings for Complex Logical Reasoning in Knowledge Graphs](https://link.springer.com/content/pdf/10.1007/978-3-031-10983-6_20.pdf?pdf=inline%20link), KSEM'22  
  43. (Var2Vec) [Efficient Embeddings of Logical Variables for Query Answering over Incomplete Knowledge Graphs](https://ora.ox.ac.uk/objects/uuid:27c9b239-20d0-449f-b425-b5065eb128fe/download_file?file_format=application%2Fpdf&safe_filename=Wang_et_al_2022_Efficient_Embeddings_ofAM.pdf&type_of_work=Conference+item), AAAI'23
  44. (CQD-A) [Adapting Neural Link Predictors for Complex Query Answering](https://arxiv.org/pdf/2301.12313.pdf)
  45. (Query2Geom) [Analysis of Attention Mechanisms in Box-Embedding Systems](https://link.springer.com/chapter/10.1007/978-3-031-26438-2_6), 2023
  46. (SQE) [Sequential Query Encoding For Complex Query Answering on Knowledge Graphs](https://arxiv.org/pdf/2302.13114.pdf), arxiv 2023  
  47. (CylE) [CylE: Cylinder Embeddings for Multi-hop Reasoning over Knowledge Graphs](https://aclanthology.org/2023.eacl-main.127.pdf), EACL 2023  
  48. (RoConE) [Modeling Relational Patterns for Logical Query Answering over Knowledge Graphs](https://arxiv.org/pdf/2303.11858.pdf)  
  49. (FIT) [On Existential First Order Queries Inference on Knowledge Graphs](https://arxiv.org/pdf/2304.07063.pdf), arxiv 2023  
  50. (LitCQD) [LitCQD: Multi-Hop Reasoning in Incomplete Knowledge Graphs with Numeric Literals](https://arxiv.org/pdf/2304.14742.pdf), arxiv 2023  
  51. (LARK) [Complex Logical Reasoning over Knowledge Graphs using Large Language Models](https://arxiv.org/pdf/2305.01157.pdf), arxiv 2023  
  52. (WFRE) [Wasserstein-Fisher-Rao Embedding: Logical Query Embeddings with Local Comparison and Global Transport](https://arxiv.org/pdf/2305.04034.pdf), arxiv 2023
  53. (EFOk-CQA) [EFOk-CQA: Towards Knowledge Graph Complex Query Answering beyond Set Operation](https://arxiv.org/abs/2307.13701) arxiv 2023
</details>

## Application Papers (7)
<details>
  <summary>Click to expand </summary>

  1. (SE-KGE) [SE-KGE: A Location-Aware Knowledge Graph Embedding Model for Geographic Question Answering and Spatial Semantic Lifting](https://arxiv.org/pdf/2004.14171.pdf), Transactions in GIS 2020, GQE with scalar (x,y) coordinate prediction / encoding
  2. (LEGO) [Lego: Latent execution-guided reasoning for multi-hop question answering on knowledge graphs](https://proceedings.mlr.press/v139/ren21a.html), ICML 2021
  3. (CBR-SubG) [Knowledge base question answering by case-based reasoning over subgraphs](https://proceedings.mlr.press/v162/das22a.html) ICML 2022, application to Question Answering, entailment only, custom datasets
  4. (LogiRec) [Towards High-Order Complementary Recommendation via Logical Reasoning Network](https://arxiv.org/pdf/2212.04966.pdf) Application: BetaE in RecSys, arxiv 2022
  5. [Context-aware explainable recommendation based on domain knowledge graph](https://www.mdpi.com/1458952), Big Data and Cognitive Computing, 2022
  6. (PLM4CLQA) [Unifying Structure Reasoning and Language Model Pre-training for Complex Reasoning](https://arxiv.org/pdf/2301.08913.pdf), arxiv 2023
  7. [Unifying structure reasoning and language model pre-training for complex reasoning](https://arxiv.org/pdf/2301.08913), arxiv 2023
</details>

## Potentially Relevant 
<details>
  <summary>Click to expand </summary>

  1. [Hybrid Structured and Similarity Queries over Wikidata plus Embeddings with Kypher-V](https://www.isi.edu/~hans/publications/WDWS-ISWC-2022.pdf), ISWC 2022
  2. [Combining RDF Graph Data and Embedding Models for an Augmented Knowledge Graph](https://dl.acm.org/doi/fullHtml/10.1145/3184558.3191527), BigNet 2018 Workshop @ WWW'18
  3. [TrQuery: An Embedding-based Framework for Recommanding SPARQL Queries](https://arxiv.org/pdf/1806.06205.pdf), 2018
  4. [Towards Empty Answers in SPARQL: Approximating Querying with RDF Embedding](https://link.springer.com/content/pdf/10.1007/978-3-030-00671-6.pdf), ISWC 2018
</details>

## Citation

If you find this work useful, please cite the original paper:

```bibtex
@article{ren2023ngdb,
    title={Neural Graph Reasoning: Complex Logical Query Answering Meets Graph Databases},
    author={Hongyu Ren and Mikhail Galkin and Michael Cochez and Zhaocheng Zhu and Jure Leskovec},
    year={2023},
    eprint={2303.14617},
    archivePrefix={arXiv},
}
```
