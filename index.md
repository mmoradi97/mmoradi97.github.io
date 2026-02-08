---
layout: default
title: Home
---

<div class="hero">
  <p class="kicker">Personal blog & updates</p>
  <h1>Mo’s Blog</h1>
  <p class="lead">Notes, projects, and short writeups. Built with Jekyll + GitHub Pages.</p>
</div>

<h2>Latest posts</h2>
<ul class="post-list">
  {% for post in site.posts limit: 8 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>

<p class="home-note">More links (About / Projects / Contact / RSS) are in the footer.</p>
