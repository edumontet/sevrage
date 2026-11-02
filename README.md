# Mon arrêt

Web app indépendante, à l'adresse `https://edumontet.github.io/sevrage/`. Elle compte les jours sans alcool (depuis le 5 octobre 2026) et sans tabac (depuis le 18 octobre 2026), calcule les économies en direct (10 €/jour d'alcool, 13,50 €/jour de tabac) et propose un texte à lire pour chaque semaine, chaque mois puis chaque année, avec ses sources. Les dates et les montants sont fixés dans `index.html`.

Elle s'installe sur l'écran d'accueil de l'iPhone (Safari › Partager › Sur l'écran d'accueil).

## Mettre en ligne

Dans le dépôt GitHub : **Settings › Pages**, source **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.

## Technique

Un seul fichier `index.html` (HTML, CSS et JavaScript), sans étape de build ni dépendance.
