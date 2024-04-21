## Heart Disease Dectection

![images (2)](https://github.com/Estimatorbeat/HeartDiseaseUsingMachineLearning/assets/154437491/6487c9be-247d-440c-9b45-857e75ad9cbe)


## Project Overview
The "Heart Disease Using Machine Learning' project aims to develop an intelligent system capable of predicting the likelihood of a patient having heart disease. By leveraging advanced analytics and machine learning techniques on patients data, to accurately predict the likelihood of a patient having heart disease and implement targeted retention initiatives

## Project Objective
The primary objective of this project is to build and train a robust machine learning model that can accurately detect if Patient is likely to have heart disease. The model will be designed to accurately predict the likelihood of a patient having heart disease.

## Data Sources
The dataset used in this project was provided by 10Alytics. The data set contains Patient demprographic including age, sex, and other relevant information

## Data Preprocessing
Before feeding the data into the machine learning model, extensive data processing was performed. This include feature engineering and scaling features. Additionally, feature engineering techniques were applied to extract relevant information from the data

## Machine Learning Model
The prediction model is built using a supervised marchine learning approach. Training and test data was spilt 80:20. Several classification algorithm were experimented with such as:

- **Decisipon Trees
- **Random Forest
- **Logistic Regression
- **SGD Classifier
- **Support Vector Classifier (SVC) 
- **Naive Bayes
- **XGB Classifier

After Extensive experimentation and tuning, the final machine learning was selected based on its performance and generalization capabilities.

## Evaluation Metrics
To assess the performance of the machine learning model, the following evaluation metrics were used:

- **Precision: The proportion of correctly identified cases of heart disease among all patients classified as positive.
- **Recall: The proportion of correctly identified cases of heart disease among all actual patients classified as postive.
- **F1-score: The harmonic mean of precision and recall, providing a balance metric for model evaluation.
- **Accuracy: Accuracy measures the overall correctness of the model's predictions.(both heart disease and not).
  
## Key Insights
The purpose of this project aims to develop an intelligent system capable of predicting the likelihood of a patients having heart disease.
The best model that predicts with less error is to be chosen, subjecting them to the diiferent metrics including k-fold cross validation(accuracy, precision and recall).
The confusion matrix displays the error value for each model in terms of False Positive (Where the model predicts a patient have heart disease when they actually didn't - Precision) and False Negative (Where the model predicts a patient don't have heart disease where they actually have - Recall).
After Cross Validation, the model with the highest recall will be deployed. Recall is the most relevant matrix for evaluation in this business problem. This is because, the effort of the error (Recall) on the business if not addressed will be massive compared to that of precision.

## Conclusion
The 'Heart Disease using Marchine Learning' project showcases the effectiveness of machine learning algorithms in prediciting the likelihood of a patient having heart disease. By accurately identifying and predicting the likelihood of a patient having heart disease, this model enhances personalized predictions for individual patients based on their characteristics, blood pressure, heart rate achieved, and chest pain type with the Hospital.
Support Vector Classifier (SVC): For this business problem, Recall score is of more relevant and Support Vector Classifier (SVC) has highest recall score compared to other models. Hence, It should be depolyed by Peterside
Hospital for faceing the pressing need to address the likelihood of a patient having heart disease, as it has 89% Recall and Accuracy is 89%.

