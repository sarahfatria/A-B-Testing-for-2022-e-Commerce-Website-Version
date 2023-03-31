# A/B Testing Implementation Using Chi-Square Test
This project involves implementing A/B testing on a website version using the chi-square test to analyze the relationship between the website version and the customer's decision to purchase products. A/B testing is a method of comparing two different versions of a website to see which one performs better. The chi-square test is used to determine if there is a significant difference between the expected and observed values in a contingency table.


## Hypotheses
While implementing the chi-square test, we have created two hypotheses:
- **Null Hypothesis**: There is no relation between page version and customer's decision to purchase products. They are independent.
- **Alternate Hypothesis**: There is a relation between page version and customer's decision to purchase products. They are dependent.

If the p-value is less than 0.05, we reject the null hypothesis and accept the alternate hypothesis. Otherwise, we do the opposite. The acceptance value is set to 0.05.


## Results
 - **dof value**:  1
 - **chi2_statistic value**:  1.87605695553178
 - **p_value**:  0.17078297802593548
 - **critical value**:  3.841458820694124
 
 since the p_value is  0.17078297802593548  which is >= 0.05, the null hypothesis should be accepted and alternate hypothesis should be rejected.
 
**Accepted Hypothesis**: there is no relation between page version and customer's decision to purchase products. they are independent

## Dataset
The dataset used in this project can be accessed through [this link](https://www.kaggle.com/datasets/putdejudomthai/ecommerce-ab-testing-2022-dataset1)
