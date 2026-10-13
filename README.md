# 🚀 Spaceship Titanic - End-to-End Machine Learning Pipeline

Bienvenue sur le dépôt de mon projet de Machine Learning réalisé pour la compétition Kaggle **Spaceship Titanic**. L'objectif est de prédire quels passagers ont été transportés vers une dimension alternative lors de la collision du vaisseau avec une anomalie spatio-temporelle.

---

## 🏆 Performances & Résultats

Ce pipeline rigoureux m'a permis d'atteindre le **Top 6.5%** du classement mondial (Leaderboard Public) :

* **Score Leaderboard (Public)** : `0.81014`
* **Score Local OOF (Accuracy)** : `0.81100`
* **AUC Local** : `0.90582`

---

## 🛠️ Architecture du Pipeline & Étapes clés

Le projet repose sur un pipeline de données modulaire et robuste :

1. **Analyse Exploratoire & Feature Engineering** :
   * Extraction des caractéristiques cachées à partir des identifiants (`PassengerId` -> Groupe, Taille du groupe, Pont, Numéro de cabine, Côté).
   * Traitement des variables textuelles et catégorielles.

2. **Imputation Intelligente des Valeurs Manquantes** :
   * Stratégies d'imputation avancées pour les données financières, d'aménagement et d'âge afin de préserver la distribution des données.

3. **Modélisation & Ensemble Learning** :
   * Entraînement de modèles de Gradient Boosting de pointe : **LightGBM**, **XGBoost** et **CatBoost**.
   * Optimisation des hyperparamètres et combinaison des prédictions (Ensemble Stacking/Blending) pour maximiser la robustesse de la généralisation.

---

## 🗂️ Structure du Dépôt

    ├── train.csv               # Données d'entraînement
    ├── test.csv                # Données de test
    ├── sample_submission.csv   # Format de soumission requis
    ├── Spaceship_Titanic.ipynb # Notebook principal du pipeline end-to-end
    ├── requirements.txt        # Dépendances du projet
    └── .gitignore              # Fichiers ignorés par Git

---

## ⚙️ Stack Technique

* **Langage** : Python 3.x
* **Manipulation & Calcul** : Pandas, NumPy
* **Machine Learning & Modélisation** : Scikit-Learn, LightGBM, XGBoost, CatBoost
* **Visualisation** : Matplotlib, Seaborn

---

## 🚀 Installation & Utilisation

Clone le dépôt sur ta machine :
    `git clone [https://github.com/chouaibmouidis-py/-Spaceship-Titanic---Machine-Learning-Pipeline.git](https://github.com/chouaibmouidis-py/-Spaceship-Titanic---Machine-Learning-Pipeline.git)`
    `cd -Spaceship-Titanic---Machine-Learning-Pipeline`

Installe les dépendances requises :
    `pip install -r requirements.txt`

Ouvre le notebook Jupyter pour lancer le pipeline :
    jupyter notebook Spaceship_Titanic.ipynb
