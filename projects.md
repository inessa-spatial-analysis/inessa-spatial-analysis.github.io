[← Back to Home](index.md)

# 📂 Detailed Case Studies


**Role:** GeoData Scientist | **Location:** Global (Israel, Russia, UK, SA)
![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python) ![Optimization](https://img.shields.io/badge/-Linear_Programming-333?style=flat)

**The Challenge**   
The company needed to optimize its existing delivery network and plan expansion into new markets. The goal was to balance **fast delivery times** (customer satisfaction) with **operational costs** (minimizing the number of darkstores).

**The Methodology (Pipeline)**  
I built an end-to-end simulation engine to solve this:

```text
[Raw Demand Data] ──> [Spatial Clustering] ──> [Optimization Algo] ──> [Final Site Coordinates]
(Socio-demographics)      (DBSCAN)              (Gurobi / LP)           (Strategic Locations)
```

**The Solution:**
* Built an automated **Economic Growth Simulation** in Python.
* The tool allowed managers to run "What-If" scenarios (e.g., *"What happens to profit if we move Store A 500m north?"*) and instantly see the financial impact.

**The Challenge II: Strategic Expansion (Israel & Russia)**
The company wanted to expand into new cities but didn't know which specific neighborhoods offered the highest return on investment.

**The Solution:**
* Developed a Machine Learning model that predicted potential daily order volume at a **200m x 200m resolution**.
* This granular map allowed the real estate team to target only the highest-potential city blocks.

**The Challenge III: Market Entry Strategy (UK & South Africa)**
Before entering these new markets, the company needed to determine the optimal number of stores to open to balance high coverage with low CAPEX.

**The Solution:**
* **Demand Modeling:** Estimated potential demand for every major city based on socio-economic profiles.
* **Granular Projection:** Downscaled city-level demand to the individual building level.
* **Network Optimization:** Used **Integer Linear Programming** algorithms to mathematically calculate the "perfect" number of stores needed to maximize coverage while minimizing setup costs.

![Yango Project Map](https://via.placeholder.com/800x400.png?text=Map+of+Delivery+Zones+and+Demand+Heatmap)

---

### ⛽ Global Retail Site Selection (Locatium)
**Industry:** Retail & Energy
**Location:** UAE, USA, Global

**The Challenge**
A global client needed to select the most profitable locations for new gas stations and retail chains across vast regions in the UAE and USA. Manual scouting was too slow and data-poor.

**The Solution**
* **Automated Data Pipeline:** Built a system to automatically harvest and clean open data on urban infrastructure, demographics, and Points of Interest (POIs) using APIs and web scraping.
* **Predictive Modeling:** Developed Geo-ML models using **Scikit-Learn and PySAL** to score every potential site based on its surrounding features.
* **Innovation:** Created a custom Python library to predict economic potential at the **building level** using "morphometrics" (analyzing building shapes to guess their value), successfully applied in data-scarce regions like Nigeria, Indonesia, and Brazil.

![Locatium Project Map](https://via.placeholder.com/800x400.png?text=Site+Selection+Heatmap+Example)

---

### 🍦 Data-Driven Site Selection (Rivareno Gelato)
**Industry:** Food & Beverage
**Location:** Tel Aviv Metropolitan Area (2025)

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
