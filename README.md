# Pewlett Hackard Analysis Overview
Known as HP today, Pewlett Hackard has been around for a long time and still employs many baby boomers nearing retirement. HP hired us to help analyze employee data.

## Project Overview
Using PostgresSQL to built HP employees database from scratch thru data modeling, engineering to help answer Bobby's (an HR analyst) burning questions about the future of the HP workforce:
How many employees are nearing retirement in each department?
Who are those eligible for mentorships?
How to replace critical vacancies in time?


### Steps
1. Installed PostgresQSL pgAdmin.
2. created ERD schema. 
3. Create a complete employee database from HP's six excel files.
4. Begin analyzing the data.

### Below is the ERD schema we built to create a relatiships among our tables
![Schema image](https://user-images.githubusercontent.com/72223864/105619915-45726f00-5dc5-11eb-8680-f091c2fa5496.JPG)

### We show employees due for retirement by titles

![Retiring by Title](https://user-images.githubusercontent.com/72223864/105620149-b7e44e80-5dc7-11eb-99d7-73d4fe011d93.JPG)


#### Results:
1. Total employees = 300,024
2. Reached retirement age = 90,398
3. Retiring by title above: Table
4. Eligible for Mentorship = 1549 

### Below you can find a table showing the percent retiring by title
![Percent Retiring by Title](https://user-images.githubusercontent.com/72223864/105661198-da936780-5e9a-11eb-8874-d2813ff04dbd.PNG)

### Summary:
In summary, 30% of HP employees eligible for retirement. After creating a "mentoship_ready by title" table, I found that overall, only 2% are eligible for mentorship - 1% at the Senior Engineers and staffs, 2% Senior Staffs and Technique Leaders, and 0% manager title. Please see the complete table below with queries at the queries files.
### The mentorship ready table
![Eligible Mentors by department](https://user-images.githubusercontent.com/72223864/105661342-29410180-5e9b-11eb-9bfe-92cefcd3f3d5.PNG)
