# Pret à dépenser
![Static Badge](https://img.shields.io/badge/Python-blue) | ![Static Badge](https://img.shields.io/badge/Conda-green)

![Static Badge](https://img.shields.io/badge/Sklearn-dark_green) | ![Static Badge](https://img.shields.io/badge/XGBoost-blue) | ![Static Badge](https://img.shields.io/badge/LightGBM-yellow) | ![Static Badge](https://img.shields.io/badge/ML%20Flow-%2308089C)

## Problématique
Au sein de la société financière "Prêt à dépenser", l'objectif est de développer un outil de "scoring crédit" pour évaluer la probabilité de remboursement d'un client et classifier les demandes de crédit comme accordées ou refusées. Pour cela, un algorithme de classification basé sur diverses sources de données, y compris des données comportementales et provenant d'autres institutions financières, doit être mis en place. La société souhaite également répondre à la demande croissante de transparence des clients en développant un dashboard interactif pour les chargés de relation client. 

La mission comprend la construction d'un modèle de scoring, le développement d'un dashboard interactif, la mise en production du modèle via une API, et l'exploration d'une démarche MLOps pour la gestion du cycle de vie du modèle. Des spécifications détaillées pour le dashboard incluent la visualisation des scores, l'interprétation des prédictions, et des fonctionnalités de filtrage et de comparaison des informations clients. L'utilisation des librairies Dash, Bokeh ou Streamlit est recommandée. Une démarche d'élaboration des modèles avec Cross-Validation, une analyse de Data Drift avec la librairie evidently, et la prise en compte du déséquilibre des classes et des coûts métier sont des aspects essentiels de la mission. Le déploiement de l'application et de l'API se fera sur une plateforme Cloud gratuite, et une note technique documentant l'ensemble de la démarche sera fournie pour partager les réalisations avec l'équipe.

### Source des données
https://www.kaggle.com/c/home-credit-default-risk/data

## Modelisation
Traitement et mise en forme des données. Test des différents modèles dans un environnement ML Ops via ML Flow.
Optimisation du modèle en forction de la métrique métier.
Visualisation de l'importance des variable dans la décision.

## API
Réalisation de l'API, qui permet de réaliser la prédiction. Mise en production via Heroku.

## Dashboard
Dashboard de visualisation, qui permet de visualiser, comparer les données clients, ainsi qu'observer la décision. Mise en production via Heroku.

## Note Méthodologique
Note explicative de la méthode employée.

## Présentation
Support de présentation orale, explication rapide de la méthodologie, démonstration de l'APi et du dashboard. Ainsi que les conclusion concernant le Data Drift.

## Rapport Data drift
Dashboard de visualisation concernant le Data Drift.