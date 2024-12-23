---
title: Distance-Aware Non-IID Federated Learning for Generalization and Personalization
  in Medical Imaging Segmentation
abstract: Federated learning (FL) in healthcare suffers from non-identically distributed
  (non-IID) data, impacting model convergence and performance. While existing solutions
  for the non-IID problem often do not quantify the degree of non-IID nature between
  clients in the federation, assessing it can improve training experiences and outcomes,
  particularly in real-world scenarios with unfamiliar datasets. The paper presents
  a practical non-IID assessment methodology for a medical segmentation problem, highlighting
  its significance in medical FL. We propose a simple yet effective solution that
  utilizes distance measurements in the embedding space of medical images and statistical
  measurements calculated over their metadata. Our method, designed for medical imaging
  and integrated into federated averaging, improves model generalization by downgrading
  the contribution from the most distant client, treating it as an outlier. Additionally,
  it enhances model personalization by introducing distance-based clustering of clients.
  To the best of our knowledge, this method is the first to use distance-based techniques
  for providing a practical solution to the non-IID problem within the medical imaging
  FL domain. Furthermore, we validate our approach on three public FL imaging radiology
  datasets (FeTS, Prostate, and Fed-KITS2019) to demonstrate its effectiveness across
  various radiology imaging scenarios.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alekseenko24a
month: 0
tex_title: Distance-Aware Non-IID Federated Learning for Generalization and Personalization
  in Medical Imaging Segmentation
firstpage: 33
lastpage: 47
page: 33-47
order: 33
cycles: false
bibtex_author: Alekseenko, Julia and Karargyris, Alexandros and Padoy, Nicolas
author:
- given: Julia
  family: Alekseenko
- given: Alexandros
  family: Karargyris
- given: Nicolas
  family: Padoy
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
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/alekseenko24a/alekseenko24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
