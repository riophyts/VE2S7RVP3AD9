# rio.tech - Portfolio Ingenieur Logiciel

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![License MIT](https://img.shields.io/badge/license-MIT-blue)

Portfolio personnel minimaliste et performant, construit en HTML et CSS purs. Aucun framework, aucune dependance runtime, aucun build : juste des fichiers statiques servis directement par GitHub Pages.

## Apercu

Un site one-page qui presente mon parcours d'ingenieur logiciel full-stack, mes services, une selection de projets recents et mes coordonnees. Le site est concu pour etre :

- **Rapide** : pas de JavaScript bloquant, pas de dependances lourdes
- **Accessible** : HTML semantique, contrastes respectes, navigation clavier
- **Maintenable** : structure simple, CSS variables, commentaires clairs

## Tech Stack

- **HTML5** - Markup semantique (header, nav, section, article, footer)
- **CSS3** - Custom properties, CSS Grid, Flexbox, media queries
- **Google Fonts** - Inter (400 a 800)
- **GitHub Pages** - Hebergement statique gratuit avec HTTPS

## Structure

```
/
├── index.html            # Page d'accueil / redirection
├── portfolio/
│   ├── index.html        # Portfolio principal (one-page)
│   ├── style.css         # Feuille de styles complete
│   └── assets/           # Images et ressources
├── docs/
│   └── CONTRIBUTING.md   # Guide de contribution
├── .gitignore            # Exclusions git
├── LICENSE               # Licence MIT
└── README.md             # Ce fichier
```

## Installation locale

Clone du depot puis ouverture dans un navigateur :

```bash
git clone https://github.com/riophyts/VE2S7RVP3AD9.git
cd VE2S7RVP3AD9
```

Pour un serveur local (recommande pour tester les chemins relatifs) :

```bash
# Python 3
python -m http.server 8000

# Ou avec Node
npx serve .
```

Puis ouvrir `http://localhost:8000/portfolio/` dans le navigateur.

## Deploiement

Le site est deploye automatiquement via GitHub Pages a chaque push sur la branche `main`.

URL de production : [https://riophyts.github.io/VE2S7RVP3AD9/](https://riophyts.github.io/VE2S7RVP3AD9/)

Pour activer GitHub Pages sur un fork :

1. Settings > Pages
2. Source : `Deploy from a branch`
3. Branch : `main` / `/ (root)`
4. Sauvegarder

## Personnalisation

1. Editer le contenu dans `portfolio/index.html` (textes, projets, liens)
2. Ajuster la palette dans `portfolio/style.css` (variables `:root`)
3. Ajouter vos visuels dans `portfolio/assets/`
4. Commit et push sur `main` pour declencher le redeploiement

Les couleurs primaires sont definies via `--primary` et `--primary-dark`. Changer ces deux variables suffit a retheme l'ensemble du site.

## Contribuer

Voir [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md) pour le guide complet.

## Licence

Projet sous licence [MIT](LICENSE). Libre de reutilisation avec mention du copyright.

---

Fait a Bordeaux avec du cafe et du code propre.
