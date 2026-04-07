# France Mobilités - Tableau de Bord Décisionnel 🚌🚆

## 📊 Présentation du Projet
Ce projet est un tableau de bord de Business Intelligence complet, réalisé avec **Power BI** pour "France Mobilités". Il a pour objectif de fournir des analyses basées sur les données concernant la mobilité urbaine dans les grandes métropoles françaises (Paris, Lyon, Marseille, Toulouse, Bordeaux, etc.). 

L'analyse s'articule autour de trois grands axes :
1. **Performance Opérationnelle :** Suivi de la ponctualité, des retards moyens et des taux d'utilisation selon les différents modes de transport (Bus, Tram, Métro).
2. **Empreinte Environnementale (Pollution) :** Suivi de la consommation d'énergie, des émissions de CO2 et de l'Indice de Qualité de l'Air (AQI) par ville.
3. **Sécurité Urbaine (Impact) :** Analyse du nombre d'accidents, de leur gravité, de la congestion du trafic et des indicateurs de sécurité urbaine globaux.

## 📁 Contenu du Dépôt (Repository)
*   `Urbain mobility dashbords.pbix` : Le fichier principal du tableau de bord Power BI.
*   `Dataset/` : Dossier contenant les données brutes (fichiers CSV/Excel) utilisées pour cette analyse.
*   `Documentation_DAX.pdf` : Un document listant et expliquant les mesures DAX personnalisées et les colonnes calculées créées pour ce projet.

## 🧮 Principales Mesures DAX Utilisées
*   **Retard Moyen :** Calcul du retard moyen des véhicules sur l'ensemble du réseau.
*   **Évolution CO2 (YoY) :** Mesure de l'évolution d'une année sur l'autre (Year-over-Year) des émissions de carbone.
*   **Taux de Ponctualité :** Pourcentage de trajets effectués à l'heure par rapport au total des trajets prévus.

## 🛠️ Outils Utilisés
*   **Microsoft Power BI :** Visualisation, modélisation des données et création du tableau de bord.
*   **DAX (Data Analysis Expressions) :** Langage de formule pour les calculs avancés.
*   **Git / GitHub :** Contrôle de version, documentation et déploiement du projet.
