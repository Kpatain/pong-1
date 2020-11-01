# Formules magiques

## Pour installer jQuery

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


