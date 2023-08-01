# TASK 1
## Introduction
As part of the prerequisite of my data analysis training, a task is to be completed after every class. My first class introduced me to data analysis and it tools. We kicked off with Excel where i learnt to navigate excel cells, worksheets and workbooks. Furthermore we worked on data manipulations and management. The task was to create a table with 20 rows of information having the fields: Employee ID, Employee Full Name, Department (Communications, Sales, I.T), Salary (between $5000 to $25000), Job type (Part-time, Freelance, Contract).
## Task
Create 3 worksheet Using same data information
- In worksheet 1, Show only employees who are ‘Freelancers’ and highlight the ones whose salaries are above $10000
- In worksheet 2, split the employees’ full names into first name and last name. Check for duplicates and highlight if any (do not delete)
- In worksheet 3, highlight employees whose names begin with the letter ‘E’ (in yellow). Format the Salary column such that the highest SALARY has a green background and the lowest SALARY has a red background. Save the Excel file.
## Concept Demonstrated
1. Data manipulations and management
2. Data Filtering/Data Sorting
3. Conditional Formatting
4. Data validation
5. Text-to-Column using delimited to seperate data into columns
## Raw Dataset
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Raw%20data%20for%20task1.png)
## Task Solutions
**In the worksheet below**, I applied filter on all column heading by using sort and filter under _HOME Tab_, I filtered for Employees who are freelancers only by clicking the filter button on the "job type" column and selecting just freelance. To highlight salaries above $10000, I used conditional formatting, chose "Highlight cells rules" then used "greater than", I inputted the value in question($10000) and chose suitable color.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Freelancers%20that%20earn%20above%20%2410%2C000.png)
**In the worksheet below**, I used TEXT TO COLUMN from the _DATA Tab_ to seperate the Full Name column into First name and Last name by choosing delimited and selecting the parameter that seperated the two data which was SPACE. I also used conditional formatting to Highlight duplicates in the first name column.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Employee%20first%20name%20with%20duplicates.png)
**In the worksheet below**, I used conditional formatting, clicked on more rules and chose "cells that only contain". I specified the text by using specific text format and included the yellow color. To highlight highest SALARY with green background and the lowest SALARY with red background again I used conditional formatting, this time I chose "format only top or bottom ranked" that is after clicking on more rules, then I used "top 1" for highest and "Bottom 1" for lowest and applied the relevant colors.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Employee%20whose%20name%20begin%20with%20e.png)
