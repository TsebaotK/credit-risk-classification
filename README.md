# credit-risk-classification


In this assignment, a dataset of historical lending activity is used to build a model that can identify the creditworthiness of borrowers. I have used various techniques to train and evaluate the model based on loan risk. 
Initially, I split the data into training and testing datasets using the train test split. I then fitted Logistic regression to the training data and predicted the test dataset. 
In the next step, I resampled the original split sample using a random over-sampler module and fit it to the original training dataset. Then, I fitted the resampled training data using the Logistic Regression classifier and predicted the test data. 
The final step was to evaluate the models using the confusion matrix and print the classification report to see the accuracy of the prediction. 
