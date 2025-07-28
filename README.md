# Risk–Return Analysis of Tech Stocks (2015–2023)

A data-driven exploration of the trade-off between risk and return for five major tech giants — Apple (AAPL), Microsoft (MSFT), Netflix (NFLX), Amazon (AMZN), and Google/Alphabet (GOOGL) — using historical stock data from 2015 to 2023.

## Overview

This project investigates:

- Monthly and annualised returns
- Volatility (standard deviation of returns)
- Sharpe Ratios (risk-adjusted returns)
- Stock behaviour during COVID-19 (2019–2021)

By visualising these metrics and comparing them across time, we identify which stocks delivered the best value for risk-tolerant vs. risk-averse investors.

## Tools and Methods

- Python (pandas, numpy, matplotlib, seaborn, yfinance)
- Excel for tabulations and dashboards
- Key Metrics:
  - Monthly returns from adjusted closing prices
  - Annualised return = average monthly return × 12
  - Annualised volatility = standard deviation × √12
  - Sharpe Ratio = (Return − Risk-Free Rate) ÷ Volatility  
    (Assumed risk-free rate = 3%)

## Key Insights

- Best Risk-Adjusted Performer: Microsoft (MSFT) – Sharpe ≈ 1.21  
- Highest Raw Return: Netflix (NFLX) – ~32.6% p.a., but most volatile  
- COVID-19 Volatility:
  - Volatility spiked for most stocks in 2020
  - Apple had the largest increase (0.24 → 0.40)
  - Netflix surprisingly became calmer (0.37 → 0.20)

## Investor Personas

| Persona           | Strategy                        | Suggested Stock(s)     |
|-------------------|----------------------------------|-------------------------|
| Cautious Carla    | Low risk, steady returns         | MSFT, GOOGL             |
| Balanced Ben      | Growth with some risk            | AAPL, AMZN              |
| Adrenaline Alex   | High return, high risk tolerance | NFLX (small position)   |

## Project Structure:

-  Summary_Dashboard.xlsx # Summary stats and visuals
-  Tech_RiskReturn_Summary.pdf # PDF report with key findings
-  risk_return_analysis.ipynb # (To be added) Full Python workflow
-  README.md # Project overview


## Author

**Ayo Ososanya**  
Final-Year Economics Student | Data Enthusiast | Private Tutor  
Passionate about data, finance, and education. Building a portfolio to break into data analysis roles.

