# Chernobyl Cancer Analysis  
**Statistical Test on Cancer Rates Before and After the Chernobyl Disaster**

## Overview
Used real-world cancer data (1977–1994) from Belarus to analyze the effect of the Chernobyl accident using a non-parametric Mann-Whitney U Test.

## Dataset
- Source: Kaggle (Byelorussian Center of Medical Technologies)
- Metric: Kidney & thyroid cancer cases per 100,000 people
- Periods: 1977–1985 (Before), 1986–1994 (After)

## Method
- Test: Mann-Whitney U Test (n1 = 12, n2 = 12)
- Reason: Small, independent samples with non-normal distribution
- U = 24 < Critical Value = 37 → Reject null hypothesis at α = 0.05

## Result
Significant increase in cancer rates after the disaster.

## Tools
Python, Pandas, Matplotlib, Statistical Testing
