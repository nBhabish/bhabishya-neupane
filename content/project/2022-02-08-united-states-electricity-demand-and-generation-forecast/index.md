---
title: United States Electricity Demand and Generation Forecast
author: R package build
date: '2022-02-08'
slug: []
excerpt: Forecasting daily electricity demand and generation forecast in the United States until 2023.
categories:
  - timeseries forecasting
  - machine learning
  - R Shiny
  - timetk
  - modeltime
tags: []
links:
- icon: door-open
  icon_pack: fas
  name: Application
  url: https://bhabishya-neupane.shinyapps.io/US-Electricity-Forecast/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/nBhabish/US-Electricity-Forecast
---

### About the Data

The data comes from [Rami Krispin's GitHub](https://www.linkedin.com/in/rami-krispin/). By no means, I am trying to take credit for how much he has contributed as an open source contributor. 99.99 % of heavylifting was done by him.

Also, I decided to pick this data up as a #TidyTuesday project, hence not a lot of time was spent putting this together. Only 12-13 hours was spent working on this project. So, please don't be harsh. At some point, I will go back to fixing some things in there. 

```toml
Please click the link above to view dashboard.
```
### Key Takeaways

- Ensembling average your best models doesn't guarantee a better prediction accuracy.
- Base models are sometimes better than hyperparameter tuned models and ensemble averaged models.
- Post-Forecast Diagnostics inform that most of the information wasn't picked up by the fitted models.
- Hyperparameter tuning base models doesn't imply the resulting model will give a better prediction accuracy.
- Maybe, my pc doesn't have enough cores, but tuning PROPHET model is very time consuming. Depending on how many background applications are running, you can finish a YouTube video that is 12 mins long and still find your PROPHET model being tuned.

### Improvisation

- Picking up lag 14 and lag 30 might give us better prediction accuracy.
- Always perform post-forecast diagnostics to see how well the information is being picked up by the fitted models.
