---
layout: default
title: Artificial Intelligence
permalink: /ai/
---

# AI Posts

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'ai' %}
    <li>
      {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
