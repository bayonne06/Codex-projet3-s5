Fiche d'architecture — projet/

Objectif
- Page statique présentant l'équipe (fichier `team.html`) avec styles séparés en partials CSS.

Arborescence
```
projet/
├── team.html
├── images/
│   └── avatar-placeholder.svg
└── css/
    ├── main.css        ← regroupe tout (importe les fichiers ci-dessous)
    ├── variables.css
    ├── reset.css
    ├── components.css
    ├── header.css
    ├── team.css
    └── footer.css
```

Description des fichiers
- `team.html` : page d'entrée. Lie `css/main.css`.
- `css/main.css` : fichier central qui importe les partials (`reset.css`, `variables.css`, `components.css`, `header.css`, `team.css`, `footer.css`).
- `css/variables.css` : variables CSS (couleurs, taille max du container...).
- `css/reset.css` : reset minimal.
- `css/components.css` : styles réutilisables (boutons, inputs, liens, icônes).
- `css/header.css` : styles de l'en-tête.
- `css/team.css` : styles spécifiques à la page équipe (grille, cartes membres).
- `css/footer.css` : styles de pied de page.
- `images/avatar-placeholder.svg` : image de remplacement pour les avatars.

Prévisualisation locale
- Ouvrir `projet/team.html` directement dans le navigateur ou lancer un petit serveur local depuis la racine du projet :

```bash
python3 -m http.server 8000
```

Puis ouvrir : http://localhost:8000/projet/team.html

Conseils & remarques
- Pour le prototypage, garder les partials séparés facilite la maintenance.
- Pour production, envisager un build (concaténation/minification) pour générer un `main.min.css`.
- Respecter les noms de fichiers et chemins relatifs pour que `main.css` importe correctement les partials.

Si vous voulez, je peux :
- Générer un `main.min.css` combiné.
- Ajouter des exemples de cartes membres supplémentaires dans `team.html`.
- Exécuter le serveur local et ouvrir la page pour vous (si vous souhaitez).