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

## Data Preparation

The data preparation process involved the following key steps:

Data Cleaning: Addressed missing values, removed duplicates, and handled outliers to ensure data accuracy and consistency.
Feature Engineering: Created derived features like LotSizeCategory and Percentage Error to enhance model performance.
Data Transformation: Standardized numerical features (e.g., Lot_Area, Sale_Price) and encoded categorical variables (e.g., Bldg_Type, House_Style) for seamless integration into predictive models.
Table Relationships: Established logical relationships between tables (e.g., df1, DateTable, Prediction_Table) to facilitate efficient querying and data exploration.

These steps ensured a clean, structured, and well-integrated dataset ready for analysis and predictive modeling.

![Data Preparation](data%20preparation.png)

---

## Model Selection

This dashboard leverages machine learning models developed using Microsoft Fabric to predict housing sale prices. A regression-based approach was employed, enabling the analysis of relationships between key property features (e.g., lot size, year built, and exterior condition) and sale prices. By integrating Microsoft Fabric's powerful data processing and modeling capabilities, the regression models provide accurate and actionable predictions, enhancing insights for real estate stakeholders.

![Model Selection](Model%20Selection.png)

---

## Model Development

The dashboard leverages the XGBoost Regressor, identified as the best-performing model through extensive evaluation of 46 different models. This regression model was trained on 2,413 selected data points, with 1,930 points used for training and 483 for cross-validation. Key metrics demonstrate the model's performance:

R² (Coefficient of Determination): 1.0, indicating perfect predictive accuracy.
Mean Squared Error (MSE): 23,040,876.2
Mean Absolute Error (MAE): 11,031.6
Median Absolute Error: 797.7
Variance: 1.0

This robust model development process highlights the efficacy of the chosen regression model in accurately predicting housing sale prices, providing reliable insights for stakeholders.

![Model Development](Model%20development.png)



