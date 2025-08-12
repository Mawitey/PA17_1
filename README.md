# Comparing Classifiers
Here is link to the notebook - https://github.com/Mawitey/PA17_1/blob/main/practical%20assignment%203.ipynb

###  Problem statement
This project compares multiple machine learning models to predict whether a customer will subscribe to a term deposit (binary classification: yes or no) based on personal, economic, and campaign-related data. The dataset is sourced from the UCI Machine Learning Repository: Bank Marketing Data Set.

### Results
LogisticRegression has 91% test accuracy, while knn has 90% test accuracy. Decision tree has 88.77% test accuracy while SVC has 89.45% test accuracy.
### Findings
Four classification models were evaluated — Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM) — based on their training and test accuracy. KNN achieved the highest test accuracy (92.24%), indicating strong generalization to unseen data. Logistic Regression showed a balanced performance, with train and test accuracies closely matched (~91%), suggesting minimal overfitting. The Decision Tree model demonstrated perfect training accuracy (100%) but a lower test accuracy (88.77%), indicating overfitting. SVM provided stable but slightly lower accuracy (~89%) compared to KNN and Logistic Regression. While Logistic Regression was the slowest to train, KNN offered the best balance between accuracy and generalization, making it the top-performing model in this comparison.


### Next steps
Next I will try to deploy the best performing model, so I can have an end to end working model.
