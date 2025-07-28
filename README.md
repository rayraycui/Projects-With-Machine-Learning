This repository contains a few small machine learning projects that I completed

# STROKE PREDICTOR

Dataset: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data
Compiler: fedesoriano 

I predict using 10 different features:
1) gender: "Male", "Female" or "Other"
2) age: age of the patient
3) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
4) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
5) ever_married: "No" or "Yes"
6) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
7) Residence_type: "Rural" or "Urban"
8) avg_glucose_level: average glucose level in blood
9) bmi: body mass index
10) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*

<img width="1394" height="36" alt="image" src="https://github.com/user-attachments/assets/64c0b7e5-bb2b-4b4a-9235-134dcb7ff416" />




## A comparison of performance between the stroke predictor usingTabpfn and the stroke predictor using other algorithms such as RandomForest, ADAboost, SVC, Decision Tree, and Logistic Regression


### pr_auc and auc_roc for Tabpfn:
<img width="1447" height="489" alt="image" src="https://github.com/user-attachments/assets/74f42077-1cac-41a0-922c-5ba30a4680e4" />

### pr_auc and auc_roc for non-Tabpfn predictors:
<img width="1441" height="103" alt="image" src="https://github.com/user-attachments/assets/3ed791e6-d02d-4449-88bb-7bb89e74a01d" />
