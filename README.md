## credit-risk-classification

This project aims to develop a machine learning model for credit risk classification using historical lending data from a peer-to-peer lending services company. The dataset contains information on loan status, with '0' indicating a healthy loan and '1' indicating a high-risk loan. 


#### Tasks involved:

- Read-in the lending_data.csv data into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.
- Create a Logistic Regression Model with the Original Data
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model by generate a confusion matrix and the classification report.


