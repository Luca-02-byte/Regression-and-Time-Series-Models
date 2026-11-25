# Regression and Time-Series Models

*Regression and Time Series Models* course projects, using Python.

## Homework 1: Linear Regression and the CAPM on U.S. Banks
CAPM estimation on 14 U.S. banks from the STOXX North America 600 Banks index (November 2009 – November 2024), individually and as a portfolio.
- Diagnostic tests: RESET, Breusch-Godfrey, White, HAC-robust estimation
- Structural breaks: Chow test
- Time-varying alpha and beta: rolling-window estimation
- Multifactor extension: SMB, HML, RMW, CMA (Kenneth French Data Library) and the U.S. unemployment rate (BLS), with Ljung-Box and Breusch-Pagan residual tests

Report: `hw1_capm_us_banks.pdf`

## Homework 2: Time Series Modelling on Spain
Daily and monthly analysis of the IBEX35 total return index, three stocks (Inditex, Iberdrola, Banco Santander) and four macro indicators (IPI, CPI, 10-year yield, unemployment), January 2010 – December 2024.
- Log transformation, returns and volatility
- Stationarity: Augmented Dickey-Fuller test and first differencing
- ARMA(p, q) identification via ACF/PACF and AIC, residual diagnostics with Ljung-Box
- Rolling-window out-of-sample forecasts (last 2 years monthly, last 6 months daily)

Report: `hw2_time_series_spain.pdf`

## Data
Data were downloaded from Refinitiv and are not included in this repository.
