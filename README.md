# 🌪️ Analysis of Cyclone Data (2018–2022)

This project involves the **Exploratory Data Analysis (EDA)** of cyclone track data from **2018 to 2022**, focusing on wind speed, pressure, grade classification, and seasonal patterns. The goal is to identify insights and trends that can aid in meteorological research and disaster preparedness.

---

## 🎯 Objectives

- Analyze cyclone patterns and intensity over 5 years
- Understand seasonal and regional distribution
- Identify trends in cyclone grade and formation
- Support future cyclone prediction and risk management efforts

---

## 🧪 Dataset Description

The dataset (converted from Excel to DataFrame) includes:

- **Cyclone name, date, time, location** (lat/lon)
- **Intensity parameters**: Wind speed, central pressure, CI Number
- **Grade**: Depression, Cyclonic Storm, Severe Cyclonic Storm, etc.
- **Classification**: Over ocean (O) or land (L)

> Missing values were imputed, non-numeric rows removed, and a new "O/L" column was added for geographical classification.

---

## 📈 Key Findings

- **Seasonal Trend**: Most cyclones occurred in the **Post-Monsoon (Oct–Dec)** season.
- **Regional Pattern**: The **Bay of Bengal** recorded more cyclones than the Arabian Sea.
- **Cyclone Grades**:
  - Most common grades: Depression and Cyclonic Storm
  - Rare grades: Very Severe Cyclonic Storm, Super Cyclonic Storm (only 2 in 5 years)
- **Year-wise Variation**: Cyclonic activity and grade distribution varied each year.
- **Multivariate Analysis**: Correlation observed between central pressure, wind speed, and grade.

---

## 📊 Visualizations

- Stacked bar charts (grade vs. year)
- Seasonal distribution by cyclone type
- Correlation heatmap for intensity parameters
- Cyclone count by year and grade

---

## 🧠 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- PowerPoint (for summary visualization)
- Excel (for initial data structure)

---

## 📌 Conclusion

- Cyclone formation and intensity are influenced by season and geography
- Cyclone grade is not always tied to lifespan
- Post-monsoon is the most cyclone-prone season
- Only two **Super Cyclonic Storms (SuCS)** occurred in 5 years, highlighting their rarity

---

## 📚 References

Mondal, M., Biswas, A., Haldar, S., Mandal, S., Bhattacharya, S., & Paul, S. (2022).  
*Spatio-temporal behaviours of tropical cyclones over the Bay of Bengal Basin in last five decades*.  
**Tropical Cyclone Research and Review**, 11(1), 1-15.

---

## 👥 Contributors

- Swarnamoy Ghosh – PG/05/MSTSTDS/2023/002  
- Debargho Chatterjee Ganguly – PG/05/MSTSTDS/2023/004  
**Adamas University, Kolkata**

---



