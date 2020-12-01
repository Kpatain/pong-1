
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

- Essayer un autre [éditeur de code](https://www.jetbrains.com/fr-fr/webstorm/download/#section=windows) 
- Revenir sur la [notion de classe](formules-magiques.md#pour-cr%C3%A9er-une-classe) Css ET Js pour nos raquettes (Certains sont passés à côté du concept et on les excuse car c'est pas évident).
- Mettre nos classes dans des fichiers.js séparés.
- Apprendre à utiliser des getter/setter pour se simplifier la vie 

## Contrôle continu :cold_sweat:

Deadline **Samedi 21 Novembre 05:00 AM**  (Heure de Paris / France / Terre)

On a vu pas mal de notions mais on ne les a pas vraiment mises en pratique par manque de temps, donc pour ne pas trop vous surcharger de travail, je vous donne plein d'exemples de code pour vous inspirer. Je vous conseille de faire les taches dans cet ordre, ce sera beaucoup plus facile

- dans le setInterval je veux 3 lignes seulement...
```javascript
raquette1.bouge(); //raquette1 peut s'appeler raquetteGauche ça me va aussi hein...
raquette2.bouge();
balle.bouge();
```

Ensuite...

- contrôler les raquettes gauche et droite respectivement avec les touches A/Q et P/M du clavier.

```javascript
// Histoire de vous mettre sur la voie...
//quand on APPUIE sur une touche du clavier
window.addEventListener("keydown", function (event) {
    if (event.defaultPrevented) {
        return; // je n'explique pas à quoi ça sert ça vous embrouillerait sans raison
    }
    if(event.key === "a"){
        joueur1.monte();
    }
    if(event.key === "q"){
        joueur1.descend();
    }
    //je vous laisse deviner pour le joueur 2...
    
    event.preventDefault(); // je n'explique pas à quoi ça sert ça vous embrouillerait sans raison
}, true);

//je vous laisse deviner pour les touches relachées...

```

- Je veux des getters sur bas et droite (balle et raquettes).
- Je veux des setters sur bas et droite (balle et raquettes).

```javascript
//dans Balle.js 
// Histoire de vous mettre sur la voie le getter (obtenir) et le setter (définir) de bas de la balle mais qui pourrait marcher aussi pour la raquette.
/**
 * Obtenir la position en bas
 * @returns {number}
 */
get bas() {
    return this.haut + this.hauteur;
}
/**
 * Permet de définir le bas, ce qui influera logiquement sur le haut
 * @param {number} value
 */
set bas(value) {
    this.haut = value - this.hauteur;
}
```

- faire rebondir la balle sur les raquettes

```javascript
//dans Balle.js
// Histoire de vous mettre sur la voie un petit bout de code pour savoir si ma balle touche la raquette gauche, à vous de définir où mettre ça et quoi faire dans ce cas là
if(this.gauche < joueur1.droite){ //si la balle dépasse à gauche la raquette gauche
  if(this.bas > joueur1.haut){ //et si la balle est plus basse que le haut de la raquette
    if(this.haut < joueur1.bas){ // et si la balle est plus haute que le bas de la raquette
      // donc la balle va rebondir sur la raquette, à vous de jouer!
    }
  }
}
```

- Enfin si la balle passe à côté des raquettes, on remet la balle au centre (X et Y) et c'est reparti.

Si vous respectez tout ça, vous avez un jeu jouable. 
C'est pas ouf encore, mais c'est jouable. :muscle: :muscle: :muscle:


# Day 04 2020/11/23 :cry:

A 15h00 nous rendrons hommage à Bastien. On va donc modifier le cours car on sera tous un peu perturbés et on n'aura pas la même capacité de concentration qu'habituellement.

#### On va...

- Prendre un peu de recul et relativiser :rainbow: l'importance de ce qui se passe dans ce cours et l'investissement que ça demande. 
- Parler un peu du cours en info 2D
- Apprendre à débugger les projets *bloqués*.
- Apprendre à débugger les projets *boggués*.

#### Pour la suite

Vous avez tous eu accès [au code source en infographie 2D](https://github.com/davidmarsprof/pong-wimbledon).
Vous trouverez [ici mon code source simplifié et commenté](https://github.com/davidmars/pong-jquery) qui ne porte QUE sur le cours de prog web. 

Vous avez vu toutes les notions importantes à ce stade. Maintenant, il vous reste à les assimiler en pratiquant. Si vous faites un copier/coller de mon code ça ne vous apportera rien. Il faut que vous continuiez à vous fixer des objectifs, à essayer de les remplir seuls et si vous bloquez reagardez mon code.

#### A l'issue du cours les délégués vont organiser un vote pour savoir comment va se dérouler la suite...

- Est ce que vous voulez qu'on repousse le partiel d'une semaine? (donc on oublie le tournoi de pong)
- Est ce que vous voulez que je continue à vous mettre des petites notes au fil de la semaine ou est ce que vous préférez être en autonomie complète ?

## Contrôle continu :cold_sweat:

Je noterai vos projets à partir de **samedi 28** au petit matin. Vous avez le code source corrigé, donc jouez le jeu, creusez vous bien la tête, fouillez les formules magiques pour trouver ce qui vous manque et seulement si vous bloquez sur un point précis alors allez voir le corrigé. Si vous ne faites pas cet effort d'une heure ou deux ça ne rentrera pas dans votre tête.

Ce que j'attends de vous :

- **Repensez au cours précédent** sur le débug des erreurs. Parlez en 5 minutes entre vous, refaites-vous le film. Cette méthodolgie de débuggage vous sera très très utile et vous évitera de paniquer inutilement quand votre code ne fonctionnera pas comme prévu. Le self control paye toujours en programmation. Ce premier point ne vous fera pas gagner de point en controle continu, il vous fera juste coder 3 fois plus vite.
- Intégrez les scores (0 | 0) en HTML + CSS (on les fera marcher plus tard en cours)
- faire accélerer petit à petit notre balle quand elle touche les raquettes (programme de Math de CP)
- donner une vitesse d'accélération maximum à notre balle pour que ça reste jouable. N'allez pas chercher midi à 14h, c'est très très simple. *Si la vitesse n'est pas trop rapide alors accelere*
- faire changer de couleur la border du terrain et des raquettes (#00FF00) quand la balle les touche (ça fait pas fonctionner le jeu mais ça le rend plus sympa)

# Day 05 2020/11/30 

#### On n'a pas fait

- Un cours de math sur PI, les sinus, les cosinus, et les calculs d'angles (de toute façon depuis 1996 je ne saurais plus faire ce cours pour être honnête avec vous). Quand j'ai besoin de faire de la physique, j'utilise [des librairies dédiées](https://brm.io/matter-js/) à ça et la plupart des programmeurs font comme moi. L'objectif de mon enseignement est justement de vous démontrer qu'avec une bonne logique et très peu de maths on peut faire plein de choses. Donc si vous voulez continuer avec des calculs d'angles allez y mais il va faloir vous creuser pas mal la tête pour gérer la vitesse, et les angles qui changent à l'impact sur la raquette. 

#### On a fait... 

- un petit retour sur vos codes
    - sur les display flex https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    - sur la fonction de mise en surbrillance des contours au contact avec la balle (on va factoriser)
        
- fonctionner les scores
- rebondir la balle un peu plus vers le haut quand elle touche le haut de la raquette, un peu plus vers le bas quand elle touche le bas (cette notion Mathématique fort complexe s'appelle un produit en croix) 😵

#### On a (j'ai) pas réussi...

Grégoire a eu la bonne idée de me demander d'animer le terrain, je lui ai proposé d'utiliser animate.css pour faire ça, facile... Sauf que pour une raison que je ne m'explique pas ça n'a pas marché... ça arrive.

Ce matin, je rééssaye et ça a fonctionné du premier coup. Bref pour que ça marche voici la [modif que j'ai faite sur le code source](https://github.com/davidmars/pong-jquery/commit/66128a554dd9416299733df68b9239021c424ae2). Et ce que ça donne https://davidmars.github.io/pong-jquery/

## Contrôle continu :cold_sweat:

Pour **Dimanche matin**

- Si votre jeu ne fonctionne pas, faites vous un peu violence, passez du temps desssus, **faites vous aider** par ceux qui sont plus à l'aise en cas de bloquage. Ne copiez pas bêtement du code sans comprendre ce que vous faites mais n'hésitez pas à vous inspirer du code des autres. Bref bossez bien cette semaine.
- intégrez l'écran de démarrage HTML + CSS par dessus votre jeu. 
Inspirez vous de mon code HTML/CSS https://github.com/davidmars/pong-jquery histoire d'avoir les notions techniques.


# Day 06 2020/12/07 

#### On va faire... 

- Démarrer notre jeu au click sur notre écran de démarrage.
- Tout le reste du cours sera consacré à remettre d'applomb les projets bloqués pour que ceux qui sont en difficulté partent avec une bonne base pour la semaine prochaine.

#### Pour ceux qui sont à l'aise, prennez un casque et faites ce qui suit en autonomie...

Intégrez le son de piano :musical_keyboard: :headphones: . Pour ce dernier point on va procéder différemment. 
- Commencez par vous demander à quoi ça va nous servir [ça](https://github.com/davidmarsprof/pong/tree/main/exemple/sound)
- Lisez [ça](https://createjs.com/getting-started/soundjs)
- Essayez un peu par vous même de faire jouer UNE SEULE note quand la balle rebondit.
    Dans votre console sur chrome vous aurez 3 erreurs qui vont s'afficher pour `soundjs.min.js:18` **ce n'est pas grave**. Une fois que le projet sera sur GitHub ces erreurs n'aparaitront plus. Ce sont des erreurs de sécurité qui ne doivent pas empêcher votre projet de fonctionner.

- Puis lisez [comment j'ai géré ça de mon côté](https://github.com/davidmars/pong-jquery/blob/main/js/Audio.js). 
   - [Vous verrez un tableau](https://github.com/davidmarsprof/pong/blob/main/formules-magiques.md#les-tableaux) ligne 21 de mon code. C'est un tableau comme en cours d'algo sauf que c'est beacoup plus simple à créer en javascript car le langage est moins strict.
   - Enfin pour la fonction `fausseNote()` c'est pas vraiment du code conventionel, c'est du code créatif. Il n'y a rien de compliqué techniquement cependant un très bon programmeur sans aucune imagination n'aura jamais l'idée de faire ça.


# Day 07 2020/12/14 :scream: :scream: :scream:

#### Vous allez faire...

- partiel

Ne vous inquiétez pas, tout ce que je vous demanderai vous l'aurez déjà fait et pratiqué en cours. Ce partiel sert à valider que vous l'avez bien compris et non pas simplement copié/collé. Vous devrez créer un nouveau repo github + github page pour me rendre votre travail donc entrainez vous histoire de pas passer 2 heures à essayer de publier un site sur github.
