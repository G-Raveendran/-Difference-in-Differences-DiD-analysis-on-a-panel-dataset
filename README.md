# -Difference-in-Differences-DiD-analysis-on-a-panel-dataset
This code performs a Difference-in-Differences (DiD) analysis on a panel dataset to evaluate the impact of a treatment over time. The treatment is assumed to have started in the year 1994, and the countries E, F, and G are designated as the treated groups. The analysis involves reading the data, creating necessary variables for DiD, and running regressions to estimate the treatment effect.

The code requires the foreign package to read Stata data files and the lm function from base R for linear regression analysis.

Summary
The code reads a panel dataset and prepares it for a DiD analysis.
Dummy variables for time and treatment are created.
The DiD estimator is calculated manually and using regression models.
The treatment effect is estimated and summarized using two methods of linear regression.
This analysis helps in understanding the impact of the treatment (assumed to start in 1994) on the outcome variable y for treated and control groups across time.
