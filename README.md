# Analyse des taux de cancer aux États-Unis

Ce projet vise à analyser les taux de cancer dans les différents États des États-Unis en relation avec divers facteurs socio-économiques. À l’aide de données publiques et d’outils d’analyse statistique et géospatiale, nous identifions les tendances et les corrélations significatives à travers le pays.

---

## Contenu du dépôt

- `projet_cancer_final.qmd` : Rapport principal du projet (format Quarto), incluant l’analyse, les visualisations et les interprétations.
- `cancer_reg.csv` : Jeu de données principal, contenant les taux de cancer et plusieurs indicateurs socio-économiques par État.
- `cartes_usa.csv` : Coordonnées géographiques utilisées pour les visualisations cartographiques des États-Unis.

---

## Objectifs

- Étudier la répartition géographique des taux de cancer.
- Identifier des corrélations entre le taux de cancer et des variables telles que :
  - le revenu moyen,
  - le taux de pauvreté,
  - le taux de personnes sans assurance santé,
  - le pourcentage de population ayant un diplôme universitaire.
- Créer des visualisations claires (cartes, graphiques) pour appuyer l’analyse.
- Fournir un rapport reproductible et facilement modifiable via Quarto.

---

##  Prérequis

### Logiciels

- [Quarto](https://quarto.org) (recommandé avec RStudio)
- R (version ≥ 4.0) ou Python (si le `.qmd` est en Python)

### Packages R suggérés

```r
install.packages(c("tidyverse", "ggplot2", "leaflet", "dplyr", "readr"))
