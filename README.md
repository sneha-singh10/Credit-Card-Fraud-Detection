# Credit-Card-Fraud-Detection

Project Overview: 

This project focuses on building a machine learning model to detect fraudulent credit card transactions. The goal is to identify potentially fraudulent activities based on transaction data.

Data:

The dataset used in this project is the "Credit Card Fraud Detection" dataset, which contains anonymized transaction data. Due to the sensitive nature of the data, the features (V1-V28) are the result of a PCA transformation. The only features not transformed are 'Time' and 'Amount'. The 'Class' column represents the target variable (0 for normal transactions, 1 for fraudulent).

Methodology:

Data Loading and Exploration: Loaded and explored the dataset to understand its structure, check for missing values, and analyze the distribution of transactions.
Handling Class Imbalance: Addressed the significant class imbalance by creating a balanced subset of the data through random sampling of normal transactions.
Data Splitting: Split the balanced dataset into training and testing sets.
Model Training: Trained a Logistic Regression model on the training data.
Model Evaluation: Evaluated the model's performance using accuracy score on both the training and testing data.
Results
The trained Logistic Regression model achieved a test accuracy of over 90% on the balanced dataset, demonstrating its ability to identify fraudulent transactions. Further evaluation with metrics like precision and recall can provide deeper insights into the model's effectiveness in a real-world fraud detection scenario.

How to Run:

Clone this repository.
Ensure you have the necessary libraries installed (e.g., pandas, scikit-learn).
Run the Jupyter Notebook or Python script containing the code.
Future Improvements
Explore other machine learning algorithms (e.g., RandomForest, Support Vector Machines) to potentially improve performance.
Implement more advanced techniques for handling class imbalance, such as SMOTE.
Perform hyperparameter tuning to optimize the model.
Analyze the importance of different features in predicting fraud.
