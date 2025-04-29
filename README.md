# Causality-of-Monetary-Policy-on-Unemployment-Rate
This project studies how the Federal Funds Rate causally impacts unemployment. Using FRED data and methods like Granger causality, VAR, cointegration, and SCMs, it quantifies how monetary policy affects employment, offering a rigorous, data-driven macroeconomic analysis.

## Experiment_1.ipynb 

* Objective: Analyze the impact of monetary policy (specifically the Federal Funds Rate) on unemployment, aligned with CFA Level 1 curriculum.

* Data Preparation:

Download monthly macroeconomic indicators (Federal Funds Rate, M2 Money Supply, CPI Inflation, GDP Growth, Unemployment) from FRED (starting 1960).

Adjust GDP (quarterly) to monthly frequency.

Handle missing values and compute percentage changes.

* Visualization:

Plot macroeconomic indicators with multiple axes to highlight scale differences (GDP, Fed Funds Rate, Unemployment, M2, Inflation).

* Time-Series Stationarity:

Applied log transformation and first differencing to stabilize variance and mean.

Used Augmented Dickey-Fuller (ADF) tests to confirm stationarity.

* Key Techniques Introduced:

Safe log transformation

Differencing to achieve stationarity

Initial exploratory plots to understand trends before modeling

## Experiment_2.ipynb 
* Objective: Perform causal analysis between monetary policy and economic outcomes using more formal statistical tests.

Analysis Steps:

* Granger Causality Tests:

Tests if the Federal Funds Rate predicts GDP and Unemployment.

Found strong Granger causality from the Federal Funds Rate to Unemployment, weaker to GDP.

* Johansen Cointegration Test:

Tested long-term relationships between Federal Funds Rate, M2 Money Supply, and GDP.

Found strong evidence of cointegration (long-run equilibrium exists).

* VAR (Vector Autoregression) Modeling:

Modeled dynamic interactions among FEDFUNDS, M2, GDP, and Unemployment.

Selected optimal lag using AIC.

* OLS Regression:

Modeled the direct effect of FEDFUNDS on Unemployment, controlling for GDP, M2, and Inflation.

Summarized model significance and coefficients.

* Key Techniques Introduced:

Granger causality interpretation

Johansen cointegration for long-term relationships

VAR modeling for dynamic systems

OLS for controlled regression analysis



