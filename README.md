# Decision-Tree
Decision Tree using Diabetes Readmissions dataset.

Steps of Decision Tree process:
1. Generate training and Test samples for the Diabetes data set, of sizes 70% and 30%. 
2. Build a Logistic Regression model for Train for predicting the “Readmitted” variable, using the other variables. Combine the < 30 days and > 30 days values to “Yes”. 
3. Generate confusion matrix on train dataset. Consider the classification bound.
4. Predict test results and assign ‘No’ / ‘Yes’ or 0 / 1 to each observation based on the classification bound.
5. Compare proportion of 0s (No) and 1s (Yes) predicted correctly in train and test.
