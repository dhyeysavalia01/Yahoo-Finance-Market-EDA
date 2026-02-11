# 📈 Stock Price Analysis & Multiple Linear Regression

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** and applies **Multiple Linear Regression** to model stock price behavior.  

The objective is to:
- Understand relationships between price variables and volume
- Engineer meaningful financial features
- Compare **sklearn Linear Regression** with a **custom Batch Gradient Descent implementation**

---
###  👉[click here for dataset](https://www.kaggle.com/datasets/suruchiarora/yahoo-finance-dataset-2018-2023)
## 📊 Dataset Features

- **Date**
- **Open**
- **High**
- **Low**
- **Close**
- **Adj Close**
- **Volume**

The dataset represents historical stock price data over a continuous time period.

---

## 🔎 Exploratory Data Analysis

EDA includes:

- Data cleaning and validation
- Statistical summaries
- Correlation analysis
- Multicollinearity check
- Feature engineering:
  - Daily Range (High − Low)
  - Daily Return
  - Moving Averages
  - Rolling Volatility
- Stationarity checks
- Autocorrelation analysis

The goal is to prepare a robust feature set for regression modeling.

---

## 🤖 Modeling Approach

Two regression methods are implemented:

### 1️⃣ Sklearn Mulitple Linear Regression
- Closed-form Ordinary Least Squares solution
- Baseline benchmark model

### 2️⃣ Custom Batch Gradient Descent
- Manual implementation of:
  - Cost function (MSE)
  - Gradient computation
  - Weight updates
- Used to understand convergence behavior
- Demonstrates importance of feature scaling

---

## 📈 Evaluation Metrics

- R² Score  
- Mean Squared Error (MSE)  
- Coefficient comparison  
- Convergence analysis (loss curve)

---

## 🧠 Key Learning Outcomes

- Practical understanding of EDA for financial data
- Handling multicollinearity in regression
- Feature scaling impact on Gradient Descent
- Difference between analytical and iterative optimization
- Preventing data leakage in time-series modeling

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run notebook or script