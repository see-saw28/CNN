# SVHN

## Introduction
Utilisation d'une dataset d'images des numéros de maison issues de Street View.
Pour chaque image, on peut ainsi avoir le numéro à prédire. Le but est donc d'obtenir la meilleure précision possible.  
La dataset utilisée est 'svhn_cropped' issue de tensorflow_dataset.
J'utiliserais la bibliothèque tensorflow sur Python

## Modèle  
Reseau de neurone + convolution  
Fonction d'activation : softmax  
Loss function : SparseCategoricalCrossentropy  
Optimizer : Adam

## Processus 
* Traitement des images : Niveau de gris + normalistion
* Création du modèle
* Entrainement du modèle 
* Validation du modèle

## Difficultés à prévoir
* Manipulation des données
* Paramétrage du modèle 
* Temps de calcul
