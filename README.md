# Medical Insurance Cost Prediction

## Project Overview

This project uses Machine Learning to predict medical insurance charges based on customer characteristics such as age, BMI, smoking status, gender, number of children, and region.

The project was developed as part of my Machine Learning and AI internship at Big Brains.

## Problem Statement

Medical insurance costs can vary depending on different personal and lifestyle factors. The goal of this project is to build a Machine Learning model that can estimate insurance charges based on customer information.

## Dataset

The project uses the Medical Cost Personal Dataset.

### Features

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Region

### Target Variable

- Charges

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Identified duplicate records
- Removed duplicate records
- Converted categorical variables into numerical values
- Prepared the dataset for Machine Learning

Categorical variables such as gender, smoking status, and region were encoded using one-hot encoding.

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the relationships between different features and insurance charges.

The analysis included:

- Age vs Insurance Charges
- BMI vs Insurance Charges
- Smoking Status vs Insurance Charges
- Correlation analysis

The analysis showed that age, BMI, and smoking status are important factors related to insurance charges.

## Machine Learning Model

A Multiple Linear Regression model was trained to predict medical insurance charges.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

The model was trained using the training dataset and evaluated using the testing dataset.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to measure the difference between actual and predicted insurance charges and evaluate the overall performance of the model.

## Prediction Application

A simple Streamlit application was created where users can enter:

- Age
- BMI
- Gender
- Smoking Status
- Number of Children
- Region

The application then uses the trained Linear Regression model to estimate the medical insurance cost.

## Screenshots

### Application Interface

Add your application screenshot here.

### Prediction Result

Add your prediction screenshot here.

### Actual vs Predicted

Add your actual vs predicted screenshot here.

## Limitations

- The model is trained on a specific dataset and may not represent all populations.
- Linear Regression assumes a relatively linear relationship between input variables and the target.
- The prediction is an estimate and should not be considered an actual insurance quote.
- Model performance depends on the quality and characteristics of the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit
- Google Colab
- GitHub

## Conclusion

This project provided practical experience in the complete Machine Learning workflow, including data collection, preprocessing, exploratory data analysis, model training, evaluation, and deployment.

The final application allows users to enter customer information and receive an estimated medical insurance cost.

#MachineLearning #Python #DataScience #AI #Streamlit #BigBrains