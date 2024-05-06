## Credit Risk Analysis Report

This project aims to develop a machine learning model for credit risk classification using historical lending data from a peer-to-peer lending services company. The dataset contains information on loan status, with '0' indicating a healthy loan and '1' indicating a high-risk loan. The tasks involve splitting the data into training and testing sets, creating a logistic regression model, evaluating its performance through confusion matrix and classification report.

Based on the classification report provided below, the logistic regression model seems to fit the oversampled data quite well in predicting both the low-risk and high-risk loans.

- Precision for healthy loan is very high at 1.00, indicating that when the model predicts the label as healthy loan, it is cohigh-risk loan is 0.86, which is also quite good, indicating that when the model predicts the label as high-risk loan, it is correct in around 86% of cases.
- Recall for label healthy loan is 0.99, meaning the model correctly identifies 99% of the instances belonging to class healthy loan. Recall for label high-risk loan is 0.94, suggesting that the model identifies 94% of the instances belonging to high-risk loan.
- Overall accuracy is 99%, suggesting that the model is performing exceptionally well on the dataset.
