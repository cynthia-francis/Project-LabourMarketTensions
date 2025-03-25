![](Pictures/app.png)

# 📂 `app/` — Application Dash pour la Tension sur le Marché du Travail

Ce dossier contient l'application Dash interactive permettant de visualiser la tension sur le marché du travail en France. L'outil propose une carte interactive et des graphiques pour explorer les indicateurs de tension selon différents critères :

1.  **Choisir le détail des catégories professionnelles** : Choisissez entre "FAP 22" (secteurs pro. généraux) ou "FAP 87" (métiers spécifiques).
2.  **Choisir le type de demandeur d'emploi à inclure** : Sélectionnez entre "Catégorie A" (chômage complet) ou "Catégories A, B et C" (inclut chômage partiel ou formation).
3.  **Choisir une catégorie d’emplois ou de professions** : Sélectionnez une famille professionnelle spécifique selon votre choix de catégorie.
4.  **Zoomer sur une région** : Possibilité de zoomer sur une département pour visualiser les données spécifiques à cette zone.

La carte affichera la tension sur le marché du travail en fonction des filtres choisis. Un graphique supplémentaire montrera l'évolution de la tension mensuelle pour la zone d'emploi sélectionnée ainsi que les données utilisés pour l'analyse sur cette zone (téléchargeable). Le graph et les données sont mises à jour en temps réel en fonction des interactions avec la carte.

## Installation

Assurez-vous que les fichiers nécessaires sont dans le dossier "data/" pour faire fonctionner l'application. Pour recréer cette dernière, il suffit d'exécuter le notebook `labour_tightness_dashboard.ipynb`.

------------------------------------------------------------------------

# 📂 `app/` — Dash Application for Labour Market Tightness

This folder contains the interactive Dash application for visualizing labour market tightness in France. The tool provides an interactive map and charts to explore tightness indicators based on different criteria:

1.  **Select Job Category Details**: Choose between "FAP 22" (general professional sectors) or "FAP 87" (specific professions).
2.  **Select Jobseeker Type to Include**: Choose between "Category A" (fully unemployed) or "Categories A, B, and C" (includes part-time unemployment or training).
3.  **Choose a Job or Profession Category**: Select a specific professional family based on your job category choice.
4.  **Zoom into a Region**: Zoom into a department to view data specific to that region.

The map will display labour market tightness based on the selected filters. An additional graph will show the monthly evolution of tightness for the selected zone d'emploi, as well as the data used for the analysis in that zone (downloadable). The figure and data are updated in real-time based on interactions with the map.

## Installation

Ensure that the necessary files are in the "data/" folder to run the application. To recreate the latest simply run the notebook `labour_tightness_dashboard.ipynb`.
