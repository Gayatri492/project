# calorie burnt prediction
# Calorie Burnt Prediction

This project predicts the number of calories burnt during physical activities based on various input features such as age, weight, height, duration, heart rate, and body temperature using machine learning models.

## Overview

Accurate calorie estimation is crucial for personalized health and fitness management. This project compares multiple regression models to identify the best approach for predicting calorie expenditure.

## Models Used

- **Linear Regression:** A simple baseline model to establish initial performance.
- **Support Vector Regressor (SVR):** Balances complexity and predictive power.
- **Random Forest Regressor:** An ensemble model that handles non-linear relationships effectively and achieved the highest accuracy.

## Results

- The **Random Forest Regressor** outperformed other models, achieving:
  - Mean Absolute Error (MAE): 2.36
  - Explained Variance: Over 99%
- Linear Regression provided a basic understanding but with lower accuracy.
- SVR offered a trade-off between model complexity and performance.

## Future Work

- Hyperparameter tuning for improved model performance
- Incorporation of more diverse features (e.g., activity type, environmental factors)
- Exploration of deep learning models for enhanced prediction accuracy

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/https://github.com/Gayatri492/project/calorie-burnt-prediction.git
