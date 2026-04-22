# OmniPower Sales: How Price and Promotion Affect Sales

This project asks a practical business question:

How much do price and promotion spending influence sales?

The model uses two inputs:

- `Price`
- `Promotion`

## What the model found

- Test R2: `0.736`
- Test RMSE: about `772` sales units
- Model equation: `Sales = 5730.03 - 54.58 x Price + 3.92 x Promotion`

## What this means in plain English

The model shows a clear and intuitive business pattern:

- When price goes up, sales usually go down
- When promotion spending goes up, sales usually go up

The model explains most of the sales movement in the dataset, so it is a useful forecasting baseline for planning and budgeting.

## What the charts show

![](images/omnipower-price-sales.png)

This chart shows the relationship between price and sales. The general pattern is downward, which means higher prices tend to be linked to lower sales.

![](images/omnipower-actual-vs-predicted.png)

This chart compares the model's predictions with the real sales values. The points are reasonably close to the pattern you would want, which is a sign that the model is working well at a baseline level.

## Business takeaway

- Price is an important lever and has a negative effect on sales
- Promotion is a positive lever and helps lift sales
- The model is useful for forecasting and scenario planning
- It is not perfect, but it gives a solid first estimate

## Limitations

- Only two drivers are included
- Other factors may also affect sales, such as seasonality, competition, and stock availability
- The dataset is small, so the model should be treated as a baseline rather than a final business rule
