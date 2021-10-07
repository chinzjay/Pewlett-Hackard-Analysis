# Pewlett-Hackard-Analysis
## Overview 
The purpose of this project is to gather information about the retiring employees so that the management can prepare for the “silver tsunami” and to identify the employees who are eligible for the mentorship program by using SQL queries.

## Results
Using SQL, a **retirement_titles** table (https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv) was created and the list of retiring employees were added. Using the DISTINCT ON(), COUNT() functions and GROUPBY clause , the list of most recent title of the retiring employee was fetched and added to the **unique_titles** (https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv). *Fig 1* depicts the code snippet that was used to retrieve the unique titles of the retiring employees.
![code_snippet](https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/code_snippet.PNG)
|:--:|
|Fig 1. Code snippet of DISTINCT ON() function to retrieve data by unique titles|

The count of retiring employees by title was added to the **retiring_titles** table (https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv). 
*Fig 2* depicts the count of the retiring employees by title.
![title_count](https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/title_count.PNG)
|:--:|
|Fig 2. Count of the retiring employees by title(retiring_titles.csv)|

 The employees eligible for the mentorship program were fetched using joins and DISTINCT ON() function and loaded into the **mentorsip_eligibility** table (https://github.com/chinzjay/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv).
 
The following analysis were made from the new tables.
 - 1,33,777 records(retiring employees) were retrieved when filtered based on the retirement criteria.
 - When filtered by the unique titles; 90,399 records were retrieved.
 - Employees with 7 unique titles are retiring.
 - The most number of employees retiring are of the titles Senior Engineer and Senior Staff.
 - 1549 employees were found eligible for the mentorship program.
 
## Summary:  
- Based on the above analysis, we can predict that about employees of 7 distinct titles has to filled before the "Silver Tsunami" makes an impact.
- 1500+ qualified, retirement-ready employees are available to mentor the next generation of Pewlett Hackard employees.

The following additional queries/tables can be made to provide more insights into the impact of upcoming "Silver Tsunami".
- The number of retirees by department can be queried to get insight on the number of employees per department who will need to be hired.
- The employees who served the longest in the company can be queried to identify the longest serving employees of Pewlett Hackard.
