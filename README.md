# TP_XGBOOST

Ce TP présente une étude approfondie de l'algorithme XGBoost en comparaison avec d'autres modèles d'apprentissage supervisé. Nous évaluons les performances de XGBoost dans les tâches de classification et de régression en utilisant différentes configurations d'hyperparamètres et en comparant ses résultats avec plusieurs algorithmes.

## I. Classification

Dans cette première partie, nous explorons l'utilisation de XGBoost pour la classification. Nous importons des jeux de données à la fois binaires et multiclasse à partir de la bibliothèque scikit-learn. Ensuite, nous comparons les performances de XGBoost avec celles de deux modèles d'arbres de décision, un modèle de régression logistique, ainsi que les algorithmes de boosting GradientBoosting et Adaboost.

### I.1 Importer les datasets

Nous importons des datasets binaires et multiclasse à partir de la bibliothèque scikit-learn, puis les divisons en ensembles d'entraînement et de test.

### I.2 Entraîner deux modèles d'arbres de décision + un modèle RandomForest

Nous entraînons deux modèles d'arbres de décision (avec les critères Gini et Entropy) ainsi qu'un modèle RandomForest pour la classification. Nous évaluons leurs performances en termes de temps d'entraînement, d'accuracy et de F1-score sur les ensembles d'entraînement et de test.

### I.3 Entraîner un modèle de régression logistique

Nous entraînons un modèle de régression logistique pour la classification et évaluons ses performances de la même manière que pour les modèles d'arbres de décision.

### I.4 Entraîner trois modèles de boosting : GradientBoosting, Adaboost et Lightgbm

Nous entraînons des modèles de boosting (GradientBoosting, Adaboost et Lightgbm) pour la classification et comparons leurs performances avec celles de XGBoost.

### I.5 Entraîner un modèle XGBOOST

Nous entraînons enfin un modèle XGBoost pour la classification et évaluons ses performances.

## II. Régression

Dans cette partie, nous étudions l'utilisation de XGBoost pour la régression en comparaison avec d'autres modèles tels que la régression linéaire, Gradient Boosting et Adaboost.

### II.1 Importer la dataset

Nous importons une dataset de la bibliothèque scikit-learn pour la régression, puis la divisons en ensembles d'entraînement et de test.

### II.2 Entraîner un modèle de régression linéaire

Nous entraînons un modèle de régression linéaire et évaluons sa performance en termes de temps d'entraînement et de Mean Squared Error (MSE) sur l'ensemble de test.

### II.3 Entraîner un modèle Adaboost et un autre Gradient Boosting

Nous entraînons des modèles Adaboost et Gradient Boosting pour la régression et comparons leurs performances avec XGBoost.

### II.4 Entraîner un modèle XGBOOST

Nous entraînons enfin un modèle XGBoost pour la régression et évaluons ses performances.

## III. Exploration des Hyperparamètres

Dans cette section, nous explorons différents hyperparamètres de XGBoost pour la classification en utilisant un dataset de réservation d'hôtels et évaluons leur impact sur les performances du modèle.

### III.1 Max depth

Nous explorons l'effet de la profondeur maximale des arbres sur les performances du modèle.

### III.2 Learning rate

Nous étudions l'impact du taux d'apprentissage sur les performances du modèle XGBoost.

### III.3 Min child weight

Nous explorons l'effet du poids minimum des enfants sur les performances du modèle.

### III.4 Autres hyperparamètres

Nous examinons également l'impact d'autres hyperparamètres tels que colsample_bytree, subsample, gamma, reg_alpha et reg_lambda sur les performances du modèle.

Ce TP offre une exploration détaillée de XGBoost et de ses performances dans différents scénarios d'apprentissage supervisé. Les résultats obtenus peuvent être utilisés pour orienter le choix d'algorithme dans différentes situations d'apprentissage automatique.
