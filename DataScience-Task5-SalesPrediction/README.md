# 📊 Sales Prediction Using Python

## Oasis Infobyte Data Science Internship — Task 5

This project focuses on analyzing the relationship between advertising expenditure and product sales and building Machine Learning models to predict sales.

The project was completed as part of my **Data Science Internship at Oasis Infobyte under the AICTE OIB-SIP program**.

---

## 🎯 Objective

The main objectives of this project are to:

- Analyze advertising expenditure across different media channels.
- Explore the relationship between advertising expenditure and sales.
- Perform Exploratory Data Analysis (EDA).
- Build regression models for sales prediction.
- Compare the performance of different Machine Learning models.
- Identify the relative importance of different advertising channels.
- Predict sales for new advertising expenditure values.

---

## 📂 Dataset

The dataset contains advertising expenditure across three different media channels along with the corresponding sales values.

### Features

| Feature | Description |
|---|---|
| `TV` | Advertising expenditure through TV |
| `Radio` | Advertising expenditure through Radio |
| `Newspaper` | Advertising expenditure through Newspaper |
| `Sales` | Corresponding sales value |

**Dataset:** `Advertising.csv`

---

## 🔍 Exploratory Data Analysis

The following analyses and visualizations were performed:

- Dataset structure and statistical analysis
- Missing value analysis
- Duplicate record detection
- Sales distribution
- TV Advertising vs Sales
- Radio Advertising vs Sales
- Newspaper Advertising vs Sales
- Pairplot
- Correlation heatmap
- Average advertising expenditure by channel

These visualizations were used to understand patterns and relationships between advertising expenditure and sales.

---

## 🤖 Machine Learning Models

Two regression models were implemented:

### 1. Linear Regression

Linear Regression was used as a baseline regression model to establish the relationship between advertising expenditure and sales.

### 2. Random Forest Regression

Random Forest Regression was implemented as an ensemble learning model capable of capturing more complex relationships between the input features and the target variable.

---

## 📊 Model Evaluation

The models were evaluated using the following metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

**Lower MAE indicates smaller prediction errors.**

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction errors and gives greater weight to larger errors.

**Lower RMSE indicates better performance.**

### R² Score

Measures how much of the variation in Sales is explained by the model.

**Higher R² generally indicates a better fit.**

---

## 📈 Model Comparison

The performance of Linear Regression and Random Forest Regression was compared using:

- MAE
- RMSE
- R² Score

The model with the higher R² score was identified as the better-performing model among the two tested models.

> **Note:** Exact evaluation values are available in the Jupyter Notebook output.

---

## 📌 Additional Analysis

### Actual vs Predicted Sales

An Actual vs Predicted plot was created to visually compare the model's predictions with the actual Sales values.

### Residual Analysis

Residuals were analyzed to understand the prediction errors and identify any visible patterns.

### Feature Importance

Random Forest feature importance was analyzed to understand the relative contribution of:

- TV
- Radio
- Newspaper

to the model's predictions.

---

## 🧪 Sample Prediction

The trained models were also used to predict Sales for a new advertising budget:

```text
TV        = 150
Radio     = 30
Newspaper = 20
