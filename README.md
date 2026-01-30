# 📊 Analyse comparative : Statistiques inférentielles vs Big Data Analytics  
## NYC Yellow Taxi Trips (2022–2024)
<img width="1536" height="1024" alt="ChatGPT Image 30 janv  2026, 10_00_29" src="https://github.com/user-attachments/assets/317c673b-4609-4310-8e2b-a2b98927af87" />

---

## 📌 Description du projet

Ce projet consiste à comparer deux approches d’analyse de données appliquées à des **données massives de mobilité urbaine** :

- **Statistiques inférentielles** basées sur un échantillon de **1 %**
- **Big Data Analytics** exploitant **100 %** des données via **Apache Spark**

L’étude porte sur les **NYC Yellow Taxi Trip Records (2022–2024)** et s’inscrit dans un contexte professionnel simulé au sein de l’entreprise **DATACO**.

---

## 🎯 Objectifs

- Analyser les caractéristiques des courses de taxis à New York  
- Calculer des indicateurs clés liés au prix, à la distance, à la durée et aux tips  
- Comparer les résultats issus :
  - d’une approche statistique classique
  - d’une approche Big Data distribuée  
- Identifier les avantages, limites et cas d’usage de chaque méthode

---

## ❓ Questions analytiques

- Prix moyen d’une course  
- Distance moyenne et durée moyenne  
- Proportion des courses avec tip > 0  
- Identification des heures de pointe  
- Analyse des différences géographiques (pickup / dropoff)  
- Analyse des outliers (courses très longues ou très chères)  
- Ratio moyen tip / fare selon le type de paiement (cash vs card)

---

## 📁 Jeux de données

### `yellow_taxi_sample_1pct_inferential`
- Échantillon représentant **1 %** des courses
- Utilisé pour l’approche **statistiques inférentielles**
- Objectif : inférer les propriétés de la population

### `DATAaspaquet`
- Données complètes des courses de taxis (2022–2024)
- Utilisées pour l’approche **Big Data Analytics**
- Traitement sans échantillonnage

---

## ⚙️ Méthodologie

1. Exploration et compréhension des données (EDA)  
2. Analyse par statistiques inférentielles (échantillon 1 %)  
3. Analyse Big Data sur population complète  
4. Comparaison des résultats  
5. Réflexion critique et restitution

---

## 🛠️ Technologies utilisées

- Databricks Community Edition  
- Apache Spark (PySpark)  
- Python  
- pandas  
- matplotlib / seaborn / plotly  
- Canva (slides de restitution)

---

## 📊 Résultats clés

- Les statistiques inférentielles fournissent de bonnes **estimations globales**
- Les écarts augmentent pour les analyses fines et les valeurs extrêmes
- Le Big Data garantit des **résultats précis et exhaustifs**
- Le choix méthodologique dépend du contexte métier et du niveau de précision attendu

---

## ✅ Conclusion

Les statistiques inférentielles sont adaptées à une **exploration rapide et peu coûteuse**, tandis que le Big Data est indispensable pour des **analyses fiables et stratégiques**.  
👉 La **combinaison des deux approches** constitue la solution la plus efficace en contexte professionnel.

---

## 📦 Livrables

- Notebook Databricks (Python / Spark)  
- Slides de présentation (Canva – PDF)
