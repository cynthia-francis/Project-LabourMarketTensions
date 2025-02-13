# Projet Tensions sur le Marché du Travail - Unédic

Ce projet vise à développer une carte interactive au niveau communal affichant des indicateurs sur les offres d’emploi, les demandeurs d’emploi (en flux comme en stock) et les tensions sur le marché du travail. La carte permettra d’identifier des catégories de territoires en fonction de l’intensité et de la nature des tensions, facilitant l’analyse statistique et éclairant les décisions en matière de politiques publiques.

## **Contexte du projet**

Le projet résulte d’une collaboration entre le MSc&T « Data and Economics for Public Policy » (École Polytechnique, ENSAE & Télécom Paris) et l'Unédic ( association chargée par délégation de service public de la gestion de l'assurance chômage en France). Il a été développé dans le cadre d’un défi proposé aux étudiants, visant la création d’un outil d’observation et d’analyse des dynamiques du marché du travail à une échelle territoriale fine.

## **La Carte Interactive**

L’outil permet de visualiser des indicateurs clés du marché du travail, notamment : - Offres d’emploi - Demandeurs d’emploi (tant en flux qu’en stock) - Tensions sur le marché du travail

L’objectif est de proposer une analyse au niveau communal pour catégoriser les territoires selon l’ampleur et la nature des tensions sur l’emploi. Ces catégories peuvent ainsi guider des politiques ciblées et des stratégies d’intervention sur le marché du travail.

### **Sources de données**

Le projet s’appuie sur des données administratives et des données en libre accès : - **Jocas 2020 (Dares)** : Disponible via l’ADISP ou en lien direct avec la Dares pour des millésimes plus récents. - **France Travail Open Data** : Données trimestrielles diffusées sur les demandeurs d’emploi au niveau communal pour les communes de plus de 5 000 habitants, avec des ventilations par métier, qualification, diplôme, sexe et âge. Pour les plus petites communes, on recourt également à des données agrégées au niveau départemental. - **Autres sources complémentaires** : peuvent être intégrées pour enrichir l’analyse.

### **Applications Potentielles**

-   **Analyse exploratoire des déséquilibres du marché du travail** à différentes échelles géographiques.
-   **Identification de clusters de territoires** selon l’offre et la demande d’emploi.
-   **Recommandations de politiques publiques** pour remédier aux inadéquations entre les offres et les demandeurs d’emploi.

## **Exécution de l’Application**

L’outil est accessible en exécutant le script localisé dans `./app`. Tous les fichiers nécessaires se trouvent dans le dossier `./data`.

Pour les utilisateurs souhaitant reproduire le projet depuis le début, les scripts nécessaires sont fournis dans le répertoire `./src`, avec des consignes détaillées dans les fichiers README. Certains ensembles de données de grande taille doivent être téléchargés manuellement.

## **Structure des Fichiers**

```         
├── README.md <- Documentation principale du projet.
├── LICENSE <- Licence du projet.
├── app <- Scripts pour exécuter l’outil de cartographie interactive.
├── data
│   ├── 1- 
│   ├── 2- 
│   ├── 3- 
├── src <- Code source pour le traitement et l’analyse des données.
│   ├── 
│   ├── 
│   └── 
├── docs
├── reports
```

## **Contributions & Contact**

Pour toute suggestion ou pour signaler des erreurs, vous pouvez contacter :

-   Alfonso Awadalla-Carreño : [alfonso.awadalla-carreno\@polytechnique.edu](mailto:alfonso.awadalla-carreno@polytechnique.edu){.email}
-   Anahi Reyes-Miguel : [anahi.reyes-miguel@polytechnique.edu](mailto:anahi.reyes-miguel@polytechnique.edu){.email}
-   Cynthia Francis : [cynthia.francis@polytechnique.edu](mailto:cynthia.francis@polytechnique.edu){.email}


Les contributions et collaborations visant à améliorer l’outil sont les bienvenues.

## **Remerciements**

Nous remercions nos encadrants académiques et notre partenaire externe pour leurs conseils et leur soutien au cours du développement de ce projet. Nous remercions tout particulièrement le programme MSc&T « Data and Economics for Public Policy » pour l’organisation de ce défi et pour l’expérience pratique en matière de politiques publiques qu’il offre.

------------------------------------------------------------------------

# Labour Market Tensions Project - Unédic

This project aims to develop an interactive map at the municipal level displaying indicators on job offers, job seekers, and labor market tensions. The map will help identify categories of territories based on the level and nature of tensions, facilitating statistical analysis and informing public policy decisions.

## **Project Context**

This project is the result of a collaboration between the MSc&T "Data and Economics for Public Policy" (École Polytechnique, ENSAE & Télécom Paris) and an and Unédic (the association responsible for managing unemployment insurance in France). It was developed as part of a challenge proposed to students to build a tool for observing and analyzing labor market dynamics at a fine territorial scale.

## **The Interactive Map**

The tool allows users to visualize key labor market indicators, including:
- Job vacancies
- Job seekers (both in terms of flows and stocks)
- Labor market tensions

The map is designed to provide insights at the municipal level, helping to categorize territories based on the intensity and nature of job market tensions. These categories can inform targeted policy interventions and labor market strategies.

### **Data Sources**
The project relies on publicly available and administrative data sources:
- **Jocas 2020 (Dares)**: Can be accessed via ADISP or through direct collaboration with Dares for more recent data.
- **France Travail Open Data**: Provides quarterly statistics on job seekers at the municipal level for communes with more than 5,000 inhabitants. These datasets include breakdowns by occupation, qualification, diploma, gender, and age. For smaller municipalities, aggregated data at the departmental level is also utilized.
- **Other complementary datasets** may be integrated to enhance the analysis.

### **Potential Applications**
- **Exploratory analysis of labor market imbalances** at different geographic levels.
- **Identification of clusters of territories** based on employment demand and supply tensions.
- **Policy recommendations** to address mismatches between job vacancies and job seekers.

## **Running the Application**

The tool is accessible by executing the script located in `./app`. All required files are included within the `./data` directory.

For users who wish to reproduce the project from scratch, the necessary scripts are provided in `./src`, with instructions available in the README files. Some large datasets must be downloaded manually due to file size constraints.

## **File Structure**
```         
├── README.md <- Documentation principale du projet.
├── LICENSE <- Licence du projet.
├── app <- Scripts pour exécuter l’outil de cartographie interactive.
├── data
│   ├── 1- 
│   ├── 2- 
│   ├── 3- 
├── src <- Code source pour le traitement et l’analyse des données.
│   ├── 
│   ├── 
│   └── 
├── docs
├── reports
```

## **Contributions & Contact**

For feedback, suggestions, or to report errors, please contact:

-   Alfonso Awadalla-Carreño : [alfonso.awadalla-carreno\@polytechnique.edu](mailto:alfonso.awadalla-carreno@polytechnique.edu){.email}
-   Anahi Reyes-Miguel : [anahi.reyes-miguel@polytechnique.edu](mailto:anahi.reyes-miguel@polytechnique.edu){.email}
-   Cynthia Francis : [cynthia.francis@polytechnique.edu](mailto:cynthia.francis@polytechnique.edu){.email}


We welcome contributions and collaborations to improve the tool further.

## **Acknowledgments**

We thank our academic mentors and external partners for their guidance and support in developing this project. Special thanks to the MSc&T "Data and Economics for Public Policy" program for organizing this initiative and fostering hands-on experience in public policy analytics.


