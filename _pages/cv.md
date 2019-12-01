---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


A PDF version of my full CV is available [here](https://skdeshpande91.github.io/files/Deshpande_cv.pdf).

Employment
======

<ul style="list-style-type:none">
  <li> Postdoctoral Associate, Massachusetts Institute of Technology, CSAIL, 2018 -- present </li>
  <ul style="list-style-type:none">
    <li> Supervisor: Tamara Broderick </li>
  </ul>
</ul>


Education
======
<ul style="list-style-type:none">
  <li> Ph.D. in Statistics, University of Pennsylvania, May 2018 </li>
    <ul style="list-style-type:none">
      <li> Thesis: "Bayesian model selection and estimation without MCMC" </li>
      <li> Thesis supervisors: Ed George and Veronika Rockova </li>
    </ul>
  <li> S.B. in Mathematics, Massachusetts Institute of Technology, June 2013 </li>
</ul>



Publications
======
  <ol reversed>{% for post in site.publications reversed %}
    {% if post.note != 'preprint' and post.note != 'in-preparation' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>

Working Papers & Papers in Progress
======
  <ul>{% for post in site.publications reversed %}
    {% if post.note == 'preprint' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %} </ul>

  <ul>{% for post in site.publications reversed %}
    {% if post.note == 'in-preparation' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %} </ul>

Awards & Honors
======
<ul>
  <li> Third prize, Ruth and William Silen, M.D. Poster Award. New England Science Symposium. 2019 </li>
  <li> Finalist, National Football League Big Data Bowl. 2019 </li>
  <li> Deming Student Scholar Award, Deming Conference on Applied Statistics. 2017 </li>
  <li> J. Parker Bursk Memorial Award (2017). </li>
      <p> <i> Awarded by the Statistics Department at the Wharton School for excellence in research. </i> </p>
  <li> Donald S. Murray Prize (2017). </li>
      <p> <i> Awarded by the Statistics Department at the Wharton School for excellence in teaching. </i> </p>
</ul>
  
Recent Talks
======
  <ul>{% for post in site.talks reversed  %}
    {% if forloop.index < 6 %}
      {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
  
Service
======
* Journal Reviewer: Annals of Applied Statistics, The American Statistician, Journal of Computational and Graphical Statistics, Bayesian Analysis, Journal of Quantitative Analysis in Sport, PLOS One

* Conference Reviewer: BNP @ NeurIPS 2018, AISTATS 2019, ICML 2019, UAI 2019, NeurIPS 2019, AAAI 2020 
