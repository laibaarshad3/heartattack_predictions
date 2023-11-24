# Heart Attack Prediction Model

## Overview
This project aims to predict the likelihood of a heart attack using a machine learning model based on logistic regression. The dataset used for training and testing includes various health-related features of individuals. The model is designed to assist in identifying potential cases of heart disease.

## Features
- Logistic Regression
- SMOTE (Synthetic Minority Over-sampling Technique) for handling class imbalance
- Removal of outliers
- No missing values or object types in the dataset

## Dataset
The dataset contains the following columns:
- age
- sex
- cp (chest pain type)
- trtbps (resting blood pressure)
- chol (serum cholesterol level)
- fbs (fasting blood sugar)
- restecg (resting electrocardiographic results)
- thalachh (maximum heart rate achieved)
- exng (exercise induced angina)
- oldpeak (ST depression induced by exercise)
- slp (slope of the peak exercise ST segment)
- caa (number of major vessels colored by fluoroscopy)
- thall (thalassemia)
- output (presence of heart disease)

## Preprocessing
- Outlier removal
- Handling class imbalance using SMOTE
- Logistic regression model training

## Setup
1. Install required dependencies: `pip install pandas numpy scikit-learn imbalanced-learn`
2. Clone the repository: `git clone https://github.com/your-username/heart-attack-prediction.git`
3. Navigate to the project directory: `cd heart-attack-prediction`
4. Run the model: `python predict_heart_attack.py`

## Usage
1. Modify the dataset or features as needed.
2. Run the script `predict_heart_attack.py` to train the model and make predictions.

## Results
The logistic regression model achieved an accuracy of X% on the test set. The SMOTE technique improved the model's performance by addressing class imbalance.

# heartattack_predictions
