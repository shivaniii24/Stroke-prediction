<div align="center">
  <h1 align="center"> " Stroke Prediction " </h1>
</div>

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/75872316/130348189-c283a8ac-4d84-4fcb-ae06-974e9b5fa617.png">
</p>

According to the **World Health Organization (WHO)** stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.This dataset is used to predict whether a patient is likely to get a stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.

This project describes step-by-step procedures for building a **Machine Learning (ML) Model for Stroke Prediction** and for analysing which features are most useful for the prediction.

</br>

### => About Dataset

The dataset contains 5110 real world observations and 10 different attributes:
- `gender` : "Male", "Female" or "Other"
- `age` : age of the patient
- `hypertension`: 
    - 0: if the patient doesn't have hypertension 
    - 1: if the patient has hypertension
- `heart_disease`: 
    - 0: if the patient doesn't have any heart diseases 
    - 1: if the patient has a heart disease
- `ever_married` : "No" or "Yes"
- `Residence_type` : "Rural" or "Urban"
- `avg_glucose_level` : average glucose level in blood
- `bmi` : body mass index
- `smoking_status` : "formerly smoked", "never smoked", "smokes" or "Unknown"
- `stroke` : 1 if the patient had a stroke or 0 if not

</br>

### => Working of System

- **SVM**: Support Vector Machine
- **Input**: Dataset can be consider as input
- **Output**: Classification into 0 (no stroke) or 1 (stroke)

</br>

## => Dataset
Refer dataset to download from [here](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).
