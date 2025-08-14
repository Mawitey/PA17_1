# Comparing Classifiers
Here is link to the notebook - https://github.com/Mawitey/PA17_1/blob/main/Practical%20Application%203.ipynb

###  Problem statement
This project compares multiple machine learning models to predict whether a customer will subscribe to a term deposit (binary classification: yes or no) based on personal, economic, and campaign-related data. The dataset is sourced from the UCI Machine Learning Repository: Bank Marketing Data Set.

### Results
LogisticRegression has the highest test accuracy, it's probably making fewer total errors (false positive and false negative) than the other models. Decision trees has perfect training data but it makes more wrong predictions on unseen data which could be a mix of both FP and FN. KNN is almost tied with Logistic regression and SVM has balanced but slightly lower accuracy.
### Findings
From the comparison, Logistic Regression achieved the highest test accuracy (0.9521), slightly outperforming KNN (0.9463). However, it was the slowest to train (96.58 s) due to the high max_iter value. KNN trained very quickly (0.02 s) while maintaining competitive accuracy, making it a good balance of speed and performance. Decision Tree had perfect training accuracy (1.0) but the lowest test accuracy (0.9378), indicating overfitting. SVM offered solid and balanced performance (test accuracy 0.94) but required significantly more time than KNN or Decision Tree. Overall, KNN or Logistic Regression may be optimal depending on whether speed or slightly higher accuracy is the priority.


### Next steps
Next I will try to deploy the best performing model, so I can have an end to end working model.
