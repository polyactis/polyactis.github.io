---
layout: page
title: Accucopy
description: A computational method that infers Allele-Specific Copy Number alterations from low-coverage low-purity tumor sequencing data.
img: assets/img/Accucopy_frontpage.png
importance: 1
category: work
related_publications: true
---

# Introduction

[Accucopy](https://github.com/polyactis/Accucopy) {% cite Fan2021Accucopy %} is a CNA-calling method that extends our previous [Accurity](https://github.com/polyactis/Accurity) model to predict both total (TCN) and allele-specific copy numbers (ASCN) for the tumor genome. Accucopy adopts a tiered Gaussian mixture model coupled with an innovative autocorrelation-guided EM algorithm to find the optimal solution quickly. The Accucopy model utilizes information from both total sequencing coverage and allelic sequencing coverage. Through benchmark in both simulated and real-sequencing samples, we demonstrate that Accucopy is more accurate than existing methods

Accucopy's main strength is in handling low coverage and/or low tumor-purity samples.

# Publication

X Fan, G Luo, YS Huang# (2021) BMC Bioinformatics. [Accucopy: Accurate and Fast Inference of Allele-specific Copy Number Alterations from Low-coverage Low-purity Tumor Sequencing Data](https://doi.org/10.1186/s12859-020-03924-5).


