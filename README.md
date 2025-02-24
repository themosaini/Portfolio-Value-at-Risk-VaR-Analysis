# Portfolio-Value-at-Risk-VaR-Analysis
📌 Overview

This project implements Value at Risk (VaR) Analysis for a portfolio of stocks using three different methods:

Historical VaR

Parametric VaR (Normal Distribution Assumption)

Monte Carlo Simulation

Additionally, it calculates Conditional VaR (Expected Shortfall) and performs Stress Testing to assess market downturn risks.

🚀 Features

✅ Fetches real-time stock data using Yahoo Finance API (yFinance)✅ Computes VaR & CVaR for a multi-asset portfolio✅ Uses 10,000+ Monte Carlo simulations for risk estimation✅ Visualizes return distributions and risk thresholds using Matplotlib & Seaborn✅ Implements Stress Testing with market shock simulations

📊 Example Output

Portfolio VaR (95% Confidence):
Historical VaR: -0.0152
Parametric VaR: -0.0138
Monte Carlo VaR: -0.0145
--------------------------------------
Conditional VaR (Expected Shortfall):
Historical CVaR: -0.0213
Parametric CVaR: -0.0198
Monte Carlo CVaR: -0.0205
Stress Test VaR (5% Market Drop): -0.0251

🤝 Contributing

Feel free to open an issue or submit a pull request if you have suggestions for improvement!
