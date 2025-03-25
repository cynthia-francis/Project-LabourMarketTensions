# 📂 `scr/` — Scripts pour le traitement de la tension sur le marché du travail

Ce dossier contient les principaux notebooks Jupyter utilisés pour traiter et préparer les données en vue d'analyser et de visualiser la tension sur le marché du travail au niveau des communes en France. Le flux de travail implique le nettoyage, la normalisation et la fusion de plusieurs ensembles de données, notamment les fichiers STMT (demande) et JOCAS (offre), avant de calculer les indicateurs de tension.

## 🧭 Ordre d'exécution

Les scripts doivent être exécutés dans l'ordre suivant :

### 1. `01_match_communes_with_shapefile.ipynb`

**Objectif :**\
Extrait les noms des communes d'un fichier Excel STMT d'échantillon et les associe au shapefile correspondant pour les visualisations spatiales ultérieures. Cela inclut la normalisation des noms pour garantir une correspondance cohérente.

### 2. `02_clean_rome_fap_mapping.ipynb`

**Objectif :**\
Nettoie et formate la table de correspondance ROME-FAP. Cette correspondance est nécessaire plus tard pour harmoniser les catégories professionnelles entre les ensembles de données.

### 3. `03_process_stmt_demand.ipynb`

**Objectif :**\
Traite tous les fichiers STMT (demande de main-d'œuvre) et les consolide dans un jeu de données propre, prêt pour l'analyse.

### 4. `04_process_jocas_supply.ipynb`

**Objectif :**\
Traite tous les fichiers JOCAS (offre de main-d'œuvre) dans un ensemble de données unifié et formaté.

### 5. `05_compute_labour_tightness_ratio.ipynb`

**Objectif :**\
Fusionne les ensembles de données STMT et JOCAS nettoyés, les agrége à l'échelle des zones d'emploi et calcule le ratio de tension sur le marché du travail / score pour chaque zone d'emploi et chaque catégorie professionnelle. Ce résultat sera utilisé pour la visualisation et l'analyse ultérieure.

## 📝 Notebook supplémentaire

### `00_explore_jocas_missing_values.ipynb`

**Objectif :**\
Une exploration initiale des valeurs manquantes dans les fichiers JOCAS. Non nécessaire pour le flux de travail principal, mais fournit des informations utiles sur la qualité des données et la sélection des variables.

------------------------------------------------------------------------

# 📂 `scr/` — Scripts for Labour Market Tightness Processing

This folder contains the core Jupyter notebooks used to process and prepare data for analyzing and visualizing labour market tightness at the commune level in France. The workflow involves cleaning, standardizing, and merging multiple datasets, including STMT (demand side) and JOCAS (supply side) files, before computing tightness indicators.

## 🧭 Execution Order

The scripts are meant to be run in the following order:

### 1. `01_match_communes_with_shapefile.ipynb`

**Purpose:**\
Extracts commune names from a sample STMT Excel file and matches them to the corresponding shapefile for later spatial visualizations. This includes name standardization to ensure consistent matching.

### 2. `02_clean_rome_fap_mapping.ipynb`

**Purpose:**\
Cleans and formats the ROME–FAP mapping linking table. This mapping is needed later to harmonize job categories across datasets.

### 3. `03_process_stmt_demand.ipynb`

**Purpose:**\
Processes all STMT (labour demand) files and consolidates them into a clean, analysis-ready dataset.

### 4. `04_process_jocas_supply.ipynb`

**Purpose:**\
Processes all JOCAS (labour supply) files into a unified and formatted dataset.

### 5. `05_compute_labour_tightness_ratio.ipynb`

**Purpose:**\
Merges the cleaned STMT and JOCAS datasets, aggregate them at the zone d'emploi level and computes the labour market tightness ratio/score for each zone d'emploi and job category. This output will be used for visualization and further analysis.

## 📝 Additional Notebook

### `00_explore_jocas_missing_values.ipynb`

**Purpose:**\
An initial exploration of missing data in the JOCAS files. Not required for the main workflow but provides useful insights into data quality and variable selection.
