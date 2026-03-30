# 📊 Projet R208 - Examen Python : Étude Statistique

**BUT Informatique 1re année - Toulouse**

## 🎯 Objectif du projet
Ce projet consiste à réaliser, avec le langage Python, une étude statistique d'un jeu de données réel et à en présenter les résultats. 

La question centrale de notre étude est de **démontrer qu'un même ensemble de données peut être exploré selon plusieurs points de vue pour aboutir à des conclusions différentes**. Nous avons cherché à prouver que le choix de la population observée, de la période retenue et des indicateurs statistiques utilisés influence drastiquement l'interprétation finale.

## 📂 Jeu de données
* **Thème :** Les décès liés au terrorisme dans le monde.
* **Source :** Données fiables et vérifiées issues de *Our World in Data*.
* **Fichier brut :** `terrorism-deaths.csv` (à placer à la racine du projet ou dans un dossier `data/`).

## 🔍 Nos deux analyses contrastées
À partir du fichier unique téléchargé, nous avons séparé notre travail en deux axes opposés :

1.  **Analyse 1 : "Une menace mondiale en explosion"** (`analyse1.py`)
    * *Méthode :* Étude de l'évolution temporelle (2010-2017) sur la population mondiale globale.
    * *Indicateurs :* Nombres absolus et taux d'augmentation jusqu'au pic de 2014.
2.  **Analyse 2 : "Une crise hyper-localisée"** (`analyse2.py`)
    * *Méthode :* Étude de la répartition géographique sur la même période (2010-2017).
    * *Indicateurs :* Pourcentages de concentration comparant le Top 5 des pays les plus touchés au reste du monde (environ 190 pays).

## 🛠️ Installation et Exécution

**1. Prérequis**
Assurez-vous d'avoir Python installé sur votre machine. Le projet utilise les bibliothèques `pandas` pour le traitement des données et `matplotlib` pour les visualisations.

Pour installer les dépendances, exécutez la commande suivante :
"pip install pandas matplotlib"

## 👥 Auteurs
Fauroux Eliott - Développement de l'Analyse 1.
Hachim Sidi Dayane - Développement de l'Analyse 2.
Karim Rayane - Réalisation du support de l'oral.
