---
title: "Multivariate varying-coefficient {BART} with graphical horseshoe priors"
collection: 'publications'
permalink: /publications/2026-06-30-multiVCBART
excerpt: 
date: 2026-06-30-multiVCBART
venue:
paperurl:
preprinturl: https://arxiv.org/abs/2506.13007
citation: 'Ghosh, S. and Deshpande, S.K. (2026+). &quot;Multivariate varying-coefficient BART with graphical horseshoe priors.&quot;'
note: 'preprint'
---
<b> Abstract </b> : 
Modern multivariate regression problems involve several related outcomes whose regression effects are not only nonlinear, heterogeneous, and outcome-specific, but also where the residual dependence among outcomes is scientifically meaningful. Existing multivariate Bayesian tree-based methods typically address only part of this problem: some impose substantial sharing of tree architecture across outcomes, which is overly restrictive when responses depend on distinct predictors or effect modifiers, while others accommodate residual dependence but retain simpler mean structures. This paper develops multiVCBART, a multivariate varying-coefficient Bayesian additive regression tree framework that jointly models flexible outcome-specific coefficient surfaces and a sparse residual precision matrix. Each entry of the coefficient matrix $B(x)$ is represented by an independent BART ensemble, allowing predictor effects to vary nonlinearly with modifiers x across outcomes, while a Graphical Horseshoe prior on the precision matrix $\Omega$ captures parsimonious residual conditional dependence. To permit efficient computation, we introduce a sampler that reduces the multivariate Gaussian likelihood to a sequence of scalar pseudo-response updates, decoupling the tree backfitting from the Graphical Horseshoe step. Theoretically, we establish the first posterior contraction rates for a multivariate BART model with jointly estimated residual dependence, proving near-minimax adaptation to underlying smoothness and structural sparsity. Empirically, multiVCBART outperforms existing multivariate tree models and Bayesian SUR competitors on sparse, high-dimensional datasets. Finally, in a re-analysis of the Genomics of Drug Sensitivity in Cancer dataset, our method identifies distinct biomarker signals and recovers a coherent residual pharmacologic network.
---

