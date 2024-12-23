---
title: 'Disruptive Autoencoders: Leveraging Low-level features for 3D Medical Image
  Pre-training'
abstract: 'Harnessing the power of pre-training on large-scale datasets like ImageNet
  forms a funda- mental building block for the progress of representation learning-driven
  solutions in com- puter vision. Medical images are inherently different from natural
  images as they are acquired in the form of many modalities (CT, MR, PET, Ultrasound
  etc.) and contain granulated information like tissue, lesion, organs etc. These
  characteristics of medical im- ages require special attention towards learning features
  representative of local context. In this work, we focus on designing an effective
  pre-training framework for 3D radiology im- ages. First, we propose a new masking
  strategy called local masking where the masking is performed across channel embeddings
  instead of tokens to improve the learning of local feature representations. We combine
  this with classical low-level perturbations like adding noise and downsampling to
  further enable low-level representation learning. To this end, we introduce Disruptive
  Autoencoders, a pre-training framework that attempts to re- construct the original
  image from disruptions created by a combination of local masking and low-level perturbations.
  We curate a large-scale dataset to enable pre-training of 3D medical radiology images
  (MRI and CT). The proposed pre-training framework is tested across multiple downstream
  tasks and achieves state-of-the-art performance. Notably, our proposed method tops
  the public test leaderboard of BTCV multi-organ segmentation chal- lenge. Our code
  can be found here: https://github.com/Project-MONAI/research-contributions/tree/main/DAE.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valanarasu24a
month: 0
tex_title: 'Disruptive Autoencoders: Leveraging Low-level features for 3D Medical
  Image Pre-training'
firstpage: 1553
lastpage: 1570
page: 1553-1570
order: 1553
cycles: false
bibtex_author: Valanarasu, Jeya Maria Jose and Tang, Yucheng and Yang, Dong and Xu,
  Ziyue and Zhao, Can and Li, Wenqi and Patel, Vishal M. and Landman, Bennett Allan
  and Xu, Daguang and He, Yufan and Nath, Vishwesh
author:
- given: Jeya Maria Jose
  family: Valanarasu
- given: Yucheng
  family: Tang
- given: Dong
  family: Yang
- given: Ziyue
  family: Xu
- given: Can
  family: Zhao
- given: Wenqi
  family: Li
- given: Vishal M.
  family: Patel
- given: Bennett Allan
  family: Landman
- given: Daguang
  family: Xu
- given: Yufan
  family: He
- given: Vishwesh
  family: Nath
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
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/valanarasu24a/valanarasu24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
