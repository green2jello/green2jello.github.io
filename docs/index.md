---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Yet Another Personal Blog
---

I'm just talking out loud.

## Index of Posts
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%-d %B %Y" }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
