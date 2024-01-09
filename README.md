# PandasvsPolars
## Cas pratique de comparatif de performance entre Pandas et Polars

L’objectif de ce TP est de manipuler et visualiser un jeu de donnés très volumineux, ce qui nous permettra de mettre en place les notions apprises pendant le cours et de comparer la performance de Pandas vs. Polars.

Pour ce cas pratique, nous allons utiliser un une de données appelé « E-commerce Customer Behavior ». Ces données fournissent une vue complète du comportement des clients au sein d'une plateforme de commerce électronique. Chaque entrée de l'ensemble de données correspond à un client unique, offrant une répartition détaillée de ses interactions et transactions.

Les données devraient être téléchargées à partir du lien suivant :

https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store/download

Toutes les activités énoncées à continuation devront être faites sur Polar et Pandas, avec l’affichage du temps de traitement pour chaque étape afin de pouvoir comparer les différences de performance. Finalement, il sera nécessaire de préparer un graphique de comparaison entre les performances obtenues avec Pandas et Polars.

<b>Tâches à accomplir avec Pandas et Polars :</b>
1.	Lecture des deux jeux de données et concaténation dans un seul dataset.
2.	Affichage d'informations basiques du jeu de données : quantité de lignes, colonnes, types des données, etc.
3.	Affichage de la quantité de produits, marques et utilisateurs dans le dataset, sans répétitions (valeurs uniques).
4.	Affichage du top 5 de marques et catégories qui ont le prix moyen le plus élevé.
5.	Calcul du min, du max et de la moyenne de prix par marque et par catégorie.
6.	Affichage des 5 prix les plus élevés.
7.	Affichage de la quantité d’articles par marque et par catégorie, en utilisant une fonction d’agrégation.
8.	Affichage de la quantité d’événements par type, en utilisant une fonction d’agrégation.
9.	Création et affichage d'un tableau contenant la quantité d’événements de chaque type par marque.
10.	Création et affichage d'un tableau contenant la quantité d’événements de chaque type par marque et utilisateur.
11.	Affichage du pourcentage de données vides ou nulles (valeurs manquants) par colonne.
12.	Suppression de lignes vides sur l’ensemble de colonnes où le total de valeurs manquants ne dépasse pas un 15%.

<b>Tâches comparatives :</b>
1.	Calcul et affichage du temps totaux d’opération sur chaque librairie
2.	Affichage des graphiques pertinents qui montrent la différence de performance (type et quantité de graphiques au choix)

