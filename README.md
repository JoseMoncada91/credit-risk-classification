Module 20 Challenge - Credit Risk Classification
By: Jose Moncada

Project Overview:
This project uses a logistic regression model to classify loan data into two categories: healthy loans (0) and high-risk loans (1). The goal is to assess how well the model can predict both types of loans based on a variety of features.

Project Steps:
Data Loading: The dataset was loaded from a CSV file located in the Resources folder.
Data Preprocessing: The labels (loan status) and features (other columns) were separated, and the data was split into training and testing datasets.
Model Training: A logistic regression model was trained using the training dataset.
Model Prediction: The model made predictions on the testing dataset.
Model Evaluation: The performance of the model was evaluated using a confusion matrix and classification report.

Key Insights:
Healthy Loans (Class 0): The model achieved nearly perfect precision (1.00) and recall (0.99) for predicting healthy loans.
High-Risk Loans (Class 1): The model showed good precision (0.84) and recall (0.94) for high-risk loans but had slightly lower performance compared to healthy loans.
Overall Accuracy: The model achieved a high overall accuracy of 99%, indicating strong performance.

Technologies Used:
Python
Pandas
Scikit-learn
NumPy
