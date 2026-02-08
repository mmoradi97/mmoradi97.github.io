---
layout: default
title: Home
---

# Mo’s Blog

Welcome! This is my personal blog where I post notes, projects, and updates.

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small> — {{ post.date | date_to_long_string }}</small>
    </li>
  {% endfor %}
</ul>
