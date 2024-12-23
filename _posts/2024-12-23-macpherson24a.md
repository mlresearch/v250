---
title: Automated ranking of chest x-ray radiological finding severity in a binary
  label setting
abstract: 'Machine learning has demonstrated the ability to match or exceed human
  performance in detecting a range of abnormalities in chest x-rays. However, current
  models largely operate within a binary classification paradigm with findings either
  present or absent using fixed decision thresholds, whereas many clinical findings
  can be more usefully described on a scale of severity which a skilled radiologist
  will incorporate into a more nuanced report. This limitation is due, in part, to
  the difficulty and expense of manually annotating fine-grained labels for training
  and test images versus the relative ease of automatically extracting binary labels
  from the associated free text reports using NLP algorithms. In this paper we examine
  the ability of models trained with only binary training data to give useful abnormality
  severity information from their raw outputs. We assess performance on a ranking
  task using manually ranked test sets for each of five findings: cardiomegaly, consolidation,
  paratracheal hilar changes, pleural effusion and subcutaneous emphysema. We find
  the raw model output agrees with human-assessed severity ranking with Spearmanś
  rank coefficients between 0.563 - 0.848. Using patient age as an additional radiological
  finding with full ground truth ranking available, we go on to compare a binary classifier
  output against a fully supervised RankNet model, quantifying the reduction in training
  data required in the fully supervised setting for equivalent performance. We show
  that model performance is improved using a semi-supervised approach supplementing
  a smaller set of fully supervised images with a larger set of binary labelled images.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: macpherson24a
month: 0
tex_title: Automated ranking of chest x-ray radiological finding severity in a binary
  label setting
firstpage: 949
lastpage: 963
page: 949-963
order: 949
cycles: false
bibtex_author: Macpherson, Matthew and Muthuswamy, Keerthini and Amlani, Ashik and
  Goh, Vicky and Montana, Giovanni
author:
- given: Matthew
  family: Macpherson
- given: Keerthini
  family: Muthuswamy
- given: Ashik
  family: Amlani
- given: Vicky
  family: Goh
- given: Giovanni
  family: Montana
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
pdf: https://raw.githubusercontent.com/mlresearch/v250/main/assets/macpherson24a/macpherson24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
