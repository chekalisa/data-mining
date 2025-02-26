# **Challenge MOSEF: Bank Churn Prediction**

## Description du projet

Ce projet a été réalisé dans le cadre du challenge Kaggle MOSEF sur la prédiction du churn bancaire. L'objectif est de développer un modèle de machine learning performant capable de prédire si un client quittera ou non la banque (étiquette binaire "Exited").

## Données

Les données sont divisées en deux ensembles :

Train (Entraînement) : 10 000 observations avec 14 variables (dont 11 essentielles)

Test : 5 000 observations avec 13 variables (sans la variable cible "Exited")

## Prétraitement des données

- Gestion des valeurs aberrantes

- Feature Engineering

- Normalisation avec RobustScaler

## Modélisation

**Modèle choisi** : CatBoostClassifier (adapté aux données catégorielles et résistant au surapprentissage)

**Métrique d'évaluation** : ROC-AUC

**Optimisation des hyperparamètres** : Grid Search + Validation croisée K-Fold (stratifiée)



## Performance du modèle

Meilleur score ROC-AUC : 0.9385 (validation croisée)

Score final sur validation : 0.9324







