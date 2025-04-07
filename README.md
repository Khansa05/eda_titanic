# titanic_eda
An Exploratory Data Analysis (EDA) of the Titanic dataset, focusing on data cleaning, missing value handling, outlier detection, and visualizations.
# Titanic Dataset - Exploratory Data Analysis (EDA)
This repository contains the code and analysis for performing Exploratory Data Analysis (EDA) on the Titanic dataset. The goal of this analysis is to gain insights into the dataset, clean the data, handle missing values, detect outliers, and create visualizations for better understanding.

## Project Overview
The Titanic dataset contains information about passengers on the Titanic, including whether they survived or not, along with details like age, sex, class, and more. The objective of this project is to perform a detailed EDA and visualize the data using Seaborn and Matplotlib.

## Key Steps
1. **Data Loading**: The Titanic dataset is loaded from Seaborn's built-in dataset.
2. **Initial Exploration**:
   - Checking the shape of the dataset.
   - Getting summary statistics of both numerical and categorical features.
   - Checking for missing values and duplicates.
3. **Data Cleaning**:
   - Removing duplicates.
   - Handling missing values using imputation techniques (filling missing values with the mode or median).
   - Dropping columns with too many missing values (like `deck`).
4. **Outlier Detection**:
   - Identifying outliers using boxplots.
   - Removing outliers using the Interquartile Range (IQR) method.
5. **Visualization**:
   - Creating visualizations for both categorical and numerical data.
   - Generating a correlation heatmap for numerical features.
   - Exploring distributions for `age` and `fare`, and categorical distributions for `sex`, `class`, and `embarked`.

## Requirements
- Python 3.x
- Pandas
- Numpy
- Seaborn
- Matplotlib

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Khansa05/titanic-eda.git
   cd titanic-eda
