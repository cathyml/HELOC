## Predicting Risk of Loan Default

In this project, I use the dataset from the [FICO Explainable Machine Learning Challenge](https://community.fico.com/s/explainable-machine-learning-challenge/).

1. Auto Feature Engineering

    Manual feature engineering is a tedious task and is limited by both human imagination - there are only so many features we can think to create - and by time - creating new features is time-intensive. Automated Feature Engineering supplements domain knowledge with an automated workflow. I implementated [Featuretools](https://www.featuretools.com/), an open-source Python library for automatically creating features with relational data (where the data is in structured tables). 
    
    
2. Feature Selection: Apply 5 Feature Selection Techniques and combine the results.
    

3. Model selection and hyperparameter tuning


4. Interpreting the results: Apply the ML interpretation tools Eli5, LIME and SHAP.


## Dataset

* `heloc`: dataset of home equity line of credit (HELOC) applications

A dataset of home equity line of credit (HELOC) applications made by real homeowners. A HELOC is a line of credit typically offered by a bank as a percentage of home equity (the difference between the current market value of a home and its purchase price). The customers in this dataset have requested a credit line, and the fundamental task is to use the information about the applicant in their credit report to predict whether they will repay their HELOC account within 2 years. This prediction is then used to decide whether the homeowner qualifies for a line of credit and, if so, how much credit should be extended.
