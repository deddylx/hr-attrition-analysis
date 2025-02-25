# HR Attrition Analysis
## Overview
Conducted analysis in SQL and Python to uncover insights on employee attrition and workplace satisfaction for an HR Analytics dataset containing 1,480 employee records. Worked independently for one weeks to clean, transform, and analyze the data, identifying key metrics such as attrition rate, average monthly income, and employee satisfaction levels. Built an interactive dashboard in Tableau to visualize trends related to attrition by department, job role, gender, and age. Delivered actionable insights and recommendations for the HR team, focusing on improving employee retention and workplace satisfaction.


## Tools and Technologies
- **Python**: Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, transformation, and analysis.
- **Visualization**: Tableau for creating interactive dashboards.
- **Version Control**: GitHub for project documentation and code sharing.

## Dataset
Source: [HR Analytics Dataset](https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset)

<details>   
<summary>Description: The dataset contains employee records with the following columns:
</summary>

- `EmpID`: Unique identifier for each employee.
- `Age`: Age of the employee.
- `AgeGroup`: Age group of the employee (e.g., 18-25).
- `Attrition`: Whether the employee has left the company (Yes/No).
- `BusinessTravel`: Frequency of business travel (e.g., Travel_Rarely).
- `DailyRate`: Daily rate of pay.
- `Department`: Department the employee belongs to.
- `DistanceFromHome`: Distance from home to work.
- `Education`: Education level of the employee.
- `EducationField`: Field of education.
- `EmployeeCount`: Number of employees (always 1).
- `EmployeeNumber`: Unique identifier for each employee.
- `EnvironmentSatisfaction`: Employee satisfaction with the work environment.
- `Gender`: Gender of the employee.
- `HourlyRate`: Hourly rate of pay.
- `JobInvolvement`: Level of job involvement.
- `JobLevel`: Job level of the employee.
- `JobRole`: Job role of the employee.
- `JobSatisfaction`: Employee satisfaction with their job.
- `MaritalStatus`: Marital status of the employee.
- `MonthlyIncome`: Monthly income of the employee.
- `SalarySlab`: Salary slab (e.g., Upto 5k).
- `MonthlyRate`: Monthly rate of pay.
- `NumCompaniesWorked`: Number of companies the employee has worked for.
- `Over18`: Whether the employee is over 18 (Y/N).
- `OverTime`: Whether the employee works overtime (Yes/No).
- `PercentSalaryHike`: Percentage of salary hike.
- `PerformanceRating`: Performance rating of the employee.
- `RelationshipSatisfaction`: Employee satisfaction with relationships at work.
- `StandardHours`: Standard hours of work.
- `StockOptionLevel`: Level of stock options.
- `TotalWorkingYears`: Total number of years worked.
- `TrainingTimesLastYear`: Number of training times last year.
- `WorkLifeBalance`: Employee satisfaction with work-life balance.
- `YearsAtCompany`: Number of years at the company.
- `YearsInCurrentRole`: Number of years in the current role.
- `YearsSinceLastPromotion`: Number of years since the last promotion.
- `YearsWithCurrManager`: Number of years with the current manager.
</details>

## Project Workflow
1. **Data Loading and Cleaning**
   - The dataset was downloaded from Kaggle and loaded into Python using Pandas.
   - Data cleaning steps included:
     - Removing duplicate records
     - Handling missing values.
     - Transforming categorical columns (e.g., Attrition) into numerical values for analysis.
2. **Data Analysis with Python**
   - The cleaned data was analyzed using Python.
   - Key analyses performed:
     - Attrition rate by department and job role.
     - Average monthly income and years at the company.
     - Employee satisfaction levels (environment, job, work-life balance).
     - Impact of business travel and overtime on attrition.
     - Relationship between salary hike and performance rating.
3. **Dashboard Creation**
   - The analyzed data was used to create an interactive dashboard in Tableau.
   - Key visualizations:
     - Gender and age distribution of employees.
     - Attrition rate by department and job role.
     - Average monthly income and years at the company.
     - Employee satisfaction levels (environment, job, work-life balance).
     - Impact of business travel and overtime on attrition.

## Tableau Screenshot
<img width="1199" alt="Screenshot 2025-02-25 at 13 11 44" src="https://github.com/user-attachments/assets/7bbd9565-0378-4d50-ac8c-4dd4f3b50d27" />

The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/deddy.putra/viz/HRAnalytics2_17404586516460/Dashboard33).
## Project Structure
```
hr-attrition-analysis/
├── data/
│   └── HR_Analytics.csv
├── notebooks/
│   └── hr_analysis.ipynb
├── dashboard/
│   └── hr_dashboard.twbx
├── images/
│   └── dashboard_screenshot.png
└── README.md
```

## Key Insights

1. **Attrition Rate**: The overall attrition rate is 16.1%, with the highest attrition in the Sales department (20.7%).
2. **Job Role Impact**: Sales Representatives have the highest attrition rate (39.3%).
3. **Employee Satisfaction**: Employees with lower environment and job satisfaction scores are more likely to leave.
4. **Income and Tenure**: Employees with lower monthly income and shorter tenure are more likely to leave.
5. **Overtime Impact**: Employees working overtime have a higher attrition rate (25.5%) compared to those who do not (14.2%).

## **Recommendations**  

- **Targeted Retention Programs**: Focus on high-attrition roles such as Sales Representatives and Laboratory Technicians.
- **Improve Satisfaction Levels**: Enhance workplace environment and job satisfaction through employee engagement programs.
- **Income and Tenure Analysis**: Review compensation and tenure policies to retain employees with lower income and shorter tenure.
- **Overtime Management**: Implement policies to manage overtime and reduce burnout among employees.

## Contact
For questions or feedback, feel free to reach out:
- Name: Deddy Laudryansyah Putra
- Email: ldeddy25@gmail.com
- LinkedIn: [@deddyl](https://www.linkedin.com/in/deddyl/)
- GitHub: [deddylx](https://github.com/deddylx)
