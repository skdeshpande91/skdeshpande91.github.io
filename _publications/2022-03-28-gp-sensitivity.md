---
title: "Measuring the robustness of Gaussian processes to kernel choice"
collection: 'publications'
permalink: /publications/2022-03-28-gp-sensitivity
excerpt: 
date: 2022-03-28
venue: 'AISTATS 2022'
paperurl:
preprinturl: https://arxiv.org/abs/2106.06510
citation: 'Stephenson, W.T., Ghosh, S., Nguyen, T.D., Yurochkin, M, Deshpande, S.K., and Broderick, T. (2022). &quot;Measuring the sensitivt of Gaussian processes to kernel choice.&quot; <it>AISTATS 2022</i>.'
note: 'accepted'
---
<b> Abstract </b>: 
Gaussian processes (GPs) are used to make medical and scientific decisions, including in cardiac care and monitoring of carbon dioxide emissions. But the choice of GP kernel is often somewhat arbitrary. In particular, uncountably many kernels typically align with qualitative prior knowledge (e.g. function smoothness or stationarity). But in practice, data analysts choose among a handful of convenient standard kernels (e.g. squared exponential). In the present work, we ask: Would decisions made with a GP differ under other, qualitatively interchangeable kernels? We show how to formulate this sensitivity analysis as a constrained optimization problem over a finite-dimensional space. We can then use standard optimizers to identify substantive changes in relevant decisions made with a GP. We demonstrate in both synthetic and real-world examples that decisions made with a GP can exhibit substantial sensitivity to kernel choice, even when prior draws are qualitatively interchangeable to a user.
---

A pre-print is available at [arXiv:2106.06510](https://arxiv.org/abs/2106.06510).

