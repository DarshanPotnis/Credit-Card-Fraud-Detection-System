# Credit-Card-Fraud-Detection-System

📊 Project Description:
Welcome to the Credit Card Fraud Detection project! In this repository, I have developed a machine-learning model using Logistic Regression to tackle the challenging problem of identifying fraudulent credit card transactions. To address the issue of imbalanced data, I have applied undersampling techniques to balance the dataset effectively.

📉 Imbalanced datasets are a common occurrence in fraud detection tasks, where the number of genuine transactions far outweighs the occurrences of fraudulent ones. This severe class imbalance can lead to biased model predictions, favoring the majority class and severely impacting the detection of fraud cases. To combat this, I have implemented undersampling techniques to reduce the number of genuine transactions, allowing the model to learn from a more balanced dataset.

🛠️ The project consists of the following key components:

Data Preprocessing: I have carefully processed the credit card transaction data, handling missing values, and performing feature scaling as necessary. The dataset has been split into training and testing sets to evaluate model performance accurately.

Logistic Regression Model: I selected the Logistic Regression algorithm as it is an effective tool for binary classification problems. The model has been trained on the undersampled training dataset, leveraging the Scikit-learn library in Python.

Undersampling Techniques: To achieve a balanced dataset, I have employed various undersampling techniques, such as Random Undersampling and NearMiss, strategically reducing the instances of genuine transactions while retaining the fraud cases.

Model Evaluation: The performance of the Logistic Regression model is assessed using relevant evaluation metrics, including precision, recall, F1-score, and accuracy. Additionally, I have plotted the confusion matrix to gain deeper insights into the model's performance.

Results and Discussions: The project's findings and observations are documented in detail, highlighting the impact of undersampling on model performance and the trade-offs involved.
