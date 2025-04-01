# 🏠 Iowa Housing Sales Dashboard

🔗 **Live Dashboard**  
👉 [Click here to view on Power BI](https://app.powerbi.com/view?r=eyJrIjoiMmEwM2VkOTQtODY3My00NmQxLTgzMGEtMTVjNTM5YmY0ZjlkIiwidCI6ImYxYWQ2ODFmLTZmNjItNDNhOS04MjQxLTA3MDMxNjBlMTM0OCIsImMiOjN9)

---

## 📋 Executive Summary

The project faced the challenge of accurately predicting home sale prices using diverse property features while managing complex relationships and ensuring clean, consistent data.

A comprehensive data-driven approach included:
- 📦 Cleaning and standardizing the dataset
- 🧠 Model development using linear regression and random forest
- 📊 Hyperparameter tuning to optimize performance

The model delivered highly accurate predictions and a scalable framework for dynamic market forecasting.

![Executive Summary](images/executive-summary.png)

---

## 📌 Project Overview

**Goal**: Predict housing sale prices and uncover the most influential property features using 130+ years of historical data from Iowa.

---

## 🎯 Objectives

- Visualize housing sales trends across Iowa from 1872–2010  
- Identify key features influencing home sale prices  
- Deliver accurate predictions using machine learning  
- Evaluate renovation ROI through case-based insights  

---

## 🗂️ Data Overview

- **Source**: Kaggle (Ames Housing Dataset)
- **Core Tables**:
  - `df1`: Property details (lot size, basement, bedrooms, etc.)
  - `DateTable`: Enables time-series slicing
  - `Prediction_Table`: Predictions, errors, and MAE evaluation

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

