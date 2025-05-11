# UKvsUS_IndustrialProduction
Forecasting UK and US industrial output to explore what the next decade may look like and why the trends point that way.

This project analyzes and forecasts long-term trends in the Industrial Production Index (IPI) for the United Kingdom and the United States. Using historical data from 1948 to 2024, it evaluates how both economies have evolved, how they responded to major global economic shocks, and what their future trajectories might look like based on time series forecasting.

# Project Objectives
Analyze long-term IPI trends in the UK and US
Investigate the impact of four major global economic shocks
Normalize and compare IPI growth post-2007
Forecast IPI trends for the next decade using SARIMA
Explore sector-wise trends within UK industrial production

# Data Source
Monthly IPI data (1948–2024)
Sector wise - uk data
Sector wise-us data
Cleaned and processed: date formatting, missing value handling, grouped by year and month

# Methodology
Data Preparation
Converted date columns
Created Year and MonthYear features
Ensured data stationarity using the Augmented Dickey-Fuller test
# Modeling
Initial ARIMA forecasting
Explored and confirmed seasonality using decomposition
Applied SARIMA for final forecasting
Tuned seasonal and non-seasonal orders for better accuracy
# Comparison
Normalized data (2007 = 100) for both countries
Analyzed YoY and MoM percentage changes
Focused on critical periods: 1973 oil crisis, 1980–82 recession, 2008 financial crisis, and COVID-19 pandemic

# Key Insights
Long-Term Trends
From 1948 to 1990, the UK led in IPI performance
After 1990, the US began to catch up
Post-2008, the US overtook the UK and has continued to grow, while the UK plateaued

# Forecast Results
US industrial production is projected to maintain stable growth
UK industrial production is likely to remain flat or decline slightly unless structural changes are made

# UK Sector Analysis
Growth in pharmaceuticals and consumer non-durables
Decline in automotive manufacturing and energy supply
Stagnation post-Brexit and disruption from COVID-19 are visible in trends

# Tools and Libraries Used
Python (pandas, matplotlib, statsmodels)
Time series models: ARIMA, SARIMA
Statistical testing: ADF test
Visualization: trend and growth comparisons, decomposition plots


