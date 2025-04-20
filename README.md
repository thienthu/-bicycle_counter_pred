# 🚴‍♂️ Predicting Bicyclist Volume on Coupure Links  
*Machine Learning Project – Ghent University (2023–2024)*

## 🧠 Overview

This repository contains the solution to **Project 1** of the *Predictive Modeling* course at **Ghent University**. The task is to build a machine learning model that predicts the **hourly number of bicyclists** passing through **Coupure Links**, a street near the Bioscience Engineering campus. The data is collected by the **City of Ghent**.

The prediction is based on **historical weather data**, and the final goal is to support **policy-making** decisions, such as determining when car bans might be appropriate based on expected bicycle traffic.

## 🎯 Objective

- Predict the number of bicyclists per hour using machine learning techniques.
- Perform thorough **EDA**, **feature engineering**, **model training**, **evaluation**, and **interpretation**.
- Use weather features (both given and externally sourced) as predictors.
- Deliver a report detailing the full modeling pipeline.

## 📂 Project Structure
```
├── data/                  # Raw data
├── notebooks/             # Jupyter Notebooks (EDA, modeling, evaluation)
├── models/                # Trained model files and/or model selection outputs
├── output/                # Output file of description to submit
└── README.md              # This file
```

## 🔍 Key Steps

1. **Exploratory Data Analysis (EDA)**  
   Visualize trends, missing values, feature distributions, and temporal patterns.

2. **Feature Engineering**  
   - Create new features from date/time (hour, weekday, season, holidays).
   - Incorporate and expand on provided weather data (temperature, rainfall, wind, etc.).
   - Merge external data sources if useful.

3. **Model Training & Selection**  
   Train multiple models, tune hyperparameters via cross-validation, and compare performances.

4. **Evaluation**  
   Evaluate models using appropriate regression metrics (e.g., MAE, RMSE). Ensure generalizability and avoid overfitting.

5. **Discussion**  
   Interpret feature importances and model behavior. Discuss practical implications for policy making.

## 📊 Data

The dataset includes:

- Historical bicycle counts (target variable)
- Sample weather data (temperature, wind, rain, etc.)
- [Additional weather data](#) (sourced externally)


## 📝 Author
- **Author**: Thu Nguyen.
- **Disclaimer**: This project was developed as part of the Machine learning course at Ghent University.




