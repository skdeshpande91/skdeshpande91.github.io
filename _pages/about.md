---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor in the Department of Statistics at the University of Wisconsin--Madison.
Prior to that, I completed a postdoc with Professor Tamara Broderick at MIT and earned my Ph.D. in Statistics at Wharton where I was supervised by Professors Ed George and Veronika Rockova.
My research interests include Bayesian hierarchical modeling, Bayesian regression trees, model selection, causal inference, and applications in public health and sports.

My CV is available [here](https://skdeshpande91.github.io/files/Deshpande_cv.pdf).


Recent Papers
======

{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
    {%include archive-single-publication-about.html %}
  {% endif %}
{% endfor %}

Working with me
======
If you are currently enrolled in, or accepted to, a UW-Madison graduate program (i.e. an MS, MA, or Ph.D. program), please feel free to email me about potential research opportunities.


If you are not a current or incoming UW-Madison graduate student but are interested in working together, please submit an application to one of our graduate programs; [more info at this link](https://stat.wisc.edu/graduate-studies/graduate-admissions/).
Unfortunately, I am not able to reply to all inquiries from students who are at other universities or are in the process of applying to UW-Madison graduate programs.




More about me
======

Before Wharton, I studied mathematics at MIT and spent a year at Jesus College, Cambridge as part of the (now sadly defunct) Cambridge-MIT Exchange.
When I'm not thinking about statistics, I enjoy cooking, making cocktails, photography, and watching sports (esp. Dallas teams!).
