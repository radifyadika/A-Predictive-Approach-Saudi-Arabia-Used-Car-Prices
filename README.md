# BetaGroup_JC_DS_OL_14_A_FinalProject
# Saudi Arabia Used Cars Analysis and Modeling

## Background

This project involves analyzing and modeling a dataset on used cars in Saudi Arabia. The data is sourced from the [Saudi Arabia Used Cars dataset](https://www.kaggle.com/turkibintalib/saudi-arabia-used-cars-dataset?select=UsedCarsSA_Unclean_EN.csv). The analysis and modeling are split into two notebooks, focusing on different aspects of the data journey: analytics and machine learning.

## Problem Statement

The used car market in Saudi Arabia is vast, and it is essential to understand key trends in the market, such as factors influencing car prices, common characteristics of sold cars, and patterns in demand. This project aims to answer the following questions:

1. What factors affect the prices of used cars in Saudi Arabia ? And What insights can we derive from the data to inform business decisions in the used car market ?
2. Can we build a predictive model to estimate the price of a used car based on various features ?

## Objective

The project is divided into two main objectives:
1. Analytics : 
   - Clean the dataset and handle missing values.
   - Perform exploratory data analysis (EDA) to uncover key trends and insights.
   - Provide business recommendations based on the analysis.

2. Machine Learning : 
   - Feature engineering to transform raw data into useful inputs for models.
   - Build and evaluate several machine learning models to predict the prices of used cars.
   - Compare model performances and provide recommendations for the best model to use.

## Stakeholder

The stakeholders for this project can be defined to these 3 major group :

1. Car Sellers
   - Pain Point : Difficulty in determining the right selling price for their used vehicles.
   - Benefit : A reliable estimate based on market trends and vehicle specifications to help price their car competitively and fairly.

2. Car Buyers
   - Pain Point : Lack of transparency in market prices, often resulting in overpaying or missing better deals.
   - Benefit : Trustworthy predictions that enable them to make informed decisions when negotiating or searching for cars within their budget.

3. Used Car Dealerships
   - Pain Point : The need for quick, accurate appraisals to stay competitive in the market.
   - Benefit : Access to a tool that offers fast, reliable price estimates, allowing them to adjust their listings or offer competitive buy prices to sellers.

## Research Questions

### 1. Analytics:
- What are the key factors affecting the used car prices in Saudi Arabia ?
- What are the common trends in car sales, such as popular brands, models, and mileage ?
- How do different features (e.g., age, mileage, transmission type) affect car prices ?

### 2. Machine Learning:
- How can we use the available data to predict car prices ?
- Which machine learning model provides the most accurate predictions for used car prices ?
- What feature engineering techniques can improve model performance ?

## Description of Features

| Feature               | Description                                                    |
|-----------------------|----------------------------------------------------------------|
| `Brand`               | The brand or make of the car (e.g., Toyota, Ford).              |
| `Model`               | The specific model of the car.                                  |
| `Year`                | The year the car was manufactured.                             |
| `Mileage`             | The number of kilometers the car has been driven.              |
| `Price`               | The price at which the car is listed or sold.                  |
| `Gear_Type`           | The type of transmission (Manual, Automatic, etc.).            |
| `Location`            | The city or region where the car is listed.                    |
| `Fuel_Type`           | The type of fuel used by the car (Petrol, Diesel, etc.).        |
| `Color`               | The color of the car.                                           |

## Analysis and Modeling

### 1. Analytics Notebook:
The **Analytics.ipynb** notebook focuses on:
- Data cleaning and handling missing values.
- Exploratory data analysis (EDA) using visualizations such as histograms, bar charts, and scatter plots.
- Deriving key insights and trends from the data to provide actionable business recommendations.

### 2. Machine Learning Notebook:
The **Machine Learning.ipynb** notebook covers:
- Feature engineering, including handling categorical variables and creating new features.
- Building several machine learning models, such as:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - XGBoost
- Evaluating model performance using metrics such as RMSE, MAE, and **MAPE (Mean Absolute Percentage Error)**.
- **Final evaluation is based on MAPE** to compare model performance and choose the best predictive model for car prices.

## Libraries Used

The following Python libraries are used in the notebooks:

- `pandas`
- `numpy`
- `sklearn`
  - `LinearRegression`
  - `DecisionTreeRegressor`
  - `RandomForestRegressor`
  - `KNeighborsRegressor`
  - `Pipeline`
  - `StandardScaler`
  - `OneHotEncoder`
  - `ColumnTransformer`
  - `train_test_split`
  - `RandomizedSearchCV`
- `xgboost`
  - `XGBRegressor`
- `category_encoders`
- `matplotlib`
- `seaborn`
- `scipy`
- `math`
- `warnings`
- `r2_score`
- `rfpimp`
- `permutation_importances`
- `kurtosis`
- `skew`
- `sqrt`

## Conclusion

This project provides a comprehensive analysis of the Saudi Arabian used car market, identifying key trends and building predictive models for car prices. The insights derived from the analysis can be used to inform business strategies, while the machine learning models provide a robust solution for price prediction.

The final model evaluation is based on **MAPE** (Mean Absolute Percentage Error), which allows us to choose the most accurate model in terms of percentage error for price prediction.

## Dashboard

To view the interactive dashboard, visit:
[Tableau Dashboard](https://public.tableau.com/app/profile/radif.ramadan/viz/DashboardFinproPurwadhika/Dashboard1?publish=yes)

## Contributors

- [Edo Sigit Aditya](https://github.com/eaditya99)
- [Katarina Santosa](https://github.com/santoskt)
- [Radif Ramadhan](https://github.com/radifyadika)


