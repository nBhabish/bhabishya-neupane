---
title: United States Natural Gas Demand Forecast
author: Bhabishya Neupane
date: '2022-02-08'
slug: []
excerpt: Forecasting monthly natural gas demand in the United States until 2023-01-01 (i.e. next 24 months based on the dataset in use)
categories:
  - R Shiny
  - timeseries forecasting
  - timetk
  - modeltime
tags: []
links:
- icon: door-open
  icon_pack: fas
  name: Application
  url: https://bhabishya-neupane.shinyapps.io/US-Natural-Gas-Demand-Forecast-Dashboard/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/nBhabish/US-Natural-Gas-Demand-Forecast
---

### About the Data

The data comes from `USgas` package by Rami Krispin, Data Science and Engineering Manager @Apple.

```toml
Please click the link above to view dashboard.
```
### Key Takeaways

- Out of all the models, `auto_arima()` gave us the best forecasting accuracy. 
- TBATS was the worse performing model. 
- Post-Forecast Diagnostics inform that most of the information was picked up by the fitted models.


### Improvisation

- Machine Learning models like XGBoost, or a combination of XGBoost and PROPHET could give us a better accuracy. XGBoost by itself is great a picking up patterns, but XGBoost when combined with PROPHET (given seasonality parameters are turned off for PROPHET), would be ideal at picking up multiple seasonalities. 
