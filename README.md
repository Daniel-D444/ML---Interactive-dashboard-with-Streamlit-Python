# Binary Classification Web App - Mushroom Dataset

Ce projet est une application **interactive** développée avec [Streamlit](https://streamlit.io/).  
Elle permet de comparer plusieurs modèles de **classification binaire** afin de prédire si un champignon est **comestible** ou **toxique**.

---

## Fonctionnalités

- Interface web interactive avec **Streamlit**
- Chargement automatique du dataset `mushrooms.csv`
- Encodage automatique des variables catégorielles
- Séparation des données en **train/test**
- Choix de trois classifieurs :
  - Support Vector Machine (SVM)
  - Régression Logistique
  - Random Forest
- Réglage des **hyperparamètres** via la barre latérale
- Visualisation des métriques :
  - ✅ Matrice de confusion
  - ✅ Courbe ROC
  - ✅ Courbe Précision-Rappel
- Affichage des scores :
  - Accuracy
  - Precision
  - Recall
- Option d’affichage des **données brutes**

---

## Aperçu du Dashboard

<img width="1905" height="910" alt="image" src="https://github.com/user-attachments/assets/563dd849-4f48-41b4-8a9d-6cde356b8f9d" />

---

## Dataset

Le dataset utilisé est `mushrooms.csv`, disponible sur [Kaggle - Mushroom Classification](https://www.kaggle.com/uciml/mushroom-classification).  
Chaque ligne représente un champignon avec ses caractéristiques (couleur, taille, odeur, etc.) et sa classe (`edible` ou `poisonous`).

---

## Installation et Exécution

### 1. Cloner le repo

git clone https://github.com/Daniel-D444/ML---Interactive-dashboard-with-Streamlit-Python.git

### 2. Installer les dépendances (Télécharger au préalable requirements.txt)

pip install -r requirements.txt

### 3. Exécuter depuis un terminal

Streamlit run Appstreamlit.py

