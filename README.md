# Linear Regression Workshop Projects

This repository contains two linear regression projects completed as part of a Machine Learning workshop. Each project demonstrates how to build, train, evaluate, and visualise a linear regression model using scikit-learn.

## Projects

### 1. Boston Housing - Simple Linear Regression
**Folder:** `Boston/`

- **Goal:** Predict median home value (MEDV) from the Boston Housing Dataset
- **Type:** Simple linear regression (single feature)
- **Dataset:** `boston.csv`
- **Notebook:** `Machine_Learning_Linear_Reg_WS1.ipynb`

### 2. OmniPower Sales - Multiple Linear Regression
**Folder:** `Omnipower/`

- **Goal:** Predict product sales based on Price and Promotion spending
- **Type:** Multiple linear regression (two features)
- **Dataset:** `OmniPower.csv`
- **Notebook:** `Linear_Reg_WS2_Omnipower.ipynb`
- **Regression Equation:** Sales = 5730.03 - 54.58 x Price + 3.92 x Promotion
- **R-squared:** 0.754 (75.4%)
- **Key Findings:**
  - Higher price reduces sales (-54.58 per $1 increase)
  - More promotion spending increases sales (+3.92 per $1 increase)

## Skills Demonstrated
- Building simple and multiple linear regression models with scikit-learn
- Train/test splitting (80/20)
- Interpreting model coefficients and R-squared values
- Visualising actual vs predicted values
- Using seaborn pairplots to explore feature relationships

## Tech Stack
- Python, pandas, matplotlib, seaborn, scikit-learn
