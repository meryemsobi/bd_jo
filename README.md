# 🌟 Tableau de bord JO - Projet Universitaire

## 📄 Contexte du projet

Ce projet a été réalisé dans le cadre de ma formation en BUT Informatique, lors du second semestre de l'année universitaire 2023-2024. Il s'agit d'un projet **de visualisation et de manipulation de données** issues des Éditions des Jeux Olympiques (Édition 2020, ou 1956 pour ma partie), à partir d'une base de données Oracle.

> 🔹 Le projet a été réalisé en **binôme** avec d'autres étudiant(e)s.
> 🔹 Finalisation du projet : **juin 2024**.

## 📊 Objectifs

* Se connecter à une base de données Oracle et effectuer des requêtes SQL
* Créer des **tableaux de bord statistiques** (nations, athlètes, médailles)
* Ajouter de nouvelles données dans la base
* Manipuler les résultats via des requêtes SQL complexes
* Réaliser des **représentations graphiques** avec `matplotlib` et `seaborn`

## 🚀 Fonctionnalités principales

### ✅ Connexion à la base Oracle

Connexion sécurisée avec gestion manuelle des identifiants via `getpass` et `oracledb`.

### ✅ Extraction des données

Requêtes SQL sur plusieurs tables :

* Nombre de nations
* Nombre d’athlètes par genre et par pays
* Médailles par pays et par épreuves
* Répartition par NOC (National Olympic Committee)

### ✅ Visualisation

* Graphiques avec `matplotlib` et `seaborn`
* Tableaux de données avec `pandas`

### ✅ Ajout et modification de données

* Ajout d'une nouvelle épreuve : **Tir à l'arc à poulies (Compound)**
* Insertion des résultats simulés à partir d'une épreuve existante
* Attribution automatique des médailles (or, argent, bronze)

### ✅ Nettoyage des données

* Suppression des éléments ajoutés pour restaurer la base initiale

## 🔗 Technologies et bibliothèques utilisées

* Python 3.x
* Oracle DB (`oracledb`)
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📖 Organisation du code

* `Connexion` : classe pour gérer les connexions Oracle
* `requete_vers_dataframe()` : fonction pour exécuter proprement les requêtes et récupérer les données
* Scripts répartis entre :

  * Partie **Consultation des données**
  * Partie **Ajout d'épreuves**
  * Partie **Insertion de résultats et médailles**
  * Partie **Nettoyage de la base**

## 📊 Exemples de sorties (visuels)

* Graphiques en barres sur la répartition des athlètes par genre ou pays
* Tableaux de médailles individuelles et par équipe
* Classement des pays selon leurs résultats

## 📅 Dates clés

* Début du projet : avril 2024
* Finalisation : juin 2024

## 👨‍💼 Rôle personnel

* Conception des requêtes SQL avancées (jointures complexes, filtres, agrégats)
* Création des visuels statistiques
* Ajout manuel des épreuves, résultats et médailles
* Nettoyage et test de cohérence des données

## ✨ Conclusion

Un projet très formateur pour la **manipulation de bases de données relationnelles** en environnement Oracle, l'écriture de requêtes SQL complexes et l'utilisation de Python pour l'analyse de données.

> ✅ Ce projet m’a permis de renforcer mes compétences en SQL, Python et visualisation de données.
