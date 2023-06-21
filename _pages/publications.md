---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=coVrnWIAAAAJ&hl=en">on Google Scholar</a>.</u>


Pre-prints & Working Papers
======
<ol>{% for post in site.publications reversed %}
  {% if post.note == 'preprint' or post.note == 'revision' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>

Peer-reviewed Publications
======
<!-
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
-->
{% include base_path %}

<ol reversed> {% for post in site.publications reversed %}
  {% if post.note != 'preprint' and post.note != 'in-preparation' %}
    <li>{% include archive-single-publication.html %}</li>
  {% endif %}
{% endfor %}</ol>
