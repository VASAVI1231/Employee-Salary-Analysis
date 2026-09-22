Employee Salary Analysis

Project Overview

Employee Salary Analysis is a beginner-level Python project that examines a sample set of employee salaries. It uses Pandas to calculate the total, average, highest, and lowest salary, and compares each employee's salary with the average.


Objectives


Practice basic data processing with Python and Pandas.

Calculate key salary statistics.

Compare individual salaries with the dataset average.

Export the analysis to a CSV file.


Technologies Used


Python 3

Pandas

Google Colab or Jupyter Notebook


Dataset

The project uses a small, manually created sample dataset of five employees. Salaries are illustrative annual amounts in Indian rupees and are not real employee records.


Employee	Annual salary
Employee 1	₹300,000
Employee 2	₹450,000
Employee 3	₹500,000
Employee 4	₹600,000
Employee 5	₹750,000

How to Run

In Google Colab


Open Google Colab: https://colab.research.google.com/

Create a New notebook.

Copy the code from employee_salary_analysis.py into a code cell.

Run the cell. If Pandas is not available in your environment, run !pip install pandas first.

The output displays the dataset and statistics. The CSV file is created in the notebook's current working directory.


Locally


Install Python 3.

Install Pandas: pip install pandas

Run: python employee_salary_analysis.py


Key Results for the Sample Data


Employee count: 5

Total salary: ₹2,600,000

Average salary: ₹520,000

Highest salary: ₹750,000

Lowest salary: ₹300,000


Project Files


employee_salary_analysis.py — complete Python source code.

README.md — project explanation and run instructions.

Employee_Salary_Analysis_Report.pdf — short project report.


Possible Improvements


Read employee data from an Excel or CSV file.

Add department-wise salary comparisons.

Handle missing or invalid salary values.

Visualize the salary distribution using Matplotlib.


Disclaimer

This project is an educational demonstration using invented sample data. It should not be interpreted as analysis of any real organization's payroll.

