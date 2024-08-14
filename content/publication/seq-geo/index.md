---
title: Cross-View Image Sequence Geo-localization
authors:
- admin
- Waqas Sultani
- Safwan Wshah
date: '2023-01-01'
publishDate: '2024-08-14T01:12:33.371943Z'
publication_types:
- paper-conference
publication: '*2023 IEEE/CVF Winter Conference on Applications of Computer Vision
  (WACV)*'
# doi: 10.1109/WACV56688.2023.00293
abstract: Cross-view geo-localization aims to estimate the GPS location of a query
  ground-view image by matching it to images from a reference database of geo-tagged
  aerial images. To address this challenging problem, recent approaches use panoramic
  ground-view images to increase the range of visibility. Although appealing, panoramic
  images are not readily available compared to the videos of limited FieldOf-View
  (FOV) images. In this paper, we present the first cross-view geo-localization method
  that works on a sequence of limited FOV images. Our model is trained endto-end to
  capture the temporal structure that lies within the frames using the attention-based
  temporal feature aggregation module. To robustly tackle different sequences length
  and GPS noises during inference, we propose to use a sequential dropout scheme to
  simulate variant length sequences. To evaluate the proposed approach in realistic
  settings, we present a new large-scale dataset containing ground-view sequences
  along with the corresponding aerial-view images. Extensive experiments and comparisons
  demonstrate the superiority of the proposed approach compared to several competitive
  baselines.
tags:
- Cross-View Image Geo-localization
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10031017/

url_pdf: 'https://arxiv.org/pdf/2210.14295'
url_code: 'https://gitlab.com/vail-uvm/seqgeo'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
