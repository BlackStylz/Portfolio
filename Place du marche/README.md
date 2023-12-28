# Place du marché
![Static Badge](https://img.shields.io/badge/Python-blue) | ![Static Badge](https://img.shields.io/badge/Conda-green)

![Static Badge](https://img.shields.io/badge/NLP-grey) | ![Static Badge](https://img.shields.io/badge/ComputerVision-orange)

## Problématique
La société "Place de marché" souhaite automatiser l'attribution des catégories des articles sur sa plateforme e-commerce. Actuellement effectuée manuellement, cette tâche est peu fiable en raison d'un petit volume d'articles. L'objectif est de rendre l'expérience utilisateur fluide en automatisant cette tâche. Le Lead Data Scientist, charge d'étudier la faisabilité d'un moteur de classification d'articles basé sur des images et des descriptions. 

La première itération implique une analyse exploratoire, une extraction de features textuelles et d'images, une réduction en 2D, et une évaluation de la faisabilité de regrouper automatiquement des produits de même catégorie. 
La deuxième itération demande une classification supervisée à partir des images avec data augmentation. De plus, le Lead Scientist souhaite tester la collecte de produits "champagne" via une API et demande une extraction des 10 premiers produits avec certaines informations spécifiques.

## Partie Texte
Analyse du jeu de données textuelles. 
Test de faisabilité via un clustering et comparaison.
Comparaison des différentes approches de classification:
- 2 approches de type “bag-of-words”, comptage simple de mots et Tf-idf
- une approche de type word/sentence embedding classique avec Word2Vec
- une approche de type word/sentence embedding avec BERT
- une approche de type word/sentence embedding avec USE
Comparaison.

## Partie Image
Analyse du jeu de données visuelles.
Test de faisabilité via un clustering et comparaison.
Comparaison des différentes approches de classification:
- un algorithme de type SIFT
- un algorithme de type CNN Transfer Learning
Comparaison.

## Script API
Script pour la collecte de produits à base de champagne via une API.

## Présentation
Support de présentation orale, description de différentes approches et présentation des résiultats.