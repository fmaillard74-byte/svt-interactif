# Règles du dépôt svt-interactif

Site publié avec GitHub Pages depuis la branche `main` :
https://fmaillard74-byte.github.io/svt-interactif/

Le dépôt est **public** : tout ce qui est déposé est visible par tous, élèves compris.

## Créer une page HTML
- Toujours un **fichier HTML autonome** (CSS et JS dans le fichier), jamais un « Document » ou un « Design » Claude : ceux-ci ne s'affichent pas sur GitHub Pages.
- Bibliothèques externes autorisées uniquement depuis un CDN avec une version fixe ; polices Google Fonts acceptées.
- Mise en page lisible sur téléphone.
- Langue : français.

## Créer un PDF
- Enregistrer les PDF dans le dossier `pdf/`.
- Si une page HTML existe sur le même thème, y ajouter un lien vers le PDF.

## Quand l'utilisatrice ou l'utilisateur dit « Version finale : dépose sur GitHub »
1. Nommer le fichier court, en minuscules, sans accents ni espaces (tirets), ex. `respiration-cellulaire.html`.
2. Si la page remplace une version existante, écraser l'ancien fichier (même nom) plutôt que d'en créer un nouveau.
3. Ajouter la page (et le PDF éventuel) dans `index.html`, dans la bonne rubrique (SVT ; Physique-chimie et technologie ; Français ; Histoire ; Divers).
4. Vérifier que les liens de `index.html` pointent vers des fichiers existants.
5. Commit avec un message en français, puis push sur la branche de travail **et** sur `main`.
6. Donner l'adresse finale : `https://fmaillard74-byte.github.io/svt-interactif/<nom>.html` (et `.../pdf/<nom>.pdf`).
7. Si la page contient un corrigé, une évaluation ou un document professeur, le signaler avant de déposer (le site est public).
