# Heart Diabetes Prediction Project

## Introduction
This project aims to predict the presence of heart diabetes in patients based on various medical attributes. The model is built using multiple machine learning algorithms to achieve better accuracy and performance.

## Algorithms Used
- Logistic Regression
- Decision Tree
- Random Forest Regression

## Dataset Columns
Below are the column names and their descriptions:

| Column    | Description                                                                                          |
|-----------|------------------------------------------------------------------------------------------------------|
| `sex`     | Gender of the patient (1 = Male, 0 = Female)                                                         |
| `cp`      | Chest Pain Type (0: Typical angina, 1: Atypical angina, 2: Non-anginal pain, 3: Asymptomatic)        |
| `trtbps`  | Resting blood pressure (in mm Hg)                                                                    |
| `chol`    | Serum cholesterol level in mg/dl                                                                     |
| `fbs`     | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)                                                |
| `restecg` | Resting electrocardiographic results (0: Normal, 1: ST-T abnormality, 2: Left ventricular hypertrophy)|
| `thalachh`| Maximum heart rate achieved                                                                          |
| `exng`    | Exercise induced angina (1 = yes, 0 = no)                                                            |
| `oldpeak` | ST depression induced by exercise relative to rest                                                   |
| `slp`     | Slope of the peak exercise ST segment (0: Upsloping, 1: Flat, 2: Downsloping)                        |
| `caa`     | Number of major vessels (0-3) colored by fluoroscopy                                                 |
| `thall`   | Thalassemia (0: Normal, 1: Fixed defect, 2: Reversible defect)                                       |

## Conclusion
Using Logistic Regression, Decision Tree, and Random Forest Regression, we aim to accurately classify whether a patient has heart diabetes based on the provided features. By comparing the performance of these algorithms, the model provides a reliable prediction that assists in the early diagnosis of heart diabetes.
