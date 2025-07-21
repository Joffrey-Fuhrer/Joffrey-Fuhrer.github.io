---
title: "Personal thoughts"
layout: default
permalink: /categories/thoughts/
---

<h1>Posts in category: thoughts</h1>

<ul>
  {% for post in site.categories.thoughts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
