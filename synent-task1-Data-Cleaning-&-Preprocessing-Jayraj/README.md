# Task 1: Data Cleaning & Preprocessing

## Overview

This project focuses on cleaning and preprocessing the Titanic dataset to prepare it for data analysis and machine learning tasks. Data preprocessing is a crucial step in the data science workflow because real-world datasets often contain missing values, duplicate records, inconsistent data types, and poorly formatted column names.

The objective of this task is to transform the raw Titanic dataset into a clean and structured dataset that is ready for further analysis.

---

## Dataset

**Dataset:** Titanic Dataset

The dataset contains information about passengers aboard the Titanic, including demographic details, ticket information, cabin information, and survival status.

### Features

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

---

## Objectives

* Handle missing values
* Remove duplicate records
* Convert columns to appropriate data types
* Rename columns for better readability
* Generate a cleaned dataset for further analysis

---

## Data Cleaning Steps

### 1. Missing Value Handling

The following missing values were addressed:

* **Age:** Filled using the median value.
* **Embarked:** Filled using the most frequent value (mode).
* **Cabin:** Missing values replaced with `"Unknown"`.

### 2. Duplicate Removal

Duplicate rows were identified and removed to ensure data consistency.

### 3. Data Type Conversion

Categorical columns were converted to appropriate data types:

* Survived
* Pclass
* Sex
* Embarked

### 4. Column Renaming

Several columns were renamed to improve readability and understanding.

Example:

| Original Column | Renamed Column  |
| --------------- | --------------- |
| PassengerId     | Passenger_ID    |
| Survived        | Survived_Status |
| Pclass          | Passenger_Class |
| Name            | Passenger_Name  |
| Sex             | Gender          |
| Age             | Age_Years       |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Kaggle Notebook

---

## Project Workflow

1. Load Titanic dataset
2. Explore dataset structure
3. Check missing values
4. Remove duplicate records
5. Handle missing values
6. Convert data types
7. Rename columns
8. Save cleaned dataset

---

## Output

The final output is a cleaned dataset:

```text
titanic_cleaned.csv
```

This dataset is ready for:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning Model Development

---

## Results

After preprocessing:

* Missing values successfully handled
* Duplicate records removed
* Data types standardized
* Column names improved
* Dataset prepared for analysis and modeling

---

## Conclusion

Data cleaning and preprocessing significantly improve the quality and usability of the dataset. The cleaned Titanic dataset provides a reliable foundation for performing exploratory data analysis and building predictive machine learning models.
