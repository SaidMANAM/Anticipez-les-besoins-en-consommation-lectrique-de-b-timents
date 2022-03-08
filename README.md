# Anticipez-les-besoins-en-consommation-lectrique-de-batiments


### Sommaire


- [Description](#description)
- [Compétences](#how-to-use)
- [Technologies](#references)

---

## Description

La prédiction des émissions de CO2 et la consommation totale d’énergie de bâtiments. L'évaluation de l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions.
La ville de Seattle a pour de devenir ville neutre en émissions de carbone en 2050, à l'aide de Deux relevés minutieux en 2015 et en 2016( qui vont construire notre dataset) on va prédire les émissions de CO2 et la consommation totale d’énergie de bâtiments.

Cette prédiction se basera sur les données déclaratives du permis d'exploitation commerciale (taille et usage des bâtiments, mention de travaux récents, date de construction..).

Ce notebook contient notre travail de nettoyage, préparation de nos données et une analyse exploratoire. La modélisation est dans le deuxième notebook: Pélec_01_Code.

## Compétences

- import des données; Source des données : https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv  
- L'uniformisation et la concaténation des datasets
- La résolution du problème de la fuite des données
- Analyse des données manquantes
- Analyse exploratoire de données
- Feature engineering
- Modèle baseline: DummyRegressor
- Modèle Ridgecv()
- Modèle Support Vector Machines
- Modèle RandomForest
- évaluation de l’intérêt de la variable "ENERGYSTARScore" pour la prédiction d’émissions
- Interprétation du model

## Technologies


- SHAP
- SCIKIT-LEARN
- Python
- PANDAS


[Back To The Top](#read-me-template)
