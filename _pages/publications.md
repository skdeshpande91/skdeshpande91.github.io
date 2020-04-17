---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.note != 'preprint' and post.note != 'in-preparation' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
<!--
Pre-prints & Working Papers
======
{% for post in site.publications reversed %}
  {% if post.note == 'preprint' or post.note == 'in-preparation' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

-->
