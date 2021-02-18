# SVHN

## Introduction
Utilisation d'une dataset d'images des numéros de maison issues de Street View.
Pour chaque image, on peut ainsi avoir le numéro à prédire.

## Modèle  
Reseau de neurone + convolution
Loss function : SparseCategoricalCrossentropy
Optimizer : Adam

## Processus 
* Traitement des images : Niveau de gris + normalistion
* Création du modèle
* Entrainement du modèle 
* Validation du modèle

## Difficultés à prévoir
* Paramétrage du modèle 
* Manipulation des données
* Temps de calcul
