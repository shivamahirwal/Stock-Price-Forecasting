# Stock-Price-Forecasting

This repository contains an analysis of ZEEL stock using data obtained from the BSE website, spanning the years 2010 to 2020. The primary objective was to examine patterns and potential seasonality within the stock's closing prices, utilizing them as the target variable for further analysis.

To accomplish this, datetime features were generated and plotted, providing valuable insights into the stock's behavior over time. In order to forecast future trends, the Prophet library was employed, utilizing historical data from the previous year. Two distinct forecasts were conducted: one for the period of 2016 to 2018 and another for 2019 to 2020.

The first forecast, covering 2016 to 2018, yielded a Mean Absolute Percentage Error (MAPE) of 15%, showcasing the model's accuracy in capturing the stock's behavior during this period. However, the second forecast, encompassing 2019 to 2020, resulted in a higher MAPE of 57%, indicating the affect of COVID-19 pandemic in accurately predicting the stock's performance during this timeframe.

By sharing this analysis, I aim to provide valuable insights into the ZEEL stock and contribute to the understanding of its historical behavior and forecasting potential.
