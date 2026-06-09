# HR Analytics and Employee Attrition Analysis

# Project Overview

Employee attrition is one of the most significant challenges faced by organizations, as high turnover rates can lead to increased recruitment costs, reduced productivity, and loss of experienced talent. Understanding the factors that contribute to employee attrition helps organizations make data-driven decisions to improve employee retention and workplace satisfaction.

This project focuses on analyzing employee data to identify patterns and factors influencing attrition. Using Python-based data analysis techniques, the dataset was cleaned, explored, and visualized to uncover relationships between employee turnover and various attributes such as age, income, department, job role, overtime, work-life balance, job satisfaction, and marital status.

Through exploratory data analysis (EDA), the project provides actionable insights that can help HR departments develop effective retention strategies and improve employee engagement.

# Problem Statement

Employee attrition can negatively impact an organization's performance and growth. Frequent employee turnover results in increased hiring costs, training expenses, and operational disruptions.

The goal of this project is to analyze employee data and identify the key factors associated with attrition. By understanding these factors, organizations can proactively address employee concerns and implement strategies to reduce turnover.

# Objectives

The primary objectives of this project are:

* Analyze employee attrition patterns within the organization.
* Identify demographic and workplace factors contributing to employee turnover.
* Examine the relationship between attrition and variables such as age, income, overtime, department, and job satisfaction.
* Discover trends and hidden patterns through data visualization.
* Generate actionable insights and recommendations for HR decision-making.
* Support employee retention initiatives using data-driven analysis.

---

# Dataset Information

The dataset contains information about employees, including demographic details, job-related attributes, compensation, satisfaction levels, and attrition status.

### Key Features

* Age
* Gender
* Marital Status
* Department
* Job Role
* Education Field
* Monthly Income
* Business Travel
* Overtime
* Work-Life Balance
* Job Satisfaction
* Years at Company
* Total Working Years
* Performance Rating
* Attrition

### Target Variable

**Attrition**

* Yes → Employee left the organization
* No → Employee stayed in the organization

---

# Data Cleaning & Preprocessing

Before analysis, the dataset was carefully examined and prepared to ensure data quality and consistency.

The preprocessing steps included:

* Understanding dataset structure and dimensions.
* Checking data types of all features.
* Identifying missing values.
* Detecting duplicate records.
* Validating feature consistency.
* Preparing data for visualization and analysis.

These steps ensured that the dataset was reliable for generating meaningful insights.

---

# Feature Engineering

Additional analysis-focused features were created to improve interpretation and understanding of employee behavior.

Examples include:

* Employee age categories.
* Income segmentation.
* Experience-based grouping.
* Attrition percentage calculations.
* Department-level comparisons.

Feature engineering helped reveal patterns that were not immediately visible in the raw dataset.

---

# Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand employee demographics, workplace characteristics, and attrition behavior.

The analysis was divided into three stages:

### Univariate Analysis

Analyzed individual variables to understand their distributions.

Examples:

* Employee age distribution
* Gender distribution
* Department distribution
* Monthly income distribution
* Work-life balance ratings

### Bivariate Analysis

Examined relationships between attrition and other variables.

Examples:

* Attrition vs Gender
* Attrition vs Department
* Attrition vs Job Role
* Attrition vs Overtime
* Attrition vs Marital Status

---

# Data Visualizations & Insights

The project includes multiple visualizations to better understand employee behavior and attrition trends.

### Employee Attrition Distribution

Analyzes the proportion of employees who left the organization compared to those who stayed.

![Employee Attrition Distribution](images/attrition-distribution.png)

---

### Department-wise Employee Distribution

Shows the distribution of employees across different departments.

![Department Distribution](images/department-distribution.png)

---

### Gender Distribution

Provides insights into workforce gender composition.

![Gender Distribution](images/gender-distribution.png)

---

### Job Role Distribution

Displays the number of employees in each job role.

![Job Role Distribution](images/job-role-distribution.png)

---

### Age Distribution

Illustrates employee age patterns and workforce demographics.

![Age Distribution](images/age-distribution.png)

---

### Monthly Income Distribution

Analyzes salary distribution among employees.

![Monthly Income Distribution](images/monthly-income-distribution.png)

---

### Attrition by Department

Identifies departments experiencing higher employee turnover.

![Attrition by Department](images/attrition-department.png)

---

### Attrition by Job Role

Highlights job roles with higher attrition rates.

![Attrition by Job Role](images/attrition-job-role.png)

---

### Attrition by Overtime

Examines the relationship between overtime and employee turnover.

![Attrition by Overtime](images/attrition-overtime.png)

---

### Job Satisfaction vs Attrition

Investigates how satisfaction levels impact employee retention.

![Job Satisfaction vs Attrition](images/job-satisfaction-attrition.png)

---

### Correlation Heatmap

Displays relationships between numerical variables in the dataset.

![Correlation Heatmap](images/correlation-heatmap.png)

---

# Key Findings

* Employees working overtime showed a higher tendency to leave the organization.
* Certain job roles experienced significantly higher attrition rates.
* Employees with lower job satisfaction were more likely to leave.
* Monthly income appeared to influence retention patterns.
* Work-life balance had a noticeable impact on employee turnover.
* Younger employees showed higher attrition compared to experienced employees.
* Attrition varied across departments, indicating department-specific challenges.

---

# Recommendations

Based on the analysis, the following recommendations can help reduce employee attrition:

* Improve work-life balance initiatives.
* Monitor and reduce excessive overtime.
* Develop targeted retention programs for high-risk job roles.
* Enhance employee engagement and satisfaction programs.
* Review compensation structures for employees with lower income levels.
* Conduct regular employee feedback surveys.
* Strengthen career growth and development opportunities.

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

This HR Analytics project successfully explored employee attrition patterns using data analysis and visualization techniques. The findings reveal that factors such as overtime, job satisfaction, income, work-life balance, and job role play important roles in employee turnover.

The insights generated from this analysis can help HR teams make informed decisions, improve employee retention strategies, and create a more productive work environment. By leveraging data-driven approaches, organizations can proactively address attrition and enhance workforce stability.
