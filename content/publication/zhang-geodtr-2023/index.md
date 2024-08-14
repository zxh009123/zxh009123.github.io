---
title: 'GeoDTR+: Toward generic cross-view geolocalization via geometric disentanglement'
authors:
- admin
- Xingyu Li
- Waqas Sultani
- Chen Chen
- Safwan Wshah
date: '2023-08-01'
publishDate: '2024-08-13T21:41:03.437790Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Cross-View Geo-Localization (CVGL) estimates the location of a ground image
  by matching it to a geo-tagged aerial image in a database. Recent works achieve
  outstanding progress on CVGL benchmarks. However, existing methods still suffer
  from poor performance in cross-area evaluation, in which the training and testing
  data are captured from completely distinct areas. We attribute this deficiency to
  the lack of ability to extract the geometric layout of visual features and models’
  overfitting to low-level details. Our preliminary work [1] introduced a Geometric
  Layout Extractor (GLE) to capture the geometric layout from input features. However,
  the previous GLE does not fully exploit information in the input feature. In this
  work, we propose GeoDTR+ with an enhanced GLE module that better models the correlations
  among visual features. To fully explore the LS techniques from our preliminary work,
  we further propose Contrastive Hard Samples Generation (CHSG) to facilitate model
  training. Extensive experiments show that GeoDTR+ achieves state-of-the-art (SOTA)
  results in cross-area evaluation on CVUSA [2], CVACT [3], and VIGOR [4] by a large
  margin (16.44%, 22.71%, and 17.02% without polar transformation) while keeping the
  same-area performance comparable to existing SOTA. Moreover, we provide detailed
  analyses of GeoDTR+.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2308.09624
---
