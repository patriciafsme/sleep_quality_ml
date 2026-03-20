# Sleep Quality Prediction: A Supervised Learning Approach

## Project Overview
This project performs an in-depth statistical analysis to identify the key factors influencing **Sleep Quality**. Using a dataset of individual habits, health metrics, and stress indicators, we built and compared several predictive models to determine which variables (such as cholesterol, age, or bedtime) most impact rest.

## Methodology & Models
Implemented a multi-model approach in **R** to ensure robust results:
- **Exploratory Data Analysis (EDA):** Deep dive into correlations and data distributions.
- **Generalized Linear Models (GLM):** Ordinal and Multinomial Logistic Regression to understand baseline probabilities.
- **Decision Trees:** For non-linear relationship mapping.
- **Advanced Ensembles:**
  - **Random Forest:** To handle high-dimensional interactions and reduce overfitting.
  - **Gradient Boosting Machine (GBM):** Our champion model for high-accuracy classification.

## Key Findings
- **Feature Importance:** Bedtime, cholesterol levels, and stress index were identified as the primary predictors of sleep quality.
- **Model Performance:** The GBM model provided the highest Kappa index and accuracy, effectively handling the class imbalance in sleep categories.

## Tech Stack
- **Language:** R
- **Reporting:** Quarto / HTML / PDF
- **Key Libraries:** `caret`, `randomForest`, `gbm`, `ggplot2`, `dplyr`.

https://patriciafsme.github.io/sleep_quality_ml/sleep_quality_ml.html

---
*Project developed as part of the Applied Data Science degree (UCM).*
