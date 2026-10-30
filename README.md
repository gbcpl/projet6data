# Projet 6 — Optimiser la gestion des données d'une boutique avec Python

## Présentation du projet

Ce projet consiste à analyser les données d'une boutique de vins en ligne afin de fiabiliser les informations commerciales et d'étudier les performances des ventes et des stocks.

À partir de trois sources de données (ERP, site web et table de correspondance), j'ai réalisé des traitements sous Python pour consolider les données, détecter les anomalies et calculer plusieurs indicateurs commerciaux.

## Objectifs

- Nettoyer et contrôler la qualité des données.
- Consolider plusieurs sources grâce aux jointures.
- Détecter les valeurs atypiques dans les prix.
- Analyser le chiffre d'affaires et les quantités vendues.
- Étudier la valorisation des stocks et les taux de marge.
- Formuler des recommandations pour améliorer la fiabilité des données.

## Méthodologie

1. **Exploration :** analyse de la structure des fichiers, des types de variables, des valeurs manquantes et des doublons.
2. **Nettoyage :** identification des incohérences concernant les prix, les stocks et les références produits.
3. **Consolidation :** rapprochement des données ERP et web à l'aide de jointures Pandas.
4. **Analyse commerciale :** calcul du chiffre d'affaires, des quantités vendues, de la valorisation des stocks et des taux de marge.
5. **Analyse statistique :** détection des valeurs atypiques par score Z et méthode de l'intervalle interquartile (IQR), puis étude des corrélations.
6. **Restitution :** visualisation des résultats et export des données consolidées.

## Résultats clés

- **143 680,10 € de chiffre d'affaires** calculé à partir des données analysées.
- **298 555,76 € de valorisation des stocks** estimée à partir des quantités en stock et des prix d'achat.
- **39 articles atypiques** identifiés selon le critère statistique retenu, soit environ 4,73 % des 825 entrées initiales de l'ERP.
- Identification d'anomalies : prix négatifs, stocks incohérents, doublons et références sans correspondance.
- Mise en évidence de l'influence des anomalies sur la fiabilité des indicateurs financiers.

## Outils et technologies

- **Python** : langage d'analyse.
- **Jupyter Notebook** : environnement de travail.
- **Pandas et NumPy** : préparation, nettoyage et consolidation des données.
- **Matplotlib, Seaborn et Plotly Express** : visualisation et analyse exploratoire.
- **Excel** : export et consultation des données consolidées.

## Livrables

- [Notebook Jupyter — Analyse des données](./Capell_Gabriel_1_notebook_032026.ipynb)
- [Présentation PowerPoint — Synthèse du projet](./Capell_Gabriel_2_presentation_032026.pptx)

## Compétences développées

Python - Pandas - Nettoyage des données - Jointures SQL-like avec Pandas - Statistiques descriptives - Détection des valeurs atypiques - Analyse commerciale - Datavisualisation - Qualité des données.

## Conclusion

Ce projet m'a permis de mettre en pratique une démarche complète d'analyse de données, de la préparation de sources hétérogènes à la production d'indicateurs commerciaux.

Il souligne l'importance de la qualité des données pour fiabiliser les analyses et éclairer les décisions relatives aux ventes, aux stocks et aux marges.

---

**Domaine** : e-commerce et gestion commerciale

**Langage** : Python

**Environnement** : Jupyter Notebook

**Outils principaux** : Pandas, NumPy, Plotly Express, Seaborn

**Type de projet** : formation Data Analyst

**Dépôt GitHub :** [gbcpl/projet6data](https://github.com/gbcpl/projet6data)
