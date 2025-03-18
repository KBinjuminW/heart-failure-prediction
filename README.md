# Heart Failure Prediction Project

This project focuses on predicting the likelihood of heart failure based on clinical data using machine learning. The dataset used for this project contains clinical records of patients, including medical information such as age, blood pressure, diabetes, and serum levels, among other factors.

## Project Overview

In this project, we aim to analyze the clinical dataset to predict whether a patient will experience a heart failure event (`DEATH_EVENT`). The main objective is to perform data cleaning, exploratory data analysis (EDA), and machine learning modeling to understand the factors influencing heart failure and predict outcomes for new patients.

### Dataset
The dataset used in this project is the **Heart Failure Clinical Data** dataset, which can be found on [Kaggle](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data). It contains the following columns:
- `age`: Age of the patient
- `anaemia`: Whether the patient has anaemia (1 if yes, 0 if no)
- `creatinine_phosphokinase`: Level of creatinine phosphokinase in the blood
- `diabetes`: Whether the patient has diabetes (1 if yes, 0 if no)
- `ejection_fraction`: Percentage of blood leaving the heart during a heartbeat
- `high_blood_pressure`: Whether the patient has high blood pressure (1 if yes, 0 if no)
- `platelets`: Platelets in the blood
- `serum_creatinine`: Serum creatinine levels
- `serum_sodium`: Serum sodium levels
- `sex`: Gender of the patient (1 for male, 0 for female)
- `smoking`: Whether the patient smokes (1 if yes, 0 if no)
- `time`: Duration of the patient's observation in days
- `DEATH_EVENT`: Outcome (1 if the patient passed away, 0 if the patient survived)

## Steps in the Project

1. **Data Preprocessing**: 
   - Import necessary libraries (e.g., pandas, numpy, seaborn, sklearn).
   - Load the dataset into a pandas DataFrame.
   - Clean the data (handle missing values, encode categorical variables, etc.).

2. **Exploratory Data Analysis (EDA)**: 
   - Explore the dataset visually using various plots (e.g., histograms, bar charts, box plots) to understand the distribution of data and relationships between features.
   - Perform statistical analysis to observe trends in the data.

3. **Feature Engineering**: 
   - Analyze the features and decide which features are most important for predicting the target variable (`DEATH_EVENT`).
   - Transform the data into a format suitable for machine learning models.

4. **Model Building**: 
   - Train machine learning models such as logistic regression, random forest, or gradient boosting classifiers.
   - Evaluate the models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

5. **Model Evaluation**: 
   - Compare different models and choose the best-performing one.
   - Use the model to make predictions and evaluate its performance on test data.

6. **Visualization**: 
   - Visualize model performance, feature importance, and any other relevant insights.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heart-failure-prediction.git
   cd heart-failure-prediction
# heart-failure-prediction
