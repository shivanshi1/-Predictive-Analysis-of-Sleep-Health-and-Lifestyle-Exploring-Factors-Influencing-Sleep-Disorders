# Predictive Analysis of Sleep Health and Lifestyle
This project explores factors influencing sleep disorders such as Insomnia and Sleep Apnea using machine learning techniques. 
The dataset used for analysis is sourced from Kaggle and includes various health and lifestyle attributes.

## Project Overview
The main objectives of this project are:
1. Analyze the correlation between sleep disorders and health/lifestyle factors.
2. Predict the presence of Insomnia and Sleep Apnea based on individual characteristics.
3. Evaluate models using accuracy metrics and classification reports.

## Project Structure

### Data Loading and Preprocessing
- Loaded the dataset from 'Sleep_health_and_lifestyle_dataset.csv'.
- Handled missing values and encoded categorical variables (gender, occupation, BMI category, and blood pressure) using one-hot encoding.
- Encoded the target variable 'Sleep Disorder' using LabelEncoder.

### Modeling
- Trained Logistic Regression and Decision Tree Classifier models to predict sleep disorders.
- Split the data into training and testing sets.

### Evaluation
Evaluated model performance using accuracy score and classification report for both Logistic Regression and Decision Tree Classifier.

### Visualizations
- Visualized the distribution of sleep duration using a histogram.
- Created a correlation heatmap to analyze relationships between variables.
- Plotted a count of sleep disorders to understand their frequency in the dataset.

## Python Libraries Used
pandas, 
scikit-learn, 
matplotlib, 
seaborn

## Files Included
Data_Analytics_Predict_sleep_disorders.ipynb: Jupyter notebook containing the entire code for data preprocessing, modeling, evaluation, and visualizations.
Sleep_health_and_lifestyle_dataset.csv: Dataset downloaded from Kaggle
