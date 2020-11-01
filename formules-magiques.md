# Formules magiques

# Javascript natif

### La console de votre navigateur

La console de votre navigateur doit être tout le temps ouverte quand vous testez votre code. 
Si la console affiche du rouge, alors il faut résoudre le problème avant de passer à autre chose.

#### La console vous permet de tester du code.


Copiez / collez ce code dans la console et appuyez sur ENTER

```javascript
  // Je ne comprends rien au code ci-dessous mais je peux le tester quand même...
  alert("Hello world");
  if(confirm("Si tu as compris appuies sur OK")){
    alert("super");
  }else{
    alert("Annuler n'est pas une option");
  }
```

#### La console vous permet de *logger* des choses.
Copiez / collez ce code dans votre fichier javascript principal

```javascript
  console.log("Hello world");
  console.log(new Date());
```
### Un peu de Maths...

```javascript
  console.log(1+1);
  console.log(10-5);
  console.log(10*5);
  console.log(1000 / 4);
  
  // utiliser des variables
  let a = 10;
  let b = 5;
  let c = a + b;
  console.log(c);
  
  // incrémenter pour aller plus vite
  let a=0;
  a++;
  a++;
  a++;
  console.log(a);
  
  //ou bien encore...
  let b=10;
  b+=5;
  console.log(b);
  
```

#### Ma fonction préférée Math.random()

[Math.random()](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Math/random) renvoie un chiffre aléatoire entre 0 et 1;

Essayez ceci dans la console...

```javascript
  console.log(Math.random());
  console.log(Math.random());
  console.log(Math.random());
```

Pour générer un chiffre aléatoire entre 0 et 100 on fera donc...

```javascript
  console.log( Math.random() * 100 );
```

## Pour installer jQuery

Les diverses méthodes d'installation sont expliquées ici:
https://jquery.com/download/

Celle que nous allons utiliser pour ne pas perdre de temps...

```html
<!--à placer dans votre <head> -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
```

## Pour sélectionner un élément HTML avec jquery 

## Pour connaître les postions et tailles d'un élément jQuery HTML

## Classes javascript

Pour créer une classe...

```javascript

//fichier Eleve.js
class Eleve{
  constructor(nom,prenom){
    this.nom=nom;
    this.prenom=prenom;
    this.ecole="ETPA";
    this.nomEtPrenom=this.prenom+" "+this.nom;
  }
  //fait parler l'élève
  parle(phrase){
    let blabla="My name is "+ this.nom +", "+this.nomEtPrenom+", je voulais vous dire: "+phrase;
    alert(blabla);
  }
}
```

Pour utiliser cette classe...

```javascript

let jamesBond=new Eleve("Bond","James");
jamesBond.parle("On ne vit que deux fois");

```

## Pour gérer le son


