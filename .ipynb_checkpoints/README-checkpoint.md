
# Titanic Survival Prediction

## Description
Ce projet utilise **Pandas** pour manipuler les données et **Seaborn** pour visualiser les résultats afin de prédire si un passager aurait survécu au naufrage du Titanic. Les données proviennent du registre réel du Titanic, disponible sur [Kaggle](https://www.kaggle.com/c/titanic). Le travail a été réalisé en suivant une vidéo d'entraînement proposée par la chaîne YouTube **Machine Learnia**.

Ce projet a été conçu pour pratiquer et approfondir mes compétences en manipulation de données et en visualisation dans le cadre de l'apprentissage du machine learning.

---

## Objectifs
1. **Explorer et analyser les données du Titanic** pour identifier les relations entre les caractéristiques des passagers (âge, sexe, classe, etc.) et leurs chances de survie.
2. **Visualiser les données** pour mieux comprendre les tendances grâce à Seaborn.
3. **Utiliser des algorithmes de machine learning supervisé** pour prédire la survie des passagers.

---

## Fichiers inclus
- `titanic.ipynb` : Notebook Jupyter contenant l'intégralité du code, des analyses, et des visualisations.
- `README.md` : Ce fichier, expliquant le projet.

---

## Étapes réalisées

### 1. Chargement des données
- Les données sont importées dans un DataFrame à l'aide de **Pandas**.
- Nettoyage des données :
  - Gestion des valeurs manquantes dans les colonnes comme `Age` et `Embarked`.
  - Encodage des variables catégoriques (`Sex`, `Embarked`) en valeurs numériques.

### 2. Exploration et analyse des données
- **Analyse des distributions** :
  - Visualisation de la répartition des passagers par sexe, classe sociale, et âge.
  - Identification des groupes ayant une meilleure probabilité de survie.
- **Visualisations principales avec Seaborn** :
  - Diagrammes en barres, en boîtes (boxplots), et heatmaps pour illustrer les relations entre les variables.

### 3. Modélisation
- Implémentation d’un modèle de machine learning supervisé pour prédire la survie :
  - Utilisation d'un algorithme comme la **régression logistique** (ou un autre modèle supervisé basique).
  - Évaluation des performances avec des métriques comme l’accuracy.

---

## Exemples de visualisations
Voici quelques exemples de graphiques générés avec **Seaborn** :
- **Survie selon le sexe** :
  - Les femmes avaient significativement plus de chances de survie que les hommes.
- **Survie selon la classe sociale** :
  - Les passagers de première classe avaient une probabilité de survie plus élevée que ceux des classes inférieures.
- **Répartition des âges** :
  - Les enfants (âgés de moins de 16 ans) avaient également une meilleure probabilité de survie.

---

## Résultats
- Le modèle atteint une précision d'environ **80%** (variable selon les paramètres choisis et les données d'entraînement).
- Les caractéristiques les plus influentes sur la survie sont :
  - Le sexe (`Sex`)
  - La classe (`Pclass`)
  - L'âge (`Age`)

---

## Prérequis
Pour exécuter ce projet, vous aurez besoin des bibliothèques suivantes :
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn (si machine learning utilisé)

Installez-les avec :
```bash
pip install pandas seaborn matplotlib scikit-learn

---

## Comment exécuter
Clonez ce dépôt sur votre machine locale :
```bash
git clone https://github.com/mimiecmoua/titanic-ml-supervised.git

## Accéder au répertoire
cd titanic-ml-supervised

## Lancez le notebook titanic.ipynb avec JupyterLab :
jupyter lab

---

### Crédit 
Ce projet a été réalisé grâce à une vidéo d'entraînement de la chaîne YouTube Machine Learnia.

## Auteur 
Emilie Clain 
Passionnée de machine learning et de data science.
www.linkedin.com/in/emilieclain
