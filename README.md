# 🏠 Iowa Housing Sales Dashboard

🔗 **Live Dashboard**  
👉 [Click here to view on Power BI](https://app.powerbi.com/view?r=eyJrIjoiMmEwM2VkOTQtODY3My00NmQxLTgzMGEtMTVjNTM5YmY0ZjlkIiwidCI6ImYxYWQ2ODFmLTZmNjItNDNhOS04MjQxLTA3MDMxNjBlMTM0OCIsImMiOjN9)

---

## Executive Summary

This dashboard visualizes key metrics related to housing sales, price trends, and the impact of various property features. It provides actionable insights to help stakeholders understand historical data, optimize pricing strategies, and identify key drivers of market performance.

![Executive Summary](executive%20summary.png)


---

## Background

Housing sales are influenced by numerous factors, including location, property size, and market conditions. By analyzing over a century's worth of data, this dashboard enables a deeper understanding of market trends, helping real estate professionals and policymakers make informed decisions.

![Background](background.png)

---

## Problem Statement

How can we accurately predict the sale prices of homes using various property features, while understanding the key drivers that influence housing market trends? This includes addressing challenges such as handling diverse data types, capturing complex relationships, and ensuring actionable insights for real estate stakeholders like agents, buyers, and investors.

---

## Objectives

Visualize housing sales trends across Iowa over time.
Identify key property features influencing sale prices.
Optimize decision-making through predictive sales models.



---

## 🧪 Methodology

### 🧼 Data Prep
- Removed outliers, imputed missing values
- Engineered features like `LotSizeCategory`, `Post2000Flag`, `PercentageError`

### 🤖 Model Training
- Evaluated 46 models using Microsoft Fabric
- Final Model: `XGBoost Regressor`
  - R²: 1.0
  - MAE: 11,031.6
  - MSE: 23M

---

## 📊 Visualizations

- Heatmaps of property value by location
- Predicted vs Actual scatter plot
- Key driver bar charts
- ROI simulation visuals

📸 *More screenshots coming soon*

---

## 💡 Case Study Highlights

### Case 1: Modernization Strategy
- 🟢 Post-2000 homes = +49% price premium  
- 🔴 Small basements = -32% value  
- 💰 Renovation ROI = 111%

### Case 2: Lot Size & Curb Appeal
- 🟢 Lots >10,000 sqft = +36% value  
- 🔴 Poor exterior = -40% value  
- 💰 Landscaping ROI = 327%

---

## 📈 Business Impact

- 📈 Optimized pricing strategies for agents & investors
- 🎯 Clear renovation priorities for higher ROI
- 🧠 Actionable analytics for stakeholders
- 🛠️ Scalable solution for evolving markets

---

## 🚀 Future Enhancements

- Integrate macroeconomic data (interest rates, jobs)
- Enable real-time insights with live data refresh
- Expand geospatial analysis for market targeting

---

## 👤 Author

**Donald Gray**  
Senior BI Developer | Power BI | Azure | Microsoft Fabric  
📧 djgray433@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/donald-gray-9576119b/)

