## **README - Évaluation des Risques Climatiques et Financiers** 🌍💰

### **Projet : Data Challenge - Caisse des Dépôts et Consignations**

### 📌 **Contexte**
Le changement climatique représente un défi majeur pour les institutions financières. Dans le cadre de ce **Data Challenge organisé par la Caisse des Dépôts et Consignations (CDC)**, notre mission est d’**évaluer la vulnérabilité d’un portefeuille d’actifs fictifs** face aux risques climatiques en France métropolitaine.

### 🎯 **Objectifs**
Ce projet se divise en **deux grandes parties** :
1. **Analyse des risques climatiques** : Identifier et cartographier les aléas climatiques majeurs (inondations, sécheresses, feux de forêt et vagues de chaleur).
2. **Évaluation du risque financier** : Intégrer ces risques dans un **scoring des actifs financiers** en tenant compte de la localisation, du secteur d’activité et de la maturité des investissements.

### 🛠 **Technologies utilisées**
- **Python** (Jupyter Notebook)
- **Analyse de données** : `pandas`, `numpy`
- **Machine Learning** : `scikit-learn`, `KMeans`
- **Cartographie et analyse géospatiale** : `GeoPandas`, `QGIS`
- **Visualisation** : `matplotlib`, `seaborn`, `plotly`

### 🔍 **Méthodologie**
1. **Scoring des risques climatiques** :
   - Sélection d’indicateurs clés par type d’aléa climatique.
   - Classification des communes françaises en **clusters de risque** à l’aide de **K-Means**.
   - Visualisation cartographique sous **QGIS**.

2. **Scoring des actifs financiers** :
   - Attribution d’un **score de vulnérabilité climatique** aux actifs en fonction de leur localisation et secteur d’activité.
   - Pondération du risque en fonction de la **maturité et de l’encours financier**.
   - Analyse de l’impact économique des risques sur le portefeuille.

### 📊 **Résultats attendus**
- **Cartographie des risques climatiques** en France métropolitaine.
- **Modèle de scoring climatique et financier** pour évaluer la vulnérabilité des actifs.
- **Recommandations** pour la gestion des risques financiers face au changement climatique.

---

## **README - Climate and Financial Risk Assessment (🇬🇧)** 

### 📌 **Context**
Climate change is a **major challenge for financial institutions**. In this **Data Challenge organized by the Caisse des Dépôts et Consignations (CDC)**, our goal is to **assess the vulnerability of a fictitious asset portfolio** to climate risks in metropolitan France.

### 🎯 **Objectives**
This project is divided into **two main parts**:
1. **Climate risk analysis**: Identify and map major climate hazards (floods, droughts, wildfires, and heatwaves).
2. **Financial risk assessment**: Integrate these risks into a **scoring model for financial assets**, considering location, business sector, and investment maturity.

### 🛠 **Technologies Used**
- **Python** (Jupyter Notebook)
- **Data Analysis**: `pandas`, `numpy`
- **Machine Learning**: `scikit-learn`, `KMeans`
- **Geospatial Analysis and Mapping**: `GeoPandas`, `QGIS`
- **Visualization**: `matplotlib`, `seaborn`, `plotly`

### 🔍 **Methodology**
1. **Climate Risk Scoring**:
   - Selection of key indicators for each climate hazard.
   - Classification of French municipalities into **risk clusters** using **K-Means**.
   - Geospatial visualization with **QGIS**.

2. **Financial Asset Scoring**:
   - Assigning a **climate vulnerability score** to assets based on **location and business sector**.
   - Weighting risk by **maturity and outstanding financial amount**.
   - Assessing the economic impact of climate risks on the portfolio.

### 📊 **Expected Results**
- **Climate risk maps** for metropolitan France.
- **Climate and financial risk scoring model** to evaluate asset vulnerability.
- **Recommendations** for financial risk management in the face of climate change.

---

📂 **Structure du projet / Project Structure**
```
📁 DataChallenge_CDC
│── 📄 DataChallenge_BAILLET_MILLOT_ELHABTI.ipynb  # Notebook principal
│── 📄 livrable.pdf       # Rapport détaillé du projet
│── 📁 data/              # Dossier contenant les données (non incluses sur GitHub)
│── 📁 models/            # Dossier avec les modèles entraînés (optionnel)
```

🚀 **Instructions pour exécuter le projet**
1. **Cloner ce repository** :
   ```bash
   git clone https://github.com/[TON_GITHUB]/DataChallenge_CDC.git
   cd DataChallenge_CDC
   ```
2. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```
3. **Lancer le Notebook Jupyter** :
   ```bash
   jupyter notebook DataChallenge_BAILLET_MILLOT_ELHABTI.ipynb
   ```

---

💡 **Contact**
Pour toute question ou suggestion, n’hésitez pas à me contacter via **GitHub** ou **LinkedIn**.
