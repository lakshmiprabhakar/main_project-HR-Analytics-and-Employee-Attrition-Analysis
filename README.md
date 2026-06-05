# HR Analytics and Employee Attrition Analysis

## Project Overview

This project focuses on analyzing employee attrition data using Python, Pandas, Matplotlib, and Seaborn. The primary objective is to identify patterns, trends, and factors that contribute to employee attrition and provide insights that can help organizations improve employee retention strategies.

## Objectives

* Understand employee attrition patterns.
* Identify factors influencing employee turnover.
* Analyze employee demographics, job roles, income, satisfaction levels, and work-life balance.
* Create meaningful visualizations to support data-driven HR decisions.

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset Information

### Dataset Name

HR Analytics Employee Attrition Dataset

### Dataset Description

The dataset contains employee-related information including:

* Age
* Gender
* Department
* Job Role
* Monthly Income
* Business Travel
* Education
* Job Satisfaction
* Environment Satisfaction
* Work-Life Balance
* Overtime
* Total Working Years
* Years at Company
* Attrition Status

### Target Variable

**Attrition**

* Yes = Employee left the company
* No = Employee stayed with the company

## Data Cleaning Process

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected dataset structure and data types.
3. Checked for missing values.
4. Checked for duplicate records.
5. Renamed column names to maintain consistency.
6. Identified constant-value columns:

   * EmployeeCount
   * Over18
   * StandardHours
7.  Created new columns where applicable.
8. Verified numerical and categorical features.

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### Employee Demographics Analysis

* Age Distribution
* Gender Distribution
* Marital Status Analysis

### Attrition Analysis

* Attrition Distribution
* Attrition by Gender
* Attrition by Department
* Attrition by Job Role
* Attrition by Overtime

### Compensation Analysis

* Monthly Income Distribution
* Income vs Attrition

### Experience Analysis

* Total Working Years Distribution
* Years at Company Analysis

### Satisfaction Analysis

* Job Satisfaction vs Attrition
* Environment Satisfaction vs Attrition
* Work-Life Balance vs Attrition

### Correlation Analysis

* Correlation Heatmap for Numerical Features

## Visualizations Created

* Count Plots
* Bar Charts
* Histograms
* Boxplots
* Pie Charts
* Heatmaps

## Key Insights

* Employees working overtime showed significantly higher attrition rates.
* Certain departments and job roles experienced higher employee turnover.
* Lower income groups were more likely to leave the organization.
* Employees with lower job satisfaction demonstrated higher attrition rates.
* Work-life balance played an important role in employee retention.
* Employee experience and tenure showed strong relationships with attrition behavior.

## Project Structure

HR-Analytics-Employee-Attrition-Analysis/

│

├── HR Analytics and Employee Attrition Analysis.ipynb

├── WA_Fn-UseC_-HR-Employee-Attrition.csv

├── README.md

└── Images/

```
  ├── attrition_distribution.png

  ├── income_distribution.png

  ├── overtime_attrition.png

  └── correlation_heatmap.png
```

## How to Run

1. Clone this repository.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells sequentially.

## Future Improvements

* Build predictive machine learning models for attrition prediction.
* Develop an interactive dashboard using Power BI or Tableau.
* Perform advanced statistical analysis.
* Deploy the project as a web application.

## Conclusion

This project demonstrates how data analytics techniques can be applied to HR data to uncover employee attrition patterns and workforce trends. The insights generated can assist HR teams in making informed decisions regarding employee engagement, retention, and organizational development.

