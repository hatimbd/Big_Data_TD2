## TD Big Data — Analyse de Popularité avec Tri
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Ce Td consiste à manipuler un jeu de données issu de Wikipédia francophone, et à analyser les performances de différents algorithmes de tri (tri à bulle, tri fusion) sur des fichiers de tailles croissantes.  
L’objectif est de déterminer empiriquement les capacités maximales d’un système de calcul.

#### 📥 Téléchargement du jeu de données

Téléchargez le fichier original `wikirank-fr-v2.tsv.zip` à partir du lien suivant :

👉 [https://kirgizov.link/teaching/polytech-dijon/bigdata/dataset/wikirank-fr-v2.tsv.zip](https://kirgizov.link/teaching/polytech-dijon/bigdata/dataset/wikirank-fr-v2.tsv.zip)

Décompressez l’archive pour obtenir le fichier `wikirank-fr-v2.tsv`.

#### Objectifs du TD

- Nettoyer les données (colonne `popularity`)
- Générer des sous-ensembles de tailles différentes
- Implémenter et comparer des algorithmes de tri
- Mesurer les temps d’exécution
- Visualiser les performances avec Matplotlib

#### 📁 Organisation

Les fichiers générés doivent être placés dans un dossier `datasets/`, et nommés selon le format :
wikirank_subset_<taille>.tsv


Exemples : `wikirank_subset_100.tsv`, `wikirank_subset_10000.tsv`, etc.

#### 📦 Dépendances

- Python ≥ 3.8
- `matplotlib`
- `pandas`
- `csv`
- `numpy`
- `os`
- `time`

---

Bon TD ! 💻📈


