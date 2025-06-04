# Homework 6 - Statistical Data Analysis (R)

This repository contains my solution to Homework 6 from the *Statistical Data Analysis 2* course at the University of Potsdam. The analysis is written in R using R Markdown and covers key topics in linear and mixed-effects modeling.

## Overview

This project involves:

- Multiple linear regression with interaction terms
- Mixed-effects modeling using `lmerTest`
- Variance Inflation Factor (VIF) checks for multicollinearity
- Model comparison using likelihood ratio tests
- Model diagnostics (QQ plots and residual checks)
- Interpretation of model parameters

## Files

- `Homework06_YigitKasal.Rmd`: The main R Markdown file containing the full analysis.
- `StressSymptoms2.txt`: Dataset for Exercise 1 (not included here).
- `EEG_Indiv_RT_Dataset20180706out.csv`: Dataset for Exercise 2 (not included here).

## Required Packages

Make sure the following R packages are installed:

```r
install.packages(c("tidyverse", "readr", "car", "lmerTest", "languageR", "MASS", "Rmisc"))
# If needed:
# devtools::install_github("vasishth/lingpsych")
```

## Topics Covered

- Centering predictors to reduce multicollinearity
- Interpreting interaction terms
- Handling skewed residuals with transformations
- Evaluating model fit and assumptions

## Notes

This was an academic assignment. All data and code are for educational purposes only.

## Author

Yigit Kasal  
MSc Linguistics Student  
University of Potsdam  
