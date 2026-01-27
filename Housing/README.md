# 🏡 Ames Housing Price Predictor (Linear Regression)

## 🎯 Project Overview
A machine learning project to predict residential home prices in Ames, Iowa. This project transitions from raw data auditing to a refined linear regression model.

## 🛠️ Data Architecture & Mastery
This project followed a strict "Data First" approach:
- **Technical Audit:** Handled missing values through group-based imputation (Neighborhood/LotFrontage).
- **Multicollinearity Control:** Identified and removed redundant features (e.g., GarageArea, 1stFlrSF).
- **Target Normalization:** Applied Log-Transformation to `SalePrice` to fix right-skewness.
- **Feature Engineering:** - `SqFtPerRoom`: Measuring house density.
    - `EffectiveAge`: Capturing the impact of remodeling on value.
    - `One-Hot Encoding`: Quantifying the "Location Premium" of neighborhoods.

## 📈 Model Performance
- **Algorithm:** Linear Regression
- **R-Squared:** [Your Final R2]% 
- **Average Error (MAE):** $[Your Final Dollar Error]