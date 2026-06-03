# House Price Prediction using Machine Learning

## Overview

House Price Prediction is a machine learning project that predicts housing prices based on various numerical features such as crime rate, number of rooms, tax rate, age of the property, and neighborhood-related factors.

This project demonstrates the complete machine learning workflow including data preprocessing, feature scaling, regression modeling, evaluation, and prediction using Linear Regression.

---

## Objective

The objective of this project is to predict house prices using numerical housing features and analyze how different factors influence pricing.

---

## Dataset

This project uses the **Boston Housing Dataset** from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/vikrishnan/boston-house-prices

### Dataset Features

The dataset contains several housing-related features including:

* CRIM → Crime rate by town
* ZN → Residential land zoning proportion
* INDUS → Non-retail business acres proportion
* CHAS → Charles River dummy variable
* NOX → Nitric oxide concentration
* RM → Average number of rooms per dwelling
* AGE → Proportion of older houses
* DIS → Distance to employment centers
* RAD → Accessibility to highways
* TAX → Property tax rate
* PTRATIO → Student-teacher ratio
* B → Demographic-related feature
* LSTAT → Lower status population percentage
* MEDV → Median house price (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Model Used

### Linear Regression

Linear Regression was used to predict house prices based on multiple numerical input features.

---

## Project Workflow

1. Import required libraries
2. Load and clean dataset
3. Perform exploratory data analysis (EDA)
4. Visualize feature distributions and relationships
5. Handle preprocessing and normalization
6. Split dataset into training and testing sets
7. Train Linear Regression model
8. Evaluate performance using regression metrics
9. Predict house prices for new data

---

## Data Visualization

The following visualizations were used:

* Correlation Heatmap
* Feature Distribution Histograms
* House Price Distribution
* Rooms vs House Price Scatter Plot
* Actual vs Predicted Price Plot

These visualizations help understand relationships between housing features and pricing.

---

## Model Evaluation

The model performance was evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics measure prediction accuracy and model performance.

---

## Example Prediction

### Input Features

* Rooms (RM): 6.5
* Crime Rate (CRIM): 0.03
* Property Tax (TAX): 242
* Distance to Employment Centers (DIS): 4.5

### Predicted Output

Predicted House Price: 23.5

---

## Expected Results

The model generally achieves a good prediction performance with:

* R² Score ≈ 0.70+
* RMSE ≈ 4–5

Predicted prices are generally close to actual values.

---

## Skills Gained

* Regression modeling
* Data preprocessing
* Feature scaling
* Exploratory Data Analysis (EDA)
* Model evaluation using regression metrics
* House price prediction

---

## Conclusion

This project demonstrates how machine learning can be applied to predict house prices using numerical features. It provides practical experience in regression modeling, feature engineering, preprocessing, visualization, and performance evaluation using Python and Scikit-learn.
