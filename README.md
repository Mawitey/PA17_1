# 
Here is link to the notebook - https://github.com/Mawitey/RA11_1/blob/main/Pricing%20for%20used%20car%20dealership.ipynb

###  Problem statement
This project compares multiple machine learning models to predict whether a customer will subscribe to a term deposit (binary classification: yes or no) based on personal, economic, and campaign-related data. The dataset is sourced from the UCI Machine Learning Repository: Bank Marketing Data Set.

### Results
 Model	            Train Time	Train Accuracy	Test Accuracy
LogisticRegression    20.89        0.94            0.95
KNN                   0.0098       0.96            0.947
Decision Tree         0.13         1.0             0.93
SVC                   5.48         0.94            0.945
### Findings
Logistic Regression had the best performance overall with high accuracy and fast training time. Decision Trees were the most interpretable but slightly overfit. KNN required tuning but performed well. Feature scaling was critical for SVM and Logistic Regression.

### Next steps
