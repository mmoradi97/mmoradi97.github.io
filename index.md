---
layout: default
title: Home
---

<div class="layout">
  <main class="main">
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
  </main>

  <aside class="sidebar">
    <div class="card">
      <h3>Quick links</h3>
      <p><a href="/about/">About</a></p>
      <p><a href="/projects/">Projects</a></p>
      <p><a href="/contact/">Contact</a></p>
    </div>

    <div class="card">
      <h3>Subscribe</h3>
      <p><a href="/feed.xml">RSS feed</a></p>
    </div>

    <div class="card">
      <h3>Contact</h3>
      <p>Email: <a href="mailto:mmoradi97@icloud.com">mmoradi97@icloud.com</a></p>
    </div>
  </aside>
</div>
