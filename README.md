# ATPHQC

**A**nalyse de **T**extes **PH**ilosophiques **Q**uébé**C**ois assistée par ordinateur

Ce dépôt contient les sources du site web du projet d’analyse de textes philosophiques québécois assistée par ordinateur.

# Notes techniques

Documentation du framework (Wowchemy) : https://bootstrap.hugoblox.com

## Serve

Pour développement local :

```bash
$ hugo serve
```

## Build

Local build :

```bash
$ hugo --minify
```

GH build :

```bash
$ git checkout main
$ git push
```

## Contenus

`content/`

### Acceuil

`content/_index.md`

## Partial template

Les *partial templates* locaux ont priorité sur le module Wowchemy. Voir [https://gohugo.io/templates/partials/#partial-template-lookup-order](https://gohugo.io/templates/partials/#partial-template-lookup-order).

## URL de déploiement

Ne pas oublier de configurer la variable `baseURL`

## Publications

- https://wowchemy-docs.netlify.app/content/publications/
  - voir section Modifying Publication Types
  - modifier i18n + data/publication_types.toml