# Predict Heart Disease Using Machine Learning

This repository contains a Jupyter Notebook that uses various Python-based Machine Learning and Data Science libraries to build a model capable of predicting whether someone has heart disease based on their medical attributes.

## Data
The dataset used in this project is from the UCI Heart Disease Data available on [Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).

## Features
The dataset contains the following features:

1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
  * 0: Typical angina
  * 1: Atypical angina
  * 2: Non-anginal pain
  * 3: Asymptomatic
4. trestbps - resting blood pressure (in mm Hg)
5. chol - serum cholesterol in mg/dl
6. fbs - fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. restecg - resting electrocardiographic results
8. thalach - maximum heart rate achieved
9. exang - exercise induced angina (1 = yes; 0 = no)
10. oldpeak - ST depression induced by exercise relative to rest
11. slope - the slope of the peak exercise ST segment
12. ca - number of major vessels (0-3) colored by fluoroscopy
13. thal - thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
14. target - diagnosis of heart disease (1 = yes; 0 = no)

## Notebook Structure
This notebook follows a structured approach to machine learning modeling:

1. Exploratory Data Analysis (EDA): Understanding the dataset and identifying patterns.
2. Data Preprocessing: Cleaning and preparing data for modeling.
3. Model Training: Building various models such as Logistic Regression, K-Nearest Neighbors, and Random Forest.
4. Model Evaluation: Evaluating model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
5. Model Comparison: Comparing different models to find the best performing one.
6. Model Fine-Tuning: Improving the chosen model through techniques like cross-validation and hyperparameter tuning.
7. Feature Importance: Identifying the most important features for the prediction task.
8. Reporting: Summarizing findings and presenting results.

## Results
The notebook evaluates several machine learning models and selects the best performing model based on various metrics.

## License
This project is licensed under the MIT License.
