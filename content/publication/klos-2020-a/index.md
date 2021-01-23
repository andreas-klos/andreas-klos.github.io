---
title: "Ensemble transfer learning for emergency landing field identification on moderate resource heterogeneous kubernetes cluster"
date: 2020-01-01
publishDate: 2021-01-23T21:30:18.757948Z
authors: ["Andreas Klos", "Marius Rosenbaum", "Wolfram Schiffmann"]
publication_types: ["0"]
abstract: "Copyright © 2020, arXiv, All rights reserved. The full loss of thrust of an aircraft requires fast and reliable decisions of the pilot. If no published landing field is within reach, an emergency landing field must be selected. The choice of a suitable emergency landing field denotes a crucial task to avoid unnecessary damage of the aircraft, risk for the civil population as well as the crew and all passengers on board. Especially in case of instrument meteorological conditions it is indispensable to use a database of suitable emergency landing fields. Thus, based on public available digital orthographic photos and digital surface models, we created various datasets with different sample sizes to facilitate training and testing of neural networks. Each dataset consists of a set of data layers. The best compositions of these data layers as well as the best performing transfer learning models are selected. Subsequently, certain hyperparameters of the chosen models for each sample size are optimized with Bayesian and Bandit optimization. The hyperparameter tuning is performed with a self-made Kubernetes cluster. The models outputs were investigated with respect to the input data by the utilization of layer-wise relevance propagation. With optimized models we created an ensemble model to improve the segmentation performance. Finally, an area around the airport of Arnsberg in North Rhine-Westphalia was segmented and emergency landing fields are identified, while the verification of the final approach's obstacle clearance is left unconsidered. These emergency landing fields are stored in a PostgreSQL database."
featured: false
publication: "*arXiv*"
---

