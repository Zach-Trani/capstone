# Stroke Prediction Machine Learning Model - Portfolio Project

## Overview
This project showcases my capstone work in developing a machine learning model to predict the likelihood of stroke occurrences in patients. The goal was to transition from a reactive to a preventative approach in healthcare, leveraging data science and machine learning to provide actionable insights for patients and healthcare providers.

## Project Summary
The project involved creating a logistic regression model to predict stroke risk based on various contributing factors such as age, BMI, gender, and smoking status. The model was designed to be interpretable, allowing both patients and doctors to understand the importance of each factor in the prediction.

### Key Features:
- **Model**: Logistic Regression for binary classification.
- **Interface**: Integrated into a web platform using Google Colab and Jupyter Notebook.
- **Data**: Utilized the "Stroke Prediction Dataset" from Kaggle, ensuring all HIPAA regulations were followed.

## Data Summary
The dataset used contained over 5,000 anonymous patient records with various medical statistics. Key steps in data preparation included:
- **Data Cleaning**: Removal of entries with missing values in critical columns like BMI and smoking status.
- **Data Transformation**: Conversion of categorical data into numerical values suitable for the model.
- **Outlier Handling**: Retained outliers to understand their impact on stroke prediction.

## Implementation
The project followed the SEMMA methodology (Sample, Explore, Modify, Model, Assess) for development:

### Sample
- **Objective**: Select a subset of data focusing on relevant medical characteristics.
- **Application**: Identified variables such as age, gender, BMI, and preexisting conditions.

### Explore
- **Objective**: Analyze data to identify trends and correlations.
- **Application**: Created visualizations like box plots and histograms to explore relationships between variables.

### Modify
- **Objective**: Prepare data for modeling.
- **Application**: Cleaned data by removing missing values and transforming text data into numerical formats.

### Model
- **Objective**: Implement and train the logistic regression model.
- **Application**: Split data into training (75%) and testing (25%) sets for model training and validation.

### Assess
- **Objective**: Evaluate model performance.
- **Application**: Calculated accuracy and validated the model on a separate test dataset.

## Results
The logistic regression model successfully predicted stroke occurrences with a high degree of accuracy. The model's interpretability allowed for clear understanding of the contributing factors, providing valuable insights for preventative healthcare measures.

## User Guide
To use the model:
1. Access the True Health Care Provider website.
2. Navigate to the stroke prediction tool.
3. Input the required patient data.
4. View the model's prediction and the contributing factors.

## Conclusion
This project demonstrates my ability to apply machine learning techniques to real-world problems, particularly in the healthcare sector. By developing a predictive model, I aimed to enhance patient care through proactive health management.

## Reference Page
- Kaggle: Stroke Prediction Dataset
- HIPAA Regulations
- SEMMA Methodology

---

This README provides a comprehensive overview of the project, highlighting the key aspects and outcomes. It serves as a portfolio piece to showcase my skills in data science and machine learning.
