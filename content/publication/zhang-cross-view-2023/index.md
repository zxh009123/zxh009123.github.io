---
title: Cross-View Geo-Localization via Learning Disentangled Geometric Layout Correspondence
authors:
- Xiaohan Zhang
- Xingyu Li
- Waqas Sultani
- Yi Zhou
- Safwan Wshah
date: '2023-06-01'
publishDate: '2024-08-13T21:41:03.448450Z'
publication_types:
- article-journal
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
doi: 10.1609/aaai.v37i3.25457
abstract: Cross-view geo-localization aims to estimate the location of a query ground
  image by matching it to a reference geo-tagged aerial images database. As an extremely
  challenging task, its difficulties root in the drastic view changes and different
  capturing time between two views. Despite these difficulties, recent works achieve
  outstanding progress on cross-view geo-localization benchmarks. However, existing
  methods still suffer from poor performance on the cross-area benchmarks, in which
  the training and testing data are captured from two different regions. We attribute
  this deficiency to the lack of ability to extract the spatial configuration of visual
  feature layouts and models' overfitting on low-level details from the training set.
  In this paper, we propose GeoDTR which explicitly disentangles geometric information
  from raw features and learns the spatial correlations among visual features from
  aerial and ground pairs with a novel geometric layout extractor module. This module
  generates a set of geometric layout descriptors, modulating the raw features and
  producing high-quality latent representations. In addition, we elaborate on two
  categories of data augmentations, (i) Layout simulation, which varies the spatial
  configuration while keeping the low-level details intact. (ii) Semantic augmentation,
  which alters the low-level details and encourages the model to capture spatial configurations.
  These augmentations help to improve the performance of the cross-view geo-localization
  models, especially on the cross-area benchmarks. Moreover, we propose a counterfactual-based
  learning process to benefit the geometric layout extractor in exploring spatial
  information. Extensive experiments show that GeoDTR not only achieves state-of-the-art
  results but also significantly boosts the performance on same-area and cross-area
  benchmarks. Our code can be found at https://gitlab.com/vail-uvm/geodtr.
tags:
- 'CV: Applications'
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/25457
---
