# Analyse-ventes-Superstore
J'ai réalisé ce projet pour mettre en pratique mes connaissances de ma formation en Data analyst.

L'objectif est d'analyser les ventes d'une entreprise à partir du jeu de données Superstore en utilisant :

- Python (Pandas) pour le nettoyage et la préparation des données.
- Power BI pour la modélisation, la création des mesures DAX et la réalisation de tableaux de bord interactifs.

Ce projet met en pratique l'ensemble du processus d'analyse de données, depuis le traitement des données brutes jusqu'à la restitution des résultats sous forme de dashboards.

Technologies utilisées
- Python
- Pandas
- Power BI
- DAX

Le projet repose sur le dataset Superstore Sales, contenant notamment :

- les commandes
- les clients
- les produits
- les catégories
- les régions
- les ventes
- les dates de commande
- les modes de livraison

Nettoyage des données

Le nettoyage des données a été réalisé sous Python avec Pandas.

Les principales étapes ont été :

- import du fichier CSV ;
- suppression des colonnes inutiles ;
- conversion des types de données ;
- conversion des dates au format datetime ;
- correction des valeurs manquantes ;
- correction du code postal manquant de Burlington (Vermont) ;
- correction des erreurs présentes dans la colonne Sales (valeurs « 16GB ») ;
- récupération des montants stockés dans une colonne supplémentaire ;
- contrôle des doublons ;
- export des données nettoyées vers un nouveau fichier CSV destiné à Power BI.


Tableaux de bord réalisés
1. Tableau de bord KPI

Ce tableau de bord présente une vue d'ensemble des performances commerciales :

- Chiffre d'affaires total
- Nombre de commandes
- Panier moyen
- Évolution mensuelle des ventes
- Évolution annuelle des ventes
- Répartition des ventes par catégorie
- Top clients

<img width="640" height="358" alt="image" src="https://github.com/user-attachments/assets/b85ace48-8305-44e6-adbb-975b8823abde" />


2. Analyse géographique

Cette page permet d'analyser les ventes selon leur localisation.

Elle comprend :

- une carte des ventes par État ;
- le Top 10 des États générant le plus de chiffre d'affaires ;
- des filtres par année et par région.

<img width="657" height="368" alt="image" src="https://github.com/user-attachments/assets/215cf239-a064-4fbe-8f6f-ffbe7c7db403" />


3. Analyse logistique

Cette page est dédiée aux performances de livraison.

Les indicateurs présentés sont :

- délai moyen ;
- délai minimum ;
- délai maximum ;
- délai médian ;
- délai moyen par mode de livraison ;
- délai moyen par région ;
- évolution annuelle du délai de livraison.

<img width="663" height="374" alt="image" src="https://github.com/user-attachments/assets/21b676f6-6c76-4786-bafa-e8065ad9eae5" />

Principaux enseignements

L'analyse met notamment en évidence que :

- la Californie est l'État générant le plus de chiffre d'affaires ;
- les ventes progressent entre 2016 et 2018 ;
- les ventes sont relativement équilibrées entre les trois catégories de produits ;
- le délai moyen de livraison est d'environ 4 jours ;
- le mode Standard Class présente le délai de livraison le plus long.




