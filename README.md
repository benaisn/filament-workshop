# Atelier Filament

Visionneuse 3D de fichiers STL et 3MF, avec choix des couleurs dans le catalogue Prusament PLA et PETG.

**Site :** https://benaisn.github.io/filament-workshop/

## Fonctions

- Ouverture de fichiers STL et 3MF, y compris les projets PrusaSlicer et Orca/Bambu : pièces, extrudeurs et peinture multicolore.
- Rendu réaliste : lignes de couche, effet soie, paillettes, irisé, translucide, ombres douces.
- 102 teintes Prusament PLA et PETG, avec les couleurs mesurées de la base [OpenPrintTag](https://github.com/OpenPrintTag/openprinttag-database) (`data/prusament.json`), et ton stock personnel, enregistré dans le navigateur.
- **Partage avec un ami** : *Partager* crée un lien. Ton ami y choisit ses couleurs parmi ton stock et te renvoie un lien de réponse.
- Interface en français, en anglais et en allemand.

## Partager un modèle

Lors du premier partage, l'appli te demande de connecter GitHub. Pour cela, crée un jeton *fine-grained* limité à ce dépôt, avec la permission « Contents : Read and write ». Le jeton reste enregistré dans ton navigateur.

Ensuite, **Partager** envoie automatiquement le fichier dans [`modeles/`](modeles/) et crée le lien. Tu peux aussi déposer des fichiers à la main dans ce dossier et les ouvrir avec **Mes modèles**.
