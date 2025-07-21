---
title: "Know yourself"
layout: default
permalink: /categories/thoughts/
---

<h1>Posts in category: thoughts</h1>

<ul>
  {% for post in site.categories.know %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
