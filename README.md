# 🚗 Analyse des Accidents Routiers | Projet Power BI

## 📌 Aperçu du projet

Ce projet présente un tableau de bord interactif développé avec **Power BI** pour analyser les données des **accidents routiers** et identifier les principaux facteurs influençant leur fréquence et leur niveau de risque.

L’objectif est d’explorer :

- Les indicateurs généraux des accidents
- L’impact de l’infrastructure routière
- Les facteurs de risque liés aux conditions de circulation

---

## 📊 Tableaux de bord

## 1️⃣ Dashboard : Indicateurs des Accidents Routiers

Ce tableau de bord offre une vue d’ensemble sur la fréquence et la répartition des accidents.

### KPI principaux :

- **Taux moyen des accidents :** `1,19`

### Visualisations :

- **Accidents par période de la journée**
  - Matin
  - Après-midi
  - Soir

- **Accidents par type de route**
  - Autoroute
  - Zone urbaine
  - Zone rurale

- **Accidents par conditions météorologiques**
  - Brouillard
  - Temps clair
  - Pluie

### Principaux insights :

✔ Le soir présente légèrement plus d’accidents  
✔ Les autoroutes enregistrent le plus grand nombre d’accidents  
✔ Le brouillard augmente la fréquence des accidents  

---

## 2️⃣ Dashboard : Infrastructure Routière

Ce tableau analyse l’impact des caractéristiques de l’infrastructure sur les accidents.

### KPI principaux :

- **Pourcentage des routes avec panneaux :** `49,92 %`
- **Pourcentage des routes privées :** `49,77 %`
- **Pourcentage des routes publiques :** `50,23 %`

### Visualisations :

- **Accidents par nombre de voies**
- **Accidents par type d’éclairage**
  - Lumière du jour
  - Faible luminosité
  - Nuit

### Principaux insights :

✔ Les accidents sont répartis de manière similaire selon le nombre de voies  
✔ Les conditions de faible éclairage augmentent le risque d’accident  
✔ Les routes publiques et privées présentent une répartition équilibrée  

---

## 3️⃣ Dashboard : Risque Routier

Ce tableau de bord permet d’évaluer le niveau de risque moyen selon plusieurs facteurs.

### Filtres interactifs :

- Période de la journée
- Vacances / Hors vacances

### Visualisations :

- **Risque moyen par type de route**
- **Risque moyen par limitation de vitesse**

### Principaux insights :

✔ Les routes urbaines présentent un risque moyen légèrement plus élevé  
✔ Le risque augmente fortement avec des limitations de vitesse élevées (60–70 km/h)  
✔ Les périodes de vacances peuvent influencer les tendances des accidents  

---

## 🛠️ Outils utilisés

- **Power BI Desktop**
- **Power Query**
- **DAX (mesures et KPI)**
- **Modélisation de données**

---

## 📂 Variables analysées

Les principales variables utilisées dans ce projet :

- `road_type` → type de route
- `weather` → conditions météorologiques
- `lighting` → conditions d’éclairage
- `speed_limit` → limitation de vitesse
- `time_of_day` → période de la journée
- `holiday` → vacances
- `num_lanes` → nombre de voies
- `risk_score` → score de risque
- `total_accidents` → nombre total d’accidents

---

## 🎯 Objectifs du projet

- Analyser les tendances des accidents routiers
- Évaluer l’impact de l’infrastructure
- Identifier les situations à haut risque
- Aider à la prise de décision pour améliorer la sécurité routière

---

## 📸 Aperçu du dashboard

Inclure ici les captures d’écran des trois tableaux de bord :

- Dashboard Indicateurs des Accidents
- Dashboard Infrastructure Routière
- Dashboard Risque Routier

---

## 🚀 Compétences démontrées

✅ Nettoyage des données  
✅ Modélisation des données  
✅ Création de KPI  
✅ Calculs DAX  
✅ Conception de dashboards interactifs  
✅ Data storytelling  

---

