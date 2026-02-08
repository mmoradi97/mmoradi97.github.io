---
layout: default
title: Home
---

<div class="hero">
  <p class="kicker">Personal blog & updates</p>
  <h1>Mo’s Blog</h1>
  <p class="lead">Notes, projects, and short writeups. Built with Jekyll + GitHub Pages.</p>

  <div class="cta-row">
    <a class="btn" href="/about/">About</a>
    <a class="btn btn-ghost" href="/projects/">Projects</a>
    <a class="btn btn-ghost" href="/contact/">Contact</a>
  </div>
</div>

<div class="grid">
  <div class="card">
    <h3>What I write about</h3>
    <p>Programming, tools, economics notes, and whatever I’m learning.</p>
  </div>

  <div class="card">
    <h3>Now</h3>
    <p>Building this site, adding a few posts, and polishing the design.</p>
  </div>

  <div class="card">
    <h3>Subscribe</h3>
    <p>Use the RSS feed to follow new posts.</p>
    <p><a href="/feed.xml">RSS feed</a></p>
  </div>
</div>

<hr />

## Latest posts

<ul class="post-list">
  {% for post in site.posts limit: 7 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
