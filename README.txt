README

-ICWars-

# Description du Jeu
Ce jeu se joue à deux joueurs, tour à tour.
Les deux joueurs disposent de la même liste d’unités militaires.
Le but du jeu est d’éliminer toutes les unités ennemies de l’aire de jeu, en déplaçant les siennes et en attaquant.

# Unités
-	Les soldats : ils ont un maximum de 5 points de vie, un rayon d’action de 2 et inflige 2 dégâts par attaque.
-	Les tanks : ils ont un maximum de 10 points de vie, un rayon d’action de 4 et inflige 7 dégâts par attaque.

# Actions possibles
-	Déplacer le curseur à l’aide des flèches directionnelles ;
-	Sélectionner une unité en pressant Entrée ;
-	Une fois une unité sélectionnée, choisissez l’action à effectuer  touche A pour attaquer, touche W pour attendre.
-	Si vous choisissez d’attaquer, sélectionner votre cible parmi celle dans le rayon de votre unité à l’aide des flèches droite et gauche. 
-	Une fois la cible choisie, pressez Entrée pour infliger des dégâts à l’unité ciblée.
-	Si vous choisissez d’attendre, rien ne se passe.
-	Pour changer de joueur, pressez la touche TAB.
-	Changez de niveau avec la touche N.
-	Recommencez au début du niveau avec la touche R.

Vous pouvez effectuer une action par unité par tour. 
Après chaque action (déplacement + attaquer/attendre), votre unité est marquée comme utilisée et vous ne pourrez plus vous en servir jusqu’au tour suivant.

# Système de défense stars 
A chaque type de cellule est associé un nombre d’étoiles de défense 
-	Route et rivière : 0
-	Plaine : 1
-	Ville : 2 
-	Bois : 3
-	Montagne : 4
A chaque attaque subie, une unité perd un nombre de points de vie correspondant à la quantité de dégâts qu’inflige l’unité qui la cible, auquel on soustrait le nombre d’étoiles de défense correspondant à la cellule où se trouve l’unité attaquée. Pensez donc à placer vos unités de façon stratégique.

# Fin du jeu
Lorsqu’une unité n’a plus de points de vie, elle disparaît, et lorsqu’un joueur n’a plus aucune unités, il est considéré comme défait.
Le gagnant est donc le dernier joueur auquel il reste des unités utilisables.

