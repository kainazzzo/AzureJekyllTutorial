---
layout: default
title: Home
---

<h2>Welcome to My Jekyll Site</h2>

<p>This is a simple Jekyll site that is hosted on Azure Static Web Apps.</p>

<h3>Latest Blog Posts</h3>

<ul>
  {% for post in site.posts limit:5 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
