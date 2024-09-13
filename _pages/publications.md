---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles <a href="https://scholar.google.com/citations?user=coVrnWIAAAAJ&hl=en">on Google Scholar</a>.


Pre-prints & working papers
======
<ol>{% for post in site.publications reversed %}
  {% if post.note == 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>

Peer-reviewed Publications
======
{% include base_path %}

<ol reversed> {% for post in site.publications reversed %}
  {% if post.note != 'preprint' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>
