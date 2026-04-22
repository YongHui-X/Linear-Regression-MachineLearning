# Boston Housing: Can Room Count Explain Home Value?

This project asks a simple business question:

If a home has more rooms, does it usually cost more?

The model looks at the number of rooms (`RM`) and tries to estimate the home value (`MEDV`).

## What the model found

- Test R2: `0.371`
- Test RMSE: about `6.8` thousand dollars
- Model equation: `Home value = -36.25 + 9.35 x rooms`

## What this means in plain English

The model found a positive relationship between rooms and home value. In simple terms, homes with more rooms usually have higher prices.

But the result is only moderately strong. That means room count gives a useful direction, but it does not explain house prices very well on its own.

For business use, this is best seen as a baseline model, not a final pricing tool.

## What the charts show

![](images/boston-scatter.png)

The scatter plot shows the raw relationship between room count and home value. The points trend upward, which means more rooms are generally linked to higher values.

![](images/boston-regression-line.png)

The red line is the average trend the model learned. It is a simple summary of the pattern, but many homes sit far away from that line, which is why the prediction accuracy is limited.

## Business takeaway

- More rooms usually means a higher home value
- Room count alone is not enough to explain the full market price
- The model is useful for a quick directional estimate, not a final valuation

## Limitations

- Only one feature is used
- Housing value depends on many other factors, such as location, age, and condition
- The dataset is small for a real pricing model
