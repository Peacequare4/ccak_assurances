# Projet CCAK Assurances - Site Web Vitrine

Ce projet est un site web vitrine complet pour le cabinet **CCAK Assurances**, développé uniquement avec HTML, CSS et JavaScript.

## Arborescence du Projet

Pour ouvrir ce projet dans **VS Code**, ouvrez simplement le dossier racine `ccak_project`.

```text
ccak_project/
├── index.html              # Fichier principal (Structure)
├── assets/
│   ├── css/
│   │   └── style.css       # Design et Styles (Bleu Confiance, Montserrat)
│   ├── js/
│   │   └── script.js       # Interactivité (Menu mobile, Tabs, Scroll)
│   ├── images/             # Dossier pour vos ressources visuelles
│   │   ├── hero.jpg        # Image de la bannière principale
│   │   ├── about.jpg       # Image de présentation du cabinet
│   │   ├── partners/       # Logos des partenaires (NSIA, STAR, SAAR)
│   │   ├── services/       # Images pour les services
│   │   ├── products/       # Images pour les produits
│   │   └── team/           # Photos de l'équipe (DG, etc.)
│   └── fonts/              # (Optionnel) Polices locales
└── README.md               # Guide d'utilisation
```

## Instructions pour les Images

J'ai déjà inclus des images illustratives pour vous permettre de voir le rendu. Pour personnaliser le site avec vos propres visuels :

1. **Logo** : Remplacez le texte dans `index.html` (classe `.logo-text`) par une balise `<img>` pointant vers votre fichier logo.
2. **Renommage** : Je vous suggère de garder des noms simples et descriptifs en minuscules, par exemple :
   - `logo-principal.png`
   - `banniere-accueil.jpg`
   - `photo-dg.jpg`
   - `partenaire-nsia.png`
3. **Format** : Utilisez du `.png` pour les logos (avec fond transparent) et du `.jpg` ou `.webp` pour les photos afin d'optimiser le temps de chargement.

## Modification sur VS Code

- Modifiez les textes directement dans `index.html`.
- Pour changer les couleurs, éditez les variables `:root` au début du fichier `assets/css/style.css`.
- Le site est entièrement responsive et prêt pour une mise en ligne.
