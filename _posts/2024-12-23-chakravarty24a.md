---
title: Predicting Age-related Macular Degeneration Progression from Retinal Optical
  Coherence Tomography with Intra-Subject Temporal Consistency
abstract: The wide variability in the progression rates of Age-Related Macular Degeneration
  (AMD) and the absence of well-established clinical biomarkers make it difficult
  to predict an individualś risk of AMD progression from intermediate stage (iAMD)
  to late dry stage (dAMD) using Optical Coherence Tomography (OCT) scans.To address
  this challenge, we propose to jointly train an AMD stage classifier to discriminate
  between iAMD and dAMD with a Neural-ODE that models the future trajectory of the
  disease progression in the learned embedding space. A temporal ordering is imposed
  such that the distance of a scan from the decision hyperplane of the AMD stage classifier
  is inversely related to its time-to-conversion. In addition, an intra-subject temporal
  consistency in the predicted conversion risk scores is ensured by incorporating
  a pair of longitudinal scans from the same eye during training. We evaluated our
  proposed method on a longitudinal dataset comprising 235 eyes (3,534 OCT scans)
  with 40 converters. The results demonstrate the effectiveness of our approach, achieving
  an average area under the ROC of 0.84 for predicting conversion within the next
  6, 12, 18 and 24 months. Additionally, the Concordance Index of 0.78 surpasses the
  performance of several popular methods for survival analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakravarty24a
month: 0
tex_title: Predicting Age-related Macular Degeneration Progression from Retinal Optical
  Coherence Tomography with Intra-Subject Temporal Consistency
firstpage: 184
lastpage: 198
page: 184-198
order: 184
cycles: false
bibtex_author: Chakravarty, Arunava and Emre, Taha and Lachinov, Dmitrii and Rivail,
  Antoine and Schmidt-Erfurth, Ursula and Bogunovi\'c, Hrvoje
author:
- given: Arunava
  family: Chakravarty
- given: Taha
  family: Emre
- given: Dmitrii
  family: Lachinov
- given: Antoine
  family: Rivail
- given: Ursula
  family: Schmidt-Erfurth
- given: Hrvoje
  family: Bogunović
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
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/chakravarty24a/chakravarty24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
