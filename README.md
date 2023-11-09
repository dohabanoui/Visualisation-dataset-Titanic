# Analyse du Dataset Titanic en Python

Ce référentiel contient un exemple d'analyse du dataset Titanic en utilisant Python, avec un accent particulier sur l'utilisation de bibliothèques telles que pandas, matplotlib, et seaborn. L'analyse comprend différentes étapes, de la lecture du dataset à la visualisation des données.

## Contenu

- [Tâches à faire](#tâches-à-faire)
- [Lire le dataset Titanic](#lire-le-dataset-titanic)
  - [Affichage des premières lignes du dataframe](#affichage-des-premières-lignes-du-dataframe)
  - [Afficher des dernières lignes du dataframe](#afficher-des-dernières-lignes-du-dataframe)
  - [Affichage de la forme du DataFrame](#affichage-de-la-forme-du-dataframe)
  - [Affichage des informations sur le DataFrame](#affichage-des-informations-sur-le-dataframe)
  - [Vérification des valeurs manquantes](#vérification-des-valeurs-manquantes)
  - [Statistiques descriptives](#statistiques-descriptives)
  - [Les colonnes existantes](#les-colonnes-existantes)
  - [Affichage des valeurs uniques dans les colonnes "Sex" et "Survived"](#affichage-des-valeurs-uniques-dans-les-colonnes-sex-et-survived)
  - [Cleaning data](#cleaning-data)
- [Analyse de la corrélation entre les variables](#analyse-de-la-corrélation-entre-les-variables)
  - [Dataset pour les survivants](#dataset-pour-les-survivants)
  - [Dataset pour les non-survivants](#dataset-pour-les-non_survivants)
  - [Diagramme en boîte des âges pour les survivants et les non-survivants](#diagramme-en-boîte-des-âges-pour-les-survivants-et-les-non-survivants)
  - [Histogrammes de l'âge en fonction de "Survived"](#histogrammes-de-lâge-en-fonction-de-survived)
  - [Histogramme des âges pour les survivants et les non-survivants](#histogramme-des-âges-pour-les-survivants-et-les-non-survivants)
  - [Distribution de l'Âge en Fonction de la Survie](#distribution-de-lâge-en-fonction-de-la-survie)
  - [Diagramme en barres pour le nombre de survivants par classe](#diagramme-en-barres-pour-le-nombre-de-survivants-par-classe)
  - [Diagramme en barres pour le nombre de survivants par sexe](#diagramme-en-barres-pour-le-nombre-de-survivants-par-sex)
  - [Visualisation en 3D](#visualisation-en-3d)
  - [Création de DataFrames pour les Masculins et Féminins Survivants](#création-de-dataframes-pour-les-masculins-et-féminins-survivants)
    - [Répartition de l'Âge des Masculins et des Femmes Survivants](#répartition-de-lâge-des-masculins-et-des-femmes-survivants)

## Comment utiliser ce code

1. [Téléchargez le dataset](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html) du Titanic.
2. Chargez le dataset en utilisant la bibliothèque pandas.
3. Exécutez chaque section du code pour effectuer l'analyse étape par étape.

## Dépendances

Assurez-vous d'avoir installé les dépendances suivantes avant d'exécuter le code :
- pandas
- matplotlib
- seaborn
- plotly

