# 🔍 Analyse prédictive du risque de défaut de paiement et scoring client
### 💡 À l’aide des outils de Business Intelligence et de Big Data
---
## 🎯 Objectifs

Ce projet vise à **identifier et résoudre un problème concret lié à la gestion du risque client** dans le contexte d’une activité de crédit.  
Il s’appuie sur deux domaines : **Business Intelligence** et **Big Data**. Deux problématiques centrales guident l’approche :

- **Quels clients présentent un risque élevé de défaut de paiement ?**  
- **Comment estimer le niveau de risque individuel de crédit d’un client ?**

L’objectif  principal est de fournir une **analyse prédictive complète**, d’en **extraire des insights décisionnels** pertinents et de les **restituer via un dashboard interactif**, en combinant **machine learning avancé** et **visualisation dynamique**.

---

## 🧭 Plan détaillé du projet

### 1. Introduction
- Enjeux du risque de crédit
- Problématiques et objectifs
- Méthodologie et outils mobilisés : Python, Power BI, Spark, etc.

### 2. Préparation des données
- Source : Dataset **"Give Me Some Credit"** (Kaggle)
- Nettoyage : valeurs manquantes, outliers
- Feature engineering
- Prétraitement pour la modélisation

### 3. Analyse exploratoire (Business Intelligence)
- Dashboard interactif (Power BI ou Tableau)
- Visualisation :
  - Répartition des revenus, âges, charges
  - Taux de défaut par segment
  - Profils de clients à risque
  - Corrélations visuelles

### 4. Modélisation prédictive (Big Data / Machine Learning)
- Algorithmes testés :
  - Régression logistique
  - Random Forest
  - XGBoost (meilleur score)
- Évaluation :
  - AUC-ROC, précision, rappel, F1-score
  - Matrice de confusion

### 5. Scoring et segmentation client
- Estimation de la **probabilité individuelle de défaut**
- Création de **3 classes de risque** :
  - Faible (<10%)  
  - Moyen (10-30%)  
  - Élevé (>30%)
- Intégration dans un **dashboard dynamique**

### 6. Recommandations stratégiques
- Aide à la décision automatisée
- Système d’alertes dynamiques
- Actions ciblées de recouvrement ou prévention

### 7. Conclusion et perspectives
- Résultats clés
- Limites du modèle
- Pistes d’amélioration : données transactionnelles, historique, etc.

---

## 🧰 Outils & technologies

| Outil | Utilisation |
|------|-------------|
| **Python** | Préparation, modélisation, scoring |
| **scikit-learn / XGBoost** | Machine learning |
| **PySpark (optionnel)** | Traitement Big Data |
| **Power BI / Tableau** | Visualisation interactive |
| **PostgreSQL** | Stockage et manipulation des données |
| **Jupyter Notebook** | Documentation et reproductibilité |

---

## 📁 Structure du dépôt

