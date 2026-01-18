# Data Science Mastery
# 🚢 Titanic Survival Predictor (80.45% Accuracy)

A Machine Learning project analyzing passenger data from the Titanic to predict survival using a **Random Forest Classifier**.

## 📊 Key Insights
* **Social Class:** 1st and 2nd class children had a 91% survival rate, compared to only 37% in 3rd class.
* **Gender:** Being female was the strongest predictor of survival across all classes.
* **Economic Gap:** The fare distribution showed extreme outliers, with some tickets costing over $500 while others were free.

## 🤖 The Model
* **Algorithm:** Random Forest Classifier (Scikit-Learn)
* **Pre-processing:** Handled missing Age data, converted categorical variables (Sex) to numeric.
* **Performance:** Achieved **80.45% accuracy** on unseen test data.

## 🛠️ Project Structure
- `/data`: Raw and cleaned Titanic datasets.
- `/notebooks`: Exploratory Data Analysis and ML training.
- `/results`: Visualizations and model performance metrics.