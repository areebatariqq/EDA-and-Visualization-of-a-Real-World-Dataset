# EDA-and-Visualization-of-a-Real-World-Dataset
**Project Overview:
**
This project presents a comprehensive Exploratory Data Analysis (EDA) of the Titanic Dataset. The primary objective was to uncover insights from the data using statistical methods and visualizations. The process includes data cleaning, identifying and handling missing values and outliers, and generating meaningful charts to understand variable distributions and relationships.

This analysis was performed as part of Task 1: EDA and Visualization of a Real-World Dataset.

**Dataset**:

Source: Titanic Dataset (commonly available via Kaggle(https://www.kaggle.com/))
Records: 891 rows × 12 columns
Type: Mixed (categorical & numerical)
Problem Type: Binary classification (Survival prediction)

**Technologies Used**:

Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab

**Key Steps Performed**

**1. Loading and Exploring the Dataset**:
Loaded dataset using pandas.read_csv

Explored shape, data types, index, and previewed first few records

**2. Data Cleaning**:

Identified missing values and calculated their percentage

Dropped the Cabin column due to excessive null values

Imputed missing values in Age (mean) and Embarked (mode)

Removed duplicate entries

Identified and removed outliers in Age and Fare using the IQR method and boxplots

**3. Visualizations**:

Bar Charts for categorical features like Sex, Embarked, etc.

Histograms for numerical features such as Age, Fare, SibSp, and Parch

Correlation Heatmap for understanding numeric relationships

**Key Insights**:

Gender and Survival: Females had significantly higher survival rates than males.

Class Influence: Passengers in 1st Class had the highest survival rate.

Embarked Location: Most passengers boarded from Southampton.

Outliers in Fare and Age could skew results; removing them helped normalize distributions.

Age Distribution: Majority of passengers were between 20–40 years old.

**Files**:

Titanic_EDA_Notebook.ipynb – Full Colab notebook containing code, plots, and insights

Titanic-Dataset.csv – Dataset used for analysis

README.md – This summary
