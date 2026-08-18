---
layout: default
permalink: /blog/
title: blog
nav: false
pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1
    after: 3
---

<div class="post">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="post-description">Research notes and updates.</p>
  </header>

  <ul class="post-list">
    {% for post in paginator.posts %}
      <li>
        <h3><a class="post-title" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>
</div>
