---
title: "Crime in Philadelphia: Bayesian Clustering with Particle Optimization" 
collection: 'publications'
permalink: /publications/2019-11-27-particle-clustering
excerpt: ''
date: 2019-11-27
venue:
paperurl: 
preprinturl: https://arxiv.org/abs/1912.00111
citation: 'Balocchi, C., Deshpande, S.K., George, E.I., and Jensen, S.T. (2019). &quot;Crime in Philadelphia: Bayesian clustering  with particle optimization.&quot;'
note: 'preprint'
---
<b> Abstract </b> : 
Accurate estimation of the change in crime over time is a critical first step towards better understanding of public safety in large urban environments.
Bayesian hierarchical modeling is a natural way to study spatial variation in urban crime dynamics at the neighborhood level, since it facilitates principled "sharing of information" between adjacent neighborhoods. 
Typically, however, cities contain many physical and social boundaries that may manifest as spatial discontinuities in crime patterns.
In this situation, standard prior choices often yield overly-smooth parameter estimates, which can ultimately produce miscalibrated forecasts.
To prevent potential over-smoothing, we introduce a prior that first partitions the set of neighborhoods into several clusters and then encourages spatial smoothness within each cluster.
In terms of model implementation, conventional stochastic search techniques are computationally prohibitive, as they must traverse a combinatorially vast space of partitions.
We introduce an ensemble optimization procedure that simultaneously identifies several high probability partitions by solving one optimization problem using a new local search strategy.
We then use the identified partitions to estimate crime trends in Philadelphia between 2006 and 2017.
On simulated and real data, our proposed method demonstrates good estimation and partition selection performance.

---

A pre-print is available at [arXiv:1912.00111](https://arxiv.org/abs/1912.00111).

Code for this paper is available at [this GitHub repo](https://github.com/cecilia-balocchi/particle-optimization).

