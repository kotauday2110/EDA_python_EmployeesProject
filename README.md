# EDA_python_EmployeesProject

# 💼 Employee Salary Data Analysis using Python

This project performs **Exploratory Data Analysis (EDA)** on a public employee salary dataset using Python. The goal is to gain insights into employee pay structure, identify trends, and clean the data for better understanding and usage.

## 📁 Dataset Structure

The dataset is a CSV file with the following columns:

- `Id`: Unique identifier
- `EmployeeName`: Name of the employee
- `JobTitle`: Employee's job title
- `BasePay`: Base salary
- `OvertimePay`: Pay received for overtime work
- `OtherPay`: Other forms of compensation
- `Benefits`: Benefits received
- `TotalPay`: Total pay including base, overtime, and other pay
- `TotalPayBenefits`: Total compensation including benefits
- `Year`: Year of the record
- `Notes`: Additional notes (mostly blank)
- `Agency`: The department or agency
- `Status`: Employment status

## ✅ Tasks Performed

1. **Display Top 10 Rows of the Dataset**
2. **Display Last 10 Rows of the Dataset**
3. **Find the Shape of the Dataset (Rows and Columns)**
4. **Get Detailed Info About the Dataset (Column Types, Memory Usage)**
5. **Check for Null (Missing) Values**
6. **Drop Unnecessary Columns: `Id`, `Notes`, `Agency`, `Status`**
7. **Generate Descriptive Statistics (mean, median, std, etc.)**
8. **Find Top 5 Most Frequent Employee Names**
9. **Count Number of Unique Job Titles**
10. **Count Job Titles Containing the Word 'Captain'**
11. **Display All Employees from the Fire Department (`JobTitle` or `Agency`)**
12. **Find Minimum, Maximum, and Average `BasePay`**
13. **Replace 'Not Provided' in `EmployeeName` Column with `NaN`**
14. **Drop Rows Having 5 or More Missing Values**
15. **Find the Job Title of "ALBERT PARDINI"**
16. **Calculate Total Compensation (`TotalPayBenefits`) of "ALBERT PARDINI"**
17. **Find the Person with the Highest `BasePay`**
18. **Calculate Average `BasePay` of All Employees Per Year**
19. **Calculate Average `BasePay` of All Employees Per Job Title**
20. **Calculate Average `BasePay` for Job Title 'ACCOUNTANT'**
21. **Display Top 5 Most Common Job Titles**

## 🧰 Libraries Used

- `pandas` for data manipulation
- `numpy` for numerical computations

## 💡 Key Insights

- Identified high-paying roles and salary distributions
- Cleaned and transformed columns with missing or invalid data
- Found job roles with most employees
- Year-wise trends in employee salaries

