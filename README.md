# TP - Segmentation Client par Algorithme K-Means

Description
Ce projet réalise une segmentation de clients d'un centre commercial utilisant l'algorithme K-Means. L'objectif est d'identifier des groupes de clients ayant des comportements similaires basés sur leurs caractéristiques socio-économiques.


Objectifs
- Appliquer l'algorithme K-Means pour du clustering non supervisé
- Identifier le nombre optimal de clusters
- Analyser et interpréter les segments clients
- Proposer des recommandations marketing


Données
Dataset : Mall_Customers.csv  
Source : Kaggle  
Nombre de clients :200  

Variables :
- CustomerID, Gender, Age
- Annual Income (k$)
- Spending Score (1-100)

Technologies Utilisées
- Python 3
- Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler, silhouette_score)
- Matplotlib, Seaborn
- Google Colab

Méthodologie
1. Préparation des données : Nettoyage et standardisation
2. Analyse exploratoire : Visualisations et corrélations
3. Détermination de k : Méthode du coude et score de silhouette
4. Clustering K-Means : Application avec k=5
5. Interprétation : Profilage des segments et recommandations

