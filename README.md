# 📈 Statistical Model Analysis on Bitcoin (BTC)

This project aims to identify the best statistical model to fit and forecast Bitcoin prices using various regression and time series techniques, including Linear Regression, Quadratic Regression, and ARIMA. It was developed in RStudio and compiled into an interactive HTML report using RMarkdown.

🔗 **View the Full Report:**  
👉 [Bitcoin Forecast Report (GitHub Pages)](https://pd-bds.github.io/Statistical-Analysis-on-Bitcoin/)

---

## 🎯 Project Objective

To analyze historical monthly Bitcoin (BTC) prices and determine a statistical model that best fits the data for reliable forecasting of future prices.

---

## 🔬 Methodology

- **Dataset:** Monthly average BTC/USD prices from Jan 2015 to Nov 2023.
- **Models Used:**
  - Linear Regression
  - Quadratic Regression
  - ARIMA
- **Model Evaluation:** Residual analysis, ACF/PACF, AIC/BIC, Shapiro-Wilk Test, and Forecast Accuracy Metrics

---

## 📦 R Packages Used

```r
library(rmdformats)
library(dplyr)
library(ggplot2)
library(forecast)
library(lmtest)
library(kableExtra)
library(knitr)
library(tseries)
library(TSA)
```

---

## 📊 Key Sections in the Report

- **Data Cleaning & Feature Engineering**
- **Descriptive Analysis with Monthly & Yearly Trends**
- **Regression Modeling & Residual Analysis**
- **Stationarity Testing (ADF), EACF for ARIMA Order Selection**
- **Model Evaluation via AIC, BIC, MAPE, RMSE, etc.**
- **Forecast of Bitcoin Prices for Next 12 Months**

---

## 🧠 Final Model

📌 **Selected Model:** ARIMA(0,1,2)  
Chosen based on model selection criteria (AIC, BIC), accuracy metrics, and residual diagnostics.

📈 **Forecast:** 12-month forecast of BTC/USD prices plotted and tabulated.

---

## 📁 Project Structure

```
bitcoin-model-analysis/
├── Statistical-Analysis-on-Bitcoin.Rmd       # RMarkdown source file
├── index.html                                # Final report (to host on GitHub Pages)
└── README.md                                 # Project overview
```

---

## 🚀 How to Reproduce

1. Clone the repo and open `.Rmd` in RStudio
2. Ensure required packages are installed
3. Knit the report to HTML

---


## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- [RStudio](https://posit.co/)
- [rmdformats](https://github.com/juba/rmdformats)
- [Tidyverse](https://www.tidyverse.org/)
- [Forecast Package](https://pkg.robjhyndman.com/forecast/)
