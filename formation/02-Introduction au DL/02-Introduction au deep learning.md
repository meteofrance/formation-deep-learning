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

Introduction au Deep Learning
=

<br/>

### Présentation partagée sous la licence Apache 2.0

---

<!-- *page_number: true -->

# Le Deep Learning 

![image Dl](./Images/04-intro_DL/DL.PNG)

---

<!-- *page_number: true -->

## Un neurone
 
 <center>
 
![image neurone](./Images/04-intro_DL/neurone.png) 
 
</center>

* *f* est la fonction d'activation
* Question : quelle fonction *f* choisir pour retrouver le modèle linéaire ?

---

<!-- *page_number: true -->

## Fonctions d'activation couramment utilisées

<center>

![Sigmoid/relu](./Images/04-intro_DL/sigmoid_relu.PNG)
</center>

|Utilisation : à mettre en fin de réseau pour prédire une probabilité (entre 0 et 1) |Utilisation : entre chaque couche pour dé-linéariser (à coût de calcul faible)|
|:---:|:---:|

---

<!-- *page_number: true -->

## D'autres fonctions d'activation 

![images fonctions](./Images/04-intro_DL/fonction_activation.PNG) 

---

<!-- *page_number: true -->

## Les couches / layers 

<center>

![image layers](./Images/04-intro_DL/layers.PNG)

##### profondeur = 1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; profondeur = 2 

</center>

---

<!-- *page_number: true -->

## Intuition

Un réseau de neurones peut approcher n'importe quelle fonction continue.

![center 2_segments](./Images/04-intro_DL/approche_courbe_segments.png)
<center>Couche cachée à 2 neurones &nbsp;&nbsp;&nbsp; Couche cachée à 4 neurones
</center>

---

<!-- *page_number: true -->

## Classifier une image avec un réseau de neurones sans couche cachée

+ Objectif : classifier une image 32x32 en 10 classes

![image Classif](./Images/04-intro_DL/classif.PNG)

+ Plus de 30 000 paramètres pour un petit réseau et une petite image 
+ Explose avec la résolution de l'image et la complexité du réseau

---

# Réseaux de neurones convolutionnels

<!-- *page_number: true -->


---

<!-- *page_number: true -->

## Convolution sur une image 

<center> 
  
![image convolution](./Images/04-intro_DL/convolution2.PNG)

</center>

+ Multiplication pixel par pixel (produit scalaire)

---

<!-- *page_number: true -->

## Convolution sur une image 

![image convolution générale](./Images/04-intro_DL/convolution.PNG)

- 1 filtre 5x5

- Exemple en images : <http://setosa.io/ev/image-kernels/>

--- 

<!-- *page_number: true -->

## Autres types de couches 

 
- MaxPooling

- DropOut

---

<!-- *page_number: true -->

## Max Pooling : Réduire la dimension

![image Max-Pooling](./Images/04-intro_DL/maxpooling.PNG)

---

<!-- *page_number: true -->

## Dropout : supprimer aléatoirement des neurones 

<center>

 Méthode de régularisation 

![image dropout](./Images/04-intro_DL/dropout.PNG)

</center>

---

<!-- *page_number: true -->

## Exemple de réseau convolutionnel complet 

![Réseau complet](./Images/04-intro_DL/réseau_complet.PNG)


