# TSLA STOCK PRICE ANALYSIS 
### Time Series Final Project 
#### Authors: 
#### Course: 

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)
* [Code](#Code)
* [Data](#data)
* [Models](#models)
* [Results](#results)
* [Resources](#resources) 

## Introduction
Tesla – electric vehicle and solar panel manufacturer went IPO 2010. 
This project creates various model that predict Tesla stock price. 
	
## Technologies
Project is created with:
* R
* Google Colaboratory 
	
## Setup
To run this project, install and run the following packages: 

```
library(zoo)
library(xts)
library(forecast)
library(tseries)
library(dplyr)
library(tidyverse)
library(tidyr)
library(rugarch)
library(PerformanceAnalytics)
library(quantmod)
library(keras)
library(tensorflow)
library(FNN)
#library(caret)
library(class) 
library(rpart.plot)
library(rpart)  
library(glmnet)
library(NeuralNetTools) 
library(PRROC)
library(ROCR) 
library(Metrics)
```
## Code
- TSLA_in_R.ipynb

## Data
- CSV 
- Link to dataset: https://www.kaggle.com/datasets/timoboz/tesla-stock-data-from-2010-to-2020

## Models
- Holt-Winters
- ARIMA
- GARCH
- Neural Network

## Results
| **MODEL** | **MSE**  | 
| :---:   | :-: | 
| ARIMA | 301 | 
| Holt-wintes | 301 | 
| GARCH | 301 |
| Neural Network | 301 | 

## Resources
- Ederington, Louis H., and Wei Guan. “Longer-Term Time-Series Volatility Forecasts.” The Journal of Financial and Quantitative Analysis, vol. 45, no. 4, 2010, pp. 1055–76. JSTOR, http://www.jstor.org/stable/40930464. Accessed 1 Jun. 2022.
- “A Short Introduction to the RUGARCH Package.” Unstarched, 11 Jan. 2014, http://www.unstarched.net/r-examples/rugarch/a-short-introduction-to-the-rugarch-package/.
- Eric Zivot, EZ. (2013, April 24). Univaritae Garch Computational Finance & Risk Management, University of Washington. https://faculty.washington.edu/ezivot/econ589/univariateGarch2012powerpoint.pdf
- https://www.frontiersin.org/articles/10.3389/fphy.2021.741106/full
- https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194889
- https://a-little-book-of-r-for-time-series.readthedocs.io/en/latest/src/timeseries.html
- https://afit-r.github.io/ts_exp_smoothing
 
