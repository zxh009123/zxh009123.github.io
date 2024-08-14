---
title: Fine-Grained Permeable Surface Mapping through Parallel U-Net
authors:
- Nathaniel Ogilvie
- admin
- Cale Kochenour
- Safwan Wshah
date: '2024-01-01'
publishDate: '2024-08-13T21:41:03.498468Z'
publication_types:
- article-journal
publication: '*Sensors*'
# doi: 10.3390/s24072134
abstract: Permeable surface mapping, which mainly is the identification of surface
  materials that will percolate, is essential for various environmental and civil
  engineering applications, such as urban planning, stormwater management, and groundwater
  modeling. Traditionally, this task involves labor-intensive manual classification,
  but deep learning offers an efficient alternative. Although several studies have
  tackled aerial image segmentation, the challenges in permeable surface mapping arid
  environments remain largely unexplored because of the difficulties in distinguishing
  pixel values of the input data and due to the unbalanced distribution of its classes.
  To address these issues, this research introduces a novel approach using a parallel
  U-Net model for the fine-grained semantic segmentation of permeable surfaces. The
  process involves binary classification to distinguish between entirely and partially
  permeable surfaces, followed by fine-grained classification into four distinct permeability
  levels. Results show that this novel method enhances accuracy, particularly when
  working with small, unbalanced datasets dominated by a single category. Furthermore,
  the proposed model is capable of generalizing across different geographical domains.
  Domain adaptation is explored to transfer knowledge from one location to another,
  addressing the challenges posed by varying environmental characteristics. Experiments
  demonstrate that the parallel U-Net model outperforms the baseline methods when
  applied across domains. To support this research and inspire future research, a
  novel permeable surface dataset is introduced, with pixel-wise fine-grained labeling
  for five distinct permeable surface classes. In summary, in this work, we offer
  a novel solution to permeable surface mapping, extend the boundaries of arid environment
  mapping, introduce a large-scale permeable surface dataset, and explore cross-area
  applications of the proposed model. The three contributions are enhancing the efficiency
  and accuracy of permeable surface mapping while progressing in this field.
tags:
- aerial imagery
- cross-domain adaptation
- image segmentation
- impervious surface mapping
- permeable surface mapping
- U-Net
links:
- name: URL
  url: https://www.mdpi.com/1424-8220/24/7/2134
---
