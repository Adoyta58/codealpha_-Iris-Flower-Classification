# 🌸 CodeAlpha_Iris_Classification

Ce projet a été réalisé dans le cadre de mon stage en data science chez **CodeAlpha**.  
Il consiste à prédire l'espèce d'une fleur d'iris à partir de ses caractéristiques morphologiques (longueur/largeur des pétales et sépales), en utilisant des modèles de classification supervisée.

---

## 🎯 Objectif du projet

- Comprendre et appliquer les concepts de classification supervisée.
- Construire un modèle capable de prédire l’espèce d’une fleur (Setosa, Versicolor, Virginica).
- Explorer visuellement les différences entre les espèces.

---

## 🧰 Outils et bibliothèques utilisés

- **Python 3**
- **Pandas** – manipulation des données
- **Seaborn** et **Matplotlib** – visualisation
- **Scikit-learn** – modélisation machine learning (KNN, SVM, Decision Tree, etc.)

---

## 🌸 Jeu de données

- **Source** : [Kaggle - Iris Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv)
- Le dataset contient 150 observations et 4 caractéristiques :
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- La variable cible est `Species` (3 classes).

---

## 🧪 Étapes du projet

1. **Chargement et exploration des données**
   - Analyse statistique et vérification des valeurs manquantes.
   - Visualisation des relations entre les variables avec Seaborn.

2. **Préparation des données**
   - Séparation des variables indépendantes (features) et dépendante (target).
   - Découpage en jeu d’entraînement et de test.

3. **Modélisation**
   - Entraînement de plusieurs algorithmes de classification :
     - K-Nearest Neighbors
     - Decision Tree
     - Support Vector Machine (SVM)
   - Comparaison de leurs performances.

4. **Évaluation**
   - Matrice de confusion
   - Accuracy / Precision / Recall
   - Cross-validation (facultatif)
