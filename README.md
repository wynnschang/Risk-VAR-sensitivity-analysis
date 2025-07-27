# Risk-VAR-sensitivity-analysis

Risk Analysis: Portfolio VaR Estimation (SOFR Swap + Equities)

calculation of 1-day 95% Value at Risk (VaR) for a mixed portfolio consisting of:

Four US equities: AAPL, MSFT, F (Ford), BAC
One 10Y USD SOFR interest rate swap (payer: pay fixed, receive floating)
Using one year of historical data (2022-10-31 to 2023-10-30), we compute VaR as of 30/10/2023 under three commonly used approaches:

Models Implemented
Parametric VaR (variance-covariance method)
Monte Carlo VaR
Full revaluation
