# Spilou - site web

site web officiel de Spilou, service de création de sites web express et modernes.

## description

Spilou est un service de création de sites web ultra rapides, personnalisables et intuitifs. Notre promesse : livrer un site moderne, professionnel et évolutif, en un temps record.

## technologies utilisées

- **Astro** : framework statique ultra-rapide
- **TailwindCSS** : styling moderne et responsive
- **TypeScript** : typage et robustesse du code
- **Netlify** : hébergement et déploiement continu

## installation

### prérequis

- Node.js v20.10+
- Yarn v1.22+

### commandes

```bash
# installation des dépendances
yarn install

# lancement en développement
yarn run dev

# build production
yarn run build

# prévisualisation du build
yarn run preview
```

## structure du projet

```
/
├── public/              # assets statiques (images, fonts, etc.)
├── src/
│   ├── components/      # composants réutilisables
│   ├── content/         # contenu markdown (blog, pages)
│   ├── layouts/         # layouts de page
│   ├── pages/           # pages du site
│   ├── styles/          # styles globaux
│   └── config/          # fichiers de configuration
├── astro.config.mjs     # configuration Astro
├── tailwind.config.js   # configuration Tailwind
└── package.json
```

## configuration

### couleurs de la marque

les couleurs sont définies dans `tailwind.config.js` :

- **primary** : #9FB3DF (bleu doux)
- **secondary** : #9EC6F3 (bleu clair)
- **tertiary** : #BDDDE4 (bleu-vert pastel)
- **accent** : #FFF1D5 (crème)

### contenu

le contenu est géré via des fichiers markdown dans `src/content/` :

- `src/content/pages/` : pages statiques
- `src/content/blog/` : articles de blog
- `src/config/` : configuration (menu, social, etc.)

## modification du contenu

### via l'interface

1. éditer les fichiers markdown dans `src/content/`
2. commit et push sur GitHub
3. déploiement automatique via Netlify

### via ChatGPT (intégration future)

les modifications pourront être effectuées via ChatGPT qui interagira directement avec le repository GitHub.

## déploiement

le site est déployé automatiquement sur Netlify à chaque push sur la branche `main`.

### configuration Netlify

- **build command** : `yarn build`
- **publish directory** : `dist`
- **domaine** : spilou.com

## SEO

le site est optimisé pour le référencement :

- métadonnées configurables par page
- sitemap automatique
- robots.txt
- Open Graph et Twitter Cards
- temps de chargement < 1 seconde

## performance

scores PageSpeed Insights visés :

- performance : 90-100
- accessibilité : 90-100
- bonnes pratiques : 100
- SEO : 100

## contact

pour toute question : contact@spilou.com

## licence

© 2025 Spilou. tous droits réservés.
