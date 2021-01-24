# Pewlett Hackard Analysis
Known as HP today, Pewlett Hackard has been around for a long time and still employes a large number of the baby boomers who are nearing
retirement. 
## Project Overview
Using PostgresSQL to built HP employees database from scratch thru data modeling, engineering to help answer Bobby's (an HR analyst) burning questions about the future of the HP workforce:
1. How many employees are nearing retirement in each department?
2. Who are those eligible for mentorships?
3. How to replace critical vacancies in time?

### Steps
1. Installed PostgresQSL pgAdmin.
2. Create a complete employee database from HP's six excel files.
3. created ERD schema. 
4. Begin analyzing the data.

### Below is the ERD schema we built to create a relatiships among our tables
![Schema image](https://user-images.githubusercontent.com/72223864/105619915-45726f00-5dc5-11eb-8680-f091c2fa5496.JPG)

### We show employees due for retirement by titles

![Retiring by Title](https://user-images.githubusercontent.com/72223864/105620149-b7e44e80-5dc7-11eb-99d7-73d4fe011d93.JPG)


#### SELECT COUNT(*) FROM employees 
Gave us the total number of employees which is 300,024
#### SELECT COUNT(*) FROM retirement_titles (A table we recreated for employees born between 1952 and 1955).
The total number of employees eligible for retirement = 133,776. 
Thus, 45% of HP employees have reached the retirement age, and HR must act now.

## Conclusion 
We upgraded Pawlett Hackard's database system from Excel to PostgresSQL for efficiency and convenience and found out 45% of their workforce 
are eligible for retirement. 
