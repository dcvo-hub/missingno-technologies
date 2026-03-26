# MissingNo Technologies

Version Hugo de la landing page statique.

## Lancer en local

```bash
hugo server
```

## Build de production

```bash
hugo
```

Le site généré sera dans `public/`.

## Déploiement GitHub Pages

Le workflow `.github/workflows/hugo.yml` est inclus.

### Pré-requis

- créer un dépôt GitHub
- pousser ce projet sur la branche principale
- dans GitHub : **Settings > Pages**
- Source : **GitHub Actions**

Le workflow publiera automatiquement le site.
