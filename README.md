# Module 12 Report Template

## Overview of the Analysis

1. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
2. The data that has been used are loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, 
    and from these data, the purpose is to predict loan_status if it's True or False
3. Total of 77536 data has been used for this analysis
4. To describe the stages of ML process, first to split the data randomly and then fit the data using "LogisticRegression" model and predicted it.
    To verify the result, refited the data using RandomOverSampler and done the same procedure.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
![<alt Description>](<./img/ML1.png>)

    
    
    

* Machine Learning Model 2:
![<alt Description>](<./img/ML2.png>)


## Summary

Machine Learning Model 2 fits better for this data.
    - There are not much difference in true positive cases between model 1 and 2. Also, False negative value drops drastically with Model 2.
      Also the accuracy score is about 5% higher in model 2. 
    - Therefore, Model 2 will be more useful for this data set.