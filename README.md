# Gestion des Ressources Humaines au Sénégal

Ce projet propose un ensemble complet d'outils et d'analyses pour aider les entreprises au Sénégal à gérer efficacement leurs ressources humaines. Il comprend la génération d'un jeu de données fictif représentatif des RH, le traitement et l'analyse de ces données, ainsi que des recommandations pour améliorer la gestion des ressources humaines.

## Objectifs du Projet

- **Génération d'un jeu de données réaliste :** Créer un jeu de données fictif mais représentatif des employés dans les entreprises sénégalaises, en tenant compte des spécificités du contexte local.
- **Traitement et analyse des données :** Exploiter les données générées pour fournir des analyses approfondies sur divers aspects des ressources humaines, comme la démographie, les salaires, et la performance.
- **Proposer des solutions :** Élaborer des recommandations concrètes pour aider les entreprises à améliorer leur gestion des ressources humaines au Sénégal.

## Principales Fonctionnalités

### Générateur de Données RH Sénégalaises

- Génère un jeu de données fictif de **8 950 employés**.
- Inclut des informations détaillées telles que l'identification des employés, leurs postes, salaires, évaluations de performance, etc.
- Utilise des données spécifiques au contexte sénégalais (noms, régions, départements, etc.), grâce à la bibliothèque Faker avec la locale `fr_SN`.

### Traitement et Analyse des Données

- **Analyse des données démographiques :** Étude des distributions par genre, âge, et niveau d'éducation.
- **Étude des tendances salariales :** Analyse des salaires moyens, et des écarts liés au genre et à l'éducation.
- **Évaluation de la performance :** Analyse des évaluations de performance et de leur corrélation avec d'autres facteurs.
- **Visualisation des données :** Création de tableaux de bord interactifs pour une meilleure compréhension des résultats.

### Solutions pour la Gestion des RH au Sénégal

- **Recommandations pour attirer et retenir les talents :** Stratégies pour améliorer le recrutement et la rétention des employés.
- **Développement des compétences :** Propositions pour renforcer les programmes de formation et de développement des compétences.
- **Amélioration des processus RH :** Suggestions pour optimiser le recrutement, la gestion des performances, et d'autres processus RH.
- **Rémunération équitable :** Bonnes pratiques pour assurer une rémunération compétitive et équitable au sein des entreprises.

## Utilisation du Projet

Ce projet est conçu pour être utile à divers acteurs :

- **Entreprises au Sénégal :** Améliorer la gestion des ressources humaines grâce aux analyses et solutions proposées.
- **Cabinets de conseil RH :** Utiliser le jeu de données et les analyses pour concevoir des recommandations adaptées au marché sénégalais.
- **Institutions académiques :** Exploiter le projet pour la formation, la recherche, et l'enseignement en ressources humaines et analyse de données.
- **Organismes gouvernementaux :** Informer les politiques publiques sur la gestion des ressources humaines au Sénégal.

## Prérequis

- Python 3.x
- Bibliothèques Python : `pandas`, `numpy`, `faker`, `datetime`, `matplotlib`, `seaborn`, etc.

## Exécution du Projet

1. Clonez ou téléchargez le dépôt du projet.
2. Installez les bibliothèques Python requises :
   ```bash
   pip install pandas numpy faker matplotlib seaborn
   ```
3. Exécutez le script principal pour générer le jeu de données et lancer l'analyse :
   ```bash
   python generateur_rh_senegal.py
   ```
4. Explorez les résultats, les visualisations, et les solutions proposées dans les fichiers de sortie.

Le fichier `RessourcesHumaines.csv` sera généré dans le même répertoire que le script, prêt à être utilisé pour des analyses plus poussées.
