Titanic – Supervised Classification (TP)

Ce projet présente un pipeline complet de classification supervisée appliqué au dataset Titanic afin de prédire la variable cible Survived (0/1).

Contenu du projet

Exploration des données (EDA) : analyse de la cible et visualisations (survie par sexe, impact de la taille de famille).

Prétraitement :

gestion des valeurs manquantes,

extraction de Initial (titre : Mr, Mrs, Miss, Master…) depuis Name,

imputation de Age par la moyenne au sein de chaque groupe Initial,

création de features : Family_size et Alone,

encodage des variables catégorielles (Sex, Embarked, Initial) en numérique.

Modélisation & comparaison :

Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Naive Bayes, SVM

Évaluation : accuracy, matrice de confusion, precision/recall/F1-score

Pistes d’amélioration : ajout/sélection de variables, standardisation, tuning hyperparamètres (validation croisée)

Technologies

Python, pandas, matplotlib

scikit-learn (modèles + métriques)

DataSet Link :- https://www.kaggle.com/datasets/yasserh/titanic-dataset
