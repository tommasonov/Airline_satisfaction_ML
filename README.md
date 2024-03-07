# Airline Customer Satisfaction Prediction Project

## Introduction
- The dataset represents a survey conducted among customers of an airline.
- Features include gender, age, flight type, and service ratings.
- Our goal is to analyze the data and build a model to predict customer satisfaction.

## Files
- `train.csv`: Training dataset containing customer data for model training.
- `test.csv`: Test dataset for evaluating the trained models.

## Initial Analysis and Data Preprocessing
- Explored the dataset using descriptive statistics and identified missing values.
- Managed missing values by dropping columns and imputing values using appropriate strategies.
- Conducted exploratory data analysis (EDA) to identify correlations between variables.
- Visualized relationships between categorical variables and satisfaction levels.
- Preprocessed the data, including encoding categorical variables and scaling numerical features.

## Models and Evaluation
- Developed classification models using logistic regression, random forest, and support vector machines (SVM).
- Tuned hyperparameters using grid search and cross-validation to improve model performance.
- Evaluated models using recall score to measure their ability to predict customer satisfaction.
- Selected the best-performing model based on evaluation metrics.

## Feature Importance
- Analyzed feature importance using the best-performing model (Random Forest).
- Identified significant features influencing customer satisfaction.

## Model Deployment
- Deployed the trained model to predict customer satisfaction in real-time scenarios.
- Provided recommendations for improving customer satisfaction based on model insights.

## Usage
- Clone the repository to your local machine.
- Ensure you have the required dependencies installed (see `requirements.txt`).
- Run the Jupyter Notebook or Python script to train and evaluate the models.
- Use the trained model to make predictions on new data or in production environments.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
