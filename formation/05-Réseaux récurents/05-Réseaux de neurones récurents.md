<style>

.slide {
 background-color: White ;
 font: 25px arial, sans-serif; 
 position: relative;
 background-image: url('./Images/logo.png');
 background-repeat: no-repeat, repeat;
 background-position: bottom 10px left 10px;
 }

.slide a {
 color: black;
 }
 
.slide h1 {
 color: Black !important;
 } 
 
.slide h2 {
 color: SteelBlue ; 
 } 
 
 .slide h3 {
 color: LightSkyBlue ; 
 }
 
 .slide h4 { 
 color: Black; 
 }
 
 .slide h5 {
 color: Red
 }
 
</style>

<!-- *page_number: true -->

![Logo météo](./Images/logo2.PNG)

<br/>

# Réseaux de neurones récurrents 

<br/>

### Présentation partagée sous la licence Apache 2.0

---

<!-- *page_number: true -->

## Rappels 

■ Réseaux convolutionnels : traiter la dimension spatiale

* Hypothèse : des pixels voisins représentent des choses similaires
* Convolution : Connexion locale des pixels (voisinage) pour détecter des objets plus gros (lignes/courbes) 

<center>

![image réseau](./Images/09-réseaux_récurents/réseau.PNG)

</center>

■ Réseaux récurrents : Traiter la dimension temporelle ? 

---
  
<!-- *page_number: true -->

## Série Temporelles 

Selon Wikipédia :
*Les séries temporelles sont considérées à tort comme étant une branche exclusive de l'économétrie. Cette dernière est une discipline qui est relativement jeune alors que les séries temporelles ont été utilisées bien avant par exemple en astronomie (1906) et en météorologie (1968).*

* L'objet des séries temporelles est l'étude des variables au cours du temps 

Exemples : 

![Séries temporelles](./Images/09-réseaux_récurents/séries_temporelles.PNG) 

---

<!-- *page_number: true -->

## Apprentissage avec des séries temporelles

■ Classification 

* Identifier les épisodes pluvieux/non pluvieux 
* Identifier si une personne fait du sport, dort, etc ... 
* Identifier si une station météo est défaillante.

■ Regression 

* Prédire la température maximale de la journée 
* Prédire la quantité de pluie attendue
* Corriger la température mesurée

---

<!-- *page_number: true -->

## Les différents types de RNN 

![image RNN](./Images/09-réseaux_récurents/RNN.PNG) 

---

<!-- *page_number: true -->

## Exemple : prédiciton de lettre 

![Image prédiciton de lettres](./Images/09-réseaux_récurents/prédiction_lettres.PNG)

---
  
<!-- *page_number: true -->

## Exemple : prédiction de lettre 

Première période : Réseau de neurone classique
  
* La couche cachée est appélée "cellule"
* Il y a une sortie par période 

<center>

![Image première pédiode](./Images/09-réseaux_récurents/prédiction_lettres2.PNG)

</center>

---
  
<!-- *page_number: true -->

## Exemple : prédiction de lettres

Périodes suivantes - réseau de neurone presque classique :
* la couche intermédiaire a une entrée supplémentaire : la sortie intermédiaire du réseau précédent

![image période suivante](./Images/09-réseaux_récurents/prédiction_lettres3.PNG)

---

<!-- *page_number: true -->

## Représentation en graphe 

![graphe](./Images/09-réseaux_récurents/graphe.PNG) 

---
 
<!-- *page_number: true -->

## Représentation enroulée

![graphe](./Images/09-réseaux_récurents/graphe2.PNG) 

---

<!-- *page_number: true -->

## Autres exemples : Générer du Shakespeare 

![texte Shakespeare](./Images/09-réseaux_récurents/shakespeare.PNG) 

* Entraînement : tous les textes de Shakepeare
* Puis on donne au réseau une première lettre, et il prédit la suite 

---

<!-- *page_number: true -->

## Autres exemples : générer du code LaTex 

<center>

![Code LaTex](./Images/09-réseaux_récurents/Latex.PNG) 

</center>

* Le réseau tente de démontrer les lemmes 

* Il reproduit la structure d'un cours de maths

* Mais ça ne veut rien dire !


---

<!-- *page_number: true -->

## Étude de cas NetAtmo 

<center>

![image NetAtmo](./Images/09-réseaux_récurents/NetAtmo.PNG) 

</center>

---

<!-- *page_number: true -->

## Étude de cas NetAtmo 

<center>

![image NetAtmo 2 ](./Images/09-réseaux_récurents/NetAtmo2.PNG) 

</center>

---

<!-- *page_number: true -->

## Étude de cas NetAtmo 

#### Objectif : deviner la courbe bleue (Météo-France) à partir des autres courbes (NetAtmo) 

<center>

![image NetAtmo 3](./Images/09-réseaux_récurents/NetAtmo3.PNG) 

</center>

---
 
<!-- *page_number: true -->

## Étude de cas NetAtmo 

![image NetAtmo 4](./Images/09-réseaux_récurents/NetAtmo4.PNG) 

* La prédiciton est robuste aux pics anormaux de températures des stations NetAtmo (grises) 

--- 

<!-- *page_number: true -->

## Bonus : code Keras 

<center>

![code Keras NetAtmo](./Images/09-réseaux_récurents/Keras_NetAtmo.PNG) 

</center>

* le paramètre return_sequences permet de spécifier si on veut uniquement la sortie de la dernière période (False) ou toute la séquence y compris périodes intermédiaires (True).

