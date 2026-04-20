# Contribuer au projet

Merci de votre interet pour ce projet. Voici comment contribuer efficacement.

## Workflow de contribution

1. Forkez le repository
2. Creez une branche dediee (`git checkout -b feature/ma-feature`)
3. Committez vos changements avec un message clair (`git commit -m "feat: ajout de la section temoignages"`)
4. Pushez votre branche (`git push origin feature/ma-feature`)
5. Ouvrez une Pull Request en decrivant le pourquoi du changement

## Conventions de code

- **Pas de framework** : on reste en HTML et CSS vanilla, sans build step
- **Indentation** : 4 espaces, jamais de tabulations
- **CSS** : privilegier les custom properties deja definies dans `:root`
- **Nommage** : classes en kebab-case, pas de camelCase
- **Responsive** : tester sur mobile (<768px) avant de soumettre
- **Accessibilite** : respecter la semantique HTML, attributs `alt` sur les images, contrastes minimaux WCAG AA

## Images et assets

- Format prefere : WebP (avec fallback JPG/PNG si necessaire)
- Poids max par image : 200 KB apres optimisation
- Dimensions : adapter au contexte d'affichage, ne pas livrer de 4K pour un thumbnail 300px
- Outils recommandes : [Squoosh](https://squoosh.app), `sharp-cli`, `imagemin`

## Messages de commit

Format recommande (non strict) :

```
<type>: <description courte>

[corps optionnel]
```

Types courants : `feat`, `fix`, `docs`, `style`, `refactor`, `chore`.

Exemples :
- `feat: ajout d'une section temoignages clients`
- `fix: correction du overflow sur mobile < 360px`
- `docs: mise a jour du README pour le deploiement`

## Signaler un bug

Ouvrez une issue en precisant :

- Le **comportement attendu**
- Le **comportement observe**
- Les **etapes de reproduction**
- Votre **navigateur et OS** (ex: Chrome 131 / macOS 15.1)
- Une **capture d'ecran** ou une video courte si possible

## Suggestions et questions

Pour toute suggestion de fonctionnalite ou question generale, ouvrez une issue avec le tag `question` ou `enhancement`. Les discussions sont toujours bienvenues.

## Code of conduct

Soyez respectueux et constructif. Les contributions techniques comme humaines sont valorisees de la meme maniere.
