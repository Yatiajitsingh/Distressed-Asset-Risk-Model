# Farm Finance Guardian: Econometric Risk Model

### 🌐 Live Interactive Dashboard: [Farm Finance Guardian Simulator](https://id-preview--692dba05-991f-4cb1-9dde-71908904cd41.lovable.app/)
### 💻 Backend Code: [View Google Colab Notebook Here]

## Project Overview
An end-to-end quantitative risk model built to evaluate the financial insolvency rates of controlled-environment agricultural assets under severe climate shocks. 

## Data Architecture & Scale
* **Market Telemetry:** Aggregated and cleaned over 2.3 million rows of wholesale transaction records across 5 distinct regional hubs.
* **Climate Shocks:** Ingested 10 years of continuous satellite data (NASA POWER) to track localized extreme weather events.
* **ETL Pipeline:** Engineered a highly performant relational join, locking daily asset pricing to exact environmental stress parameters.

## Causal Econometric Analysis
* Deployed an Ordinary Least Squares (OLS) multivariable regression to isolate the causal impact of market disruptions.
* **Heat Penalty:** Quantified that a 1°C ambient spike causally drives a ₹200.36 drop in wholesale valuation (p < 0.001).
* **AC Premium:** Determined the market only yields a ₹222.78 premium for peak cooling loads, mathematically confirming the bankruptcy trap.

## Uncertainty Quantification
* Modeled variance and tail-risk by calculating a 95% Confidence Interval for all climate-induced market shocks.
* Integrated strict p-value significance testing to filter out market noise and validate the core financial thesis.
