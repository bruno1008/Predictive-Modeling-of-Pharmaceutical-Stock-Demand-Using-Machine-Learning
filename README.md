# Predictive-Modelling-of-Pharmaceutical-Stock-Demand-Using-Machine-Learning

## Overview

This repository contains a comprehensive project that applies machine learning techniques to predict pharmaceutical stock demand. Using an XGBoost regression model, the project demonstrates the potential for optimising inventory management in pharmacies through predictive analytics.

## Features

- **Synthetic Data Generation**: Simulates realistic pharmacy operations for one year, including customer profiles, medication preferences, and temporal patterns.
- **Advanced Feature Engineering**: Incorporates moving averages, frequency metrics, and seasonality effects to enhance predictive accuracy.
- **Model Training and Evaluation**: Employs XGBoost regression with hyperparameter tuning and cross-validation.
- **Visualisations**: Provides insights into model performance, residuals, and feature importance.

## Visual Insights

### Predicted vs. Actual Quantities
Predicted vs Actual

### Residual Analysis
Residual Plot

### Correlation Matrix
Correlation Matrix

## Usage

1. **Dataset Preparation**:
   - The dataset is synthetically generated to mimic pharmacy operations.
   - Includes features such as `Medicine`, `Pickup_Date`, `Quantity`, `Frequency`, and `Moving_Average`.

2. **Model Training**:
   - Utilises an XGBoost regressor with cross-validation for robust performance evaluation.
   - Hyperparameters are optimised for accuracy and generalisation.

3. **Prediction**:
   - Offers functionality to predict future stock requirements for specific medications on given dates.

4. **Visualisation**:
   - Graphical analysis of predicted vs actual quantities.
   - Residual plots and feature importance visualisations.

## Requirements

To replicate the analysis, ensure the following dependencies are installed:

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - matplotlib

## How to Run

1. Clone the repository and navigate to the project directory.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Execute the Jupyter notebook (`Predictive Modelling of Pharmaceutical Stock Demand Using Machine Learning.ipynb`) to generate synthetic data, train the model, and visualise results.
4. Use the provided functions to make predictions or analyse feature importance.

## Results Summary

The XGBoost regression model achieved:

- **R² Score**: 0.94
- **Root Mean Squared Error (RMSE)**: 0.09
- **Mean Absolute Error (MAE)**: 0.06

These metrics indicate a high level of predictive accuracy.

## Future Enhancements

Potential improvements include:

- Incorporating external factors such as weather or public health events.
- Comparing XGBoost with other machine learning models.
- Validating the model with real-world pharmacy datasets.

---

This project exemplifies how machine learning can transform inventory management in the pharmaceutical sector by enabling data-driven decision-making.
