# Predicting Heart Disease - Machine Learning Using R

Author: Sarah Choi, Sophoa Oldfield, Brett Hungsanger


## Introduction 

Today, cardiovascular diseases are the primary cause of death in United States. People with cardiovascular disease or at high cardiovascular risk need early detection and management 

Cardiovascular disease describes heart conditions that involve diseased blood vessels, structural problems within the heart and blood clots.Some examples of more known heart diseases are congenital heart disease, arrhythmia, and high blood pressure 

The ultimate goal of our model is to accurately understand heart health and complications through heart failure while having predictive accuracy and interpretability. 

Variables: 
- Age 
- Sex 
- Chest pain type: typical angina (TA), Atypical Angina (ATA), Nonanginal Pain (NAP), Asymptomatic (ASY)
- Resting BP: (mmHg)
- Cholesterol 
- FastingBS: Fasting blood sugar (1 if > 120 mg/dl, 0 otherwise)
- RestingECG: resting ecochardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR 
- ExerciseAngina: whether there was exercise induced angina (Y or N)
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- OldPeak: oldpeak = ST [Numeric value measured in depression]
- HeartDisease: output class [1: heart disease, 0: Normal]
- Heart Disease binary: categorical heartDisease
- Measured cholesterol: many variables were missing cholesterol variables so this variable stated whether a case has a cholesterol value

Detailed data context and information can be found here: https://www.kaggle.com/fedesoriano/heart-failure-prediction


## Regression Task 

The goal of our regression task was to accurately predict an individual’s resting blood pressure (RestingBP) using all 12 predictors in our data set.

### Models/Methods

1. Ordinary least squares model (OLS)
2. LASSO model
3. GAM model (using natural splines) 

Model evaluations: 
RMSE and MAE, Residual plots

## Classification Task 

The goal of our classification task was to accurately predict an individual’s likelihood of getting heart disease based on	predictors

### Models/Methods

1. LASSO Logistic Regression
2. Random Forest

Model Evaluations: 
Accuracy measure, threshold 

## Unsupervised Learning Task 

The goal of our unsupervised learning task was to see what natural groupings can be found within our dataset

### Models/Methods

1. Hierarchical clustering 

## Resources/Additional Info

You can find a recorded presentation of our project here: https://drive.google.com/file/d/1Lo-wfCum082djZQnAe4aoLYWQO5CgraR/view?usp=sharing

Slideshow link: https://docs.google.com/presentation/d/1mcofLmQ22B2fSFFRMPtjxekTzqYWD9Od8pW31bCowoE/edit?usp=sharing

