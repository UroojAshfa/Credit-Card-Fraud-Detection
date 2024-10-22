Designed a machine learning-based system to detect fraudulent credit card transactions using the highly imbalanced dataset.


Data Preprocessing:
Applied data cleaning techniques, including dropping irrelevant features and handling missing values.
Split the dataset into features (X) and target variable (Class), which indicates fraud (1) or non-fraud (0).
Addressed class imbalance through oversampling techniques to balance the number of fraudulent and non-fraudulent transactions.


Modeling:
Implemented multiple machine learning models including Logistic Regression and Decision Tree Classifier to predict fraudulent transactions.
Evaluated model performance using metrics such as Accuracy, Precision, Recall, and F1-Score. The Logistic Regression model achieved a high accuracy of 94.21%, while the Decision Tree Classifier attained 91.05%.
Logistic Regression achieved superior precision (98.9%) and recall (90.19%) for identifying fraudulent cases.


Model Optimization: Tuned hyperparameters to improve model performance and addressed convergence issues in logistic regression.


Model Deployment: Utilized joblib for saving and loading the trained models, enabling ease of future deployment.


The dataset on which the model is based on is: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.
(The project was inspired from a youtube video.)



