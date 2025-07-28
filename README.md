Risk–Return Analysis of Tech Stocks (2015–2023)
A data-driven exploration of the trade-off between risk and return for five major tech giants — Apple (AAPL), Microsoft (MSFT), Netflix (NFLX), Amazon (AMZN), and Google/Alphabet (GOOGL) — using historical stock data from 2015 to 2023.

Overview
This project investigates:

Monthly and annualised returns

Volatility (standard deviation of returns)

Sharpe Ratios (risk-adjusted returns)

Stock behaviour during COVID-19 (2019–2021)

By visualising these metrics and comparing them across time, we identify which stocks delivered the best value for risk-tolerant vs. risk-averse investors.

Tools & Methods
Python (pandas, numpy, matplotlib, seaborn, yfinance)

Excel for basic tabulations and summaries

Financial Statistics

Monthly returns computed from adjusted closing prices

Annualised return = mean monthly return × 12

Annualised volatility = std dev of monthly return × √12

Sharpe ratio = (return − risk-free rate) / volatility

Key Insights
Best Risk-Adjusted Performer: Microsoft (MSFT) had the highest Sharpe Ratio (~1.21), meaning investors got more return for each unit of risk.

Highest Raw Return: Netflix (NFLX) led with ~32.6% annual return, but also had the highest volatility (~42.5%), lowering its risk-adjusted appeal.

COVID-19 Volatility: Volatility jumped for most stocks in 2020, but Netflix surprisingly became calmer due to predictable lockdown demand.

Investor Personas
Cautious Carla – wants safety: MSFT or GOOGL

Balanced Ben – growth with balance: AAPL or AMZN

Adrenaline Alex – chases high returns: NFLX (but with caution)

Project Structure
bash
Copy
Edit
.
├── Summary_Dashboard.xlsx       # Summary stats and visuals
├── Tech_RiskReturn_Summary.pdf # PDF report with insights & visuals
├── risk_return_analysis.ipynb  # (To be added) Full Python workflow
└── README.md                   # Project overview
Next Steps
 Upload Jupyter Notebook with Python code

 Add interactive charts (optional: Plotly or Power BI)

 Expand dataset to include non-tech sectors or post-2023 data

Author
Ayo Ososanya
Final-Year Economics Student | Data Enthusiast | Tutor
Currently building a portfolio in finance & education analytics to break into data analysis roles.

