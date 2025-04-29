# Causality-of-Monetary-Policy-on-Unemployment-Rate
This project studies how the Federal Funds Rate causally impacts unemployment. Using FRED data and methods like Granger causality, VAR, cointegration, and SCMs, it quantifies how monetary policy affects employment, offering a rigorous, data-driven macroeconomic analysis.

### Experiment_1.ipynb Objective: Analyze the impact of monetary policy (specifically the Federal Funds Rate) on unemployment, aligned with CFA Level 1 curriculum.

Data Preparation:

Download monthly macroeconomic indicators (Federal Funds Rate, M2 Money Supply, CPI Inflation, GDP Growth, Unemployment) from FRED (starting 1960).

Adjust GDP (quarterly) to monthly frequency.

Handle missing values and compute percentage changes.

Visualization:

Plot macroeconomic indicators with multiple axes to highlight scale differences (GDP, Fed Funds Rate, Unemployment, M2, Inflation).

Time-Series Stationarity:

Applied log transformation and first differencing to stabilize variance and mean.

Used Augmented Dickey-Fuller (ADF) tests to confirm stationarity.

Key Techniques Introduced:

Safe log transformation

Differencing to achieve stationarity

Initial exploratory plots to understand trends before modeling

