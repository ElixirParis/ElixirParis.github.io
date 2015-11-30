---
layout: default
title: Paris.ex - Elixir à Paris
desc: Paris.ex - Groupe des utilisateurs francophone du langage Elixir 
---

<div class="col-sm-5">

  <h2 class="page-header">Présentation</h2>
  
  <p><b>Paris.ex</b> est le groupe parisien de ceux qui s’intéressent au <a href="http://elixir-lang.org">langage de programmation Elixir</a>. Elixir a été écrit par José Valim, un membre bien connu et respecté de la communauté Ruby. Elixir pourrait très bien être le nouvell langage prisé dans la boîte à outils des développeurs.</p>

  <p>Elixir est un langage fonctionnel construit au-dessus de la machine virtuelle Erlang, intégrant la meta-programmation au coeur de sa conception. C’est un langage dynamique à la syntaxe flexible, incluant des macros, qui exploitent les capacités d’Erlang pour construire des applications distribuées, tolérantes aux pannes, supportant les mises à jour de code à chaud. Elixir fournit également un support de premier plan pour le "pattern matching", le polymorphisme via des protocoles (similaire à Clojure), des aliases et des structures de données associatives (généralement connues sous le nom dicts ou hashes dans d'autres langages de programmation).</p>

  <p>Enfin, Elixir et Erlang partagent les mêmes bytecode et les mêmes types de données. Cela signifie que vous pouvez appeler le code Erlang depuis Elixir (et vice-versa) sans aucune conversion ou baisse de performance. Cela permet à un développeur de mélanger l'expressivité d’Elixir avec la robustesse et les performances d’Erlang.</p>

</div>
<div class="col-sm-1"></div>
<div class="col-sm-6">
  <h2 class="page-header">Où nous rencontrer</h2>
  
  <p><a href="http://www.meetup.com/fr/elixir/">Page Meetup de Paris.ex</a></p>
  
  <p><a href="https://groups.google.com/forum/#!forum/elixir-lang-fr">Liste de diffusion Paris.ex</a> (Google Groups)</p>

  <p><a href="https://github.com/ElixirParis">Paris.ex sur Github</a></p>

  <p>Channel IRC Paris.ex IRC: #elixir-lang-fr sur Freenode</a></p>

  <h2 class="page-header"><a href="/news">Dernières Nouvelles</a></h2>

  <ul class="media-list">
    {% for post in site.posts limit:1 %}
      <li class="media">
        <h3 class="media-heading"><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>
</div>
