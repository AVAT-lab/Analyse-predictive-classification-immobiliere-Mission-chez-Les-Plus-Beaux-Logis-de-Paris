# 🏙️ Analyse prédictive & classification immobilière – Mission chez Les Plus Beaux Logis de Paris

## 🎯 Objectif du projet

En tant que Business Intelligence Analyst chez ESN Data, j’ai accompagné le client **Les Plus Beaux Logis de Paris** dans l’analyse de son portefeuille immobilier parisien.

Ce projet s’articule autour de deux axes :
1. **Prévoir l’évolution des prix/m² à Paris entre 2017 et 2021** ;
2. **Automatiser la classification des biens** pour orienter les décisions d’achat et de revente.

---

## 🏢 Contexte

Le client souhaitait mieux comprendre les dynamiques de prix à Paris selon les zones et les types de biens, tout en industrialisant la catégorisation de son portefeuille (logement, local commercial…).

---

## 🧩 Méthodologie

### 🔹 Partie 1 – Analyse exploratoire & prédiction

- Étude temporelle et géographique des prix au m²
- Tests statistiques : **ANOVA**, **Kruskal-Wallis**, **corrélation de Pearson**
- Modèle de **régression linéaire** pour prédire les prix futurs
- Segmentation client : **Particuliers vs Corporate**

### 🔹 Partie 2 – Classification automatique (clustering)

- Nettoyage et normalisation des données
- Algorithme **KMeans** sur prix/m² et localisation
- Interprétation des clusters et validation métier (logement vs commerce)

---

## 📊 Résultats clés

- 📈 Corrélation prix/temps très forte (**Pearson = 0.90**)
- 🏢 Les locaux commerciaux > logements en termes de prix au m²
- 📦 Le **segment Corporate** représente **58 %** de la valeur du portefeuille

---

## 📁 Livrables

- 🧪 [Notebook d’analyse (Jupyter)](./Vatin_Antoine_1_Notebook_022025.ipynb)
- 🎤 [Présentation des résultats (PPTX)](./Vatin_Antoine_présentation_2_032025.pptx)

---

## 🧠 Compétences mobilisées

### 🔧 Hard Skills

- 📉 Analyse de séries temporelles
- 📊 Tests statistiques : ANOVA, Kruskal-Wallis, corrélation
- 📈 Régression linéaire
- 🤖 Clustering avec **KMeans**
- 🧼 Nettoyage & normalisation de données (Pandas, Scikit-learn)

### 🤝 Soft Skills

- Reformulation métier ↔ technique
- Présentation pédagogique pour la direction
- Recommandations stratégiques d’arbitrage
- Esprit de synthèse & storytelling

---

## ✅ Recommandations formulées

- 🏘️ Céder les biens résidentiels situés en zones à faible croissance
- 🏦 Conserver les locaux dans les arrondissements en développement
- 📊 Prioriser les biens à forte valorisation potentielle
- 🔄 Enrichir les modèles futurs par des variables qualitatives
