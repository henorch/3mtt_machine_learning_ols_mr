## Marketing ROI Analysis Using Multiple Linear Regression
## Project Overview
This project applies Multiple Linear Regression using Python and statsmodels to evaluate how different media channels drive revenue. By assessing statistical significance and model fit, this analysis isolates high-performing channels to provide a data-backed roadmap for marketing budget optimization.

## Model Summary & Findings

## Core Regression Equation

    Sales=43.8100+8.2843(Radio)+0.1022(Social Media)
    
Note: The OLS model automatically excluded the TV feature due to perfect collinearity or data constraints 

## Key Performance Indicators

1. Goodness of Fit Adjusted (R-Squared) 
    Value: 0.735 (73.5%)

## Interpretation: 
Roughly 73.5% of the variance in Sales is explained by the changes in Radio and Social Media advertising spend. The model is highly robust, and the overall regression is statistically sound F-statistic = 794.1, p approx 0.00.




## P-Value
given that Radio and Social media has the following p-value 0.000, 0.927 respectively the figures shows that only Radio has a statistical significance to overall Sales


## Business Recommendation (ROI-Based)

Prioritize Radio Allocations: Radio is the clear performance driver for this brand. It offers a massive, statistically significant returns yield ($8.28 return per unit spent). Future marketing budgets should heavily favor this channel.Halt or Restructure Social 


Media Spend: Social Media investments show near-zero financial returns and complete statistical insignificance. Budgets should be paused or strictly audited for targeting errors before any further money is funneled here.