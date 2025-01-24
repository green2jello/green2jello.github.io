---
layout: default
title: OMSCS
permalink: /omscs/
---

# OMSCS Posts

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'omscs' %}
    <li>
      {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
