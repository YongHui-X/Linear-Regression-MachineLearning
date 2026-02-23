# Multiple Linear Regression - OmniPower Sales Prediction

## 1. Project Overview
The goal of this project is to apply **Multiple Linear Regression** to the OmniPower dataset to predict **Sales** based on **Price** and **Promotion** spending.
The model learns a linear relationship between the two features and the target variable (Sales).

## 2. Dataset Description
The dataset (`OmniPower.csv`) contains 34 observations with 3 columns:
- **Sales** — Number of units sold (dependent variable)
- **Price** — Product price in dollars (independent variable)
- **Promotion** — Promotion budget in dollars (independent variable)

The data is split into:
- 80% training data (27 samples)
- 20% test data (7 samples)

## 3. Model & Results

### Regression Equation
**Sales = 5730.03 - 54.58 x Price + 3.92 x Promotion**

### Coefficient Interpretation
| Coefficient | Value | Meaning |
|---|---|---|
| Intercept | 5730.03 | Baseline sales when Price and Promotion are both 0 |
| Price | -54.58 | Every $1 price increase reduces sales by ~55 units |
| Promotion | +3.92 | Every $1 increase in promotion spending increases sales by ~4 units |

### Key Takeaways
- **Higher price hurts sales** — the negative coefficient confirms the expected inverse relationship between price and demand.
- **Promotion drives sales** — increased promotion spending has a positive effect on units sold.
- **R-squared = 0.754 (75.4%)** — the model explains about 75% of the variance in Sales. The remaining ~25% is due to noise or other factors not captured in the model.

### Example Prediction
For Price = $50 and Promotion = $200, the model predicts **Sales = 3784 units**.

## 4. Visualisations
The notebook includes:
- **Price vs Sales scatter plot** — shows the negative trend between price and sales
- **Seaborn pairplot** — displays pairwise relationships and distributions across all variables
- **Actual vs Predicted Sales** — evaluates model accuracy; points closer to the diagonal indicate better predictions

## 5. Skills Demonstrated
- Building a multiple linear regression model with scikit-learn
- Training, evaluating, and interpreting model coefficients
- Using R-squared to assess model performance
- Visualising relationships and model predictions
