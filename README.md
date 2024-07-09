# Analyzing Household Income in Greater Louisville Area

## Description
This project investigates household incomes in the Greater Louisville area, utilizing a dataset from a random survey conducted by Greater Louisville Inc (GLI). Through various statistical models, we aim to understand the significance of different variables in predicting household income, the impact of education and work hours, and the likelihood of achieving a higher income. This analysis will provide valuable insights into income dynamics, helping to inform policy and business decisions.

## Technologies
SPSS (Statistical analysis)

Excel (Data manipulation)

## Dataset:
The dataset used in this project is available through this link : https://docs.google.com/spreadsheets/d/1WHX0GlXH9juHGf1-oRoSR4o3-1ejvu1d/edit?usp=sharing&ouid=103866616450836273114&rtpof=true&sd=true

The data is from a survey conducted by Greater Louisville Inc.

## Task List
**Determine the significance of all variables in modeling household income:**

Model Creation: Perform regression analysis with INCOME as the dependent variable and AGE, EDUC, HRS1, SPHRS1, EARNRS, CHILDS, and HEAD as independent variables.

Model Evaluation: Use a general linear F-test to compare the full model with a reduced model excluding non-significant variables.

Conclusion:  The reduced model excluding CHILDS and HEAD is preferred.

**Model the total number of hours worked per week:**

Model Creation: Create a new variable TOTAL (sum of HRS1 and SPHRS1) and perform regression analysis using AGE, EDUC, and HEAD as 
  independent variables.

Model Evaluation: Evaluate coefficients, standard errors, t-values, p-values, and the R-squared value.

Conclusion: Age and gender of the head of household are significant predictors; education is not.

**Assess the impact of an interaction term between EDUC and HRS1 on annual household income:**

Model Creation: Create a model for annual household income with EDUC and HRS1 as independent variables, including an interaction term.

Model Evaluation: Assess the significance of the interaction term through regression analysis.

Conclusion: The interaction term is significant, improving the model.

**Model the likelihood of a household income exceeding $75,000:**

Model Creation: Use logistic regression to model the likelihood of income exceeding $75,000 based on AGE, EDUC, and TOTAL.

Model Evaluation: Evaluate the logistic model output, including predicted probabilities and pseudo R-squared.

Conclusion: Age, education, and total hours worked are significant predictors of higher income likelihood.

## Final Thoughts:
The analysis provides valuable insights into household income dynamics in the Louisville metro area. The preferred reduced model excludes CHILDS and HEAD. Total hours worked are effectively modeled using AGE, EDUC, and HEAD. The interaction term between EDUC and HRS1 is significant but does not drastically alter predictions. Logistic regression effectively models the likelihood of income exceeding $75,000, highlighting the importance of education and work hours.

