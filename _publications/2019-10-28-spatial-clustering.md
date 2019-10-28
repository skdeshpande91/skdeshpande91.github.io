---
title: "Bayesian spatial clustering of crime in Philadelphia with particle optimizatino" 
collection: 'publications'
permalink: /publications/2019-10-28-spatial-clustering
excerpt:
date: 2019-10-28
venue:
paperurl:
citation: 'Balocchi, C., Deshpande, S.K., George, E.I., and Jensen, S.T. (2019). &quot; Bayesian spatial clustering of crime in Philadelphia with particle optimization&quot; (technical report).'
note: 'preprint'
---

<b> Abstract </b>: 
Bayesian hierarchical modeling is a natural way to study spatial variation in crime dynamics within a city at the neighborhood level, since it facilitates principled “sharing of information” between spatially adjacent neighborhoods. Typically, however, cities contain many physical and social boundaries that may manifest as spatial discontinu- ities in crime patterns. As a result, standard prior choices often yield overly-smooth pa- rameter estimates, which can ultimately produce mis-calibrated forecasts. To prevent potential over-smoothing, we introduce a prior that first partitions the neighborhoods into several clusters and then encourages spatial smoothness within each cluster. In our prior, we allow the effect of different covariates to be partitioned independently. As a result, conventional stochastic search techniques are computationally prohibitive, as they must traverse a combinatorially vast product space of partitions. We introduce an ensemble optimization procedure that simultaneously identifies several high prob- ability combinations of partitions by solving one optimization problem using a new local search strategy. We then use the identified combinations of partitions to estimate crime trends in Philadelphia between 2006 and 2017. On simulated and real data, our proposed method demonstrates good estimation and partition selection performance.

[Download paper here](https://skdeshpande91.github.io/files/spatial_clustering.pdf)
