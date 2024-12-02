# Union Membership and Wage Analysis

This project investigates the effect of union membership on wages using data from the National Longitudinal Survey of 545 American male workers, who graduated in 1980 and worked from 1980 to 1987. The goal is to determine if union members earn higher wages compared to non-union workers.

## Dataset

The dataset (`males_wage.csv`) contains the following columns:

- **id**: Worker ID
- **Years**: Year of observation
- **School**: Years of education
- **Expert**: Work experience (years)
- **Union**: Dummy variable indicating union membership (1 if the worker is in a union, 0 if not)
- **Married**: Dummy variable indicating marital status (1 if married, 0 if not)
- **Black**: Dummy variable indicating African American workers (1 if Black, 0 if not)
- **Hisp**: Dummy variable indicating Hispanic workers (1 if Hispanic, 0 if not)
- **Wage**: Logarithm of the wage

## Objectives

- **Preliminary Data Analysis**: Analyze the dataset and explore key statistics and distributions
- **Model Building**: Test different models to assess the impact of union membership on wages
- **Graphical Representation**: Create relevant visualizations to support the analysis
- **Interpretation**: Interpret the results of the models and provide insights on the effect of union membership on wages
- **Econometric Models**: Build econometric models and compare them with models built using **PyMC**

## Methodology

1. Conduct exploratory data analysis (EDA) to understand the data distribution and relationships between variables.
2. Use regression analysis to model the relationship between union membership and wages, while controlling for other factors like education, experience, and demographics.
3. Compare traditional econometric models with **PyMC** models for more robust analysis.

