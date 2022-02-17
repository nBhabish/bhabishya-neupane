---
title: '#TidyTuesday: Chocolate Ratings'
author: Bhabishya Neupane
date: '2022-02-16'
excerpt: Visualizing and extracting information from chocolate ratings
slug: []
categories:
  - tidyverse
  - data visualization
  - tidytuesday
tags: []
---


```r
knitr::opts_chunk$set(echo = TRUE, warning = FALSE, message = FALSE)
```

### Libraries


```r
library(tidyverse)
library(nationalparkcolors)
library(paletteer)
library(tidytuesdayR)
library(extrafontdb)
library(showtextdb)
library(extrafont)
library(showtext)
showtext_auto()
theme_set(theme_minimal())
font_add_google("BenchNine", family = "BenchNine")
```

### Data


```r
chocolate <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/2022-01-18/chocolate.csv')
```

### Exploratory Data Visualization













