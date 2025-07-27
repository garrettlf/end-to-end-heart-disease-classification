 # **Predicting Heart Disease Using Machine Learning**
This project involves creating a machine learning model capable of predicting whether or not a patient has heart disease based on their clinical attributes. The project leverages popular Python-based data science libraries to clean, explore, and model data, with the goal of identifying the most effective approach for accurate predictions.

## Approach:

## **1. Problem Definition**
The goal is to answer the following question:
"Given clinical parameters about a patient, can we predict whether or not they have heart disease?"

## **2. Data**
The dataset is sourced from the Cleveland heart disease dataset, available in the UCI Machine Learning Repository. It includes various medical attributes, such as age, sex, blood pressure, and cholesterol levels, along with a target variable indicating the presence of heart disease.

## **3. Evaluation**
The success criterion in this project is achieving at least 95% accuracy.

## **4. Features**
A detailed data dictionary includes attributes such as:

**Age**: Patient's age in years.
**Sex**: Male (1) or female (0).
**Chest Pain Type (cp)**: Four categories of chest pain (e.g., typical angina, atypical angina).
**Resting Blood Pressure (trestbps)**: Blood pressure measured in mmHg on hospital admission.
**Cholesterol (chol)**: Serum cholesterol level in mg/dL.
**Fasting Blood Sugar (fbs)**: Whether fasting blood sugar is >120 mg/dL (1 = yes, 0 = no).
**Maximum Heart Rate (thalach)**: Achieved during exercise.
**Exercise-Induced Angina (exang)**: Whether exercise causes angina (1 = yes, 0 = no).
**Target**: Indicates the presence of heart disease (1 = yes, 0 = no).
(Additional features include ECG results, ST depression, slope, and major vessel count.)

## **5. Modelling**
Logistic Regression
K-Nearest Neighbors Classifier (KNN)
Random Forest Classifier
Metrics such as accuracy, precision, recall, and F1 scores were calculated for each model using cross-validation. Additionally, ROC curves and confusion matrices were analyzed to gain a deeper understanding of model performance.

## **Process Overview**

**1. Exploratory Data Analysis (EDA)**
EDA was conducted to:

Clean and ensure the data is complete and accurate.
Visualize relationships and trends within the dataset.
Identify correlations between features and the target variable.

**2. Model Comparison**
Three machine learning models were tested:


**3. Tools Used**
The following libraries were employed:

Pandas and NumPy for data manipulation and analysis.
Matplotlib for visualization.
scikit-learn for model implementation, evaluation, and tuning.

## **Outcome**
Through comparison and evaluation, the project identified the best-performing model based on its predictive accuracy and overall evaluation metrics. The findings highlight how machine learning can provide actionable insights into predicting heart disease, with potential applications in medical diagnostics.
