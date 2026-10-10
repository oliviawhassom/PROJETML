# Analyse et prédiction sur données patients

Projet académique mené à l'EFREI : traiter un jeu de données médicales relatif au diabète, de la donnée brute jusqu'à l'évaluation des modèles.

## Déroulé

**1. Préparation.** Chargement, nettoyage, traitement des valeurs aberrantes.

**2. Analyse exploratoire.** Analyse descriptive et étude des corrélations entre variables.

**3. Apprentissage non supervisé.** Segmentation par KMeans et classification ascendante hiérarchique. Le nombre de groupes est choisi par trois méthodes croisées : la méthode du coude, l'indice de silhouette et l'indice de Davies-Bouldin.

**4. Apprentissage supervisé.** Régression linéaire simple puis multiple. Classification par KNN, avec optimisation du paramètre K.

**5. Évaluation.** Précision, rappel, exactitude et F1-score.

## Ce que ce projet m'a appris

Le choix du critère d'évaluation compte davantage que le choix du modèle.

Sur un dépistage médical, un cas manqué ne coûte pas la même chose qu'une fausse alerte : une fausse alerte sera levée par un examen complémentaire, alors qu'un malade non détecté ne sera pas soigné. C'est pourquoi on regarde le rappel en priorité, et non l'exactitude seule, qui peut rester élevée tout en manquant l'essentiel.

## Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

## Cadre

Projet de cours, majeure Big Data et Intelligence Artificielle, EFREI Paris.
