# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to provide a model for credit applications to determine the risk of defaulting on a given loan. In order to do this, a predictive model was created that took into account the following factors: loan size, interest rate, borrower income, debt-to-income ratio, number of current accounts, number of derogatory remarks, and total debt. The Machine Learning model would create two classes: 0 or 1. Class 0 loans were very likely to be non-defaulting, while Class 1 loans were likley to default. 

The machine learning algorithm used for this predictive model was Logistic Regression. This algorithm was selected as it is often used to predict the probablity of specific targeted variables in areas of classification problems. 


## Results

* Machine Learning Model 1:
    * Using the data provided from the lending company, I was able to create a model that yielded the following results:
    * For Class 0:
        * Precision 1.00- This indicates that the model is almost perfect in predicting when a loan will not default
        * Recall 0.99- the model can correctly find 99% of loans that did not default
        * F1 Score 1.00- there is a perfect relationship between the precision and recall of the Class 0 loans
    * For Class 1:
        * Precision 0.84- The model will correctly predict 84% of loans that will end in default
        * Recall 0.94- The model is able to find 94% of the loans that ended in default
        * F1 Score 0.89- There is a strong balance of recall and precision in defaulted loans
    * Overall Performance:
        * Accuracy 0.99- This model correctly predicts the likelihood of deafulting and non-defaulting loans 99% of the time. 


## Summary

Ultimately, the machine learning model predicted that Class 0 loans were 100% likely to be paid off with no concerns of defaulting. The model dropped that likelihood to 84% for Class 1 loans. While still a very high percentage, it would be concerning to a financial institution to know that 16% of the loans given out were likely to default. 

There is room for improvement with the model when dealing with Class 1 predicitions. This is particularly true in the area of Precision. To do this, the model could be adjusted to minimize false positives, or to be run again with updated information from a loan-seeker. For example, if the loan-seeker receives a promotion with a higher salary. 

Given the limitations of Class 1 predicitons, a financial institution may consider seeking additional information, or using a different model, for Class 1 loans. The potential for false-positives- predicting that a loan will default when it does not- could lead to uncessary actions being taken, or loss of business by a loan-seeker who goes elsewehere. 


