---
layout: default
title: Home
---

# Welcome to Nutritionist Melbourne 🍏
Your trusted source for health, diet, and nutrition in Melbourne.  

## Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
