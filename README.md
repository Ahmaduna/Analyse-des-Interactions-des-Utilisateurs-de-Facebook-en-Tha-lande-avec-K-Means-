# Analyse des Données des Publications Facebook

## Description du Projet

Ce projet analyse les données des publications sur Facebook collectées en Thaïlande. Les données incluent divers types de publications (photo, vidéo, etc.) ainsi que plusieurs métriques associées, telles que les réactions, les commentaires, et les partages. L'objectif est d'effectuer une analyse exploratoire des données, de réaliser une analyse en composantes principales (ACP) et de déterminer des groupes à l'aide de KMeans.

## Contenu du Répertoire

- `Live.csv` : Fichier CSV contenant les données des publications Facebook.
- 01_Kmeans_Python.py` : Script Python pour l'analyse des données, y compris la visualisation, l'ACP et le clustering.

## Prérequis

Avant de lancer le script, assurez-vous d'avoir installé les packages suivants :

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

Vous pouvez les installer en utilisant `pip` :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Utilisation

1. **Charger les Données**

   Chargez les données depuis le fichier `Live.csv` et effectuez le prétraitement nécessaire.

2. **Analyse Univariée**

   Visualisez les distributions des variables pour comprendre leur répartition.

3. **Analyse Bivariée**

   Examinez les relations entre les variables et entre les variables numériques et le type de publication.

4. **Analyse en Composantes Principales (ACP)**

   Normalisez les données, effectuez l'ACP et visualisez les résultats, y compris le cercle de corrélation et le plan factoriel.

5. **Clustering avec KMeans**

   Déterminez le nombre optimal de clusters en utilisant la méthode du coude et le score de silhouette. Appliquez KMeans pour identifier les groupes dans les données.

6. **Interprétation des Groupes**

   Analysez les statistiques des clusters et visualisez les distributions des variables pour chaque groupe.

## Exécution du Script

Pour exécuter le script Python, utilisez la commande suivante :

```bash
python nom_fichier.py
```

Assurez-vous que le fichier `Live.csv` est dans le même répertoire que le script ou modifiez le chemin dans le script en conséquence.

