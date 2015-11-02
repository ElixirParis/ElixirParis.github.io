---
layout: post
title: Paris.ex News - Elixir in Paris
desc: News from Elixir Meetups in Paris
---

<h1 class="page-header">Latest news</h1>

<ul class="media-list">
  {% for post in site.posts %}
    <li class="media">
      <h4><small>{{ post.date | date: "%d %B %Y" }}</small></h4>
      <h2 class="media-heading"><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>