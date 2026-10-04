# Turbine Health Monitoring and Failure Forecasting

## About

This project uses machine learning to monitor wind turbine health and predict possible failures.

The model uses turbine parameters such as wind speed, rotor speed, blade angle, gearbox temperature, generator temperature, vibration, and other operating conditions.

## Objectives

- Identify conditions that may lead to turbine failures
- Predict whether a turbine may fail
- Predict different types of turbine faults
- Understand which features have the most impact on predictions
- Support better maintenance decisions and reduce downtime

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- SHAP
- Jupyter Notebook

## Project Workflow

1. Data exploration and preprocessing
2. Feature engineering
3. Exploratory Data Analysis (EDA)
4. Model training
5. Model comparison
6. Hyperparameter tuning
7. Model evaluation
8. SHAP analysis
9. Failure prediction

## Machine Learning Models

The following models were tested:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

XGBoost achieved the highest accuracy of **92.0%** among the tested models and was selected as the best-performing model in the project. :contentReference[oaicite:0]{index=0}

## Key Findings

- XGBoost achieved 92.0% accuracy.
- Random Forest achieved 90.1% accuracy.
- Higher vibration levels were associated with turbine failure.
- Vibration, blade angle, wind speed, and generator temperature had a significant influence on model predictions.
- SHAP analysis was used to understand the contribution of individual features to model predictions.
- The model was able to predict both healthy and failure conditions. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

## Project Images

### Feature Interaction Analysis

<img width="806" height="741" alt="Feature interaction analysis" src="https://github.com/user-attachments/assets/018c55f1-f54a-4122-bb4e-64cdca8ce884" />


### Vibration Distribution

<img width="571" height="455" alt="Vibration distribution" src="https://github.com/user-attachments/assets/2c41d885-8315-45c0-b869-f62c5c3cce21" />


### SHAP Analysis

<img width="852" height="598" alt="SHAP explanation" src="https://github.com/user-attachments/assets/ba5c7ceb-e0a7-4607-a8e7-97b7ab071a83" />


### SHAP Interaction Analysis

<img width="583" height="680" alt="SHAP interaction analysis" src="https://github.com/user-attachments/assets/ef231317-650f-4f5b-8960-395e33611bce" />



## Repository Structure

```text
Turbine_Health_Monitoring/
│
├── Data/
│   └── turbine_data.csv   
│
├── Notebook/
│   ├── Turbine Health Monitoring.ipynb
│   └── turbine_model.pkl
│
├── Docs/
│   └── Project Document.pdf
│
├── Presentation/
│   └── Project Presentation.pptx
│
├── images/
│   ├── Feature Interaction Analysis.png
│   ├── Vibration Distribution.png
│   ├── SHAP Explaination.png
│   └── SHAP Interaction Analysis.png
│
└── README.md
