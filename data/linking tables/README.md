# 📂 `linking_tables/` — Tables de Liaison

Ce dossier contient plusieurs tables de liaison utilisées pour relier différentes variables dans le projet. Les fichiers présents ici facilitent les correspondances entre les communes, les zones d'emploi, les départements, et les familles professionnelles.

## Structure des Fichiers

### `Communes_to_ZE_2022.xlsx` :

Table de liaison utilisée pour associer les communes aux zones d'emploi.\
Source INSEE : [Base des zones d'emploi 2020 au 1ᵉʳ janvier 2022](https://www.insee.fr/fr/information/4652957).\
Télécharger : "Base des zones d'emploi 2020 au 1ᵉʳ janvier 2022" (zip, 1 Mo).

### `departements-francais.xlsx` :

Table de liaison permettant de convertir les codes des départements en noms de départements et en régions associées.\
Télécharger : [Liste des départements français - régions-et-départements.fr](https://www.regions-et-departements.fr/fichiers).

### `Rome-V3 vers Fap-2009.xls` :

Table de correspondance permettant la transition du code ROME vers les codes FAP.\
Source DARES : [Nomenclature des familles professionnelles 2009](https://dares.travail-emploi.gouv.fr/donnees/la-nomenclature-des-familles-professionnelles-2009).\
Télécharger : "Table de correspondance PCS-2003, Rome-V3 vers Fap-2009" (XLS, 298.5 Ko).

### `Rome_to_Fap_processed.csv` :

Fichier généré par le notebook "02_clean_rome_fap_mapping.ipynb". Ce fichier prend en entrée "Rome-V3 vers Fap-2009.xls" et le traite pour le rendre utilisable dans les étapes suivantes du projet.

### `name_communes_5000.csv` :

Fichier généré par le notebook "01_match_communes_with_shapefile.ipynb". Il contient les noms des communes de plus de 5000 habitants, qui peuvent être associées avec le shapefile pour la visualisation.

------------------------------------------------------------------------

# 📂 `linking_tables/` — Linking Tables

This folder contains several linking tables used to connect different variables in the project. The files here facilitate the matching of communes, employment zones, departments, and professional families.

## File Structure

### `Communes_to_ZE_2022.xlsx` :

Linking table used to match communes to employment zones.\
Source INSEE: [Base des zones d'emploi 2020 au 1ᵉʳ janvier 2022](https://www.insee.fr/fr/information/4652957).\
Download: "Base des zones d'emploi 2020 au 1ᵉʳ janvier 2022" (zip, 1 Mo).

### `departements-francais.xlsx` :

Linking table used to convert department codes into department names and associated regions.\
Download: [Liste des départements français - regions-et-departements.fr](https://www.regions-et-departements.fr/fichiers).

### `Rome-V3 vers Fap-2009.xls` :

Linking table that allows transitioning from ROME codes to FAP codes.\
Source DARES: [Nomenclature des familles professionnelles 2009](https://dares.travail-emploi.gouv.fr/donnees/la-nomenclature-des-familles-professionnelles-2009).\
Download: "Table de correspondance PCS-2003, Rome-V3 vers Fap-2009" (XLS, 298.5 Ko).

### `Rome_to_Fap_processed.csv` :

File generated through the notebook "02_clean_rome_fap_mapping.ipynb". It takes "Rome-V3 vers Fap-2009.xls" as input and processes it to be used in the following steps.

### `name_communes_5000.csv` :

File generated through the notebook "01_match_communes_with_shapefile.ipynb". It contains the names of communes with more than 5000 inhabitants that can be matched with the shapefile for visualization.
