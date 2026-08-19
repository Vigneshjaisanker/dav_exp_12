# Experiment: Performing T-Test on Diabetes Datasets

## Aim

To perform an independent samples T-Test on the UCI Diabetes Dataset and Pima Indians Diabetes Dataset and determine whether there is a statistically significant difference between their selected numerical variables.

## Objective

The objective of this experiment is to compare the mean values of selected numerical variables between the UCI and Pima diabetes datasets using an independent samples T-Test.

## Datasets

The experiment uses two diabetes datasets:

- UCI Diabetes Dataset
- Pima Indians Diabetes Dataset

## Features Used

The following numerical variables are selected for comparison:

- Glucose
- BloodPressure
- BMI

## Topics Covered

- Hypothesis Testing
- Independent Samples T-Test
- T-Statistic
- P-Value
- Significance Level
- Comparison of Dataset Means
- Statistical Decision

## Hypotheses

For each selected variable:

- **Null Hypothesis (H₀):** There is no significant difference between the mean values of the two datasets.
- **Alternative Hypothesis (H₁):** There is a significant difference between the mean values of the two datasets.

## Significance Level

The significance level used for the test is:

**α = 0.05**

## Methodology

The following steps are performed:

1. Import the required Python libraries.
2. Load the UCI Diabetes Dataset.
3. Load the Pima Indians Diabetes Dataset.
4. Select Glucose, BloodPressure, and BMI.
5. Remove missing values if present.
6. Perform an independent samples T-Test for each variable.
7. Calculate the T-Statistic and P-Value.
8. Compare the P-Value with the significance level.
9. Interpret the statistical results.

## Decision Rule

- If **P-Value < 0.05**, reject the null hypothesis.
- If **P-Value ≥ 0.05**, fail to reject the null hypothesis.

## Tools and Technologies

- Python 3.x
- Pandas
- NumPy
- SciPy
- Jupyter Notebook

## Learning Outcomes

After completing this experiment, the learner will be able to:

- Understand the concept of T-Tests.
- Perform an independent samples T-Test.
- Compare means between two datasets.
- Calculate and interpret T-Statistics.
- Interpret P-Values.
- Apply a significance level in hypothesis testing.
- Draw statistical conclusions from T-Test results.

## Result

The independent samples T-Test was successfully performed on the **Glucose, BloodPressure, and BMI** variables of the UCI and Pima diabetes datasets. The T-Statistics and P-Values were calculated to determine whether significant differences exist between the two datasets.

## Conclusion

This experiment demonstrates how an **independent samples T-Test** can be used to compare the means of two independent datasets. The P-Value is used to determine whether the observed differences between the UCI and Pima diabetes datasets are statistically significant.
