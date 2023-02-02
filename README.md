# Mobility Correlation Analysis on Indonesian Daily Positivity Rate using Multivariate Regression

#### -- Project Status: Completed

## Project Objective
In 2022, the COVID-19 pandemic has started to subside. Many people carry out normal activities, as if this virus was gone. However, people's activities and mobility, especially in the Indonesian region, still depend on the number of COVID-19 considering that there are still policies that must be obeyed to prevent an increase in the virus. Therefore, it will be seen which mobility factors are strongly affected by the increase in COVID-19 so that it can be seen which fields are able to run normally as the decline in COVID-19.

### Methods Used
* Machine Learning
* Logistic Regression
* Support Vector Machines
* Decision Tree

### Language
* Python

### Module
* skicit-learn
* matplotlib
* pandas
* numpy
* seaborn

## Conclusion
From the processing of the data above, obtained from the many mobility, based on feature selection, only obtained several mobility factors that affect the positivity rate of Covid 19, namely mobility in retail and recreation areas, mobility in grocery stores and pharmacies, and mobility in central locations. public transport. Then, a model is created that represents the effect of feature mobility with a positivity rate in the form of a multivariate regression equation as follows
$$y= -0.70471722 x_{1} + 0.52829018  x_{2} - 0.29635462 x_{3} - 9.7258368 $$

Description: <br>
1. $x_{1}$=Mobility in retail and leisure venues
2. $x_{2}$=Mobility in grocery stores and pharmacies
3. $x_{3}$=Mobility at the center of public transportation
4. $y$=Positivity Rate

By substituting the values for these mobility, **the approximate positivity rate** in Indonesia can be predicted.

## Contributing Members
|Name     |  Github Account   | 
|---------|-----------------|
|Angelica Patricia | [github.com/angelpatriciads](https://github.com/angelpatriciads)    |
|Annisa Zahra | [github.com/annisazahra01](https://github.com/annisazahra01)    |
|Hosia Josindra |    [github.com/hosiajosindra](https://github.com/hosiajosindra)    |

## Getting Started
1. You can access the raw data [here](https://github.com/angelpatriciads/positivity_rate_multivariate_regression/blob/main/mobility_positivity_rate_dataset/) within this repo.
2. All of the scripts are being kept [here](https://github.com/angelpatriciads/positivity_rate_multivariate_regression/blob/main/mobility_positivity_rate_multivariate_regression.ipynb).
