# Quantitative-Analysis-Monte-Carlo-Price-Risk-Modeling-for-RY.TO
The Jump-Diffusion Model (JDM) is superior to Geometric Brownian Motion (GBM) for risk forecasting $\mathbf{RY.TO}$ by incorporating real-world crash risk.
This project implements and compares two stochastic models—Geometric Brownian Motion (GBM) and the Merton Jump-Diffusion Model (JDM)—to forecast the price path and calculate the downside risk (Value-at-Risk) for Royal Bank of Canada (RY.TO). The JDM is chosen as the superior model due to its ability to capture fat-tailed returns and non-continuous "jump" events common in equity markets.Asset: Royal Bank of Canada (RY.TO)Initial Price ($\mathbf{S_0}$): 204.12 CAD (as of 2025-10-31)Forecast Horizon: 1 Year (252 Trading Days)Key Finding: The JDM predicts a positive expected return but reveals a significant crash risk (95% VaR: $\mathbf{22.67\%}$) that the simpler GBM model fails to capture.




