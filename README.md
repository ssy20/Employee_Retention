# Employee_Retention
This repo contains a data set with info about the employees. The challenge is to build a machine learning model to predict when employees are going to quit and understand the main drivers of employee churn.

# Data
The dataset(employee_data.csv) contains employee data from a few companies. The dataset aslo contains a binary variable indicating if a employee is still  at the company as of 2015/12/13 or they have quit. 



- employee_id : id of the employee. Unique by employee per company
- company_id : company id.
- dept : employee dept
- seniority : number of yrs of work experience when hired
- salary: avg yearly salary of the employee during her tenure within the company
- join_date: when the employee joined the company, it can only be between 2011/01/24 and 2015/12/13
- quit_date: when the employee left her job (if she is still employed as of 2015/12/13, this field is NA)

# Result
- Employees tend to quit at year anniversaries.
- Salary is the most important variable. Employees with low and high salaries are less likely to quit.

