# US-RetailSales-PostCovid
Forecasted US retail sales post-Covid using SARIMA
This project explores how retail sales in the United States evolved during and after the COVID-19 pandemic, and attempts to **forecast future retail trends** using a SARIMA time-series model.

## Project Overview
The goal was to understand retail sales patterns pre- and post-COVID and to test whether traditional forecasting models could capture the volatility introduced by the pandemic.

Key steps included:
- Collecting and cleaning U.S. Census Bureau retail sales data  
- Converting and handling date-time data using **pandas**  
- Building and evaluating **SARIMA** models  
- Performing **grid search** for hyperparameter tuning  
- Visualizing results and residuals with **matplotlib** and **seaborn**

## Findings
The SARIMA model performed reasonably well before the pandemic but struggled with post-COVID data, highlighting how traditional models fail when the underlying data-generating process shifts suddenly.  
This analysis demonstrates the limits of conventional time-series forecasting and the value of domain context when interpreting results.

## Tools & Libraries
- Python  
- pandas, numpy  
- statsmodels  
- matplotlib, seaborn  

## Skills Demonstrated
- Time-series modeling and forecasting  
- Hyperparameter tuning  
- Data cleaning and feature engineering  
- Data visualization and storytelling  

## Repository Contents
- `US Retail Sales Post Covid Prediction.ipynb` – main analysis notebook  
- `us_retail_sales` – raw data file   
- `README.md` – project overview and documentation
