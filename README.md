# Prodigy_DS_02
Titanic Dataset Analysis

This repository contains a comprehensive analysis of the Titanic dataset, including data cleaning, exploratory data analysis (EDA), and visualizations to uncover insights about survival patterns.

Dataset

The dataset used for this analysis comes from the Titanic competition on Kaggle. It consists of passenger details such as age, gender, ticket class, fare, and survival status.

Files

train.csv: Training dataset containing passenger details and survival status.

test.csv: Test dataset used for predictions.

gender_submission.csv: Example submission file for the competition.

titanic_analysis.py: Python script for data cleaning and EDA.

README.md: This documentation file.

Data Cleaning

The following steps were taken to clean the dataset:

Handled missing values in Age by filling with the median age.

Filled missing Embarked values with the most common port.

Dropped the Cabin column due to excessive missing values.

Exploratory Data Analysis (EDA)

Key analyses performed:

Survival Rate: Visualized the number of survivors and non-survivors.

Survival by Class: First-class passengers had the highest survival rate.

Survival by Gender: Women had a significantly higher survival rate than men.

Age Distribution: Analyzed how age impacted survival chances.

Visualizations

The analysis includes several visualizations using Matplotlib and Seaborn:

Bar charts for survival rates by gender and class.

Histograms for age distribution.

Boxplots for fare distribution.

