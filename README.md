# Tunisia Regional Development Index (IDR) Analysis

## 📌 Introduction
This project analyzes the **Regional Development Index (IDR)** across Tunisia’s governorates.  
The IDR is a composite indicator that reflects regional disparities in **education, wealth, health, and justice**.  
The goal is to calculate and visualize the IDR to highlight development inequalities and provide insights for potential improvement.

---

## 📊 Dataset
The dataset contains socio-economic indices for Tunisia’s governorates, with the following fields:
- **Education**
- **Wealth**
- **Health**
- **Justice**
- **Governorate name**
- **Geographic boundaries (GeoJSON)**

Additional data was used from `Tunisia_Governorates.geojson` to enable geospatial visualizations.

---

## ⚙️ Methods
1. **Data Cleaning**
   - Checked for null values (none found).
   - Verified duplicates and data types (dataset already clean).

2. **Index Calculation**
   - **Simple Mean:** Assumes all indices have equal weight.  
   - **Weighted Average:** A more accurate IDR reflecting the relative importance of each index.

3. **Visualization**
   - **Bar Chart:** IDR by governorate.  
   - **Scatter Plots:** Relationships between indices (e.g., Education vs Wealth).  
   - **Choropleth Map:** IDR mapped across Tunisia’s regions using GeoPandas.  

---

## 📈 Visualizations
- **Bar Chart:** Shows IDR per governorate (Tunis and Ariana highest, Kasserine and Sidi Bouzid lowest).  
- **Scatter Plots:** Reveal correlations (e.g., higher education tends to correlate with higher wealth).  
- **Choropleth Map:** Shades of red represent IDR (darker red = higher IDR). Southern regions are near the **0.51 average**.

---

## 🔎 Insights
- **Northern regions** (Tunis, Ariana, Ben Arous) have higher IDR scores.  
- **Kasserine and Sidi Bouzid** show the lowest IDR, requiring stronger policies in education and development.  
- **Southern regions** are around the average IDR (~0.51), showing relative balance but still room for growth.  
- Education and wealth strongly correlate, while justice shows disparities in some regions.

---

