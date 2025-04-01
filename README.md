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

![Objectives](objectives.png)

---

## Data Overview

Data Source:
Historical housing sales data from 1872 to 2010. (Kaggle)
Key Metrics:
Average Sales Price
Price per Bedroom
ROI and Post-2000 Premium
Basement Size Impact
Lot Size and Exterior Condition Analysis

![Data Overview](data%20overview.png)


---

## System Architecture

The dashboard integrates historical sales data, preprocessing pipelines, and advanced visualization techniques, ensuring a seamless and user-friendly interface for exploring insights.

![System Architecture](system%20architecture.png)

---

## Data Features

The dataset is structured into three main tables:

df1 Table: Contains core property details, such as basement category, lot area, bedrooms, building type, exterior condition, fireplaces, and geographical coordinates (latitude and longitude). It also includes temporal fields like listing date and decade.

DateTable: Focused on temporal data, including date, day, month name, month number, and quarter, enabling time-based analysis.

Prediction_Table: Features predictive metrics, such as sale price, predicted sales, absolute error, percentage error, and MAE (Mean Absolute Error). It also includes key property attributes like lot frontage, overall condition, and year built for prediction model evaluation.

This structure integrates historical, property-specific, and predictive data to support robust analysis and accurate forecasting.

![Data Features](data%20features.png)

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

