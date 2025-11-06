# **Challenge MOSEF: Bank Churn Prediction**

## English Version

## Project Description

This project was developed as part of the MOSEF Kaggle Challenge on **bank customer churn prediction**.  
The goal was to build a high-performance machine learning model capable of predicting whether a client would leave the bank (`Exited` = 1) or stay (`Exited` = 0).

---

## Data

The dataset was divided into two subsets:

- **Train:** 10,000 observations with 14 variables (including 11 key features)  
- **Test:** 5,000 observations with 13 variables (target variable `Exited` excluded)

---

## Data Preprocessing

- Outlier detection and removal  
- Feature engineering for categorical and numerical variables  
- Normalization using **RobustScaler**

---

## Modeling

- **Model used:** `CatBoostClassifier` (well-suited for categorical data and resistant to overfitting)  
- **Evaluation metric:** ROC-AUC  
- **Hyperparameter optimization:** Grid Search combined with stratified K-Fold Cross-Validation  

---

## Model Performance

- **Best ROC-AUC (cross-validation):** 0.9385  
- **Final validation ROC-AUC:** 0.9324  

---

## Authors

- [Alisa Chekalina](https://github.com/chekalisa)  
- [Carmen Cristea](https://github.com/CarmenParis)

---
## 🇬🇧 French Version

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

## Authors

- [Alisa Chekalina](https://github.com/chekalisa)
- [Carmen Cristea](https://github.com/CarmenParis)






