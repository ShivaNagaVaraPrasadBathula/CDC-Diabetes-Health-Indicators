# CDC-Diabetes-Health-Indicators
The CDC Diabetes Health Indicators dataset is a comprehensive collection of health-related data aimed at understanding diabetes risk factors. It includes health indicators (e.g., BMI, blood pressure), demographic information (e.g., age, gender), and lifestyle factors (e.g., diet, exercise). The dataset contains 253,680 instances and 21 features, categorizing individuals as diabetic, pre-diabetic, or healthy, and is suitable for classification tasks. It also includes sensitive information such as gender and income, with no missing values present.
## Dataset
The dataset can be accessed at https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators 
## Data Cleaning
The dataset has been cleaned and pre-processed to remove any duplicates and null values. 
## Feature Selection
The feature selection process involves selecting the most important features that contribute to the prediction of diabetes. Two methods have been used for feature selection: Random Forest Classifier, and Recursive Feature Elimination (RFE).
## Models
The model has been built using two different classification algorithms: Logistic Regression, Random Forest Classifier, and two clustering algorithms: K-Means Clustering, and DBSACN Clustering. The performance of each model has been evaluated using various metrics such as AUC, accuracy, precision, recall, and F1 score.
## Results
After evaluating the performance of each model, the Logistic Regression with 10 features was found to be the best performing model.
## Conclusion
This project demonstrates how machine learning can be used to predict the likelihood of a patient having diabetes based on various health indicators. The model can be further improved by incorporating additional features and using more advanced machine learning techniques.
