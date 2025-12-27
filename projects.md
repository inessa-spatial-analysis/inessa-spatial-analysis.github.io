[← Back to Home](index.md)

# 📂 Detailed Case Studies

## 🛒 Darkstores Location Strategy (Yango Deli/ Yandex Lavka)
**Role:** GeoData Scientist | **Location:** Global (Israel, Russia, UK, SA)
![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python) ![Optimization](https://img.shields.io/badge/-Linear_Programming-333?style=flat)

### The Challenge I: Develop Chain expantion strategy**   
The company needed to optimize its existing delivery network and plan expansion into new markets. The goal was to balance **fast delivery times** (customer satisfaction) with **operational costs** (minimizing the number of darkstores).

**The Methodology (Pipeline)**  
I built an end-to-end simulation engine to solve this:

```text
[Raw Demand Data] ──> [Spatial Clustering] ──> [Network Optimization] ──> [Final Site Coordinates and Service area]
(Socio-demographics)      (DBSCAN)              (Linear Programming)           (Strategic Locations)
```
**Results**
- Interactive maps with recommended locations and coverage
- Economic model

### 🛒 The Challenge II: Site Selection in  (Israel & Russia) based on historic data*
The company wanted to expand into new cities but didn't know where exactly to open new warhouses to maximise potential demand.

**The Methodology (Pipeline)**
I developed a predictive framework to forecast demand in new territories:

```text
[Multi-Source Data]  ──>  [Feature Engineering] ──>  [ML Prediction Model] ──> [Strategic Output]
(Census, Buildings, Orders) (200m Grid Aggregation) (Forecast 6-mo Volume) (Demand Heatmap)
```
---

### ⛽ Global Retail Site Selection (Locatium)
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

![Locatium Project Map](https://via.placeholder.com/800x400.png?text=Site+Selection+Heatmap+Example)

---

### ⛽ FTTH potential at building level (Locatium)
**Industry:** Telecom
**Location:** Nigeria, Brasil, Indonesia

**The Challenge**
Global clients needed to select the most profitable locations for new gas stations and retail chains across vast regions in the UAE and USA. 

**The Solution**
* **Predictive Modeling:** Developed Geo-ML models using **Scikit-Learn and PySAL** to score every potential site based on its surrounding features.
* **Innovation:** Created a custom Python library to predict economic potential at the **building level** using "morphometrics" (analyzing building shapes to guess their value), successfully applied in data-scarce regions like Nigeria, Indonesia, and Brazil.


### 🍦 Site Selection for new Gelato store (Rivareno Gelato)
**Industry:** Food & Beverage
**Location:** Tel Aviv Metropolitan Area

**The Challenge**
A premium Gelato brand needed to find the perfect location for their new branch. They needed to avoid cannibalizing their existing store while capturing high foot traffic of their specific target demographic.

**The Solution**
* Conducted a spatial analysis of competitor locations and complementary businesses.
* Mapped "human movement" patterns to identify streets with the highest volume of potential customers during evening hours.
* Delivered a ranked list of top candidate sites with estimated catchment areas.

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
* **Libraries:** `PySAL`, `Folium`, `Shapely`, `Rasterio`

### **Machine Learning & Cloud**
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
* **Models:** XGBoost, Random Forest, LGBM, DBSCAN, Kriging, Regression
* **Tools:** Jupyter, Docker, Git

---

[← Back to Home](index.md)
