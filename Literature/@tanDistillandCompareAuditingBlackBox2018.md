---
aliases:
  - "Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation"
tags: []
title: "Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation"
authors:
  - Sarah Tan
  - Rich Caruana
  - Giles Hooker
  - Yin Lou
year: 2018
doi: https://doi.org/10.1145/3278721.3278725
zotero: zotero://select/library/items/54C8PH2Y
bibliography:
  - lib
pdf: /Users/krishnajani/Zotero/storage/Q2DGYZMR/Tan et al. - 2018 - Distill-and-Compare Auditing Black-Box Models Using Transparent Model Distillation.pdf
---

<!-- START_ABSTRACT -->
Black-box risk scoring models permeate our lives, yet are typically proprietary or opaque. We propose Distill-and-Compare, an approach to audit such models without probing the black-box model API or pre-defining features to audit. To gain insight into black-box models, we treat them as teachers, training transparent student models to mimic the risk scores assigned by the black-box models. We compare the mimic model trained with distillation to a second, un-distilled transparent model trained on ground-truth outcomes, and use differences between the two models to gain insight into the black-box model. We demonstrate the approach on four data sets: COMPAS, Stop-and-Frisk, Chicago Police, and Lending Club. We also propose a statistical test to determine if a data set is missing key features used to train the black-box model. Our test finds that the ProPublica data is likely missing key feature(s) used in COMPAS.
<!-- END_ABSTRACT -->
