# Heart Disease Prediction

This repository contains Python code for a machine learning project that predicts the presence of heart disease in a person based on various health parameters. The project uses a dataset of health records and implements a Logistic Regression model from the Scikit-learn library to make the predictions.

## Features

- The code begins by importing necessary Python libraries, including NumPy, Pandas, and Scikit-learn.
- The dataset is loaded from a CSV file into a Pandas DataFrame, and some initial exploratory data analysis is performed. This includes checking the shape of the dataset, checking for missing values, and calculating some basic statistical measures.
- The data is then split into features and target variable, and further split into training and test sets.
- A Logistic Regression model is trained on the training data, and evaluated on both the training and test data to check its performance.
- The model is then used to make a prediction on a new data point.

The code is well-commented and easy to understand, making it a great starting point for beginners in machine learning, as well as a useful reference for more experienced practitioners.

## Dataset

The dataset used in this project is a collection of health records for 303 individuals, with 14 features for each individual. These features include age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thalassemia, and the presence of heart disease (target variable).

## Model

The Logistic Regression model used in this project is a binary classification model that predicts whether a person has heart disease or not, based on the given health parameters. The model is trained using the Scikit-learn library's LogisticRegression class.

## Evaluation

The model's performance is evaluated using the accuracy score metric, which is calculated on both the training and test data. The accuracy score is the proportion of correct predictions made by the model.

## Prediction

Finally, the model is used to make a prediction on a new data point, which represents the health parameters for a new individual. The predicted result indicates whether the person is likely to have heart disease or not.
