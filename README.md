# Titanic Survival Analysis

## Overview
This project is an exploratory data analysis (EDA) of the famous Titanic dataset. The goal is to uncover patterns and factors that influenced a passenger's chance of survival.

## Dataset
The dataset is from the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic) Kaggle competition. It contains information about passengers, such as their age, gender, ticket class, and whether they survived.

## Steps Performed
1.  **Data Loading & Inspection:** Loaded the data and understood its structure.
2.  **Data Cleaning:** Handled missing values in the 'Age', 'Embarked', and 'Cabin' columns.
3.  **Exploratory Data Analysis (EDA):** Used visualizations to explore relationships between features and survival.
    - Analyzed overall survival rate.
    - Investigated the strong correlation between **gender** and survival.
    - Investigated the correlation between **passenger class (Pclass)** and survival.
    - Explored the **age** distribution of survivors.
    - Created a correlation heatmap for numerical features.

## Key Insights
- **Women (Sex=female)** had a significantly higher survival rate than men.
- **Passengers in a higher class (Pclass=1)** had a higher survival rate.
- **Children** had a higher than average survival rate.
- The **port of embarkation (C)** showed some correlation with survival.

## Technologies Used
- Python
- Pandas (Data manipulation)
- NumPy (Numerical operations)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook
