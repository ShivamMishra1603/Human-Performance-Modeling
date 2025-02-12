# Human-Performance-Modeling

## Overview
This repository  involves modeling human performance using **Fitts' Law** and the **Steering Law** through linear regression. The goal is to analyze input data, compute the index of difficulty (ID), predict movement time (MT), and evaluate the model's performance.

## Files and Structure
```
📂 Human Performance Modeling
│── notebook.ipynb             # Jupyter Notebook with implementation and explanations
│── results_FL.csv             # Results file for Fitts' Law
│── results_SL.csv             # Results file for Steering Law
│── data/
│   ├── FL.csv                 # Input dataset for Fitts' Law
│   ├── SL.csv                 # Input dataset for Steering Law
│── README.md                  # Project documentation (this file)
```

## Requirements
The project consists of two main sections:

### 1. Fitts' Law
- Compute **Index of Difficulty (ID)** using the formula:
  \[ ID = \log_2 \left( \frac{D}{W} + 1 \right) \]
- Perform **linear regression** to model:
  \[ MT = a + b \times ID \]
- Plot **ID vs. MT** (both actual values and model predictions).
- Compute **R-Squared** and **RMSE** to evaluate the model.
- Provide observations and conclusions.
- Save results in `results_FL.csv` (containing `a, b, R_Squared, RMSE`).

### 2. Steering Law
- Compute **Index of Difficulty (ID)**.
- Perform **linear regression** to model:
  \[ MT = a + b \times ID \]
- Plot **ID vs. MT** (both actual values and model predictions).
- Compute **R-Squared** and **RMSE** to evaluate the model.
- Provide observations and conclusions.
- Save results in `results_SL.csv` (containing `a, b, R_Squared, RMSE`).