---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Employment
======

* Massachusetts Institute of Technology, CSAIL, 2018 -- present
    *Post-doctoral Association
    *Supervisor: Tamara Broderick

Education
======

* Ph.D in Statistics, University of Pennsylvania, May 2018
    *Thesis title: "Bayesian model selection and estimation without MCMC"
    *Thesis Supervisors: Ed George and Veronika Rockova

* S.B. in Mathematics, Massachusetts Institute of Technology, June 2013

Publications
======
  <ol reversed>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

Working Papers
======
  <ol>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
  
Recent Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
  
Service
======
* Journal Reviewer: Annals of Applied Statistics, The American Statistician, Journal of Computational and Graphical Statistics, Bayesian Analysis, Journal of Quantitative Analysis in Sport, PLOS One

* Conference Reviewer: BNP @ NeurIPS 2018, AISTATS 2019, ICML 2019, UAI 2019, NeurIPS 2019, AAAI 2020 
