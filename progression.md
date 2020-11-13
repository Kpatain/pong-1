
# Day 01 2020/11/03 :mask: :speech_balloon: :snail:

Pour ce premier cours rapide nous avons pas mal parlé (enfin surtout moi) de ce qu'est la programmation, à quoi ça sert et je vous ai fait part de mon approche plus axée sur la langue que sur les Maths.

#### Setup

- On a créé notre repo "PONG"
- On a configuré notre readme.md avec un lien vers notre projet en public
- On a pullé notre repo
- On a créé un index.html

#### HTML/CSS

- On a créé un `#terrain` dans le `body`
- On a créé une `#balle` **dans** le `#terrain`
- On a un peu galéré à mettre en place un fichier CSS en lien avec notre HTML
- On a tout bien fait comme il a dit le prof (fond noir, texte blanc, typographie en monospace)
- On a créé notre `#terrain` en proportion 800/400px
- On a créé notre `#balle` (ronde) en taille 20px
- On a passé notre `#terrain` en `relative`
- On a passé notre `#balle` en `absolute`
- On a positionné notre `#balle` au centre du `#terrain` en utilisant des pourcentages.

#### Javascript

- On a un peu galéré à mettre en place un fichier javascript en lien avec notre HTML
- On a fait dire "coucou" à notre page avec  un `alert`.
- On est allé piocher dans [formules-magiques.md](formules-magiques.md) comment intégrer jQuery à notre page HTML.
- On a fait dire à notre programme la largeur du `#terrain` grace à 
[ça](formules-magiques.md#pour-s%C3%A9lectionner-un-%C3%A9l%C3%A9ment-html-avec-jquery) 
et à [ça](formules-magiques.md#pour-connaître-les-tailles-dun-élément-jquery-html)
- Puis sans trop comprendre comment on a fait bouger en diagonale notre balle :sunglasses: grace à 
[ça](formules-magiques.md#faire-des-boucles-temporelles), 
[ça](formules-magiques.md#convertir-le-texte-150px-en-nombre-150),
[ça](formules-magiques.md#pour-connaîtredéfinir-les-positions-dun-élément-jquery-html)
et [ça](formules-magiques.md#un-peu-de-maths)

#### Pour finir

- On a pushé notre repo sans que le prof ait eu besoin de nous le dire car c'est devenu naturel chez nous :unamused:

## Contrôle continu


J'attends de vous que vous lisiez rapidement [ceci](formules-magiques.md) afin...
- d'avoir en tête les skills que vous allez avoir à votre disposition et que vous pourrez utiliser et donc comprendre le moment venu.
- vous sachiez [quelles conventions](formules-magiques.md#les-conventions-fortement-conseillées) nous allons utiliser.

Je noterai vos projets à partir de **vendredi** (donc dites vous jeudi soir car je me lève très tôt).

Pour la note, j'attends de vous que...

- votre projet respecte ce qui a été expliqué plus haut
- votre repo soit *propre*
- votre `#terrain` soit centré dans la page comme on a pu le faire dans le unserious game
- vos noms de variables soient en **français** 
- votre code Javascript et CSS soit bien indenté et commenté avec vos propres mots
- votre code javascript respecte les conventions décrites un peu partout [ici](formules-magiques.md).   


## Evangélistes de la semaine

J'aimerai que d'ici **mercredi** vous me fassiez [un tableau comme celui là](https://github.com/davidmarsprof/unserious-game/blob/main/team.md) dans
[votre repo](https://github.com/VinekNet/pong_organisation).

Je vous invite à réorganiser ce tableau afin de mettre en haut ceux qui sont plutôt à l'aise et en bas ce qui ont plus de mal. L'idée n'est pas de faire un classement mais simplement dites vous que j'ai plutôt tendance à noter en premier ce qui sont en haut et à noter en dernier ceux qui sont en bas.

Comme toutes les semaines aidez ceux qui galèrent **et qui en font la demande**.
Petit conseil, faites passer le mot qu'il faut pas attendre jeudi soir pour se manifester...

# Day 02 2020/11/09 :mask:

#### Préalables

réviser votre programme de Math de CM1/CM2 :baby:

#### On a...

- créé des classes ES6 pour notre terrain et notre balle 
- dissocié les fonctions de calcul des fonctions d'affichage :eyes:
- fait rebondir la balle :dizzy:

Qualité de code
- **Essayé** d'installer un [pluggin dans vs code](https://marketplace.visualstudio.com/items?itemName=Gydunhn.javascript-essentials) et ça n'a pas été possible.
- **Du coup on n'a pas appris** à commenter proprement notre code pour faire de javascript un langage un plus typé qu'il ne l'est.

## Contrôle continu :cold_sweat:

Je noterai vos projets à partir de **vendredi 13**, ne soyez pas supersticieux, si vous prennez une heure ou deux pour vous concentrer sur le projet, ça ira et sinon je ne pense pas qu'il y ait de miracles. A partir de maintenant les écarts vont se creuser entre ceux qui s'investissent et ceux qui se laissent porter, c'est pas le moment de lâcher et **je me tiens à votre disposition sur le chat si vous voulez que je relise votre code ou vous donne des conseils** mais c'est à vous de faire la démarche.

Pour la note, j'attends de vous que...

- votre projet respecte ce qui a été fait en cours (trop lentement pour certains, trop vite pour d'autres; je sais)
- votre repo soit *propre*
- vos noms de variables soient en **français** 
- votre code Javascript et CSS soit bien indenté et commenté avec vos propres mots
- votre code javascript respecte les conventions décrites un peu partout [ici](formules-magiques.md). 

Pour me prouver que vous avez bien assimilé (et toujours pour la note...)

- faire démarrer la balle dans une direction ou dans l'autre aléatoirement ([aléatoire en anglais ça se dit...](https://github.com/davidmarsprof/pong/blob/main/formules-magiques.md#ma-fonction-pr%C3%A9f%C3%A9r%C3%A9e-mathrandom))
- intégrer les raquettes HTML + CSS + classes JS (les raquettes font 25% de la hauteur du terrain et 10px de large)
- cacher (en css) les murs (les `borders`) gauche et droite du terrain pour que ça ressemble à [notre pong final](https://davidmarsprof.github.io/pong/exemple/).
- faire bouger les raquettes toutes seules de haut en bas :open_mouth:
- faire en sorte que la balle ne dépasse pas du terrain à droite et en bas (soustraction de la taille de la balle)

Je n'attends pas de vous que la balle rebondisse sur les raquettes, si vous voulez le faire et si vous voulez enchaîner sur les cours suivants allez-y, mais faites-le dans l'ordre et en respectant le style de code du reste s'il vous plait.

## Evangélistes de la semaine

Vous aurez vous même pas mal de choses à assimiler, donc assimilez rapidement votre travail perso pour ensuite arriver à le transmettre aux autres.
Comme toutes les semaines aidez ceux qui galèrent **et qui en font la demande**.
Petit conseil, faites passer le mot qu'il ne faut pas attendre jeudi soir pour se manifester...

# Day 03 2020/11/16 :mask:  :heart_eyes:

#### On va...

- Revenir sur la notion de classe Css ET Js pour nos raquettes (Certains sont passés à côté du concept et on les excuse car c'est pas évident).
- Mettre nos classes dans des fichiers.js séparés.
- faire bouger les raquettes avec le clavier :heart_eyes: :sunglasses:
- faire rebondir la balle sur les raquettes
- faire perdre / gagner les joueurs

Si on a le temps...

- faire changer de couleur la `border` du terrain et des raquettes (#00FF00) quand la balle les touche (ça fait pas fonctionner le jeu mais ça le rend plus sympa)
- faire accélerer petit à petit notre balle quand elle touche les raquettes (pas les murs)
- donner une vitesse d'accélération maximum à notre balle

# Day 04 2020/11/23

#### On va...

- faire rebondir la balle un peu plus vers le haut quand elle touche le haut de la raquette, un peu plus vers le bas quand elle touche le bas (cette notion Mathématique fort complexe s'appelle un produit en croix) :dizzy_face:
- Gérer les scores HTML + CSS + classes JS
- Gérer l'écran de démarrage HTML + CSS + classes JS + intégration du fullscreen

# Day 05 2020/11/30 :musical_keyboard: :headphones:

#### Penser à...

- prendre un :headphones:

#### On va faire... 

- 2 heures pour bien assimiler tout ce qu'on a fait ou faire ce qu'on aura pas eu le temps de faire
- Intégrer le son de piano pour ceux qui se sentent.

# Day 06 2020/12/07 :scream: :scream: :scream:

#### Vous allez faire...

- partiel

# Day 07 2020/12/14 :santa:  :trophy:

#### On va faire...

Un Tournoi de PONG ou partiel selon comment on aura avancé
