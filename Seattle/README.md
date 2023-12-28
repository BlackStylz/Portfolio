# Seattle
![Static Badge](https://img.shields.io/badge/Python-blue) | ![Static Badge](https://img.shields.io/badge/Conda-green)

![Static Badge](https://img.shields.io/badge/Sklearn-dark_green) | ![Static Badge](https://img.shields.io/badge/XGBoost-blue) | ![Static Badge](https://img.shields.io/badge/LightGBM-yellow)

## Problématique
Modélisation des émissions de CO2 et de la consommation d'énergie des bâtiments non résidentiels à Seattle, en vue d'atteindre l'objectif de neutralité carbone d'ici 2050. 

L'analyse se fonde sur des relevés détaillés effectués en 2016, avec pour mission de prédire ces émissions pour les bâtiments non encore mesurés. La prédiction s'appuiera sur les données structurelles des bâtiments, en incluant l'évaluation de l'utilité de l'ENERGY STAR Score dans la modélisation. La démarche implique une analyse exploratoire, des tests de modèles de prédiction, une attention particulière à la fuite de données, la déduction de variables structurelles, et la mise en place d'une évaluation rigoureuse des performances des régressions avec optimisation des hyperparamètres via une validation croisée.

### Source de données
https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy/data_preview

## Exploration
Filtrage, imputation, nettoyage et mise en forme du jeu de données.
Analyse univariée et bivariée

## Prédiction consommation énergie
Tests des différents modèles sans et avec la variable ENERGY STAR Score:
- Régression Ridge
- Régression Lasso
- Régression Elastic Net
- kNN Regressor
- Suport Vector Regressor
- XGBoost Regressor
- LightGBM Regressor
- Random Forest Regressor
Comparaison puis optimisation du modèle et observation de l'importance des variable dans la prédiction.

## Prédiction émission CO2
Tests des différents modèles sans et avec la variable ENERGY STAR Score:
- Régression Ridge
- Régression Lasso
- Régression Elastic Net
- kNN Regressor
- Suport Vector Regressor
- XGBoost Regressor
- LightGBM Regressor
- Random Forest Regressor
Comparaison puis optimisation du modèle et observation de l'importance des variable dans la prédiction. 

## Présentation
Support de présentation orale, présentation de la méthodologie et des résultats ainsi que l'effet de l'ENERGY STAR Score.