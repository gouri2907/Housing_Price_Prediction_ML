# Housing Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting housing prices using machine learning techniques. The model uses property features such as location, built-up area, carpet area, BHK, property age, amenities, and other property-related factors.

## Objectives

- Perform data cleaning and preprocessing
- Perform Exploratory Data Analysis (EDA)
- Apply feature engineering
- Train different machine learning regression models
- Compare model performance
- Evaluate the final model on unseen test data
- Predict the price of a new property

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Machine Learning Models

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression

## Model Performance

| Model | MAE (Lakhs) | RMSE (Lakhs) | R² Score |
|---|---:|---:|---:|
| Linear Regression | 33.77 | 44.35 | 0.819 |
| Decision Tree | 29.46 | 40.78 | 0.847 |
| Random Forest | 27.43 | 37.49 | 0.871 |

## Final Model Evaluation

The Random Forest Regression model achieved:

- MAE: 27.43 Lakhs
- RMSE: 37.49 Lakhs
- R² Score: 0.871

## Feature Importance

Built-up area and locality tier were among the most influential features used by the Random Forest model.

## Sample Prediction

For a sample property, the trained model predicted:

**₹227.12 Lakhs (approximately ₹2.27 Crore)**

## Project Workflow

Dataset → Data Cleaning → EDA → Feature Engineering → Preprocessing → Model Training → Model Evaluation → Feature Importance → New House Price Prediction

## Dataset

The housing dataset was obtained from Kaggle and contains property-related information used for training and evaluating the machine learning models.

## Project Files

- `Housing_price_prediction.ipynb` — Complete machine learning implementation
- `README.md` — Project documentation
