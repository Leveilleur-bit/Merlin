# Merlin

Suivi de portefeuille crypto : valeur et cours en direct, prix de revient, idées de trade, journal et fiscalité (formulaire 2086).

L'appli est publique (GitHub Pages). Les données sont dans le dépôt **privé** `Leveilleur-bit/Merlin-donnees` (fichier `data.json`) et ne sont jamais dans ce dépôt.

## Mise en ligne
1. Settings > Pages > « Deploy from a branch », branche `main`, dossier `/ (root)`, Save.
2. Après 1 à 2 minutes : `https://leveilleur-bit.github.io/Merlin/`

## Connexion aux données
1. GitHub > Settings > Developer settings > Personal access tokens > **Fine-grained tokens** > Generate new token.
2. Repository access : **Only select repositories** > `Merlin-donnees`.
3. Permissions > Repository permissions > **Contents : Read and write**.
4. Dans Merlin : roue dentée > colle le token > Connecter.

Le token reste dans le navigateur de l'appareil. À refaire sur chaque téléphone ou ordinateur.

## Installer sur le téléphone
- Android (Chrome) : menu ⋮ > « Ajouter à l'écran d'accueil ».
- iPhone (Safari) : Partager > « Sur l'écran d'accueil ».

## Notes
- Cours : API publique CoinGecko, rafraîchis toutes les 2 minutes quand l'appli est ouverte.
- Fiscalité : estimations selon la formule du 2086, à faire valider avant de déclarer.
