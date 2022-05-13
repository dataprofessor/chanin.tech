---
title: "ERpred: a web server for the prediction of subtype-specific estrogen receptor antagonists"
date: 2022-04-05T23:15:00+07:00
slug: ERpred
category: projects
summary:
description:
cover:
  image:
  alt:
  caption:
  relative: true
showtoc: true
draft: false
---

# Abstract

Estrogen receptors alpha and beta (ERα and ERβ) are responsible for breast cancer metastasis through their involvement of clinical outcomes. Estradiol and hormone replacement therapy targets both ERs, but this often leads to an increased risk of breast and endometrial cancers as well as thromboembolism. A major challenge is posed for the development of compounds possessing ER subtype specificity. Herein, we present a large-scale classification structure-activity relationship (CSAR) study of inhibitors from the ChEMBL database which consisted of an initial set of 11,618 compounds for ERα and 7,810 compounds for ERβ. The IC50 was selected as the bioactivity unit for further investigation and after the data curation process, this led to a final data set of 1,593 and 1,281 compounds for ERα and ERβ, respectively. We employed the random forest (RF) algorithm for model building and of the 12 fingerprint types, models built using the PubChem fingerprint was the most robust (Ac of 94.65% and 92.25% and Matthews correlation coefficient (MCC) of 89% and 76% for ERα and ERβ, respectively) and therefore selected for feature interpretation. Results indicated the importance of features pertaining to aromatic rings, nitrogen-containing functional groups and aliphatic hydrocarbons. Finally, the model was deployed as the publicly available web server called ERpred at http://codes.bio/erpred where users can submit SMILES notation as the input query for prediction of the bioactivity against ERα and ERβ.

# Full-text article
[Read article](https://peerj.com/articles/11716/)
