# Data Analysis Project

This project involves analyzing a dataset consisting of **458 rows and 9 columns**. The key tasks performed include **data preprocessing, exploratory data analysis (EDA), and graphical representation of findings**.

## Table of Contents
- [Preprocessing](#preprocessing)
- [Analysis Tasks](#analysis-tasks)
  - [1. Employee Distribution by Team](#1-employee-distribution-by-team)
  - [2. Employee Segmentation by Position](#2-employee-segmentation-by-position)
  - [3. Predominant Age Group](#3-predominant-age-group)
  - [4. Salary Expenditure by Team and Position](#4-salary-expenditure-by-team-and-position)
  - [5. Correlation Between Age and Salary](#5-correlation-between-age-and-salary)
- [Findings and Insights](#findings-and-insights)
- [Conclusion](#conclusion)

## Preprocessing
### Data Cleaning and Transformation
- The `height` column values were corrected by replacing them with **random values between 150 and 180** using `np.random.randint()`, ensuring consistency and integrity before proceeding with analysis.

## Analysis Tasks
### 1. Employee Distribution by Team
- **Method:**
  - Used `value_counts()` to determine the number of employees per team.
  - Calculated the **percentage split** relative to the total employees.
- **Visualization:**
  - Bar chart representing the team-wise distribution.

### 2. Employee Segmentation by Position
- **Method:**
  - Used `value_counts()` to determine the number of employees per position.
  - Plotted a **pie chart** to visualize the distribution.
- **Findings:**
  - The highest number of employees are in the **SG** position (**22.3%**, 102 employees).
  - The lowest number of employees are in the **C** position (**17.2%**, 79 employees).

### 3. Predominant Age Group
- **Method:**
  - Used `cut()` to segment and categorize age groups into bins.
  - Used `value_counts()` to determine the **age group distribution**.
  - Identified the predominant age group using `idxmax()`.
- **Visualization:**
  - **Bar chart** representing age group distribution.
- **Findings:**
  - The predominant age group is **20-25 years**, with **179 employees**.

### 4. Salary Expenditure by Team and Position
- **Method:**
  - Used `sum()` to calculate **total salary expenditure** by team and position.
  - Used `idxmax()` to identify the **team and position with the highest salary expenditure**.
- **Visualization:**
  - **Line chart** representing salary expenditures.
- **Findings:**
  - **Team with highest salary expenditure:** **Cleveland Cavaliers**.
  - **Position with highest salary expenditure:** **C**.

### 5. Correlation Between Age and Salary
- **Method:**
  - Used `corr()` to find the correlation coefficient between **Age** and **Salary**.
  - Plotted a **scatter plot** to visualize the relationship.
- **Findings:**
  - Correlation between **Age and Salary**: **0.214** (weak positive correlation).

## Findings and Insights
- **SG position** has the most employees (**22.3%**), while **C position** has the least (**17.2%**).
- **Predominant age group**: **20-25 years** (**179 employees**).
- **Cleveland Cavaliers** spends the most on salaries.
- **C position** has the highest salary expenditure.
- **Weak positive correlation** (**0.214**) between Age and Salary.

## Conclusion
This analysis provides insights into the **distribution of employees, salary trends, and age-related patterns** in the dataset. The findings help in understanding workforce distribution and financial allocation across teams and positions.

---

### 🛠 **Technologies Used**
- **Python** (pandas, numpy, matplotlib, seaborn)
- **Data Cleaning** (Handling missing values, correcting inconsistencies)
- **Data Visualization** (Bar charts, Pie charts, Scatter plots, Line charts)

---
**Author:** Swetha T S

