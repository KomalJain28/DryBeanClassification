# DryBeanClassification

Project Overview
This project focuses on classifying dry bean types using machine learning models. The dataset was preprocessed by handling missing values, encoding categorical variables, and removing unnecessary columns. A heatmap was used to analyze correlations, and the data was split into training and testing sets with the target variable as the bean class.

Models Applied & Performance

Decision Tree Classifier
Training Accuracy: 94.68%
Testing Accuracy: 90.34%
Good performance but risk of overfitting.

Logistic Regression
Training Accuracy: 71.21%
Testing Accuracy: 72.53%
Limited performance due to data complexity.

K-Nearest Neighbors (KNN)
Training Accuracy: 67.7%
Testing Accuracy: 72.53%
Moderate performance, struggles with class separation.

Random Forest Classifier
Training Accuracy: 94.00%
Testing Accuracy: 91.96%
Strong performance, better generalization.

Support Vector Classifier (SVC)
Training Accuracy: 62.72%
Testing Accuracy: 63.12%
Underperformed on this dataset.

Voting Classifier (LR + DT + SVC)
Training Accuracy: 74.80%
Testing Accuracy: 74.77%
Improved stability but not the best performer.

AdaBoost Classifier
Training Accuracy: 100%
Testing Accuracy: 89.90%
Risk of overfitting but performed well.

XGBoost Classifier (Best Model)
Training Accuracy: 99.83%
Testing Accuracy: 91.51%
Best balance of accuracy and generalization.

Key Takeaways
XGBoost provided the best results with high accuracy and generalization.
Random Forest performed well, balancing training and testing accuracy.
Decision Tree showed strong accuracy but potential overfitting.
SVC and KNN underperformed due to data complexity.
