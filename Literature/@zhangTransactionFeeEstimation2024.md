---
aliases:
  - Transaction Fee Estimation in the Bitcoin System
tags: []
title: Transaction Fee Estimation in the Bitcoin System
authors:
  - Limeng Zhang
  - Rui Zhou
  - Qing Liu
  - Chengfei Liu
  - M. Ali Babar
year: 2024
doi: ""
zotero: zotero://select/library/items/7KKP9MI6
bibliography:
  - lib
pdf: /home/krishnaj/docs/paper_lib/Zhang et al_2024_Transaction Fee Estimation in the Bitcoin System.pdf
---

<!-- START_ABSTRACT -->
In the Bitcoin system, transaction fees serve as an incentive for blockchain confirmations. In general, a transaction with a higher fee is likely to be included in the next block mined, whereas a transaction with a smaller fee or no fee may be delayed or never processed at all. However, the transaction fee needs to be specified when submitting a transaction and almost cannot be altered thereafter. Hence it is indispensable to help a client set a reasonable fee, as a higher fee incurs over-spending and a lower fee could delay the confirmation. In this work, we focus on estimating the transaction fee for a new transaction to help with its confirmation within a given expected time. We identify two major drawbacks in the existing works. First, the current industry products are built on explicit analytical models, ignoring the complex interactions of different factors which could be better captured by machine learning based methods; Second, all of the existing works utilize limited knowledge for the estimation which hinders the potential of further improving the estimation quality. As a result, we propose a framework FENN, which aims to integrate the knowledge from a wide range of sources, including the transaction itself, unconfirmed transactions in the mempool and the blockchain confirmation environment, into a neural network model in order to estimate a proper transaction fee. Finally, we conduct experiments on real blockchain datasets to demonstrate the effectiveness and efficiency of our proposed framework over the state-of-the-art works evaluated by MAPE and RMSE. Each variation model in our framework can finish training within one block interval, which shows the potential of our framework to process the realtime transaction updates in the Bitcoin blockchain.
<!-- END_ABSTRACT -->
