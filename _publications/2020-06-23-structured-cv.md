---
title: "Approximate cross-validation for structured models"
collection: publications
permalink: /publications/2020-06-23-structured-cv
excerpt: 
date: 2020-06-23
venue: 'NeurIPS 2020'
preprinturl: https://arxiv.org/abs/2006.12669
paperurl: https://proceedings.neurips.cc/paper/2020/hash/636efd4f9aeb5781e9ea815cdd633e52-Abstract.html
citation: 'Ghosh, S., Stephenson, W.T., Nguyen, T.D., Deshpande, S.K., and Broderick T. (2020). &quot;Approximate cross-validiation for structured models.&quot; <i>NeurIPS 2020</i>'
note: 'published'
---

<b> Abstract </b>:

Many modern data analyses benefit from explicitly modeling dependence structure in data -- such as measurements across time or space, ordered words in a sentence, or genes in a genome. 
Cross-validation is the gold standard to evaluate these analyses but can be prohibitively slow due to the need to re-run already-expensive learning algorithms many times. 
Previous work has shown approximate cross-validation (ACV) methods provide a fast and provably accurate alternative in the setting of empirical risk minimization. 
But this existing ACV work is restricted to simpler models by the assumptions that (i) data are independent and (ii) an exact initial model fit is available. 
In structured data analyses, (i) is always untrue, and (ii) is often untrue. 
In the present work, we address (i) by extending ACV to models with dependence structure. 
To address (ii), we verify -- both theoretically and empirically -- that ACV quality deteriorates smoothly with noise in the initial fit. 
We demonstrate the accuracy and computational benefits of our proposed methods on a diverse set of real-world applications.

---

A pre-print is available at [arXiv:2006.12669](https://arxiv.org/abs/2006.12669v1).

The proceedings version is available at [this link](https://proceedings.neurips.cc/paper/2020/hash/636efd4f9aeb5781e9ea815cdd633e52-Abstract.html).
