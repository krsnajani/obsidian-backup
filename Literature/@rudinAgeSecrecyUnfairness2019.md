---
aliases:
  - The age of secrecy and unfairness in recidivism prediction
tags: []
title: The age of secrecy and unfairness in recidivism prediction
authors:
  - Cynthia Rudin
  - Caroline Wang
  - Beau Coker
year: 2019
doi: https://doi.org/10.48550/arXiv.1811.00731
zotero: zotero://select/library/items/SU9VVB7L
bibliography:
  - lib
pdf: /Users/krishnajani/Zotero/storage/59X37SGT/Rudin et al. - 2019 - The age of secrecy and unfairness in recidivism prediction.pdf
---

<!-- START_ABSTRACT -->
In our current society, secret algorithms make important decisions about individuals. There has been substantial discussion about whether these algorithms are unfair to groups of individuals. While noble, this pursuit is complex and ultimately stagnating because there is no clear definition of fairness and competing definitions are largely incompatible. We argue that the focus on the question of fairness is misplaced, as these algorithms fail to meet a more important and yet readily obtainable goal: transparency. As a result, creators of secret algorithms can provide incomplete or misleading descriptions about how their models work, and various other kinds of errors can easily go unnoticed. By partially reverse engineering the COMPAS algorithm -- a recidivism-risk scoring algorithm used throughout the criminal justice system -- we show that it does not seem to depend linearly on the defendant's age, despite statements to the contrary by the algorithm's creator. Furthermore, by subtracting from COMPAS its (hypothesized) nonlinear age component, we show that COMPAS does not necessarily depend on race, contradicting ProPublica's analysis, which assumed linearity in age. In other words, faulty assumptions about a proprietary algorithm lead to faulty conclusions that go unchecked without careful reverse engineering. Were the algorithm transparent in the first place, this would likely not have occurred. The most important result in this work is that we find that there are many defendants with low risk score but long criminal histories, suggesting that data inconsistencies occur frequently in criminal justice databases. We argue that transparency satisfies a different notion of procedural fairness by providing both the defendants and the public with the opportunity to scrutinize the methodology and calculations behind risk scores for recidivism.
<!-- END_ABSTRACT -->
