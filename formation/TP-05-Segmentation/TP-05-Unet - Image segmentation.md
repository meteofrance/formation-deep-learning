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

# Deep Learning : Unet - Segmentation d'image

<br/>

### Présentation partagée sous la licence Apache 2.0

---
  
<!-- *page_number: true -->

## Segmenter des images avec un réseau de neurones

Identifier à quel classe appartient chaque pixel

<center> 

![Segmentation](./Images/08-Unet/segmentation.PNG)

</center> 

---

<!-- *page_number: true -->

## L'architecture Unet (Olaf Ronneberger, Philipp Fischer, and Thomas Brox - 2015)  

<center> 

![Architecture Unet](./Images/08-Unet/architecture.PNG)

</center>

---

<!-- *page_number: true -->

## Labellisation du jeu d'entraînement   

■ Pour labelliser le jeu d'entraînement : outil gratuit VGG Image annotator (VIA)   http://www.robots.ox.ac.uk/~vgg/software/via/

■ Nous allons utiliser cet outil pour 

* Délimiter les différents objets de l'image avec des polygones 
* Exporter un fichier csv contenant les polygones 

<center>

![Image cygne](./Images/08-Unet/Cygne.PNG) 

</center>

--- 

<!-- *page_number: true -->

##### <center> Travaux Pratiques : créer et entraîner un Unet </center> 
