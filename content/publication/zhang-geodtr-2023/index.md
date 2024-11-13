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
- article-journal
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence*'
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
- Cross-View Image Geo-localization
- Transformer
links:
- name: URL
  url: http://arxiv.org/abs/2308.09624

url_pdf: 'https://arxiv.org/pdf/2308.09624'
url_code: 'https://gitlab.com/vail-uvm/geodtr_plus'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=Ha1spmRvx-o'
---
