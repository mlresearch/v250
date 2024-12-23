---
title: Advancing Multiplex Immunofluorescence Imaging Cell Detection using Semi-Supervised
  Learning with Pseudo-Labeling
abstract: Accurate cell detection in multiplex immunofluorescence (mIF) is crucial
  for quantifying and analyzing the spatial distribution of complex cellular patterns
  within the tumor microenvironment. Despite its importance, cell detection in mIF
  is challenging, primarily due to difficulties obtaining comprehensive annotations.
  To address the challenge of limited and unevenly distributed annotations, we introduced
  a streamlined semi-supervised approach that effectively leveraged partially pathologist-annotated
  single-cell data in multiplexed images across different cancer types. We assessed
  three leading object detection models, Faster R-CNN, YOLOv5s, and YOLOv8s, with
  partially annotated data, selecting YOLOv8s for optimal performance. This model
  was subsequently used to generate pseudo labels, which enriched our dataset by adding
  more detected labels than the original partially annotated data, thus increasing
  its generalization and the comprehensiveness of cell detection. By fine-tuning the
  detector on the original dataset and the generated pseudo labels, we tested the
  refined model on five distinct cancer types using fully annotated data by pathologists.
  Our model achieved an average precision of 90.42%, recall of 85.09%, and an F1 Score
  of 84.75%, underscoring our semi-supervised modelś robustness and effectiveness.
  This study contributes to analyzing multiplexed images from different cancer types
  at cellular resolution by introducing sophisticated object detection methodologies
  and setting a novel approach to effectively navigate the constraints of limited
  annotated data with semi-supervised learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shokrollahi24a
month: 0
tex_title: Advancing Multiplex Immunofluorescence Imaging Cell Detection using Semi-Supervised
  Learning with Pseudo-Labeling
firstpage: 1448
lastpage: 1461
page: 1448-1461
order: 1448
cycles: false
bibtex_author: Shokrollahi, Yasin and Gonzales, Karina Pinao and Salvatierra, Maria
  Esther and Castillo, Simon P. and Gautam, Tanishq and Chen, Pingjun and Rodriguez,
  B. Leticia and Ranjbar, Sara and Team, Patient Mosaic and Soto, Luisa Solis and
  Yuan, Yinyin and Pan, Xiaoxi
author:
- given: Yasin
  family: Shokrollahi
- given: Karina Pinao
  family: Gonzales
- given: Maria Esther
  family: Salvatierra
- given: Simon P.
  family: Castillo
- given: Tanishq
  family: Gautam
- given: Pingjun
  family: Chen
- given: B. Leticia
  family: Rodriguez
- given: Sara
  family: Ranjbar
- given: Patient Mosaic
  family: Team
- given: Luisa Solis
  family: Soto
- given: Yinyin
  family: Yuan
- given: Xiaoxi
  family: Pan
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
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/shokrollahi24a/shokrollahi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
