# Pewlett-Hackard-Analysis
## Overview 
The purpose of this project is to gather the retiring employees information so taht the management can prepare for the “silver tsunami” and to identify the employees who are eligible to participate in the mentorship program by using SQL queries.

## Results
Using SQL, a *retirement_titles* table was created and the list of retiring employees were added. Using the DISTINCT ON(), COUNT() functions and GROUPBY clause , the list of most recent title of the retiring employee as well as the count was fetched and added to the *unique_titles* and *retiring_titles* table. The number of employees eligible for the mentiorship program were fetched using joins and DISTINCT ON() function and loaded into the *mentorsip_eligibility* table.
The following analysis was made from the created tables.
 - 1,33,777 records were retrieved when filtered based on the retirement criteria.
 - When filtered by the unique titles, 90,399 employees were retrieved.
 - Employees with 7 unique titles are retiring.
 - The most number of employees retiring are of the titles Senior Engineer and Senior Staff.
 - 1549 employees were found eligible for the mentorship program.
 
## Summary:  
- Based on the above analysis, we can predict that about employees in 7 unique titles has to filled before the "Silver tsunami" makes an impact.
- 1500+ qualified, retirement-ready employees are available to mentor the next generation of Pewlett Hackard employees.

The following additional queries/tables can be made to provide more insight into the upcoming "silver tsunami."
- The number of retirees by department can be queried to get insight on the number of employees per department who will need to be hired.
- The employees who served the longest can be queried to identify the longest serving employees of Pewlett Hackard.
