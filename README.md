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
**In the worksheet below** also referred to as work sheet1, I applied filter on all column heading by using sort and filter under _HOME Tab_, I filtered for Employees who are freelancers only by clicking the filter button on the "job type" column and selecting just freelance. To highlight salaries above $10000, I used conditional formatting, chose "Highlight cells rules" then used "greater than", I inputted the value in question($10000) and chose suitable color.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Freelancers%20that%20earn%20above%20%2410%2C000.png)
**In the worksheet below** also referred to as work sheet2, , I used TEXT TO COLUMN from the _DATA Tab_ to seperate the Full Name column into First name and Last name by choosing delimited and selecting the parameter that seperated the two data which was SPACE. I also used conditional formatting to Highlight duplicates in the first name column.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Employee%20first%20name%20with%20duplicates.png)
**In the worksheet below** also referred to as work sheet3, I used conditional formatting, clicked on more rules and chose "cells that only contain". I specified the text by using specific text format and included the yellow color. To highlight highest SALARY with green background and the lowest SALARY with red background again I used conditional formatting, this time I chose "format only top or bottom ranked" that is after clicking on more rules, then I used "top 1" for highest and "Bottom 1" for lowest and applied the relevant colors.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Employee%20whose%20name%20begin%20with%20e.png)



# TASK 2
## Introduction
The second class of my training was a detailed lesson on Excel formulas and function, where I learnt how to use relative and absolute referencing and the basic funtions in excel that aids the use of formulas for excel calculations. With this, I learnt how to analyze sales data and how using this formulas to answer questions can gives clarity to business growth. After the day's discussion, a task followed. The task was to use formulas and functions in excel to answer questions regarding a sales data that contained the following column headings: Segment, Country, Product, Discount, Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, Profit, and Month columns.
## Task
Using the same Sales Data, determine the following
- The total Revenue and Profit generated
- The average Revenue and Units Sold for every order
- The total Discount given in $
- Total number of sales recorded
- The highest Profit generated
- Create a column named ‘Sales Range’, return ‘High Sales’ if the Sales value is above average, otherwise, return ‘Low Sales’.
## Concept Demonstrated
1. Relative and Absolute Cell References
2. Basic Formulas in Excel
## Raw Dataset
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Raw%20data%20for%20Task%202.png)
## Task Solutions
For Question 1, I calculated for total revenue and total Profit generated. I used the **_SUM function_** i.e =SUM(J2:J701) which is the addition of all cells in the sales column and =SUM(K2:K701) which is the addition of all cells in the profit column respectively.
Total Revenue                                                       | Total Profit
:------------------------------------------------------------------:|:-----------------------------------------------------------------:
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Total%20Revenue%20Generated.png) | ![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Total%20profit%20generated.png)
Question 2, I calculated Average revenue and Average Unit sold for every order. I used The **_Average function_** i.e  =AVERAGE(J2:J701) which is the average of all cells in the sales column and =AVERAGE(E2:E701) which is the average of all cells in the column for units sold.
**Average Revenue**                                                       | **Average Unit sold**
:------------------------------------------------------------------:|:-----------------------------------------------------------------:
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Average%20revenue.png) | ![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Average%20Unit%20sold.png)

Question 3, I calculated the total Discount given by using the **_SUM funtion_** i.e =SUM(I2:I701) which is the addition of all cells in the Discount column 
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Total%20discount%20given.png)
For question 4, to calculate the total number of sales I used the **_COUNT funtion_**, which helps in numbering the sales and giving the total number i.e =COUNT(J2:J701)
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Number%20of%20sales%20Generated.png)
To calculate Highest profit in question 5, I Used the **_Max funtion_**, which returns the maximun number in a group of cells down a column. in this case for profit column i.e =MAX(K2:K701)
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/Highest%20profit%20generated.png)
For the last Question, I used the **_conditional function IF_**, where I stated a logical test and gave conditions if true and if not.It is used two conditions "high" and "low"are used to define one variable "Sales" from a particular point i.e =IF(J2>$P$3,"High sales","Low sales") where P3 is the cell name where the average sales. I also used absolute referencing to hold the cell so it becomes a constant as we move down the sales column.
![](https://github.com/AnietieJohnson/Week1-Excel-task/blob/main/High%20or%20low%20sales%20column.png)
