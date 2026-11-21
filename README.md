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

Le lien ami est court (`?p=abc123`) : la configuration du partage (modèle, couleurs, filaments en stock, message) est enregistrée dans [`partages/`](partages/). Le lien de réponse de l'ami reprend cet identifiant et ajoute seulement ses choix. Sans jeton GitHub, l'appli crée un lien long qui contient tout.

## Réalité augmentée

Le bouton **AR** affiche la pièce avec les couleurs choisies, puis la pose chez toi à sa taille réelle : sur Android (Chrome avec ARCore) et sur iPhone ou iPad (Quick Look). Il marche aussi pour tes amis. Les paillettes et l'effet marbré ne sont pas rendus en AR.
