# Effects of EV Sales on Gasoline Prices in India

Project for the **Time Series Analysis and Forecasting** course (ECO 319/619). It studies how electric vehicle (EV) sales affect gasoline prices in India, using monthly data from January 2015 to June 2025.

## What I did
- Used five monthly series: EV sales, gasoline price (INR), exchange rate, Brent crude oil price (INR) and CPI.
- Created four dummy variables for policy and shock periods: FAME 1, FAME 2, COVID-19 and the Russia–Ukraine war.
- Ran ADF unit root tests, Bayesian VAR (BVAR), Granger causality tests and impulse response functions.
- Produced **forecasts** for all variables.

## Key findings
- Gasoline prices Granger-cause EV sales (p = 0.042), but EV sales do not Granger-cause gasoline prices (p = 0.430).
- The effect of EV sales on gasoline prices is small and short-lived. Gasoline prices are driven mainly by Brent crude, the exchange rate, CPI and their own past values.
- The FAME 1 and FAME 2 policies boosted EV sales, especially FAME 2, with almost no effect on gasoline prices.
- Forecasts show EV sales staying stable with possible steady growth, and other variables staying stable.

## Files
| File | Description |
|---|---|
| `EVSales_dataset.xlsx` | Monthly dataset (Jan 2015 – Jun 2025) |
| `RajhansAditi_22252_Code.pdf` | R code and output: tests, BVAR, Granger causality, IRF, FEVD and forecasting |
| `RajhansAditi_22252_Report.pdf` | Full project report: introduction, literature review, methodology, results and conclusion |

## Tools Used
R (vars, BVAR, forecast, tseries, urca, lmtest, ggplot2, dplyr, readxl)
