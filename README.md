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

<img width="453" height="299" alt="image" src="https://github.com/user-attachments/assets/dc9c55f9-cdc8-4956-bce1-89c1a33eddb6" />


---

### Department-wise Employee Distribution

Shows the distribution of employees across different departments.

<img width="686" height="335" alt="image" src="https://github.com/user-attachments/assets/c723a0f4-37d7-46f9-b67a-3683fe3da75b" />


---

### Gender Distribution

Provides insights into workforce gender composition.

<img width="470" height="299" alt="image" src="https://github.com/user-attachments/assets/1dd6404f-c7a5-4ac9-8038-f7f571c1fa6f" />


---

### Job Role Distribution

Displays the number of employees in each job role.

<img width="814" height="336" alt="image" src="https://github.com/user-attachments/assets/550ce435-fbcf-4782-bd01-442215bd4127" />


---

### Age Distribution

Illustrates employee age patterns and workforce demographics.

<img width="574" height="335" alt="image" src="https://github.com/user-attachments/assets/38bc4065-9e95-4938-bdb8-aa780d12bff6" />


---

### Monthly Income Distribution

Analyzes salary distribution among employees.

<img width="571" height="336" alt="image" src="https://github.com/user-attachments/assets/4a456f40-37ce-4281-81a3-4f294a7419e5" />


---

### Attrition by Department

Identifies departments experiencing higher employee turnover.

<img width="675" height="337" alt="image" src="https://github.com/user-attachments/assets/f925ea6d-baf6-46d6-811c-79918d441d25" />


---

### Attrition by Job Role

Highlights job roles with higher attrition rates.

<img width="851" height="339" alt="image" src="https://github.com/user-attachments/assets/780166cc-7777-44bd-be8e-f4c3a7bd62ab" />


---

### Attrition by Overtime

Examines the relationship between overtime and employee turnover.

<img width="536" height="329" alt="image" src="https://github.com/user-attachments/assets/7fede9dd-2ce2-41cc-819a-1f0df3ac13c8" />


---

### Job Satisfaction vs Attrition

Investigates how satisfaction levels impact employee retention.

<img width="593" height="334" alt="image" src="https://github.com/user-attachments/assets/79854d93-50e4-433f-bb3a-861f1c2a8b51" />


---

### Correlation Heatmap

Displays relationships between numerical variables in the dataset.

<img width="447" height="307" alt="image" src="https://github.com/user-attachments/assets/c437e1f8-3bb2-4d69-b273-16ec378f2b98" />


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

Author

Lakshmi Prabhakar

Data Analytics Project using Python, Pandas, Seaborn, Matplotlib, and Plotly

Dataset Type: Structured CSV Dataset

Source: IBM HR Analytics Employee Attrition & Performance Dataset

Domain: Human Resource Analytics
