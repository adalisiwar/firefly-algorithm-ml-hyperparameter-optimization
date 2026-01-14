# Firefly Algorithm – Application Réelle en Machine Learning

Ce projet illustre une **application concrète du Firefly Algorithm**, une technique d’Evolutionary Computation, pour l’optimisation automatique des hyperparamètres d’un modèle de Machine Learning.

L’objectif est de démontrer l’impact réel du Firefly Algorithm sur les performances d’un modèle, plutôt que de se limiter à une implémentation théorique de l’algorithme.

---

## 🎯 Objectif du projet

- Utiliser le Firefly Algorithm comme **outil d’optimisation**
- Améliorer les performances d’un classifieur K-Nearest Neighbors (KNN)
- Travailler sur un **dataset réel**
- Mesurer l’impact en termes d’accuracy

---

## 🧠 Problème étudié

- **Tâche** : Classification binaire
- **Modèle** : K-Nearest Neighbors (KNN)
- **Dataset** : Breast Cancer Wisconsin (scikit-learn)
- **Métrique** : Accuracy (validation croisée)

Les hyperparamètres optimisés sont :
- Nombre de voisins (k)
- Type de pondération des voisins (uniform / distance)

---

## 🔥 Rôle du Firefly Algorithm

Dans ce projet :
- Chaque luciole représente une configuration d’hyperparamètres
- La luminosité correspond à la performance du modèle
- Le Firefly Algorithm explore intelligemment l’espace de recherche
- L’objectif est de maximiser l’accuracy du modèle

---

## 📈 Résultats

- Le modèle optimisé par Firefly Algorithm obtient une meilleure accuracy
- L’approche est plus efficace qu’un réglage manuel
- Le Firefly Algorithm montre son utilité dans un contexte réel et pratique

---

## 📁 Contenu du dépôt
```firefly-algorithm-ml-hyperparameter-optimization/
│── firefly_knn_optimization.ipynb
│── README.md
│── requirements.txt ```

