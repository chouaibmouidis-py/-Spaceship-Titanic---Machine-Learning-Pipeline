# 🚀 Spaceship Titanic - End-to-End Machine Learning Pipeline

Bienvenue sur le dépôt de mon projet de Machine Learning réalisé pour la compétition Kaggle **Spaceship Titanic**. L'objectif est de prédire quels passagers ont été transportés vers une dimension alternative lors de la collision du vaisseau avec une anomalie spatio-temporelle.

---

### 🏆 Performances & Résultats

Ce pipeline rigoureux m'a permis d'atteindre le **Top 6.5%** du classement mondial (Leaderboard Public).

| Modèle | Score OOF (Accuracy) | Poids dans le Blend |
| :--- | :---: | :---: |
| **LightGBM** | ~0.8080 | 41.87 % |
| **XGBoost** | ~0.8050 | 30.20 % |
| **CatBoost** | ~0.8060 | 27.93 % |
| **Ensemble (Blend final)** | **0.81077** | **Seuil : 0.52** |

> 📌 **Score Leaderboard Public :** `0.81014` *(Alignement quasi-parfait avec la validation locale OOF : 0.81077, confirmant l'absence de fuite de données).*

---

### 🛠️ Architecture du Pipeline & Étapes clés

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

### 🗂️ Structure du Dépôt

    ├── Spaceship_Titanic.ipynb # Notebook principal du pipeline end-to-end
    ├── requirements.txt        # Dépendances du projet
    └── .gitignore              # Fichiers ignorés par Git

---

### ⚙️ Stack Technique

* **Langage** : Python 3.x
* **Manipulation & Calcul** : Pandas, NumPy
* **Machine Learning & Modélisation** : Scikit-Learn, LightGBM, XGBoost, CatBoost
* **Visualisation** : Matplotlib, Seaborn

---

### 🚀 Installation & Utilisation

# Cloner le dépôt
```
git clone https://github.com/chouaibmouidis-py/-Spaceship-Titanic---Machine-Learning-Pipeline.git

# Se déplacer dans le dossier
cd -Spaceship-Titanic---Machine-Learning-Pipeline

# Installer les dépendances
pip install -r requirements.txt

# Lancer le notebook
jupyter notebook Spaceship_Titanic.ipynb
```


📫 Contact & Liens
- LinkedIn : [MOUID / Chouaib](https://www.linkedin.com/in/chouaib-mouid-200893438/)
- Profil Kaggle : [chouaibmouid](https://www.kaggle.com/chouaibmouid)
