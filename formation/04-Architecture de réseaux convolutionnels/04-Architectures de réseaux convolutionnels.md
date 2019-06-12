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

![Logo météo](./Images/logo2.PNG)

<br/>

<!-- *page_number: true -->

# Exemples d'architectures de réseaux convolutionnels

<br/>

### Présentation partagée sous la licence Apache 2.0


---

<!-- *page_number: true -->

## Schema réseau convolutionnel

![Réseaux convolutionnel](./Images/07-architecture/schema.PNG)

---
  
<!-- *page_number: true -->

## ImageNet : Présentation

<center>

![Résultats ImageNet](./Images/07-architecture/ImageNet_Scores.PNG)

</center>

---
  
<!-- *page_number: true -->

## LeNet : pionnier des réseaux convolutionnels

* peu de convolutions
* peu de couches

<center>

![1er réseau convolutionnel](./Images/07-architecture/Architecture_imagenet.PNG)

</center>

---

<!-- *page_number: true -->

## LeNet : Code Keras

![Code Keras commenté](./Images/07-architecture/Lenet_Keras.PNG)

---
  
<!-- *page_number: true -->

## Réseau AlexNet

![Réseau AlexNet](./Images/07-architecture/AlexNet.PNG)

<center>

Réseau convolutionnel suivi
d’un réseau dense

Gagnant ImageNet 2012

</center>

---

<!-- *page_number: true -->

## AlexNet sur Keras

<center>

![Code keras 2 commenté](./Images/07-architecture/AlexNet_Keras.PNG)

</center>

---

<!-- *page_number: true -->

## Réseau VGG

<center>
  
![Architecure VGG](./Images/07-architecture/Archi_VGG.PNG)

</center>

---

<!-- *page_number: true -->

## VGG sur Keras

<center>

![VGG Keras](./Images/07-architecture/VGG_Keras.PNG)

</center>

---

<!-- *page_number: true -->

## Détection d’objet en temps réel (Yolo)
 <https://www.youtube.com/watch?v=MPU2HistivI>

* Trouver tous les objets de l’image
* Classifier chaque objet 

<center>

![Classification](./Images/07-architecture/Detection_temps_reel.PNG) 

</center>

---
  
<!-- *page_number: true -->

## Unet: Classification par pixel

![Sortie U-net](./Images/07-architecture/Unet1.PNG)

---

<!-- *page_number: true -->

## U-net: Classification par pixel

<center>

![Modèle Unet](./Images/07-architecture/Unet2.PNG)


 -Encoder l’image à différentes
échelles 

 -Extraire les informations de
chaque échelle

</center>

---

<!-- *page_number: true -->

## Super Resolution

<center>

![defloutage](./Images/07-architecture/Defloutage.PNG)

 -En entrée : images basses résolution
 
 -En sortie : images hautes résolution

</center>

---

<!-- *page_number: true -->

## Super Resolution

![Architecture defloutage](./Images/07-architecture/Defloutage2.PNG)

---
  
<!-- *page_number: true -->

## ResNet : Estimer les résidus

<center>

![Exemple ResNet](./Images/07-architecture/ResNet.PNG)

</center>

---

<!-- *page_number: true -->

## ResNet : Estimer les résidus

<center>

![Modèle ResNet](./Images/07-architecture/ResNet2.PNG)

 -Convergence rapide
 
 -Apprend plus de détails

</center>

---

<!-- *page_number: true -->

## Inception v3 : l'un des meilleurs classificateur (Pourquoi ?)

![modèle InceptionV3](./Images/07-architecture/InceptionV3.PNG)

---

<!-- *page_number: true -->

# <center> Travaux récents en deep learning </center>

---

<!-- *page_number: true -->

## Deep painterly harmonization

* utilise un VGG pré-entrainé

![Exemple de deep painterly](./Images/07-architecture/Deep_painterly.PNG)

|copier/coller de la première image sur la seconde| image avant l'application des  CNNs |image après l'application des CNNs|
|:--:|:--:|:--:|

---

<!-- *page_number: true -->

## Exemples

![Exemple de deep painterly 2 ](./Images/07-architecture/Deep_painterly2.PNG)

---

<!-- *page_number: true -->

## Célébrités

<center>

![Photos célébrités](./Images/07-architecture/Célébrités.PNG)

Reconnaissez-vous ces célébrités ?

</center>

---

<!-- *page_number: true -->

## Célébrités

<center>

![Photos célébrités](./Images/07-architecture/Célébrités.PNG)

Ces célébrités ont été inventées par des réseaux de neurones !

(Generative Adversarial Network - GAN)

</center>

---
 
<!-- *page_number: true -->

## Generative Adversarial network

![GAN](./Images/07-architecture/GAN.PNG)

---
  
<!-- *page_number: true -->

<center>

![Photos célébrités](./Images/07-architecture/Célébrités.PNG)

</center>





