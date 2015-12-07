---
layout: post
title: Phoenix au Meetup Parix.ex et l’espoir d’une application Open Source de référence
type: news
---
<p>Le <a href="http://www.meetup.com/fr/elixir/events/225579791/">meetup Paris.ex #4</a> a eu lieu fin novembre. Ce fut une bonne rencontre. Nous avons maintenant le lieu idéal. Les participants sont sympas et apprécient le temps passé ensemble.</a></p>

<p>Les développeurs reviennent et commencent à se porter volontaire pour de (courtes) présentations. De nouveaux visages font leur apparition. Nous faisons un excellent travail.</p>

<p>Le thème cette fois était assez énorme et au centre de la communauté <a href="http://elixir-lang.org/">Elixir</a>.</p>

<p>J’ai fait une présentation sur le framework Phoenix couvrant la plupart de ses aspects :</p>

<ul>
<li>Explications nécessaires sur l’objectif du design du framework.</li>
<li>Description de l'accent mis sur la productivité et la performance.</li>
<li>Architecture du framework.</li>
<li>Court tutoriel couvrant la mise en place d'un nouveau projet Phoenix avec des <i>scaffoldings</i>, un exemple de plug, et une démonstration de construction d’un Channel pas à pas.</li>
</ul>

<p>Les slides de présentation en PDF peuvent être téléchargés ici : <a href="https://blog.process-one.net/wp-content/uploads/2015/11/Introduction-au-développement-Web-avec-le-framework-Phoenix.pdf">Introduction au développement Web avec le framework Phoenix</a></p>

<p>Lors de la préparation de cette présentation, j’ai eu besoin d’une application hypothétique. J’ai réalisé alors que le monde Phoenix n’avait pas une sorte d’application canonique qui pourrait servir d’exemple à la construction d’une application Phoenix. Ceux qui ont programmé en Java dans les premiers jours de la plate-forme serveur peuvent se rappeler le (tristement) célèbre <a href="http://www.oracle.com/technetwork/java/index-136650.html">Java Pet Store</a>.</p>

<p>Je pensais utiliser un exemple plus utile qui permettrait d’illustrer le développement du site web Phoenix et pourrait même se transformer en un véritable site de la communauté.</p>

<p>Depuis longtemps j’ai en tête un site communautaire pour la publication de critiques de restaurants par des enfants, en utilisant leurs propres critères (comme le temps de service, une attention particulière du personnel, l’espace pour courir entre les plats, etc...). J’avais commencé un prototype en Ruby on Rails avec mes enfants il y a quelques années.</p>

<p>J’ai pensé que je pourrais relancer le projet grâce au framework Phoenix en Elixir. Tout en préparant ma présentation Phoenix hier, je me suis dit que le groupe Meetup Paris.ex pourrait utiliser cette application comme illustration pour les présentations du prochain Meetup. Il y a plein de choses à montrer : la gestion réelle des utilisateurs / authentification, meilleur modèle pour les restaurants et les critiques des enfants, lien vers le compte des parents pour l’approbation, le déploiement en prod.</p>

<p>Nous discutons déjà d’une immersion dans Ecto ou de la démonstration d’exrm avec cette application par exemple.</p>

<p>Nous étions tous enthousiastes hier sur l'utilisation de cette démo comme un outil pour illustrer divers aspects de la programmation Elixir.</p>

<p>Ce n’est bien sûr pas exclusif à Paris.ex. Si d’autres groupes Elixir veulent se joindre et aider à construire une sorte d’application de référence en Phoenix Elixir, vous êtes les bienvenus. C’est pourquoi nous utilisons l’Anglais comme langage primaire de développement (même si nous espérons avoir une app. multilingue).
Si nous atteignons un bon état, j’ai même le nom de domaine qui convient pour déployer la version en production !</p>

<p>Voyons où cela nous mène ! J’espère que Gastronokids deviendra le framework Phoenix de référence un jour. Ce qu’il adviendra dépend de vous !</p>

<p>Le code initial du projet est sur Github : <a href="https://github.com/ElixirParis/gastronokids">ElixirParis/gastronokids</a></p>

<p>Ce n’est rien de plus qu’un <i>scaffolding</i> standard Phoenix pour le moment, mais nous espérons l’améliorer un peu plus chaque mois.</p>

<p>On se voit au <a href="http://www.meetup.com/fr/elixir/events/226102885/">prochain Paris.ex meetup en janvier 2016</a> !</p>

<p>Vous pouvez voir ici l’enregistrement de mon talk (en Français) :</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/GPF6w3CsWio" frameborder="0" allowfullscreen></iframe>
