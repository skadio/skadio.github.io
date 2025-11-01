---
permalink: /software/
title: "Software" # <i class="fa fa-code" aria-hidden="true"></> <i class="fa fa-code-fork" aria-hidden="true"></i> <i class="fa fa-terminal" aria-hidden="true"></i> 
layout: archive
author_profile: true
---

---

### LLMs, Agents & Co-Pilots
- [Text2Zinc](https://huggingface.co/datasets/skadio/text2zinc): A Cross-Domain Dataset for Modeling Optimization and Satisfaction Problems in MiniZinc [Arxiv'25](https://arxiv.org/abs/2503.10642)
- [Text2Zinc-Leaderboard](https://huggingface.co/spaces/skadio/text2zinc-leaderboard): Modeling Co-Pilots Leaderboard
- [iCBS](https://github.com/amazon-science/icbs): iterative Combinatorial Brain Surgeon [Arxiv'24](https://arxiv.org/abs/2411.17796), [Amazon Blogpost](https://aws.amazon.com/blogs/quantum-computing/quantum-amenable-pruning-of-large-language-models-and-large-vision-models-using-block-coordinate-descent/)

---

### Responsible AI

- [BoolXAI](https://github.com/fidelity/boolxai): Explainable AI using expressive Boolean formulas. [MAKE'23](https://www.mdpi.com/2504-4990/5/4/86), [ArXiv'23](https://arxiv.org/pdf/2306.03976)
- [Jurity](https://github.com/fidelity/jurity): Fairness and bias mitigation, and recommender system evaluation techniques. [ArXiv'23](https://arxiv.org/pdf/2403.12069), [LION'23](https://link.springer.com/chapter/10.1007/978-3-031-44505-7_29), [CIKM'22](https://ceur-ws.org/Vol-3318/short6.pdf), [ICMLA'21](https://ieeexplore.ieee.org/abstract/document/9680169)

---

### Personalization & Recommender Systems

- [Mab2Rec](https://github.com/fidelity/mab2rec#mab2rec-multi-armed-bandits-recommender) End-to-end framework for building bandits-based recommenders from raw interaction data to feature generation, model evaluation and deployment. [AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/30341), [ODSC'23](https://odsc.com/speakers/mab2rec-a-modular-approach-to-building-bandit-based-recommenders/), [Presentation@AAAI'24](https://underline.io/lecture/91479-building-higher-order-abstractions-from-the-components-of-recommender-systems), [Presentation@ATO'21](https://www.youtube.com/watch?v=54d_YUalvOA), [ATO Blogpost](https://2022.allthingsopen.org/introducing-mab2rec-a-multi-armed-bandit-recommender-library/)
- [MABWiser](https://github.com/fidelity/mabwiser) Parallelizable, contextual multi-armed bandits library with simulation capabilities. [Bridge@AAAI'24](http://osullivan.ucc.ie/CPML2024/papers/06.pdf), [TMLR'22](https://openreview.net/pdf?id=sX9d3gfwtE), [IJAIT'21](https://www.worldscientific.com/doi/abs/10.1142/S0218213021500214), [ICTAI'19](https://ieeexplore.ieee.org/document/8995418)

---

### Natural Language Processing

- [Ner4Opt](https://github.com/skadio/ner4opt) Given an optimization problem in natural language, extract optimization related entities from free-form text. [CPAIOR'23](https://github.com/skadio/ner4opt/blob/main/docs/%5BCPAIOR%202023%5D%20Ner4Opt%20Paper.pdf), [NeurIPS'22](https://github.com/skadio/ner4opt/blob/main/docs/%5BNeurIPS%202022%5D%20Ner4Opt%20Poster.pdf)
- [TextWiser](https://github.com/fidelity/textwiser) Text featurization NLP library that unifies several text embedding techniques. [AAAI'21](https://ojs.aaai.org/index.php/AAAI/article/view/17814)

---

### Pattern Mining 

- [Seq2Pat](https://github.com/fidelity/seq2pat) Sequence-to-Pattern generation library to find frequent patterns from large sequence databases. Joint work with CMU. [AI Magazine'23](https://onlinelibrary.wiley.com/doi/epdf/10.1002/aaai.12081), [AAAI'22](https://ojs.aaai.org/index.php/AAAI/article/view/21542), [Bridge@AAAI'23](http://osullivan.ucc.ie/CPML2023/submissions/09.pdf), [Frontiers'22](https://www.frontiersin.org/articles/10.3389/frai.2022.868085/full), [KDF@AAAI'22](https://arxiv.org/abs/2201.09178), [CMU Blog Post](https://www.cmu.edu/tepper/news/stories/2023/may/fidelity-ai.html)

---

### Feature Selection 

- [Selective](https://github.com/fidelity/selective) A white-box feature selection library that supports unsupervised and supervised selection methods for classification and regression tasks. [AMAI'24](https://link.springer.com/epdf/10.1007/s10472-024-09941-x?sharing_token=9XBJ6cdglsdji19gFwuqQve4RwlQNchNByi7wbcMAY4VwIBKydj3Ja9OBjALNpg8nuO300abjlrHmZQFBVUqar-uYhBML28cmbovFgiHRRvd7TM2QAA_Hwd5J3U2MmKx0ugXwF6yz2hW75_88JpLmXSDJSuyCEwqZqtOcB7BhJU=), [CPAIOR'21](https://link.springer.com/chapter/10.1007/978-3-030-78230-6_27), [DSO@IJCAI'21](https://arxiv.org/abs/2112.03105), [Data](https://huggingface.co/datasets/skadio/optimized_item_selection)
- [FSiHD](http://users.spa.aalto.fi/jpohjala/featureselection/) Feature Selection in High-Dimensional Classification. <span style="color:green">The bronze winner</span> at the [Interspeech Speaker Trait Challenge in 2012](http://www5.informatik.uni-erlangen.de/Forschung/Publikationen/2012/Schuller12-TI2.pdf). [Computer Speech & Language'15](https://www.sciencedirect.com/science/article/abs/pii/S0885230813001113), [Interspeech'12](https://users.aalto.fi/~jpohjala/publications/is12stc.pdf)

---

### Combinatorial Optimization & Satisfaction
- [Balans: Bandit-based Adaptive Large-Neighborhood Search](https://github.com/skadio/balans) Meta solver for mixed-integer programming problems using online learning
- [Explorateur: State-Space-Search](https://github.com/skadio/explorateur)
- [PathFinder: CP Decomposition for Capacitated Vehicle Routing with Time-Windows (CVRP-TW)](https://github.com/skadio/pathfinder) <span style="color:green">This solver was a finalist of the 2018 AIMMS/MOPTA Modelling Competition</span> Constraint programming based decomposition approach to solve a realistic variant of the vehicle routing problem. [AIMMS'18](https://arxiv.org/pdf/2106.16176.pdf), [Brown News](https://awards.cs.brown.edu/2021/08/11/brown-cs-team-takes-third-place-thirteenth-modeling-and-optimization-competition/)
- [3S: Satisfiability Solver Selector](https://sites.google.com/site/yurimalitsky/downloads). <span style="color:green">This solver won 2 gold and 7 medals in total</span> at the [International SAT Solver Competition in 2011](http://www.satcompetition.org/). [CP'11](https://link.springer.com/chapter/10.1007%2F978-3-642-23786-7_35), [SAT'11](http://link.springer.com/chapter/10.1007%2F978-3-642-21581-0_33)
- [Hegel: Dialectic Search Solver for Set Cover Problem](https://github.com/skadio/hegel) Dialectic search based local search approach for solving Set Covering Problems. [CP'09](https://link.springer.com/chapter/10.1007/978-3-642-04244-7_39)
  
--- 

### Algorithm Configuration & Portfolios

- [ISAC: Instance-Specific Algorithm Configuration](https://sites.google.com/site/yurimalitsky/downloads). Algorithm Portfolio based on the Instance-Specific Algorithm Configuration (ISAC) approach. [ECAI'10](https://ebooks.iospress.nl/publication/5873)
- [GGA: Gender-based Genetic Algorithm for Parameter Tuning](https://github.com/OPTANO/optano.algorithm.tuner). A state-of-the-art parameter tuning and algorithm configuration tool based on genetic algorithms. It is the backbone of many competition-winning constraint solvers and algorithm portfolios. Re-implemented and now maintained by [Optano GmbH](https://optano.com/). [CP'09](http://link.springer.com/chapter/10.1007%2F978-3-642-04244-7_14)
- [DASH: Dynamic Adaptive Search Heuristics & Non-Model Based Search Guidance](https://github.com/skadio/set-partitioning-instance-generator) Set Partitioning Problem (SPP) Benchmark Instance Generator. [EJOR'16](http://link.springer.com/article/10.1007%2Fs10601-015-9211-0), [AAAI'12](http://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/view/5082)
- [ASLib: Algorithm Selection Library](https://github.com/coseal/aslib_data). This library consists of scenarios and instances for benchmarking from different domains, such as SAT, CSP, and ASP. 
