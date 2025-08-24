This repository contains a few small machine learning projects that I completed

# STROKE PREDICTION USING MACHINE LEARNING MODELS

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




## Performance Comparison Between Machine Learning Models: TabPFN, Random Forest, Decision Tree, Support Vector Machine, AdaBoost, and Logistic Regression.


### pr_auc and auc_roc for TabPFN:
<img width="1447" height="489" alt="image" src="https://github.com/user-attachments/assets/74f42077-1cac-41a0-922c-5ba30a4680e4" />

### pr_auc and auc_roc for non-TabPFN predictors:
<img width="1441" height="103" alt="image" src="https://github.com/user-attachments/assets/3ed791e6-d02d-4449-88bb-7bb89e74a01d" />

#### Thoughts:
There is a very large class imbalance for this dataset. Initially, the model was predicting all negatives and achieving a 95% accuracy rate while having a 0% recall for actual stroke case.
Methods I tried to solve class imbalance:
1. Threshold Sweeping
     I tried to fine tune my threshold.
2. SMOTE
3. Focal Weighting
  

# HEART DISEASE PREDICTION USING MACHINE LEARNING MODELS

Dataset: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
Compiler: fedesoriano

I predict using 11 different features:
Age: age of the patient [years]
Sex: sex of the patient [M: Male, F: Female]
ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
RestingBP: resting blood pressure [mm Hg]
Cholesterol: serum cholesterol [mm/dl]
FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
Oldpeak: oldpeak = ST [Numeric value measured in depression]
ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

## Performance Comparison Between Machine Learning Models: TabPFN, Random Forest, Decision Tree, Support Vector Machine, AdaBoost, and Logistic Regression.

### pr_auc and auc_roc for TabPFN:
<img width="530" height="272" alt="image" src="https://github.com/user-attachments/assets/bd32a221-9962-4e5d-a37c-c9a0c61f5fa8" />

### pr_auc and auc_roc for non-TabPFN predictors:


