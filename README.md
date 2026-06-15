# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project uses Simple Linear Regression to determine which marketing channel most strongly influences sales.

## Objectives

- Clean and explore marketing data
- Identify the best predictor
- Build OLS regression model
- Validate assumptions
- Interpret results
- Recommend marketing budget allocation

## Installation

pip install pandas numpy matplotlib seaborn scipy statsmodels

## Run

Open:

regression_analysis.ipynb

Execute all cells.

## Model Summary

A multiple linear regression model was developed to determine the impact of TV, Radio, and Social Media advertising expenditures on Sales.

## The model seeks to answer:

Which advertising channels significantly influence sales?

## Key indicators

## R-squared 
At a value of 99.9% which aim at predicting sales variation using TV, Radio and Social Media advertising expenditure as feature, at 99.9% there is high level of confidence that almost every changes in sales level are explainable by the features under consideration

## Coefficients

Sales=−0.134+3.5626(TV)−0.004(Radio)+0.005(Social_Media)

The coefficient indicates that while holding other variable constant a unit increament in TV advertisment result in 3.5626 increament in sales, a unit increase in Radio advertisment expenses result in small reduction in over sales while a unit increase in social media advertisment result in 0.005 increase in sale, The Business implication of this is that TV advertisment has a significant impact on sales.


## P-Value
given that TV, Radio and Social media has the following p-value 0.000, 0.685 and 0.862 respectively the figures shows that only TV has a statistical significance to overall Sales

## Business Recommendation (ROI-Based)

TV advertising should receive the highest priority in future marketing budget allocation because it is the only channel with a statistically significant and substantial impact on sales. Radio and Social Media spending should be reviewed, optimized, or re-evaluated before allocating additional resources, since their effects on sales are statistically insignificant.