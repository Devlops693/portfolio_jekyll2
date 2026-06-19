---
layout: page
title: "Projets"
description: "Réalisations académiques et personnelles de Prénom Nom."
---

Voici une sélection de mes réalisations. Chaque projet précise le contexte,
les technologies utilisées et les liens utiles.

<ul class="project-list">
{% assign items = site.projects | sort: "date" | reverse %}
{% for project in items %}
  <li>
    <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
    <p>{{ project.summary }}</p>
    {% if project.tech %}<p><small>🛠️ {{ project.tech | join: ", " }}</small></p>{% endif %}
  </li>
{% endfor %}
</ul>

<!--
  Pour ajouter un projet : crée un fichier dans _projects/ (ex: _projects/mon-projet.md).
  Il apparaîtra automatiquement ici.
-->
