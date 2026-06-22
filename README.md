# Bike Sharing Demand Prediction using Multiple Linear Regression

## Project Overview

This project analyzes the Bike Sharing dataset to identify the key factors influencing daily bike rental demand and build a Multiple Linear Regression model capable of predicting rental counts.

The objective is to understand how environmental, seasonal, and calendar-related factors affect bike usage and to develop an interpretable predictive model.

---

## Problem Statement

A bike-sharing provider wants to understand the variables that significantly influence bike demand so that inventory planning, operational decisions, and business forecasting can be improved.

Multiple Linear Regression was used to quantify the relationship between bike rentals and various predictor variables.

---

## Dataset

The dataset contains information related to:

- Season
- Weather conditions
- Temperature
- Humidity
- Windspeed
- Holidays
- Working days
- Weekdays
- Bike rental counts (target variable)

---

## Methodology

The project was completed using the following steps:

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Dummy Variable Creation
4. Train-Test Split
5. Feature Scaling using Min-Max Scaling
6. Multiple Linear Regression Model Building
7. Iterative Feature Elimination using p-values
8. Variance Inflation Factor (VIF) Analysis
9. Residual Diagnostics
10. Final Model Evaluation

---

## Final Model Performance

| Metric | Value |
|----------|----------|
| Adjusted R² | 0.829 |
| Test R² | 0.810 |
| RMSE | 829.25 |

The final model explains approximately 81% of the variation in bike rental demand on unseen data.

---

## Key Findings

- Temperature positively influences bike demand.
- Humidity negatively affects rentals.
- Higher windspeed reduces bike usage.
- Light rain and mist significantly decrease demand.
- Seasonal effects have a measurable impact on rental counts.
- Working days and weekdays contribute positively to demand.
- Bike-sharing adoption increased significantly across years.

---

## Repository Contents

- `Bike_Sharing_Assignment_Shubham_Saxena.ipynb` – Complete Jupyter Notebook
- `AI&ML Assignment File.pdf` – PDF Report
- `README.md` – Project Documentation

---

## Author

**Shubham Saxena**

MBA (Digital Marketing + AI & ML)  
upGrad Woolf MBA Program
