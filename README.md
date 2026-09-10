# Farm Finance Guardian: Risk & Econometric Model

### 🌐 Live Interactive Dashboard: [Farm Finance Guardian Simulator](https://id-preview--692dba05-991f-4cb1-9dde-71908904cd41.lovable.app/)
### 💻 Backend Code: [View Google Colab Notebook Here] *(Note: Make sure to link your Colab file here!)*

## Project Overview
This project is an end-to-end econometric pipeline designed to quantify the bankruptcy risk of high-tech indoor farming facilities under extreme climate stress. By merging historical market data with satellite environmental telemetry, the model calculates the precise breaking point where operational HVAC costs outpace wholesale commodity pricing.

## Architecture & Data Ingestion
* **Market Data (Revenue):** Extracted and aggregated 2.3+ million rows of historical wholesale agricultural prices across five major regional hubs.
* **Climate Data (Risk):** Ingested 10 years of daily continuous Maximum Temperature and Cooling Degree Days (CDD) via satellite telemetry for target geographic zones.
* **ETL Pipeline:** Built a relational inner-join architecture using `pandas` to lock daily commodity pricing to exact localized environmental stressors.

## Econometric Methodology
To prove causality, the pipeline utilizes an Ordinary Least Squares (OLS) multivariable regression model (`statsmodels`). 

**The findings are statistically significant (p < 0.001):**
1. **Heat Penalty:** For every 1°C increase in max temperature, market price drops by ₹200.36.
2. **AC Reward:** For every unit of required cooling load, the market offers a ₹222.78 premium.
3. **The Bankruptcy Trap:** The net positive margin (₹22) during heatwaves is mathematically insufficient to cover the exponential spike in industrial HVAC electricity costs, proving the high insolvency rate of distressed vertical farming assets.

[https://id-preview--692dba05-991f-4cb1-9dde-71908904cd41.lovable.app/](https://id-preview--692dba05-991f-4cb1-9dde-71908904cd41.lovable.app/)
