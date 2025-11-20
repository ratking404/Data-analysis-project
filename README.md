 AI Data Analyzer

Author
Name: Benedict Sau  
Registration Number: 250594DAI

---

## Project Overview

The **AI Data Analyzer** is a Python-based project designed to:

- Load datasets in CSV or JSON format  
- Clean and preprocess data (handle missing values, remove duplicates)  
- Perform descriptive statistics and summarize both numeric and categorical data  
- Generate visualizations (histograms, boxplots, correlation heatmaps, scatter plots) to understand data patterns and relationships  

This project is implemented in **Google Colab** or **VS Code**, making it easy to run without complex environment setup.

---
 Libraries 

The project uses the following Python libraries:

| Library       | Purpose |
|---------------|---------|
| pandas        | Load, clean, and manipulate structured data |
| numpy         | Numerical computations and array operations |
| matplotlib    | Basic data visualization (histograms, scatter plots) |
| seaborn       | Advanced statistical visualizations (heatmaps, boxplots) |


 Data Being Analyzed

The project analyzes a dataset similar to the Titanic passenger dataset. The dataset contains demographic, travel, and ticket information for each passenger.  

Columns in the dataset:

| Column       | Type       | Description |
|--------------|------------|-------------|
| PassengerId  | Numeric    | Unique identifier for each passenger |
| Survived     | Numeric    | Survival status (0 = did not survive, 1 = survived) |
| Pclass       | Numeric    | Passenger class (1 = first, 2 = second, 3 = third) |
| Name         | Categorical | Full name of the passenger |
| Sex          | Categorical | Gender of the passenger (male/female) |
| Age          | Numeric    | Age of the passenger in years |
| SibSp        | Numeric    | Number of siblings/spouses aboard |
| Parch        | Numeric    | Number of parents/children aboard |
| Fare         | Numeric    | Ticket fare paid by the passenger |
| Embarked     | Categorical | Port of embarkation (C, Q, S) |

The analysis helps to identify patterns such as survival trends, demographic distribution, fare variation, and correlations between family members aboard.


