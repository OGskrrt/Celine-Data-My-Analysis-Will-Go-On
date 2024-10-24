# Celine Data: My Analysis Will Go On

## Overview
This repository contains an in-depth data analysis of the famous Titanic dataset, inspired by the iconic song *My Heart Will Go On* by Celine Dion. The goal of this project is to examine, clean, and analyze the Titanic dataset to uncover meaningful insights, visualize key patterns, and assess the survival likelihood of passengers based on various features such as their class, age, gender, and cabin location.

## Dataset
The Titanic dataset is publicly available and contains details about the passengers aboard the ill-fated Titanic ship. The dataset includes features such as:
- `PassengerId`: Unique identifier for each passenger.
- `Survived`: Indicates whether the passenger survived (1) or not (0).
- `Pclass`: Passenger class (1st, 2nd, or 3rd).
- `Sex`: Passenger gender.
- `Age`: Passenger age.
- `SibSp`: Number of siblings/spouses aboard the Titanic.
- `Parch`: Number of parents/children aboard the Titanic.
- `Fare`: The fare paid by the passenger.
- `Cabin`: The cabin number of the passenger.
- `Embarked`: The port where the passenger embarked (C = Cherbourg, Q = Queenstown, S = Southampton).

## Key Steps
1. **Data Cleaning**:
   - Handled missing values for the `Cabin` and `Embarked` columns.
   - Extracted deck information from the `Cabin` column and filled missing values based on passenger class.
   - Removed outliers from key numerical features (`Fare`, `SibSp`, `Parch`) using interquartile range (IQR).

2. **Exploratory Data Analysis (EDA)**:
   - Generated summary statistics for numerical columns (mean, median, mode, standard deviation).
   - Visualized distributions of key features such as `Age`, `Fare`, `Pclass`, and `Survived`.
   - Examined survival rates based on gender, passenger class, and embarkation port.

3. **Data Visualization**:
   - Plotted survival rates by `Pclass`, `Embarked`, `Sex`, and `Cabin`.
   - Created correlation heatmaps to visualize relationships between numerical variables.




