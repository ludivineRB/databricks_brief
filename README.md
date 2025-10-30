# 🚕 Analyse des données des taxis de New York avec PySpark & Databricks

## 🧩 Description du projet

Ce projet a pour objectif de **traiter et analyser les données des taxis de New York** en utilisant **PySpark** sur **Databricks**, déployé via **Microsoft Azure**.
Les traitements ont été réalisés dans trois notebooks Python distincts, chacun dédié à une étape clé de la préparation et de l’analyse des données.

---

## 📚 Données utilisées

Les données proviennent du portail officiel **NYC Taxi & Limousine Commission (TLC)** :
🔗 [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

Les datasets incluent notamment les courses des taxis jaunes (Yellow Taxi Trip Records).

---

## 🧠 Structure du projet

| Notebook                         | Description                                                                                                                                                               |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **merge_table.ipynb**            | Chargement des données brutes dans Databricks depuis le stockage Azure et conversion en DataFrame PySpark.                                                                |
| **clean_db.ipynb**               | Nettoyage des données : suppression des doublons, uniformisation des colonnes.                                                                                            |
| **create_table_azur_sql.ipynb**  | Analyses exploratoires et agrégations : identification des zones les plus fréquentées, durées moyennes de trajets, montants moyens, et export des tables vers Azur SQL.   |

---

## ⚙️ Technologies utilisées

* **Databricks** (sur Azure)
* **PySpark / Spark SQL**
* **Azur SQL**
* **Python 3.x**

---

## 📊 Résultats principaux

* Identification des **zones de départ les plus fréquentées par mois**
* Calcul des **durées moyennes de trajets**
* Visualisation des **volumes de trajets par période**

---

## 🚀 Prochaines étapes

* Ajout d’un dashboard interactif (via Power BI ou Streamlit)
* Mise en production d’un pipeline automatique (Airflow / Azure Data Factory)
* Intégration d’un modèle de prédiction de la durée ou du montant du trajet

---

## 👩‍💻 Auteur

**Ludivine Raby**
Projet réalisé dans le cadre de l’exploration des données en environnement cloud avec PySpark et Databricks.
