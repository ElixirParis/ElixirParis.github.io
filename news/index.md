---
layout: post
title: Nouvelles de Paris.ex - Elixir à Paris
desc: Nouvelles sur la rencontre Meetup Elixir à Paris
---

<h1 class="page-header">Dernières Nouvelles</h1>

<ul class="media-list">
  {% for post in site.posts %}
    <li class="media">
      <h4><small>{{ post.date | date: "%d %B %Y" }}</small></h4>
      <h2 class="media-heading"><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
