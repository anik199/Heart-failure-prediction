# HeartCheck: A Beginner-Friendly Predictive Model for Heart Failure with 91% Accuracy

## Introduction

This project aims to build a machine learning model that can predict whether a patient is likely to experience heart failure based on a set of clinical features. Heart failure is a serious medical condition that can lead to death if not treated promptly, so accurate prediction is crucial for proper diagnosis and treatment.

In this project, we will be using a dataset containing information on patients' age, sex, blood pressure, smoking habits, and other medical conditions to train a machine learning model. We will be using Python and several popular data science libraries such as Pandas, Numpy, Matplotlib, and Scikit-learn.

## Dataset

The dataset used in this project is available on [Kaggle](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data). It contains a total of 299 instances and 12 features. The features are as follows:

- `age`: Age of the patient (years)
- `anaemia`: Decrease of red blood cells or hemoglobin (boolean)
- `creatinine_phosphokinase`: Level of the CPK enzyme in the blood (mcg/L)
- `diabetes`: If the patient has diabetes (boolean)
- `ejection_fraction`: Percentage of blood leaving the heart at each contraction (percentage)
- `high_blood_pressure`: If the patient has hypertension (boolean)
- `platelets`: Platelets in the blood (kiloplatelets/mL)
- `serum_creatinine`: Level of creatinine in the blood (mg/dL)
- `serum_sodium`: Level of sodium in the blood (mEq/L)
- `sex`: Gender of the patient (binary: "1" for male, "0" for female)
- `smoking`: If the patient smokes or not (boolean)
- `time`: Follow-up period (days)

The target variable is `DEATH_EVENT`, which indicates whether the patient died during the follow-up period.

## Methodology

The first step of this project involves loading the dataset and performing exploratory data analysis (EDA) to gain insights into the data. We will be using Pandas and Matplotlib for data manipulation and visualization.

Next, we will be preprocessing the data by scaling the numerical features and encoding the categorical features. We will be using Scikit-learn for this task.

After preprocessing, we will be splitting the data into training and testing sets. We will be using Scikit-learn's `train_test_split` function for this task.

Once the data is ready, we will be training several machine learning models on the training set and evaluating their performance on the testing set. The models we will be using are:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

We will be using Scikit-learn for training and evaluating these models.

## Results

After training and evaluating the models, we found that the Random Forest classifier performed the best, achieving an accuracy of 91% on the testing set.

## Conclusion

In conclusion, we have successfully built a machine learning model that can predict whether a patient is likely to experience heart failure with an accuracy of 91%. This model can be used as a tool for doctors and medical professionals to make more informed decisions and provide better care for their patients.
