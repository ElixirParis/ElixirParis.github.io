---
layout: default
title: Paris.ex - Elixir in Paris
desc: Elixir Meetups in Paris
---

<div class="col-sm-5">

  <h2 class="page-header">About us</h2>
  
  <p><b>Paris.ex</b> is the Parisian group for people interested in learning about the <a href="http://elixir-lang.org">Elixir Programming Language</a>. Elixir was written by José Valim, a well known and respected member of the Ruby community. And it may very well be "the next big thing".</p>
  
  <p>Elixir is a functional meta-programming aware language built on top of the Erlang VM. It is a dynamic language with flexible syntax with macros support that leverages Erlang's abilities to build concurrent, distributed, fault-tolerant applications with hot code upgrades. Elixir also provides first-class support for pattern matching, polymorphism via protocols (similar to Clojure's), aliases and associative data structures (usually known as dicts or hashes in other programming languages).</p>
  
  <p>Finally, Elixir and Erlang share the same bytecode and data types. This means you can invoke Erlang code from Elixir (and vice-versa) without any conversion or performance hit. This allows a developer to mix the expressiveness of Elixir with the robustness and performance of Erlang.</p>

</div>
<div class="col-sm-1"></div>
<div class="col-sm-6">
  <h2 class="page-header">Where to meet us?</h2>
  
  <p><a href="http://www.meetup.com/fr/elixir/">Paris.ex Meetup Page</a></p>
  
  <p><a href="https://groups.google.com/forum/#!forum/elixir-lang-fr">Paris.ex Google Group</a></p>
  
  <p>Paris.ex IRC Channel: #elixir-lang-fr on Freenode</a></p>
  
  
  <h2 class="page-header"><a href="/news">Latest news</a></h2>

  <ul class="media-list">
    {% for post in site.posts limit:1 %}
      <li class="media">
        <h3 class="media-heading"><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>
</div>