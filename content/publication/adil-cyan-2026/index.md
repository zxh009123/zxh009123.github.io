---
title: 'From Remote Sensing to Multiple Time Horizons Forecasts: Transformers Model for CyanoHAB Intensity in Lake Champlain'
authors:
- Muhammad Adil
- Patrick J. Clemins
- Peter D. F. Isles
- admin
- Andrew W. Schroth
- Kareem I. Hannoun
- Panagiotis D. Oikonomou
- Scott Turnbull
- Donna M. Rizzo
- Noah B. Beckage
- Asim Zia
- Safwan Wshah
date: '2026-02-01'
publishDate: '2026-02-01T21:41:03.491006Z'
publication_types:
- article-journal
publication: '*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing
*'
# doi: 10.48550/arXiv.2408.04224
abstract: Cyanobacterial Harmful Algal Blooms (CyanoHABs) pose significant threats to aquatic ecosystems and public health globally. Lake Champlain is particularly vulnerable to recurring CyanoHAB events, especially in its northern segment: Missisquoi Bay, St. Albans Bay, and Northeast Arm, due to nutrient enrichment and climatic variability. Remote sensing provides a scalable solution for monitoring and forecasting these events, offering continuous coverage where in-situ observations are sparse or unavailable. In this study, we present a remote sensing-only forecasting framework that combines Transformers and BiLSTM to predict CyanoHAB intensities up to 14 days in advance. The system utilizes Cyanobacterial Index data from the Cyanobacterial Assessment Network and temperature data from Moderate Resolution Imaging Spectroradiometer satellites to capture long-range dependencies and sequential dynamics in satellite time series. The dataset is very sparse, missing more than 30% of the Cyanobacterial Index data and 90% of the temperature data. A two-stage preprocessing pipeline addressed data gaps by applying forward fill and weighted temporal imputation at the pixel level, followed by smoothing to reduce the discontinuities of CyanoHAB events. The raw dataset is transformed into meaningful features through equal-frequency binning for the Cyanobacterial Index values and extracted temperature statistics. Transformer-BiLSTM model demonstrates strong forecasting performance across multiple horizons, achieving F1 scores of 89.5%, 86.4%, and 85.5% at one-, two-, and three-day forecasts, respectively, and maintaining an F1 score of 78.9% with an AUC of 82.6% at the 14-day horizon. These results confirm the model's ability to capture complex spatiotemporal dynamics from sparse satellite data and to provide reliable early warning for CyanoHABs management. The dataset and trained model weights are publicly available, facilitating further research in CyanoHABs forecasting.
tags:
- Transformer
- Remote Sensing
- Forecasting
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/11361021

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
