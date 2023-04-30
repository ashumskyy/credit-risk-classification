# credit-risk-classification

In this project I had to make a loan risk prediction model that predicts whether a loan is in a high or low-risk category.
The model is trained on a dataset consisting of features such as loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status.
The dataset split into training and testing sets to evaluate the model's performance.

At first, the logistic regression algorithm trained the model on the original data.
After that I trained the model on the oversampled data to mitigate the class imbalance problem.

The model's performance is evaluated using various metrics such as accuracy, precision, recall, f1-score, which indicate the model's effectiveness in predicting high or low-risk loans. The confusion matrices were shown. 
The model achieved high precision, recall, and f1-scores for both classes in the training and testing classification reports, indicating its ability to accurately predict loan risk categories.

Compared to the model trained on non-oversampled data, the oversampled model performed better in predicting high-risk loans.
The model's performance is not affected by overfitting, indicating that the model can generalize well to new data.
The model can be used to predict loan risk categories for new loan applications, allowing lenders to make informed decisions and mitigate the risks associated with lending.
