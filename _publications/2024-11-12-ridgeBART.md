---
title: "Scalable piecwise smoothing with BART"
collection: 'publications'
permalink: /publications/2024-11-12-ridgeBART
excerpt: 
date: 2024-11-12
venue:
paperurl:
preprinturl: https://arxiv.org/abs/2411.07984
citation: 'Yee, R., Ghosh, S., and Deshpande, S.K. (2024+). &quot;Scalable piecewise smoothing with BART.&quot;'
note: 'preprint'
---

<b> Abstract </b> : 
Although it is an extremely effective, easy-to-use, and increasingly popular tool for nonparametric regression, the Bayesian Additive Regression Trees (BART) model is limited by the fact that it can only produce discontinuous output. Initial attempts to overcome this limitation were based on regression trees that output Gaussian Processes instead of constants. Unfortunately, implementations of these extensions cannot scale to large datasets. We propose ridgeBART, an extension of BART built with trees that output linear combinations of ridge functions (i.e., a composition of an affine transformation of the inputs and non-linearity); that is, we build a Bayesian ensemble of localized neural networks with a single hidden layer. We develop a new MCMC sampler that updates trees in linear time and establish nearly minimax-optimal posterior contraction rates for estimating Sobolev and piecewise anisotropic Sobolev functions. We demonstrate ridgeBART's effectiveness on synthetic data and use it to estimate the probability that a professional basketball player makes a shot from any location on the court in a spatially smooth fashion.
---


