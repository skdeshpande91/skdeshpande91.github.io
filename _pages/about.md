---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I will be joining the Statistics Department at the University of Wisconsin -- Madison in Fall 2021.
I completed a postdoc with Professor Tamara Broderick at MIT.
Prior to that, I completed my Ph.D. in Statistics at Wharton where I was supervised by Professors Ed George and Veronika Rockova.
My research interests include Bayesian hierarchical modeling, Bayesian regression trees, model selection, causal inference, and applications in public health and sports.

Recent Papers
======

{% for post in site.publications reversed %}
  {% if forloop.index < 6 and post.note != 'in-preparation' %}
    {%include archive-single-publication-about.html %}
  {% endif %}
{% endfor %}


More about me
======

Before Wharton, I studied mathematics at MIT and spent a year at Jesus College, Cambridge as part of the (now sadly defunct) Cambridge-MIT Exchange.
When I'm not thinking about statistics, I enjoy cooking, making cocktails, photography, and watching sports (esp. Dallas teams!).
