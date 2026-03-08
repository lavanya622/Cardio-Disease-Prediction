# Cardio-Disease-Prediction

Predicts cardiovascular disease risk using Logistic Regression.

# Cardiovascular Disease Prediction Project

## Overview
This project predicts the **risk of cardiovascular disease (CVD)** using a **Logistic Regression model**.  
It allows users to input patient details like **age, blood pressure, cholesterol, glucose, and lifestyle factors** to get:

- Disease prediction (Yes/No)  
- Risk probability (%)  

The goal is to provide **early warning** and help with **preventive healthcare**.

---

## Project Workflow

1. **Data Collection**  
   - Used a dataset containing patient information such as age, gender, blood pressure, cholesterol, glucose, smoking, alcohol, and physical activity.

2. **Data Preprocessing**  
   - Checked for missing values and handled them.  
   - Converted categorical variables into numeric form.  
   - Prepared the dataset for model training.

3. **Model Training**  
   - Trained a **Logistic Regression model** to predict cardiovascular disease.  
   - Evaluated model performance using **accuracy and confusion matrix**.  

4. **Prediction Script**  
   - Created `predict.py` to allow **interactive input** of new patient data.  
   - The script outputs:
     - Disease prediction (0 = No, 1 = Yes)  
     - Risk percentage (%)  

---

## Project Files
- `Cardiovascular Disease Prediction.ipynb` → Notebook with the project code and model training  
- `README.md` → This file with project explanation  

## How to Run
1. Open the notebook in Google Colab or locally using Jupyter.  
2. Run the cells in order to see data processing, model training, and prediction.  
3. Enter patient details when prompted to get the **risk prediction**.

## Notes 
- The model predictions are based on the data provided in the notebook.  
- Use realistic values for **blood pressure, cholesterol, and glucose** to get meaningful results.

