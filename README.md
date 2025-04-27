# Medical-Test-Result-Analysis-for-Disease-Risk
Objective:
The goal of this project is to predict the risk of disease (specifically diabetes) based on patient diagnostic test results and health indicators. Early prediction can help in timely preventive actions and better healthcare outcomes.

Dataset Details:

Name: diabetes_binary_5050split_health_indicators_BRFSS2015.csv

Size: 70,692 records with 21 health-related features.

Target Variable: Diabetes_binary (0 = No Diabetes, 1 = Diabetes).

Methodology:

Data Exploration:

Checked dataset shape, missing values, and feature types.

Preprocessing:

Separated features (X) and target (y).

Split the dataset into 70% training and 30% testing.

Scaled features using StandardScaler for some models.

Model Training:

Logistic Regression (for baseline binary classification).

Random Forest Classifier (for better accuracy with ensemble learning).

Evaluation Metrics:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Results:

Logistic Regression Accuracy: ~73%

Random Forest Classifier Accuracy: ~80%

Random Forest showed better predictive performance overall.

Key Influential Features: HighBP (Blood Pressure), BMI (Body Mass Index), Age, Physical Activity, Smoking.

Conclusion:

Machine learning models can effectively predict disease risk based on health indicators.

Random Forest is preferred for this dataset due to its higher accuracy.

Early identification of patients at risk allows healthcare providers to take preventive measures.

Future Scope:

Try other models like XGBoost, SVM, Neural Networks.

Perform hyperparameter tuning for even better results.

Deploy the model as a web or mobile app for real-time use.
