# Google Stock Market Analysis

A comprehensive Exploratory Data Analysis (EDA) and Machine Learning project on Google stock market data using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn. This project analyzes stock price trends, trading behavior, and predictive modeling for stock price forecasting.

---

# Project Overview

The project focuses on analyzing Google stock market data to understand:

- Stock price trends
- Market volatility
- Trading volume behavior
- Price movement patterns
- Correlation between stock variables
- Stock price prediction using regression models

The notebook includes both data analysis and machine learning techniques.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Dataset Features

The dataset includes:

- Date
- Open
- High
- Low
- Close
- Volume

---
## Data Preprocessing

The project performs:

- Date conversion  
- Missing value handling  
- Duplicate removal  
- Feature selection  
- Data formatting  
- Correlation analysis  

---

# Exploratory Data Analysis

## Visualizations Included

- Stock Closing Price Trend  
- Trading Volume Analysis  
- High vs Low Price Analysis  
- Daily Price Fluctuation  
- Correlation Heatmap  
- Moving Trend Visualization  
- Volatility Analysis  

---

# Machine Learning Models

The project includes:

## Multiple Linear Regression

Used for predicting stock closing prices using:

- Open  
- High  
- Low  
- Volume  

---

## Polynomial Regression

Applied to capture non-linear stock price trends.

---

## Decision Tree Regression

Used for improved prediction performance and non-linear relationships.

---

# Model Evaluation

Evaluation metrics used:

- R² Score  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

---

# Key Insights

- Open, High, and Low prices showed strong correlation with Closing price.  
- Trading volume varied significantly during volatile periods.  
- Decision Tree Regression provided better prediction accuracy compared to Linear Regression.  
- Polynomial Regression captured non-linear market trends more effectively.  

---

# Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
# Project Structure

```text
google_stock_analysis/
│
├── google_stock_data.ipynb
├── google_stock_dataset.csv
├── README.md
└── requirements.txt
