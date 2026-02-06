# 📈 Advanced Time Series Analysis & Forecasting
Classical Econometrics, Volatility Models & Machine Learning

## 🔑 TL;DR (for recruiters)

- End-to-end time series analysis: from statistical diagnostics to portfolio decisions
- Classical econometrics (ARIMA, VAR, VECM, GARCH) + ML (LSTM, Prophet, RF)
- Strong focus on interpretability, validation, and economic meaning
- Real-world investment project (1st place, +25% return, 10% risk)


## 🧠 Project Overview

This repository contains a comprehensive applied study of time series analysis conducted during university practice.
The project covers the full spectrum of modern time series techniques — from classical statistical analysis to multivariate econometric models, volatility modeling, machine learning, and portfolio optimization.

The work is structured into three major analytical blocks and a competition-winning investment project, demonstrating both theoretical rigor and practical decision-making skills.

## 🗂 Repository Structure
```text
.
├── datasets/          # All raw datasets used across projects
│
├── Project1/         # Univariate time series analysis
│
├── Project2/         # Multivariate econometric models
│
├── Project3/         # Neural network & ML-based forecasting
│
└── Competition/      # Investment strategies & portfolio optimization
```

## 1️⃣ Project 1 — Univariate Time Series Analysis
### 🎯 **Task Description**

**Four different types of time series were selected from open data sources:**

    1. Stationary time series

    2. Non-stationary time series

    3. Time series with pronounced seasonality

    4. Stock price time series of a financial instrument

The key requirement was a clear understanding of the economic/statistical nature of each series.

### 🔬 Methods & Analysis

For each time series, the following steps were performed:

    * ACF and PACF analysis

    * Stationarity testing (ADF, KPSS)

    * Trend and seasonality decomposition (manual parameter selection)

    * Forecasting using:

        * Exponential smoothing (SES, Holt, Holt-Winters)

        * ARIMA / SARIMA (when applicable)

    * Interpretation of model parameters
    
    * Justification of cases where ARIMA/SARIMA could not be applied

    * Volatility modeling using heteroskedastic models (ARCH / GARCH family)

### 📌 All conclusions are strictly supported by statistical tests, metrics, and model diagnostics.

## 2️⃣ Project 2 — Multivariate Time Series Models
### 🎯 **Task Description**

**Multivariate modeling of financial assets:**

    * 3 sectors of the economy

    * 3 stocks per sector

    * Markets: Russian and US markets

**Forecast horizons:**

    * 10 trading sessions

    * 20 trading sessions

    * 100 trading sessions

### 🧠 Models Used

    * Vector Autoregression (VAR)

    * VAR with exogenous variables (VARMAX)

    * Vector Error Correction Model (VECM)

### 📊 Analytical Pipeline

    * Stationarity and transformation of series

    * Lag order selection

    * Cointegration testing (Johansen)

    * Model estimation

    * Rolling-window forecasting

    * Model comparison across horizons

    * Interpretation of interdependencies between assets

## 3️⃣ Homework 3 — Neural Networks & Machine Learning
### 🎯 **Task Description**

**Previously selected time series were analyzed using machine learning and neural network methods and compared against classical approaches.**

### 🤖 Models Used

    * Prophet

    * LSTM neural networks

    * Random Forest on autoregressive features

### 📈 Key Focus

    * Forecast accuracy comparison

    * Stability across horizons

    * Comparison with ARIMA / VAR / GARCH

    * Strengths and weaknesses of each approach

    * Situations where ML models outperform classical methods — and vice versa

## 🏆 Competition Project — Investment Strategies & Portfolio Optimization
### 🥇 Result

**1st place winner**

    * Initial capital: 1,000,000 ₽

    * Forecasted portfolio growth: +25%

    * Portfolio risk: ~10%

    * Methodology: Markowitz portfolio theory

### 📌 Project Description

**Three investment strategies were developed for a non-qualified investor:**

    * Conservative

    * Balanced

    * Aggressive

Markets:

    * Russian stock market

    * Cryptocurrency market

### 📊 Project Includes

    * Historical data analysis (stocks, bonds, crypto)

    * Risk, return, and correlation analysis

    * Portfolio construction

    * Forecasting asset prices (6 and 12 months)

    * Optimal portfolio selection using risk/return criteria

### 📤 Final Output

A ready-to-submit file in the format:
```text
Ticker, Quantity, Price_purchase
```

Along with a detailed analytical report containing:

    * Visualizations

    * Statistical justification

    * Investment conclusions

## 🛠 Tech Stack

    * Python

    * pandas, numpy

    * statsmodels

    * arch

    * scikit-learn

    * Prophet

    * TensorFlow / Keras

    * matplotlib, seaborn

    * Jupyter Notebook

## 🚀 Key Takeaways

    * End-to-end expertise in time series analysis

    * Strong statistical foundation with correct inference

    * Ability to justify model selection and rejection

    * Practical application of forecasting to investment decisions

    * Experience comparing classical and ML-based methods

## 🔍 Analytical Philosophy

    * This project follows a method-first analytical approach:

    * Models are selected only after statistical diagnostics

    * Each transformation is justified by tests, not intuition

    * If a model fails — the reason is explicitly analyzed and documented

    * Forecasting results are always interpreted in an economic context

#### 📌 *The goal is not to maximize accuracy at any cost, but to ensure interpretability and reliability.*

## 🧪 Model Selection & Validation Principles

Across all assignments, the following principles were applied:

    * Train/test splits respect time ordering

    * Rolling-window validation for realistic forecasting

    * Preference for simpler models when performance is comparable

    * Explicit comparison between classical econometrics and ML methods

#### 📊 Evaluation is based on both quantitative metrics and model diagnostics.

## ⚖️ Classical vs Machine Learning Models

This repository intentionally combines:

    * Classical time series models (ARIMA, VAR, VECM, GARCH)

    * Machine learning and neural networks (Prophet, LSTM, Random Forest)

Key insight:

    More complex models do not automatically outperform classical methods, especially on short or noisy financial time series.

This comparison highlights when and why each approach should be used.

## 📉 Risk Awareness & Practical Constraints

Particular attention is paid to:

    * Volatility clustering and heteroskedasticity

    * Stability of long-horizon forecasts

    * Overfitting risks in ML models

    * Investment constraints for non-qualified investors

These constraints reflect real-world analytical environments, not theoretical exercises.

## 🧭 How to Navigate This Repository

For quick review:

    * Start with `Project1/` to see statistical foundations

    * Continue with `Project2/` for multivariate dependencies

    * Review `Project3/` for ML comparison

    * Explore `Competition/` for a real-world investment application

📌 Each folder is self-contained and includes both code and interpretation.

## 💼 Why This Project Matters

This repository demonstrates the ability to:

    * Work with time series of different statistical nature

    * Choose and justify appropriate models

    * Combine theory with practical forecasting

    * Translate analytical results into investment decisions

    * Present complex analysis in a structured, reproducible way

## 🔁 Reproducibility & Extensibility

- All experiments are reproducible using the provided datasets
- Models can be extended to other financial instruments or markets
- The project structure allows easy comparison of new models

## 👤 Author

`Boris Cherkasov`  
BI / Data / Quantitative Analyst  

- **GitHub**: https://github.com/BorDch  
- **LinkedIn**: https://www.linkedin.com/in/boris-cherkasov-data-analyst-scientist/

