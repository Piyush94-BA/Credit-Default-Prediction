# Loan-Default-Classification
The dataset contains 614 observations , 11 features, and one target variable.
The features are: Income_of_Applicant, Income_of_Joint_Applicant, Loan_Amount_Requirement, Loan_Amount_Term, Credit_History, Gender, Is_Married, No_of_Dependents, Level_of_Education, IS_Self_Employed, Area_of_Property.
The target variable is : Loan_Status

Mentioned below are the key challanges faced:

1. The Missing Data was imputed using KNN Imputation method, for both continuous and categorical variables.
2. Outliers skewed the continuous variables heavily in the data. They were balanced using Log transformation, Min-Max Scaling & Outlier Removal.
2. The target variable had class imablance (Yes: No = 70:30), whhich was controlled while buidling the model using Synthetic Minority Over Sampling Technique(SMOTE) and Random Oversampling.
3. Since the target variable had class imbalance, accuracy could not be relied upon as a means to measure the performance of the model. Hence, metrics like AUC, Specificty & Sensitivty, Recall, False Negative Rate and Weighted TPR_TNR were used.
4. Models used were Logistic Regression, Decision Trees, Random Forest, Adaboost & Gradient Tree Boosting.

Please reach out to me for further clarifications: beripiyush@gmail.com

Happy Coding! </br>
Piyush Beri
