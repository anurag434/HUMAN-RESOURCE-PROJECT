# HUMAN-RESOURCE-Analysis

# Dataset overview

*Fields (11): EmployeeID, Name, Age, Salary, Gender, Department, Position, Joining Date, Performance, Email, Phone Number
*Objective: Clean and prepare HR data for reliable analysis by fixing inconsistent formats, missing values, and invalid entries.

# Initial Observations


 1)Name: All values were in lowercase.
 
 2)Age & Salary: Contained mixed text and numeric values (e.g., "thirty", "30", "sixty thousand", "65000").
 
 3)Joining Date: Multiple inconsistent formats (e.g., April 5, 2018, 01/01/2000, 01-01-2000, 2000.12.01).
 
 4)Email, Age, Salary, Phone Number: Included missing values, nan, and NAN.
 
 5)Gender, Department, Position: Clean — no missing values, case issues, or invalid entries.
 
 6)Duplicates: None found.

 # Cleaning steps

 1)Used PROPER function to convert lowercase to proper case
 
 Handling missing values using find & replace [ctrl+H]

 Fixed joining date using Text to Columns

 Removed NAN in salary field and replace with salary median using MEDIAN function

 Created an Employee ID uding flashfill

 # POWER BI DASHBOARD

Ater cleaning HR dataset, I created a Power bi dashboard to visualize the key insights

# Used Tools

DAX and Data visualization

# key insights

[TOTAL SALARY PAID: 60M,AVG PERFORMANCE: 3.02,TOTAL EMPLOYEE: 1000]

1)Assistant have the highest salary paid and manger have the lowest

2)while comparing performance score with other department Finance have the
highest score

3)salary paid to male is higher comparing to other and female

4)Finance have the highest salary paid in department

5)highest joining date is 20 feb 2020

6)clerk and assistant roles dominate the workforce while analysts remain the
smallest group

 

 
 





