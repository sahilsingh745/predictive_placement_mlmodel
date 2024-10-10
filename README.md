# Placement Prediction Model

This project predicts student placements based on **CGPA** and **IQ** using a Logistic Regression model. The steps include data preprocessing, scaling, model training, and evaluation.

## Project Overview

The objective of this project is to develop a machine learning model that predicts whether a student will be placed based on two key features:
- **CGPA (Cumulative Grade Point Average)**
- **IQ (Intelligence Quotient)**

The target variable is **Placement** (whether the student got placed or not).

## Dataset
The dataset consists of the following columns:
- `CGPA`: Continuous numerical feature representing the student's academic performance.
- `IQ`: Numerical feature representing the student's intelligence quotient.
- `Placement`: Binary target variable, where `1` indicates the student got placed and `0` indicates they did not.

## Approach

1. **Data Preprocessing**
   - Handled missing values and checked for data consistency.
   - Scaled the features (`CGPA` and `IQ`) using **StandardScaler** to ensure all features are on the same scale.

2. **Modeling**
   - Used **Logistic Regression** as the classification algorithm to predict placement outcomes.
   - Split the dataset into training and testing sets to evaluate model performance.

3. **Model Evaluation**
   - Evaluated the model using metrics such as accuracy, precision to assess its effectiveness in predicting student placements.
   
## Requirements

Install the following dependencies before running the code:

```bash
pip install numpy pandas scikit-learn
