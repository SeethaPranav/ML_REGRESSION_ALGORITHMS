# ML_REGRESSION_ALGORITHMS
Regression analysis on the California Housing dataset using multiple algorithms to predict house prices and evaluate model performance.

# California Housing Price Prediction: Regression Models

This project demonstrates the application of various regression techniques to predict housing prices in California using the California Housing dataset from sklearn. The dataset contains information about various features of houses in California and their respective median house values.

# Project Overview

The goal of this project is to implement and evaluate several regression algorithms on the California Housing dataset to predict median house prices. The following regression models are tested and compared:

  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
  * Gradient Boosting Regressor
  * Support Vector Regressor (SVR)
    
## Key Steps:

  * Data Preprocessing: The dataset is loaded, missing values (if any) are handled, and features are standardized for consistent scaling across models.
  * Model Training: Five different regression algorithms are implemented and trained on the preprocessed dataset.
  * Model Evaluation: The models are evaluated using key metrics such as:
        Mean Squared Error (MSE)
        Mean Absolute Error (MAE)
        R-squared (R²) score
    
  * Comparison: The performance of each model is compared, with a focus on predictive accuracy and the ability to explain variance in the target variable (house prices).
    
## Results:

The Random Forest Regressor outperforms all other models, demonstrating superior predictive accuracy, lower error rates, and a higher ability to explain variance in house prices. Linear Regression performed the worst, as it struggled to capture the non-linear relationships in the dataset.

# Conclusion:

 * Best Model: Random Forest Regressor – Offers the highest predictive accuracy and handles complex non-linear relationships.

 * Worst Model: Linear Regression – Assumes a linear relationship and fails to capture the non-linear patterns in the data effectively.
