
# Construction Project Analysis

## Description

Construction Project Analysis est un projet d'analyse de données portant sur des projets de construction.

L'objectif est d'explorer, nettoyer et analyser les données afin d'identifier des tendances, des problèmes de qualité et des informations utiles à la prise de décision dans la gestion de projets de construction.

## Dataset

Le projet utilise un jeu de données contenant des informations relatives aux projets et aux formulaires de suivi de projets de construction.

Le fichier de données brutes est conservé dans :

```text
data/raw/
```

Les données brutes ne doivent pas être modifiées directement.

Les données nettoyées seront stockées dans :

```text
data/cleaned/
```

## Structure du projet

```text
Construction-Project-Analysis/
│
├── data/
│   ├── raw/
│   │   └── Construction_Data_PM_Forms_All_Projects.csv.zip
│   │
│   └── cleaned/
│
├── docs/
│   ├── data_dictionary.md
│   └── cleaning_log.md
│
├── .gitignore
└── README.md
```

## Colonnes principales

Le dataset contient notamment les colonnes suivantes :

1. REF
2. STATUS
3. LOCATION
4. NAME
5. CREATED
6. TYPE
7. STATUS CHANGE
8. OPEN ACTIONS
9. TOTAL ACTIONS
10. ASSOCIATION
11. OVERDUE
12. IMAGES
13. COMMENTS
14. DOCUMENTS
15. PROJECT
16. REPORT FORMS ST
17. REFORMS FORM GROUP

La signification et les caractéristiques de chaque colonne seront documentées progressivement dans :

```text
docs/data_dictionary.md
```

## Méthodologie

L'analyse suivra progressivement les principales étapes d'un projet d'analyse de données :

1. Compréhension du problème
2. Exploration des données
3. Contrôle de la qualité des données
4. Nettoyage des données
5. Analyse exploratoire
6. Visualisation
7. Identification des tendances et problèmes
8. Interprétation des résultats
9. Formulation de recommandations

## Outils

Les outils utilisés ou prévus pour le projet sont notamment :

* Google Sheets
* SQL
* PostgreSQL
* Python
* Pandas
* Power BI
* Git
* GitHub

## Documentation

La documentation du projet se trouve dans le dossier `docs/`.

### Data Dictionary

`data_dictionary.md` décrit les colonnes du dataset, leurs types, leur signification, leurs valeurs possibles et les règles particulières identifiées.

### Cleaning Log

`cleaning_log.md` conserve l'historique des problèmes de qualité des données, des décisions prises et des opérations de nettoyage effectuées.

## Statut du projet

Projet en cours de développement.

L'exploration et le nettoyage des données seront réalisés progressivement, puis l'analyse sera approfondie à l'aide de SQL, Python et Power BI.
