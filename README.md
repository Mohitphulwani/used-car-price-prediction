# used-car-price-prediction
Predicting the price of used cars in the Indian market using regression analysis and machine learning to support Cars4U in differential pricing strategies.
# Used Car Price Prediction (Cars4U)

## Overview
This project focuses on predicting the **price of used cars** in India to help Cars4U, a tech startup, devise **profitable pricing strategies**.  
With the pre-owned car market surpassing new car sales, accurate price prediction and market insights are critical for maximizing revenue and minimizing losses.

---

## Business Context
- **Market Insight:** In 2018–19, ~4 million used cars were sold in India, compared to 3.6 million new cars.  
- **Objective:** Build a pricing model that predicts the selling price of used cars (INR Lakhs) and provides actionable insights for differential pricing.  
- **Impact:** Helps Cars4U avoid selling below market value and optimize inventory pricing decisions.

---

## Dataset
The dataset contains the following features:

1. **S.No.**: Serial Number  
2. **Name**: Car Brand and Model  
3. **Location**: City where car is available  
4. **Year**: Manufacturing year  
5. **Kilometers_driven**: Distance driven by previous owners (KM)  
6. **Fuel_Type**: Fuel type (Petrol, Diesel, Electric, CNG, LPG)  
7. **Transmission**: Transmission type (Automatic / Manual)  
8. **Owner**: Ownership type  
9. **Mileage**: Mileage offered by the car company (kmpl or km/kg)  
10. **Engine**: Engine displacement (CC)  
11. **Power**: Maximum power of the engine (bhp)  
12. **Seats**: Number of seats  
13. **New_Price**: Price of new car (INR Lakhs)  
14. **Price**: Price of used car (INR Lakhs) – **Target variable**  

---

## Objectives
- Build a **regression model** to predict used car prices.  
- Identify significant features influencing pricing, such as **Year, Mileage, Fuel Type, Transmission, Power, and Engine size**.  
- Provide insights and recommendations for **differential pricing strategies**.

---

## Key Regression Metrics Explained
1. **Adjusted R-squared**: Measures model fit; closer to 1 indicates better performance.  
   - Example: **0.85** indicates strong model fit.  
2. **Coefficients**: Represent the effect of each independent variable on the target variable (price).  
   - Example: **Schooling coefficient** indicates how much price changes with a unit change in Schooling, holding other features constant.  
3. **Std Error**: Reflects accuracy of coefficients; smaller values indicate higher reliability.  
4. **P-value (P>|t|)**: Determines statistical significance of features.  
   - Threshold: 0.05 (5%)  
   - P < 0.05 indicates feature significantly affects price.  
5. **Confidence Interval**: Range where the true coefficient likely falls (95% confidence).

---

## Methodology
- **Data Cleaning & Preprocessing**  
  - Handle missing values, encode categorical variables, standardize numeric features.  
- **Exploratory Data Analysis (EDA)**  
  - Identify trends, outliers, and correlations between features and price.  
- **Modeling**  
  - Linear Regression, Ridge Regression, or other ML regression techniques.  
- **Model Evaluation**  
  - Metrics: R², RMSE, MAE  
- **Insights & Recommendations**  
  - Use model to inform pricing strategies, such as differential pricing or market adjustment.  

---

## Technologies Used
- **Python**  
- **Pandas & NumPy**  
- **Matplotlib & Seaborn** for visualizations  
- **Scikit-learn** for regression modeling  
- **Jupyter Notebook**  

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/mohitphulwani001/used-car-price-prediction.git
cd used-car-price-prediction

