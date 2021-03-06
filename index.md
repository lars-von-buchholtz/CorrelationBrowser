---
title       : Pitch for interactive pairs plot
subtitle    : 
author      : L.v.Buchholtz
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Detecting correlations between columns in a data frame


- a prerequisite for a successful regression analysis or feature design for machine learning is 
exploratory data analysis
- correlation between numeric or factor variables that are organized in columns in a dataframe is of particular interest

--- .class #id 

## Problem: Pairs plots get too small and cluttered on large dataframes

![plot of chunk pairs plot](assets/fig/pairs plot-1.png)
  

---

## Solution: An interactive tool to display individual pair plots


- columns of the dataframe can be selected for the x and y axes

- data frames can be uploaded as csv files

- if no csv file is uploaded the mtcar data set is displayed


---

## Just try it out!!!
