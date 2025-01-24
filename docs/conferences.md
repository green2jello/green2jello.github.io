---
layout: default
title: Conferences
permalink: /conferences/
---

# Conference Posts

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'conferences' %}
    <li>
      {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
