# bostonhousingusecaselab01

# Housing Agency Data Analysis Project

## Project Case Scenario

You are a Data Scientist with a housing agency in Boston MA, tasked with presenting insights to higher management using a dataset on housing prices derived from the U.S. Census Service. The management seeks insights into several questions regarding housing prices and related factors in Boston.

## Project Tasks

### Task 1: Familiarize Yourself with the Dataset

The dataset contains the following variables:

- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: Nitric oxides concentration (parts per 10 million)
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built prior to 1940
- DIS: Weighted distances to five Boston employment centres
- RAD: Index of accessibility to radial highways
- TAX: Full-value property-tax rate per $10,000
- PTRATIO: Pupil-teacher ratio by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in $1000's

### Task 2: Generate Basic Statistics and Visualizations for Upper Management

- Boxplot for the median value of owner-occupied homes (MEDV)
- Bar plot for the Charles River variable (CHAS)
- Boxplot for MEDV vs. AGE (Discretized into three groups)
- Scatter plot for Nitric oxide concentrations (NOX) vs. proportion of non-retail business acres per town (INDUS)
- Histogram for the pupil to teacher ratio (PTRATIO)

### Task 3: Use the Appropriate Tests to Answer the Questions Provided

For each question, state the hypothesis, use α = 0.05, perform the test, and state the conclusion.

1. Is there a significant difference in the median value of houses bounded by the Charles river or not? (T-test for independent samples)
2. Is there a difference in median values of houses for each proportion of owner-occupied units built before 1940? (ANOVA)
3. Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town? (Pearson Correlation)
4. What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes? (Regression analysis)

### Task 4: Share Your Jupyter Notebook

Share your Jupyter Notebook containing your analysis and insights with the upper management.

## Final Notes

This project is worth 15% of your final grade. Detailed instructions for each task can be found in the subsequent sections of this document.
