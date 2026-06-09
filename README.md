# Marketing ROI Analysis - Simple Linear Regression

## Project Overview
This project analyzes a marketing dataset to identify the most effective advertising channel (TV, Radio, or Social Media) for driving sales. Using Python and `statsmodels`, I built a Simple Linear Regression model, validated statistical assumptions through diagnostic plotting, and translated the statistical outputs into actionable business recommendations.

## Environment Setup
To run this notebook locally, ensure you have Python installed and run the following command to install the required libraries:
`pip install pandas matplotlib seaborn statsmodels`

## Key Findings
* **Strongest Channel:** TV Advertising showed the highest correlation with Sales (0.999).
* **ROI Impact:** The regression model indicates that for every 1 unit increase in TV advertising spend, sales increase by ~3.56 units.
* **Recommendation:** Marketing budget should be heavily prioritized toward TV advertising to maximize Sales ROI.

## Files
* `Marketing_Project.ipynb`: The Jupyter Notebook containing all data cleaning, EDA, modeling, and diagnostics.
* `marketing_and_sales_data_evaluate_lr.csv`: The dataset used for the analysis.
