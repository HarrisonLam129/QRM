In the first project, we perform statistical analysis on the EURO STOXX 50 (SX5E) index and fit time series models (GARCH and ARMA-GARCH) to the daily log returns, which are evaluated using residual diagnostic plots.  
We also compare several forecasting methodologies for the one-day-ahead Value-at-Risk (VaR) and Expected Shortfall for the ProShares Short Dow30 (DOG) ETF.
We consider the Historical Simulation (HS), Filtered Historical Simulation with EWMA (FHS-EWMA) and Filtered Historical Simulation with GARCH (FHS-GARCH) methods.
Using backtesting for VaR (unconditional and joint) and ES, we conclude that the FHS-EWMA and FHS-GARCH methods produce results that are more consistent with the model assumptions.
However, the FHS-EWMA method performs slightly better in terms of p-value under the joint coverage test, and is preferred when volatility is highly clustered.

In the second project, we perform statistical analysis on the Tesla (TSLA) stock and fit a GARCH model to the negative log-returns.  
The standardised residuals are also fitted to the t-distribution and the generalised Pareto distribution, and we observe a close fit of the GPD to the empirical excess distribution.
By evaluating VaR and ES forecasts under each model, we conclude that the Student-t and GPD innovations provide more robust forecasts and is more effective as a risk management tool.
