---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

<b> Under construction </b>


Upcoming talks
======

<ol>{% for post in site.talks reversed %}
  {% if post.note == 'upcoming' %}
    <li>{ %include archive-single-talk.html %}</li>
  {% endif %}
{% endfor %} </ol>

Past talks
======

<ol reversed> {% for post in site.talks reversed %}
  {% if post.note == "past" %}
    <li>{% include archive-single-talk.html %}</li>
  {% endif %}
{% endfor %}</ol>


