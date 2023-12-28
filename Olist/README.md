# Olist
![Static Badge](https://img.shields.io/badge/Python-blue) | ![Static Badge](https://img.shields.io/badge/Conda-green)

![Static Badge](https://img.shields.io/badge/Sklearn-dark_green)

## Problématique
Olist sollicite une segmentation des clients pour optimiser ses campagnes de communication. L'objectif est de comprendre les différents types d'utilisateurs à travers leur comportement et leurs données personnelles. Les données fournies par Olist comprennent des informations sur l'historique des commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017. 

La mission implique l'utilisation de méthodes non supervisées pour regrouper des clients similaires, en créant un notebook pour l'analyse exploratoire. Malgré des données limitées (3% des clients ont effectué plusieurs commandes), l'objectif est de produire une segmentation exploitable par l'équipe Marketing, différenciant les clients en termes de commandes et de satisfaction. De plus, une recommandation sur la fréquence de mise à jour de la segmentation est demandée pour élaborer un contrat de maintenance. Le code fourni doit respecter la convention PEP8.

### Source des données
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Nettoyage
Filtrage, imputation, nettoyage et mise en forme du jeu de données pour suivre une stratégie RFM (Récence, Fréquence, Montant).

## Exploration
Analyse univariée et bivariée

## Clustering
Test des modèles: 
- K-means
- Agglomerative Clustering (Clustering hiérarchique)
- DBScan
Choix et optimisation du modèle, interprétation des différents clusters.

## Maintenance
Verification de la stabilité du modèle sur le long terme et définition de la fréquence de maintenance.

## Présentation
Support de présentation orale, explication de la stratégie et des clusters. Justification du délai de maintenance.