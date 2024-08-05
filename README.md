# DBMS-ASSIGNMENT
**Team Members :**
Nishant Pandey,
Ria Singh ,
Rahul Govind ,
Anurag Sahu,
Mihir Kumar .

# Titanic Data Preprocessing and Logistic Regression Model

This project preprocesses the Titanic dataset and trains a Logistic Regression model to predict survival. The dataset is transformed using `StandardScaler` for numerical features and `OneHotEncoder` for categorical features, then stored in a SQLite database. Finally, the data is loaded from the database to train and evaluate the model.

## Requirements

- Python 3.7+
- pandas
- scikit-learn
- SQLAlchemy

## Installation

Usage
Place the train.csv file in the project directory. You can download it from Kaggle.

Run the **dbms_assignment7_group10.py** script:
This script will:

Load the dataset.
Fill missing values.
Drop the Cabin column.
Extract titles from names.
Create a FamilySize feature.
Transform the numerical and categorical features.
Store the transformed data in a SQLite database.
Load the transformed data from the database.
Split the data into training and testing sets.
Train a Logistic Regression model.
Evaluate the model and print the accuracy.
