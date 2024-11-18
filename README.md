# Stock Price Prediction and Portfolio Risk Analysis

This project combines machine learning and financial analysis to forecast stock prices and assess portfolio risk. Specifically, we build a predictive model for SOFI stock prices using historical data and conduct a portfolio risk analysis with a focus on optimizing returns.

## Project Overview

### Objectives

- **Stock Price Prediction**: Develop a machine learning model to predict future SOFI stock prices.
- **Portfolio Risk Analysis**: Use financial analysis methods to evaluate and optimize a diversified portfolio.

### Key Results

- **SOFI Stock Price Prediction**: Achieved a Mean Squared Error (MSE) of 0.55 on the test set using a Random Forest Regressor, indicating high predictive accuracy.
- **CAPM Analysis**: Calculated an alpha of 0.0013 and beta of -0.002 with the Nasdaq, and an alpha of 0.0013 and beta of -0.005 with the S&P 500, providing insights into risk-adjusted returns and sensitivity to market movements.

## Methodology

### 1. Data Collection and Preprocessing
   - Collected historical stock data for SOFI using `yfinance` to train the machine learning model.
   - Acquired portfolio data for the risk analysis, focusing on assets relevant to the CAPM evaluation.

### 2. Stock Price Prediction using Machine Learning
   - Built a Random Forest Regressor model to predict SOFI stock prices based on historical features.
   - Optimized model hyperparameters to minimize Mean Squared Error (MSE), achieving a test MSE of 0.55.

### 3. Portfolio Risk Analysis
   - Conducted Monte Carlo simulations to explore different portfolio allocations and risk scenarios.
   - Used the Capital Asset Pricing Model (CAPM) to calculate the portfolio's alpha and beta relative to the Nasdaq and S&P 500 indices, providing insights into expected returns and market sensitivity.

## Technical Stack

- **Programming Language**: Python
- **Libraries**:
  - **Machine Learning**: `scikit-learn` (Random Forest)
  - **Data Analysis**: `pandas`, `numpy`
  - **Financial Analysis**: `yfinance`, `scipy`
  - **Visualization**: `matplotlib`
- **Concepts**: Random Forest Regression, Monte Carlo Simulation, CAPM (Capital Asset Pricing Model)
