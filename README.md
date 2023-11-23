# Structure du Projet

Le projet se compose de trois fichiers principaux :

## HTML (`index.html`)

Le fichier HTML structure la page du jeu. Il contient les éléments suivants :
- Des panneaux pour chaque joueur affichant le nom du joueur, son score global et son score actuel.
- Des boutons pour lancer les dés, conserver les points et commencer une nouvelle partie.
- Des champs pour afficher les images des dés.
- Un champ de saisie pour définir le score gagnant.

## CSS (`style.css`)

Le fichier CSS définit le style et la mise en page du jeu. Les éléments clés incluent :
- La mise en forme et le positionnement des panneaux des joueurs.
- Les styles des boutons et des dés.
- L'affichage et l'animation des dés.
- Les styles pour indiquer le joueur actif et le gagnant.

## JavaScript (`challenges.js`)

Le fichier JavaScript contient la logique du jeu :
- Définition des variables pour les scores, le joueur actif, et l'état du jeu.
- Fonction pour initialiser le jeu et redémarrer une nouvelle partie.
- Gestion des événements pour le lancement des dés et la conservation des points.
- Logique pour changer de joueur et déterminer le gagnant.

# Fonctionnement du Jeu

À chaque tour, un joueur peut lancer les dés plusieurs fois. Chaque résultat est ajouté à son score de tour.
Si le joueur obtient un 1, il perd son score de tour et c'est au tour du joueur suivant.
Le joueur peut choisir de "Conserver" son score, l'ajoutant à son score global. C'est ensuite au tour de l'autre joueur.
Le premier joueur à atteindre le score gagnant fixé remporte la partie.

# Défis de Codage

- Un joueur perd tout son score s'il lance deux fois de suite un 6.
- Les joueurs peuvent définir un score gagnant personnalisé.
- Deux dés sont utilisés pour augmenter la complexité du jeu.
