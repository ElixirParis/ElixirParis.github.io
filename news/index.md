---
layout: post
title: Elixir Paris News
desc: News from Elixir Meetups in Paris
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>