# openfoodfacts-data-cleaning
Projet de nettoyage, exploration et visualisation d’un large jeu de données Open Food Facts pour préparer un système de suggestion automatique de valeurs manquantes, avec respect des principes RGPD.

# Open Food Facts - Nettoyage et Exploration des Données

Ce projet vise à améliorer la qualité de la base de données Open Food Facts en préparant les données pour un futur système de suggestion automatique des valeurs manquantes lors de l’ajout de nouveaux produits. J’ai réalisé un nettoyage complet, une exploration approfondie, ainsi que des visualisations claires destinées à un public non-expert. Ce travail respecte également les principes du RGPD.

## Fonctionnalités

- Chargement et formatage de plus de 300 000 produits
- Suppression des doublons et traitement des valeurs aberrantes
- Sélection des variables pertinentes selon leur taux de remplissage et corrélations métier
- Imputation des données manquantes par moyennes, médianes et règles métier
- Analyse univariée, bivariée et multivariée (ACP)
- Visualisation claire avec Matplotlib et Seaborn
- Présentation des mesures de conformité RGPD

## Technologies utilisées

- Python (pandas, NumPy, Matplotlib, Seaborn)

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/tonPseudo/openfoodfacts-data-cleaning.git
2. Installer les dépendances Python (via requirements.txt si disponible) :

bash
pip install -r requirements.txt
Lancer les notebooks ou scripts Python pour reproduire l’analyse.

## Usage
Utiliser les notebooks pour explorer et nettoyer les données Open Food Facts, générer des visualisations et préparer un dataset prêt pour un système de suggestion automatique.
