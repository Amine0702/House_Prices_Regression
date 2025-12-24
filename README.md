# House Prices Prediction using Linear Regression

## Short Description
This project predicts house prices using simple and multiple linear regression. 
The goal is to analyze the dataset, build regression models, and evaluate their performance.

## Objective
- Predict the target variable (house price) from various features.
- Apply both **simple regression** (on `Age`) and **multiple regression** (all features).
- Evaluate the models using **MSE** (Mean Squared Error) and **R² score**.
- Visualize correlations between features and predicted vs actual prices.

## Dataset
- File: `maisons.xlsx`
- Contains multiple features such as Age, Latitude, Longitude, etc.
- Data cleaning: removed unnecessary columns (`Date`, `No`) and handled binarization of Latitude and Longitude.

## Tools & Libraries
- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn (LinearRegression, train_test_split, metrics)
- matplotlib, seaborn

## Methodology / Steps
1. Load Excel dataset
2. Remove unnecessary columns
3. Binarize Latitude and Longitude columns
4. Split data into features (X) and target (y)
5. Split data into training and test sets
6. Train **Simple Linear Regression** on `Age`
7. Predict and evaluate performance (MSE & R²)
8. Train **Multiple Linear Regression** on all features
9. Predict and evaluate performance on test set
10. Display regression coefficients
11. Plot correlation heatmap of features

## Results
- Simple Regression:
  - MSE: ...
  - R²: ...
- Multiple Regression:
  - MSE: ...
  - R²: ...
- Scatter plots and heatmaps illustrate the relationships between features and target variable.

## GitHub Repository
[Link to project](https://github.com/Amine0702/Linear_Regression_Project)
