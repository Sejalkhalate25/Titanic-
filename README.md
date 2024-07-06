Titanic Dataset Analysis

This project involves an analysis of the Titanic dataset, which includes information on the passengers who were aboard the Titanic when it sank on April 15, 1912. The analysis aims to understand the factors that contributed to the survival of the passengers.

Table of Contents
Overview
Dataset
Installation
Exploratory Data Analysis (EDA)
Data Preprocessing
Modeling
Results

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1,502 out of 2,224 passengers and crew. This project uses machine learning techniques to predict which passengers survived the tragedy.

Dataset

The dataset can be found on Kaggle's Titanic page. It consists of two files:

train.csv: The training set.
test.csv: The test set.
Each row in the dataset represents a passenger, and the columns describe various attributes such as age, gender, class, etc.

Installation

To run the analysis, you need to have Python installed along with the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn

You can install the required libraries using:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn

Exploratory Data Analysis (EDA)
In this section, we explore the dataset to understand its structure, detect any anomalies, and gain insights into the data. We analyze the distribution of different variables and their correlation with the target variable, which is the survival of the passengers.

Data Preprocessing
Before feeding the data into machine learning models, we need to preprocess it. This includes:

Handling missing values Encoding categorical variables Feature scaling Splitting the data into training and validation sets Modeling We use various machine learning models to predict the survival of passengers, including:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine
K-Nearest Neighbors

We evaluate the performance of these models using appropriate metrics and select the best-performing model for the final prediction.

Results
The results of the analysis and the predictions from the best-performing model are presented in this section. We also discuss the importance of different features and how they contribute to the survival prediction.
