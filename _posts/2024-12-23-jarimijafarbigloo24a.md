---
title: Reducing Uncertainty in 3D Medical Image Segmentation under Limited Annotations
  through Contrastive Learning
abstract: Despite recent successes in semi-supervised learning for natural image segmentation,
  applying these methods to medical images presents challenges in obtaining discriminative
  representations from limited annotations. While contrastive learning frameworks
  excel in similarity measures for classification, their transferability to precise
  pixel-level segmentation in medical images is hindered, particularly when confronted
  with inherent prediction uncertainty.To overcome this issue, our approach incorporates
  two subnetworks to rectify erroneous predictions. The first network identifies uncertain
  predictions, generating an uncertainty attention map. The second network employs
  an uncertainty-aware descriptor to refine the representation of uncertain regions,
  enhancing the accuracy of predictions. Additionally, to adaptively recalibrate the
  representation of uncertain candidates, we define class prototypes based on reliable
  predictions. We then aim to minimize the discrepancy between class prototypes and
  uncertain predictions through a deep contrastive learning strategy.Our experimental
  results on organ segmentation from clinical MRI and CT scans demonstrate the effectiveness
  of our approach compared to state-of-the-art methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jarimijafarbigloo24a
month: 0
tex_title: Reducing Uncertainty in 3D Medical Image Segmentation under Limited Annotations
  through Contrastive Learning
firstpage: 694
lastpage: 707
page: 694-707
order: 694
cycles: false
bibtex_author: Jarimijafarbigloo, Sanaz and Azad, Reza and Kazerouni, Amirhossein
  and Merhof, Dorit
author:
- given: Sanaz
  family: Jarimijafarbigloo
- given: Reza
  family: Azad
- given: Amirhossein
  family: Kazerouni
- given: Dorit
  family: Merhof
date: 2024-12-23
address:
container-title: Proceedings of The 7nd International Conference on Medical Imaging
  with Deep Learning
volume: '250'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 12
  - 23
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/jarimijafarbigloo24a/jarimijafarbigloo24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
