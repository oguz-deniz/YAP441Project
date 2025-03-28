# Stock Price Prediction: Conventional AI vs. Machine Learning

This repository contains the code and data for a comprehensive study comparing conventional Artificial Intelligence (AI) methods with state-of-the-art Machine Learning (ML) models for stock price prediction. The project focuses on predicting the stock price movements of Bank of America (BAC) using time series data from 2005 to 2022, sourced from Yahoo Finance.

## Overview

The project explores a variety of approaches:

- **Conventional AI Methods**  
  - **Statistical-Stochastic Techniques:**  
    - Hidden Markov Models (HMMs) and Gaussian Mixture Model HMMs (GMMHMMs)
    - Monte Carlo Simulation
    - GARCH Models
  - **Metaheuristic Algorithms:**  
    - Genetic Algorithm (GA)
    - Colony Optimization (CO)
  - **Agentic Trade Strategies:**  
    - 13 tradebot agents with distinct buy-sell strategies

- **Machine Learning Models:**  
  - ARIMA
  - Prophet

The evaluation of these methods is based on various financial and statistical metrics, including directional accuracy, mean squared error (MSE), mean absolute error (MAE), and more.

## Project Highlights
- Comprehensive Comparison:
The project benchmarks conventional AI methods against ML models, offering insights into trade-offs between computational efficiency and prediction accuracy.

- Conventional Methods Efficiency:
Techniques such as HMMs, Monte Carlo Simulation, and GARCH provide efficient and robust forecasting with lower computational overhead.

- ML Models for Accuracy:
ARIMA and Prophet models, although more computationally demanding, deliver higher short-term prediction accuracy, particularly for immediate forecasts.

- Agentic Strategies:
A set of 13 tradebot agents demonstrates that the optimal trading strategy depends on investor risk appetite and market conditions. Notably, a 50/20-day moving average crossover strategy (Strategy 7) showed the highest long-term profitability, despite higher portfolio volatility.
## Repository Structure

- **13StrategyAnalysis.ipynb**  
  Analysis and evaluation of the 13 tradebot agent strategies.
  
- **ARIMAandProphet.ipynb**  
  Implementation and evaluation of the ARIMA and Prophet models.
  
- **GARCH.ipynb**  
  Implementation of GARCH models for volatility forecasting.
  
- **markov_models.ipynb**  
  Implementation of Hidden Markov Models (HMMs) for stock prediction.
  
- **markov_models2.ipynb**  
  Additional HMM model variations, including experiments with different state configurations and technical indicators.
  
- **metaheuristics.ipynb**  
  Implementation and evaluation of metaheuristic algorithms (GA and CO).
  
- **MonteCarloSimulation.ipynb**  
  Implementation of the Monte Carlo Simulation approach for probabilistic forecasting.
  
- **BAC.csv**  
  The dataset containing historical time series data of BAC stock.
  
- **requirements.txt**  
  List of required Python packages.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/stock-prediction-ai-ml.git
   cd stock-prediction-ai-ml

2. **Install the required packages:**
  ```bash
   pip install -r requirements.txt

