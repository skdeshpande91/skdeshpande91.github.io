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

<ul style="list-style-type:none">
  <li> Massachusetts Institute of Technology, CSAIL, 2018 -- present </li>
  <ul stle="list-style-type:none">
    <li> Supervisor: Tamara Broderick </li>
  </ul>
</ul>


Education
======
<ul>
  <li> Ph.D. in Statistics, University of Pennsylvania, May 2018 </li>
    <ul>
      <li> Thesis: "Bayesian model selection and estimation without MCMC" </li>
      <li> Thesis supervisors: Ed George and Veronika Rockova </li>
    </ul>
  <li> S.B. in Mathematics, Massachusetts Institute of Technology, June 2013 </li>
</ul>



Publications
======
  <ol reversed>{% for post in site.publications reversed %}
    {% if post.note != 'preprint' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>

Working Papers
======
  <ol>{% for post in site.publications reversed %}
    {% if post.note == 'preprint' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %} </ol>
  
Recent Talks
======
  <ul>{% for post in site.talks reversed  %}
    {% if forloop.index < 5 %}
      {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
  
Service
======
* Journal Reviewer: Annals of Applied Statistics, The American Statistician, Journal of Computational and Graphical Statistics, Bayesian Analysis, Journal of Quantitative Analysis in Sport, PLOS One

* Conference Reviewer: BNP @ NeurIPS 2018, AISTATS 2019, ICML 2019, UAI 2019, NeurIPS 2019, AAAI 2020 
