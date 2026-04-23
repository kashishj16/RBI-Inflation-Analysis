# RBI Inflation Analysis Project

## Overview

This project analyzes the relationship between inflation and monetary policy in India using CPI (Consumer Price Index) and Policy Repo Rate data.

The objective is to understand whether changes in repo rate effectively influence inflation and to model inflation dynamics using time series techniques.

---

## Data Sources

* CPI Data: MOSPI (Ministry of Statistics and Programme Implementation)
* Repo Rate: RBI DBIE (Database on Indian Economy)

---

## Methodology

1. Data Cleaning & Preprocessing
2. Time Series Conversion
3. Feature Engineering (Lag Features)
4. Model Building:

   * Linear Regression
   * Random Forest
5. Model Evaluation (R², MAE)

---

## Key Findings

* Repo rate alone has limited explanatory power over inflation.
* Inflation shows strong persistence (dependence on past values).
* Monetary policy impacts inflation with a lag.
* Non-linear models perform better than linear models.

---

## Results

* Linear Model R²: ~0.01 (Repo only)
* Lag Model R²: ~0.84 (with inflation lag)
* Random Forest captures short-term fluctuations better.

---

## Conclusion

Inflation in India is influenced by multiple factors beyond monetary policy, including supply shocks and external conditions. Repo rate plays a role but is not sufficient alone to explain inflation dynamics.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

##  Project Structure

Refer to folder structure for organization of data, notebooks, and outputs.

---

##  Author

Kashish Jain
