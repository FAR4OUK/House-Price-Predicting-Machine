🏡 House Price Prediction

This project explores the prediction of house prices using Machine Learning.
By analyzing key housing features such as living area, number of bedrooms, and bathrooms, we aim to build models that can estimate a property’s sale price.

📂 Project Overview

Accurately predicting real estate prices is a challenging problem because many factors influence the value of a house. This project uses regression techniques to model these relationships, starting from simple Linear Regression to more advanced Polynomial Regression for capturing non-linear patterns.

The dataset includes structural features of houses, such as the number of rooms, bathrooms, and total living area. The target variable is the SalePrice of the property.

⚙️ Features Used

GrLivArea – Above ground living area (sq. ft.)

BedroomAbvGr – Bedrooms above ground

FullBath – Full bathrooms

HalfBath – Half bathrooms

SalePrice – Target variable (house price)

🧩 Methodology

Data Exploration & Cleaning

Checked for missing values.

Visualized distributions using histograms.

Studied feature relationships through a correlation heatmap.

Model Training

Linear Regression was applied as a baseline model.

Polynomial Regression was introduced to capture more complex, non-linear relationships.

Evaluation

Used Mean Squared Error (MSE) and R² Score to measure accuracy and goodness of fit.

📊 Results

Linear Regression

MSE: 2406406118.899142

R²: 0.2702 (weak fit)

Polynomial Regression

MSE: 2652050483.9419575

R²: 0.6588 (much stronger fit)

➡️ Polynomial regression demonstrated a significant improvement, showing that house prices are influenced by non-linear relationships between features.

📈 Visualizations

Histograms: Show feature distributions (living area, bathrooms, bedrooms, etc.).

Heatmap: Highlights correlations between variables.

✅ Key Insights

Living area (GrLivArea) shows a strong correlation with sale price.

Polynomial regression captures the complexity of housing data better than linear regression.
