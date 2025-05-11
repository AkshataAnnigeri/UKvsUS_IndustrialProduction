# UKvsUS_IndustrialProduction
Forecasting UK and US industrial output to explore what the next decade may look like and why the trends point that way.

This project analyzes and forecasts long-term trends in the Industrial Production Index (IPI) for the United Kingdom and the United States. Drawing on historical monthly data from 1948 to 2024, it examines how the industrial outputs of these two major economies have evolved over time, how they responded to significant global economic shocks, and what their projected trajectories look like based on statistical forecasting models.

The main objectives of the project were to understand the broader trends in IPI across both countries, assess the effects of key global disruptions, and forecast future performance using time series models. To achieve this, the dataset was first cleaned and prepared by formatting date columns and creating additional features such as Year and MonthYear for trend analysis. A stationarity check was performed using the Augmented Dickey-Fuller test, confirming that both UK and US time series were non-stationary and suitable for differencing.

The forecasting began with a baseline ARIMA model, which was later refined after detecting seasonality in the data. Seasonal decomposition confirmed consistent repeating patterns, leading to the application of a SARIMA model with seasonal parameters . The model was tuned to improve forecast accuracy and applied to generate ten-year projections.

To meaningfully compare the two countries, the data was normalized using 2007 as the base year (value set to 100), allowing growth trends to be evaluated independently of scale. The analysis particularly focused on four major global events—the 1973 oil crisis, the 1980–82 recession, the 2008 global financial crisis, and the COVID-19 pandemic—to understand how each economy was impacted and how they recovered over time.

The results showed a clear shift in industrial dynamics. Between 1948 and 1990, the UK consistently led the US in industrial output. However, from the 1990s onward, the US began to close the gap, eventually surpassing the UK following the 2008 crisis. Forecasts indicate that US industrial production will continue on a modest but stable growth trajectory over the next decade, while the UK’s IPI is expected to remain flat or decline slightly unless significant policy or structural changes are introduced.

A more detailed sector-level analysis of UK industries revealed that pharmaceutical manufacturing and consumer non-durables were among the few areas showing consistent growth. In contrast, automotive manufacturing and energy supply have experienced long-term stagnation or decline. Events like the Brexit referendum in 2016 and the COVID-19 pandemic in 2020–2021 further exacerbated the UK’s stagnation, while the US showed signs of resilience and post-crisis recovery in key sectors such as durable goods, mining, and manufacturing.

In summary, the 2008 financial crisis marked a key turning point. While the US economy recovered and continued to expand, the UK’s industrial output has yet to return to its pre-crisis levels. Unless there is a substantial shift in industrial policy or investment, the divergence is expected to persist, with the US maintaining a leadership position in industrial production through the next decade.

