## Etude et Prédiction de la gravité d'un accident de la circulation

Bienvenue sur le Github présentant notre projet Python.

L'objectif de notre projet est d'étudier les caractéristiques propres à un accident de la route afin de connaître les facteurs de gravité, pour enfin pouvoir élaborer un modèle de prédiction de la gravité d'un accident. 

A partir de 4 bases de données répertoriant les caractéristiques (véhicules, lieux, usagers, caractéristiques générales) des accidents de la route ayant eu lieu en 2019, nous avons crée une variable gravité et conduit des statistiques descriptives nous permettant d'extraire les variables explicatives les plus significatives pouvant prédire la gravité de l'accident. Nous avons ensuite testé et comparé plusieurs modèles de classification et prédiction, et sélectionné celui le plus performant et adapté à nos données. Enfin, une partie Visualisation nous a permis d'étudier visuellement les caractéristiques et inégalités géographiques des accidents de la circulation en France.

Le notebook "main" est une synthèse des différents notebooks et des principaux résultats de notre projet.

### Récapitulatif des notebooks présents

* **main**: synthèse des principaux résultats des autres notebooks
* **Ouverture_données**: nettoyage, préparation et appropriation des données (étude des valeurs manquantes, étude des modalités rares, ajout de variables dont une variable gravité, création d'une base de données globale)
* **Statistiques_descriptives**: conduite des statistiques descriptives et notamment étude des différentes variables explicatives réparties en 5 catégories (Météo, Usagers, Style de Conduite, Route et Caractéristiques Propres à l'Accident) en fonction de la variable gravité
* **Heat-Maps France**: tracé des cartes de températures permettant de localiser les accidents graves et moins graves en France
* **Modélisation**: tests et comparaison de différents modèles de classification et prédiction, et détermination du modèle le plus performant


Nous vous en souhaitons une bonne découverte,

Clotilde, Camille et Pauline
