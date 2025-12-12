#rappell 
...
<script>

//fonction

// définition

// une variable permet de stocker uen ou plusieurs valeurs

// une fonction permet de stocker un ou plusieurs traitements

// une variable comme let stocke des chiffres une fonctions stocke des traitements 

// exemple de variables 
 let a = 2 


// exemple de fonction

 function b(){
let a = 10;
let b = 30;
let c = a + b ;
if (){}
for(){}
console.log() ; 


    }

    // si on veut exécuter les traiteents stockées dans une fonction 
    // il faut APPPELLER / EXECUTER cette fonction 

b(); // EXECUTION 

// la fonction qu'on viens de creer ne traitera que 10+30 donc 
// a+b

// Quand on a esoin d'une fonction dont les traitements sont les memes MAIS les valeurs à porter à ces traitements sont differents ==> on va remplacer les variables dans les fonctions PAR des PARAMETRES ; on va créer des variables sans valeurs 

// EXEMPLE 

function c(a,b){
// let a = 10;
// let b = 30 ; 
let c = a + b ;

}

c(33, 55)
c( 52 , 24)

// Si le concept de paramètres n'existait pas 


// j'aurai du creer pour chaques calcul effectué 
// exemple : 

function c1(){
let a = 33 ;
let b = 55 ;
let c = a + b 

function c2(){
let a = 52 ; 
let b = 24 ; 
let c = a + b ;

}

}

// dernier point vu c'est les return 
// mot clé que l'on trouve dans les fonctions 

// à quoi ca sert ??

function creer_profil_etudiant ( prenom, nom , age )
{

let profil = prenom + "" + nom + "" + age
// prénom = "Alain"
//nom = "DUPONT"
// age = 22 
// PROFIL = "Alain DUPONT 22" 

// la varibale profile est LOCALE
}

// en gros le calcul ne peux s'effectué qu'a l'interieur de la fonction 

// si je l'apppelle a l'exterieur des accolades c'est comme si elle n'existait plus exxemple : 
// Profil // ERREUR variable INCONNUE ?? 

// d'ou le return qui permet de récuperer la valeur stocké dans la variable local profil à l'extérieur de la fonction 

// exemple 

let etudiant1 = créer_profil_etudiant ("Alain", "DUPONT",22 );











</script>