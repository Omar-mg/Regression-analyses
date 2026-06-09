# Marketing ROI Analysis - Simple Linear Regression

## Project Overview
This project analyzes a marketing dataset to identify the most effective advertising channel (TV, Radio, or Social Media) for driving sales. Using Python and `statsmodels`, I built a Simple Linear Regression model, validated statistical assumptions through diagnostic plotting, and translated the statistical outputs into actionable business recommendations.

## Key Findings & Statistical Interpretation
* **Strongest Channel:** TV Advertising showed the highest correlation with Sales (0.999).
* **R-Squared:** 0.999. This indicates that 99.9% of the variance in Sales is explained by TV advertising spend.
* **P-Value:** 0.000. This is well below the 0.05 threshold, confirming statistical significance.
* **Confidence Interval:** The 95% confidence interval for the TV coefficient is [3.558, 3.571].
* **Coefficient Interpretation:** For every additional 1 unit spent on TV advertising, sales increase by ~3.56 units.
* **Assumption Validation:** Evaluated via Histograms, Q-Q plots, and Residuals vs Fitted plots.

## Files
* `regression_analysis.ipynb`: The Jupyter Notebook containing all data cleaning, EDA, modeling, and diagnostics.
* `marketing_and_sales_data_evaluate_lr.csv`: The dataset used for the analysis.
