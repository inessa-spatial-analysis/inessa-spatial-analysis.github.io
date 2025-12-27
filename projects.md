[← Back to Home](index.md)

# 📂 Case Studies Examples

## 🛒 Darkstores Location Strategy (Yango Deli/ Yandex Lavka)
**Role:** GeoData Scientist | **Location:** Global (Israel, Russia, UK, SA)
![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python) ![Optimization](https://img.shields.io/badge/-Linear_Programming-333?style=flat)

### The Challenge I: Develop Chain expantion strategy  
The company needed to optimize its existing delivery network and plan expansion into new markets. The goal was to balance **fast delivery times** (customer satisfaction) with **operational costs** (minimizing the number of darkstores).

**The Methodology (Pipeline)**  
I built an end-to-end simulation engine to solve this:

```text
[Raw Demand Data] ──> [Spatial Clustering] ──> [Network Optimization] ──> [Final Site Coordinates and Service area]
(Socio-demographics)      (DBSCAN)              (Linear Programming)           (Strategic Locations)
```

### The Challenge II: Site Selection in  (Israel & Russia) based on historic data
The company wanted to expand into new cities but didn't know where exactly to open new warhouses to maximise potential demand.

**The Methodology (Pipeline)**
I developed a predictive framework to forecast demand in new territories:

```text
[Multi-Source Data]  ──>  [Feature Engineering] ──>  [ML Prediction Model] ──> [Strategic Output]
(Census, Buildings, Orders) (200m Grid Aggregation) (Forecast 6-mo Volume) (Demand Heatmap)
```

<img src="images/yango_israel.png" alt="Yango Israel Map" width="900">
---

## ⛽ Global Retail Site Selection (Locatium)
**Industry:** Retail & Energy
**Location:** UAE, USA, Global

**The Challenge**   
Global clients needed to select the most profitable locations for new gas stations, retail and restaurants chains across vast regions in the UAE and USA. 

**The Methodology (Pipeline)**   
I designed a multi-stage spatial modeling framework:

```text
[Spatial Data Ingestion] ──> [Traffic Simulation] ──> [Predictive Modeling] ──> [Site Scoring Map]
(POIs, Demographics, Streets) (Gravity Models & OD Matrix) (Service Penetration)   (Optimal Locations)
```

**Examples of results**
<img src="images/ev_locations.png" alt="ev Map" width="600">


---

## ⛽ FTTH potential at building level (Locatium)
**Industry:** Telecom
**Location:** Nigeria, Brasil, Indonesia

**The Challenge**   
Major telecom operators needed to prioritize Fiber-to-the-Home (FTTH) rollouts in dense cities like Lagos, Jakarta, and São Paulo. **The main problem** was identifying profitable neighborhoods to target first, as these regions lacked high-resolution socio-economic data.

**The Methodology (Pipeline)**   
I developed a proxy-based economic modeling engine:

```text
[Satellite & Geometry] ──> [Morphometric Analysis] ──> [Spatial Clustering] ──> [Revenue Modeling]
(NDVI, Building Shapes)    (Density, Greenery)          (K-Means Context)       (Predicted ARPU)
```
**Examples of results**

<img src="images/lagos.png" alt="Lagos Map" width="600">
---

### 🍦 Data-Driven Site Selection (Rivareno Gelato)
**Role:** Spatial Analyst | **Location:** Tel Aviv (2025)
![GeoPandas](https://img.shields.io/badge/-GeoPandas-333?style=flat) ![Gravity Models](https://img.shields.io/badge/-Spatial_Interaction-333?style=flat)

**The Challenge**   
A premium Gelato brand needed to open a new branch without cannibalizing their existing store. They required a location with high evening foot traffic and specific demographic alignment.

**The Methodology (Pipeline)**   
I utilized spatial embeddings and interaction modeling to score locations:

```text
[Competitor Analysis] ──> [Traffic Simulation] ──> [Site Scoring] ──> [Interactive Dashboard]
(Embeddings & Similarity) (Gravity Model @ 100m)   (Catchment & KPIs)   (Decision Support)
```
**Examples of results**

<img src="images/traffic_sim_telaviv.png" alt="TA_traffic Map" width="300">
<img src="images/dashboard_rivareno.png" alt="TA_traffic Map" width="300">
---


## 🛠️ Technical Stack

### **languages & Core Libraries**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

### **Spatial Analytics & Visualization**
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge&logo=python&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Kepler.gl](https://img.shields.io/badge/Kepler.gl-3B3B3B?style=for-the-badge&logo=uber&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
* **Libraries:** `PySAL`, `Folium`, `Shapely`, `Rasterio`, `GeoPandas`

### **Machine Learning & Cloud**
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
* **Models:** XGBoost, Random Forest, DBSCAN, LogisticRegression, Kmeans
* **Tools:** Python, Docker, Git, BigQuery, PostGIS

---

[← Back to Home](index.md)
