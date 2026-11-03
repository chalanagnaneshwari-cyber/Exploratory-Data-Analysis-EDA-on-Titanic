*Titanic Passenger Survival Analysis Using Pandas

# Project Overview
This project analyses the Titanic passenger dataset using Python and Pandas to understand the factors associated with passenger survival.

The main objective is to clean the dataset, handle missing values, perform grouping and aggregation, and identify survival patterns.

# Objectives
- Load and inspect the Titanic dataset.
- Identify and handle missing values.
- Check duplicate records.
- Perform data cleaning using Pandas.
- Analyse survival rates based on sex, passenger class, and age group.
- Present findings using graphs and written insights.

# Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

# Research Questions
1. Did women survive more often than men?
2. Did passenger class affect survival rates?
3. Was survival different across age groups?

# Data Cleaning
- Filled missing age values using the median age of passengers with the same class and sex.
- Dropped the deck column because it contained a large number of missing values.
- Filled missing embarked values using the most frequent value.
- Checked duplicate records without blindly deleting them.
- Checked and converted appropriate data types.

# Analysis Performed
- Dataset inspection using `head()`, `info()`, and `describe()`.
- Missing-value analysis using `isna().sum()`.
- Duplicate checking using `duplicated().sum()`.
- Grouping and aggregation using `groupby()`.
- Age categorisation using `pd.cut()`.
- Survival-rate comparisons using percentage calculations.
- Data visualisation using Matplotlib.

# Key Findings
The analysis compares:
1. Survival rates between male and female passengers.
2. Survival rates across first, second, and third-class passengers.
3. Survival rates across different age groups.

The exact numerical findings are available in the Jupyter Notebook output.

# Project Files
- `Titanic_Pandas_Analysis.ipynb` – Complete analysis, Python code, outputs, and visualisations.
- `README.md` – Project documentation.

# Conclusion
This project demonstrates how Pandas can be used to clean, analyse, and interpret real-world datasets. The analysis identifies differences in survival rates across passenger groups while recognising that correlation does not necessarily imply causation.

## Author
Eshwar
