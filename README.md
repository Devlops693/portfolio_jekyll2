# Portfolio Jekyll — Démarrage

## Mise en route (100 % sur GitHub, sans rien installer)

1. Crée un dépôt sur GitHub (ex. `portfolio`).
2. Pousse tout le contenu de ce dossier dedans (branche `main`).
3. Dépôt → **Settings → Pages → Build and deployment → Source : GitHub Actions**.
4. Renseigne `url` et `baseurl` dans `_config.yml` (voir commentaires 👉).
5. Chaque `git push` sur `main` reconstruit et publie le site (onglet **Actions**).

## (Optionnel) Tester en local

```bash
bundle install
bundle exec jekyll serve
# -> http://localhost:4000
```

## Checklist du sujet

- [ ] Plusieurs pages distinctes (accueil, à propos, projets, contact)
- [ ] Navigation claire et cohérente
- [ ] Généré avec Jekyll + thème (minima)
- [ ] Déploiement automatisé via GitHub Actions (sans erreur)
- [ ] SEO : title + description sur chaque page (jekyll-seo-tag + sitemap)
- [ ] Accessibilité : alt sur images, contraste, labels de formulaire
- [ ] Collection `_projects`
- [ ] Formulaire de contact statique
- [ ] Audit Lighthouse passé
- [ ] `portfolio.md` rempli (lien dépôt + lien site)
- [ ] Ressources libres de droits ou créditées
