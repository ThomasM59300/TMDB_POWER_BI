# 📊 Dashboard TMDb - Analyse des tendances cinématographiques

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-FF6B35?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

*Projet d'analyse de données utilisant Power BI pour visualiser les tendances de l'industrie cinématographique*

## 🎬 Aperçu du projet

Tableau de bord interactif analysant les données de films via l'API TMDb, révélant des insights sur la rentabilité, les genres populaires et les performances des réalisateurs. Ce projet démontre une approche complète d'analyse de données, de l'extraction à la visualisation.

**🔗 [Accéder au dashboard Power BI](https://app.powerbi.com/links/P7ioLOm_bh?ctid=a7b3a854-5b11-4927-8868-91a5f35bc887&pbi_source=linkShare)**

## 🛠️ Compétences techniques mises en œuvre

- **ETL** : Extraction API TMDb → PostgreSQL → Power BI
- **Power Query** : Transformation et nettoyage des données
- **DAX** : Mesures avancées (ROI, rentabilité, moyennes pondérées)
- **Modélisation** : Table de fait, de dimension et d'association (permettant une relation *:*)
- **Visualisation** : KPI, graphiques interactifs, storytelling de données

## 📈 Méthodologie d'analyse

Partie n°1 (voir autre repository): 

1. **Collecte** : Extraction des données via l'API TMDb
2. **Stockage** : Base PostgreSQL structurée et optimisée

Partie n°2 :

3. **Nettoyage** : Gestion des valeurs manquantes, détection d'outliers
4. **Modélisation** : Schéma respectant les bonnes pratiques
5. **Analyse** : Segmentation par genre, période, budget et performances
6. **Visualisation** : Dashboard interactif

## 🔍 Principales découvertes

- **Rentabilité par genre** : Contrairement à ce que l'on pourrait croire, les films d'action et d'aventure ne présentent pas le meilleur ROI. Il s'agit en effet des documentaires, téléfilms et films d'animations, qui sont moins couteux à produire. Attention, cela ne signifie pas qu'elles rapportent plus en valeur absolue
- **Évolution du revenu** : Augmentation constante des revenus depuis 1980, avec un crash en 2020 à cause du COVID
- **Corrélation budget-revenus** : Forte corrélation positive entre le budget et le revenu (pour tous les genres pris en compte)
- **Performance réalisateurs** : Identification des réalisateurs les plus rentables par genre
- **Performance acteurs** : Identification des acteurs ayant engendré le plus de bénéfice total

## 🚀 Fonctionnalités du dashboard

### KPI principaux
- Revenu par genre et par année
- Note moyenne par genre et par année
- Nombre total de films par réalisateur
- ROI global et/ou par catégorie et/ou par réalisateur

### Visualisations interactives
- **Analyse des genres** : Répartition, évolution, rentabilité
- **Performance des acteurs** : Top performers en termes de bénéfices
- **Rentabilité** : Graphiques de corrélation budget/revenus
- **Tendances temporelles** : Évolution des metrics clés
- **Top 10 dynamiques** : Films en fonction du bénéfice, selon différents filtres

### Filtres et interactivité
- Filtrage par année de sortie
- Sélection par genre cinématographique
- Filtre par réalisateur
- Analyse cross-filtering entre visualisations

## 📁 Structure du projet

```
📦 TMDB_POWER_BI/
├── 📄 TMDB_power_bi.pbix          # Dashboard Power BI complet
├── 📄 mesures_dax.md              # Documentation des mesures DAX
├── 📄 modele.png                  # Schéma du modèle de données
├── 📄 readme.md                   # Documentation générale
└── 📁 captures/                   # Captures d'écran
```


## 📊 Technologies utilisées

| Technologie | Usage | Niveau |
|-------------|--------|--------|
| Power BI | Visualisation et dashboarding | Intermédiaire |
| PostgreSQL | Base de données | Intermédiaire |
| DAX | Mesures et calculs | Intermédiaire |
| Power Query | ETL et transformation | Intermédiaire |
| SQL | Requêtes et jointures | Intermédiaire |

