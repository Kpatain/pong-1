Prenons un peu de recul sur comment fonctionne ce jeu:

- Ce qui rend le jeu plus difficile c'est quand ça s'accélère.
- S'accélérer ça peut se passer en x et en y
- Mais dans un pong l'accélération qui nous intéresse c'est le temps entre deux touchers de raquettes, pas entre deux touchers de murs.
- donc au départ la vitesse en X ne doit pas être aléatoire car au départ la difficulté doit être la même à chaque partie.
- et surtout la vitesse en X ne doit pas être trop proche de zéro sinon ça va être très très très long avant que la balle touche la première raquette.

Donc on va calculer notre vitesse de déplacement x selon 2 facteurs
- un pour le `sens `de déplacement `-1` ou `1`
- un pour la `vitesse `disons `3`
- du coup on a un déplacement en x qui donnera à chaque itération `x = x + (sens * vitesse)`
- on n'a plus qu'à inverser `sens` quand la balle touche un côté gauche ou droite.
- L'étape d'après c'est l'accélération du jeu à chaque toucher de raquette, 
donc l'augmentation de la `vitesse` et là d'un coup c'est très facile, c'est une simple addition :)

Ensuite il y a le déplacement en `y` quand même. 
A vrai dire à ce stade il fonctionnera sans doute déjà bien si vous appliquez la même recette 
mais il faut observer quelques limites pour que ça reste jouable.

- Si la vitesse Y est égale à 0 alors la balle va filer tout droit.
- Si la vitesse Y et égale à la vitesse X alors on aura un déplacement en diagonale à 45 degrés
- Si le sens Y est positif ça descend.
- Si le sens Y est négatif ça monte.
- Si la vitesse Y est supérieure à la vitesse X alors on aura un déplacement qui touchera plus souvent les murs que les raquettes 
et c'est ce cas qu'on veut éviter ou du moins limiter car ça commence à rendre le jeu désagréable...

Y a t il une règle pour dire à partir de quand le jeu devient désagréable? 
Non, c'est à vous en tant que concepteur de jeu de juger de cela et c'est aux joueurs de dire si vous aviez raison ou non. 
Par le biais de simples opérations et multiplications, vous touchez déjà ici au sacro saint GAMEPLAY.

De la même manière on peut se demander si la vitesse Y doit accélérer ou non, j'ai personnellement choisi de répondre NON à cette question pour plusieurs raisons
- je n'aime pas les maths, j'ai pas envie de me prendre la tête et je sais que si on essaye de trop associer X et Y ça va se terminer en vecteurs et en calcul d'angles.
- la vitesse Y sert à une seule chose dans mon PONG c'est à diriger la balle et dans MON pong il y a que deux moments où la balle est dirigée en Y:
   - quand la balle touche un mur haut ou bas et là c'est le sens Y qu'on va modifier et non pas la vitesse Y.
   - quand la balle touche une raquette et là effectivement selon si ça touche le haut ou le bas de la raquette je vais influer la vitesse Y.
