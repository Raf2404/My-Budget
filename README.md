# Budget Pilot

Web-app de budget installable (PWA) : tableau de bord, budget & revenus annexes, apport immobilier sanctuarisé, objectifs annexes financés à temps, wishlist partageable.

## Mettre en ligne (GitHub Pages)

1. Sur GitHub : **Settings → Pages**
2. *Source* : **Deploy from a branch** → branche `main`, dossier `/ (root)` → **Save**
3. Après 1 à 2 minutes, l'appli est sur : `https://raf2404.github.io/My-Budget/`

## Installer

- **iPhone** : ouvrir le lien dans Safari → bouton Partager → **Sur l'écran d'accueil**
- **PC** : ouvrir dans Chrome ou Edge → icône d'installation dans la barre d'adresse

## Données

Les données restent dans le navigateur de chaque appareil (localStorage).
Pour passer d'un appareil à l'autre : Réglages → Sauvegarder / restaurer.
La synchro iPhone ↔ PC (Firebase) est prévue pour une prochaine version.

## Fichiers

- `index.html` : toute l'appli (HTML, CSS, JS)
- `manifest.webmanifest` + `icons/` : installation
- `sw.js` : fonctionnement hors-ligne (changer `VERSION` à chaque mise à jour)
