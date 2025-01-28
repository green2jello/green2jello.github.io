---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Yet Another Personal Blog
---

Hi! Take a look at some of the posts below, at the posts by topic in the navigation bar above or check out my [About Me](/about/) page here.

## Index of Posts
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
