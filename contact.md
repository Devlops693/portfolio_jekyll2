---
layout: page
title: "Contact"
description: "Contacter Prénom Nom."
---

## Me contacter

- 📧 **Email :** [prenom.nom@example.com](mailto:prenom.nom@example.com)
- 💻 **GitHub :** [github.com/VOTRE-USER](https://github.com/VOTRE-USER)
- 🔗 **LinkedIn :** [linkedin.com/in/votre-profil](https://linkedin.com/in/votre-profil)

## Formulaire

<form action="https://formspree.io/f/VOTRE_ID" method="POST" class="contact-form">
  <p>
    <label for="name">Nom</label><br>
    <input type="text" id="name" name="name" required>
  </p>
  <p>
    <label for="email">Email</label><br>
    <input type="email" id="email" name="email" required>
  </p>
  <p>
    <label for="message">Message</label><br>
    <textarea id="message" name="message" rows="5" required></textarea>
  </p>
  <p><button type="submit">Envoyer</button></p>
</form>

<!--
  Le sujet demande un formulaire STATIQUE (pas de backend à coder).
  Deux options simples, au choix :
   1) Formspree (gratuit) : crée un compte sur formspree.io, récupère ton ID
      et remplace VOTRE_ID dans action="..." ci-dessus.
   2) Aucun service externe : remplace le <form> par un simple lien mailto:
      <a href="mailto:prenom.nom@example.com">Écrivez-moi</a>
  Note d'accessibilité : chaque champ a bien un <label for> associé (bon pour Lighthouse).
-->
