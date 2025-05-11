# 🏡 House Price Prediction using Linear Regression

This project predicts house prices based on various features of homes and neighborhoods using linear regression. It includes data collection, preprocessing, exploratory analysis, model building, and evaluation.

## 📁 Contents

1. [Data Collection](#1-data-collection)  
2. [Data Preprocessing](#2-data-preprocessing)  
3. [Exploratory Data Analysis](#3-exploratory-data-analysis)  
4. [Model Building](#4-model-building)  
5. [Evaluation](#5-evaluation)

---

## 1. Data Collection

- Loaded the Boston Housing dataset using pandas.
- Dataset includes 14 variables such as crime rate, number of rooms, tax rate, distance to employment centers, etc.

### Key Features:
- `crim`: Crime rate by town  
- `rm`: Average number of rooms per dwelling  
- `lstat`: % of lower status population  
- `medv`: Median house value (target variable)  
- And more...

---

## 2. Data Preprocessing

- Checked for missing values.
- Identified and handled missing entries in the `rm` (rooms) column.
- Visualized the distribution of the `rm` variable using `seaborn`.

---

## 3. Exploratory Data Analysis

- Plotted correlation heatmap to understand feature relationships.
- Investigated how `rm`, `lstat`, and `ptratio` relate to `medv` using scatter plots and pairplots.
- Assessed skewness and kurtosis of key variables.

---

## 4. Model Building

- Split the dataset into training and testing sets.
- Built a **Linear Regression** model using `scikit-learn`.
- Trained the model on the training set and predicted values for the test set.

---

## 5. Evaluation

- Calculated R-squared value and mean squared error (MSE) to evaluate the model.
- Plotted actual vs. predicted house prices to visualize accuracy.

---

## 📦 Requirements

- Python 3.x  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

Install them using:
```bash
pip install pandas matplotlib seaborn scikit-learn
