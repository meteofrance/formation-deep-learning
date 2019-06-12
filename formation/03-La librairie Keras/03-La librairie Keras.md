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
 color: black;}
 
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

![Logo météo](./Images/logo2.PNG)

<br/>

<!-- *page_number: true -->

La Librairie Keras
==

<br/>

### Présentation partagée sous la licence Apache 2.0

---

<!-- *page_number: true -->

## La Librairie Keras : La librairie du Deep learning

<center>

![keras_général](./Images/05-Keras/general.PNG)

<http://keras.io/>

</center> 

<br/>

---
  
<!-- *page_number: true -->

## Keras : une librairie de haut niveau pour concevoir vos modèles de Deep Learning

■ TensorFlow, PyTorch : librairies de plus bas niveau
 * Utiles pour des chercheurs en informatique

■ Keras : une librairie pour praticiens

<br/>

---
  
<!-- *page_number: true -->

## Quand utiliser Keras ?


■ Différences entre Keras et scikit-learn:
*  Keras :
   *  flexibilité dans la création d'architecture des réseaux de neurones
   *  utilisation du GPU

■ Quand utiliser Keras au lieu de scikit-learn?
* Dès qu’on veut faire du Deep Learning (réseaux de neurones profonds)

<br/>

---
  
<!-- *page_number: true -->

## Le modèle linéaire sur Keras

![code_keras](./Images/05-Keras/code_keras.PNG)

* Le paramètre 1 de “Dense” correspond au nombre de modèles linéaires que je vais créer.
* Le nombre de paramètres en sortie de la couche Dense est égal au nombre de modèles linéaires que je vais créer.
* Ici, pour obtenir un modèle linéaire, je choisis simplement le paramètre 1.

---

<!-- *page_number: true -->

## Exemples de Layers (couches) Keras


* Convolution : Conv2D

* Fonction d’activation : Activation (relu, sigmoid , tanh, etc.. )

* Dropout : Dropout

* Combinaison linéaire : Dense

---
  
<!-- *page_number: true -->

## Le modèle linéaire sur Keras


* Rappel : sous scikit-learn, le modèle linéaire est déjà implémenté

* Sur Keras, on peut implémenter le modèle linéaire comme cas particulier du Layer “Dense”.

* En effet, le modèle linéaire est équivalent à un neurone sans fonction d'activation.
 
*<center>f(x)=Ax+b</center>*
  
---
  
<!-- *page_number: true -->

## Régression linéaire avec le code Keras

<center>
  
![code_keras](./Images/05-Keras/code_keras2.PNG)

</center>

---
 
<!-- *page_number: true -->

## Régression logistique avec le code Keras

![code_keras](./Images/05-Keras/code_keras3.PNG)

---
  
<!-- *page_number: true -->

## Librairie scikit-learn comparée à la Librairie Keras

![code_keras](./Images/05-Keras/code_keras4.PNG)

---
  
<!-- *page_number: true -->

## Exercice 1 

<center>

![Exercice1](./Images/05-Keras/exercice1.PNG)

#### Ecrivez le code Keras correspondant à ce réseau de neurones. 

</center> 

<br/>

---
  
<!-- *page_number: true -->

## Exercice 2 

<center>

![Exercice2](./Images/05-Keras/exercice2.PNG)

#### Ecrivez le code Keras correspondant à ce réseau de neurones. 

</center> 

<br/>

---
  
<!-- *page_number: true -->

## Exercice 3 

<center>

![Exercice3](./Images/05-Keras/exercice3.PNG)

#### Dessinez l’architecture correspondante

</center>

---
  
<!-- *page_number: true -->

## Exercice 4 

![Exercice4](./Images/05-Keras/exercice4.PNG)

#### Donnez le code Keras correspondant à ce réseau de neurones. 

---
  
<!-- *page_number: true -->

## Visualisation de l’entrainement :

![TensorBoard](./Images/05-Keras/tensorboard.PNG)

---

<!-- *page_number: true -->

## <center> Questions ? </center> 




