# Initiation au Deep Learning

Cette formation a été conçue pour initier au Deep Learning, en deux jours, des chercheurs, ingénieurs d'études et développeurs. Elle s'adresse à des personnes n'ayant pas de connaissance préalable du domaine.

La formation est en langue française.

Cette formation a été initialement créée par Météo-France pour ses salariés, mais elle est parfaitement adaptée à d'autres domaines d'application que la météorologie. Les supports de cours et les codes sources des travaux pratiques sont partagés en open-source dans ce dépôt.

## Pré-requis

  * Connaissances de base en programmation, idéalement en python
  * Mathématiques, niveau premier cycle universitaire

## Programme de la formation

La formation alterne cours et travaux pratiques. Elle est prévue pour être suivie dans l'ordre suivant :

  * Cours 00    - Programme de la formation
  * Cours 01    - Introduction au Machine Learning - Vidéo : https://youtu.be/9OhTBItdw18
  * Cours TP 01 - Python pour Data Scientists
  * TP 01       - Python pour Data Scientists
  * TP 02       - Reconnaissance de chiffres manuscrits (modèles linéaires, random forest...)
  * Cours 02    - Introduction au Deep Learning
  * Cours 03    - La librairie Keras
  * TP 03       - Réseaux convolutionnels : reconnaissance de chiffres manuscrits avec Keras
  * Cours TP 04 - Visualisation et Transfer Learning
  * TP 04       - Transfer Learning : classification d'images
  * Cours 04    - Architecture de réseaux convolutionnels
  * Cours TP 05 - Segmentation par pixels avec Unet
  * TP 05       - Segmentation par pixels avec Unet
  * Cours 05    - Réseaux récurrents
  
## Format des fichiers

Les planches des cours sont au format Markdown, afin d'être aisément modifiables. Une version pdf est également fournie. La version pdf est générée à partir du Markdown avec l'utilitaire Marp :

https://yhatt.github.io/marp/

## Comment faire les TP ?

### Installation

Les TP sont en Python 3, au format Jupyter Notebook. Pour plus d'informations sur l'installation et l'utilisation de Jupyter Notebook : https://jupyter.org/

Pour l'installation de Python 3 et des librairies scientifiques, nous recommandons Anaconda. Sur ce lien, choisir Python 3.6:
https://www.anaconda.com/download/

Les librairies python suivantes sont requises, certaines étant déjà incluses dans Anaconda :

  * numpy
  * pandas
  * sklearn
  * tensorflow
  * keras
  * fastai (Attention, installer la version 0.7. La nouvelle version 1.0 n'est pas compatible.)

### Les Travaux Pratiques

Dans le dossier de chaque TP, vous trouverez :

  * Le TP lui-même, sous la forme d'un notebook Jupyter à compléter,
  * La correction du TP.

## Comment contribuer ?

Les contributions pour améliorer ce cours ou pour le compléter sont bienvenues.

## Crédits

Contributeurs ayant participé à la création de cette formation : Lior Perez, Simon Moisselin, Valentin Fouqueau

Certains contenus ont été empruntés à d'autres formations. Merci à leurs auteurs :

  * Cours de Machine Learning de Stanford par Andrew NG, sur la plateforme Coursera
  * Cours de Deep Learning de Stanford University par Fei-Fei Li, Justin Johnson et Serena Yeung
  * Cours fast.ai : https://www.fast.ai/

Si vous trouvez des documents non crédités, ou si nous avons involontairement utilisé sans votre accord un contenu vous appartenant, veuillez nous contacter.

If you believe that we have unintentionally used some contents without giving credits or without approval from the authors, please contact us.

## Licence

Copyright 2018 - Météo-France

Cette formation est partagée par Météo-France sous la licence Apache 2.0.

This content is shared by Météo-France under the Apache 2.0 licence.