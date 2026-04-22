# Linear Regression Workshop Projects

This repository contains two small regression studies that turn simple business questions into forecast models.

## Projects at a Glance

| Project | What it predicts | Main result | Business readout |
| --- | --- | --- | --- |
| [Boston Housing](Boston/README.md) | Home value | Test R2: 0.371 | Room count helps explain price, but it is only a partial signal |
| [OmniPower Sales](Omnipower/Readme.md) | Sales volume | Test R2: 0.736 | Price and promotion together give a useful sales forecast |

## Boston Housing

This study looks at whether the number of rooms in a home can help explain its value.

![](Boston/images/boston-scatter.png)

![](Boston/images/boston-regression-line.png)

The pattern is positive: homes with more rooms tend to be worth more. The red line shows the average trend the model learned.

- Test R2: `0.371`
- Test RMSE: about `6.8` thousand dollars
- Plain-English takeaway: the model is directionally useful, but not precise enough to price homes on its own

[Open the full Boston summary](Boston/README.md)

## OmniPower Sales

This study looks at how price and promotion spending affect sales.

![](Omnipower/images/omnipower-price-sales.png)

![](Omnipower/images/omnipower-actual-vs-predicted.png)

The model found two clear business signals:

- Higher prices are linked to lower sales
- More promotion spending is linked to higher sales

- Test R2: `0.736`
- Test RMSE: about `772` sales units
- Plain-English takeaway: this is a useful planning model and it tracks sales reasonably well

[Open the full OmniPower summary](Omnipower/Readme.md)

## Notes

- The project READMEs are written for non-technical readers.
- The charts were exported from the notebooks and saved as image files in each project folder.
- Both studies are baseline linear regression examples, so they show clear trend insights rather than perfect predictions.
