# Cubeval : La Ferme des Fées – mises à jour

Dépôt public lu par l'appli Android Cubeval pour se mettre à jour depuis le jeu.

- `latest.json` : dernière version publiée (`build` du jeu, notes, lien du jeu, version minimale de l'appli).
- `game/cubeval-<build>.html` : le jeu complet, téléchargé et installé directement dans l'appli.
- `apk/` : l'appli Android complète, demandée seulement quand `apk_min` dépasse la version installée.

Pour publier une mise à jour : déposer `game/cubeval-<nouveau build>.html`, puis augmenter `build` et mettre à jour `html_url` et `notes` dans `latest.json`.
