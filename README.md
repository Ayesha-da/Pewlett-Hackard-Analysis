# Pewlett-Hackard-Analysis
## Overview of the analysis:
To create entity relationship diagrams (ERDs), import data into a database, troubleshoot common errors, and create queries that use data to answer questions to perform employee research to determine who will be retiring and how many vacancies need to be filled, build an employee database with sql by applying data modeling, engineering and analysis skills.
### Purpose:
To determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program.
## Results:
### Retirement Titles table 
Holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955.
![retirement_titles](https://user-images.githubusercontent.com/84524153/126687516-b73fb038-3a14-4374-9578-c4596fdf9e82.png)

### Unique Titles table
Some employees may have multiple titles in the database, because they have switched titles over the years. we will need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. 

![unique_titles](https://user-images.githubusercontent.com/84524153/126687535-205f8e59-03f8-4fa0-8f5c-2fad7e5c5847.png)

### Retiring titles table
To retrieve the number of employees by their most recent job title,we have to use the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title.

![retiring_titles](https://user-images.githubusercontent.com/84524153/126693230-8d1e7a3b-486f-49b2-888a-6b3d105efc7e.png)

### Mentorship Eligibility
To create a Mentorship Eligibility table that holds current employees who were born between January 1, 1965 and December 31, 1965, who are eligible to participate in a mentorship program so experienced and successful employees can step back into a part-time role instead of retiring completely. Their new role in the company would be as a mentor to the newly hired folks.

![mentorship_eligibilty](https://user-images.githubusercontent.com/84524153/126687539-2756c22e-b06a-44f4-992c-e2959a465d93.png)

## Summary:

The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  There are  90398 roles to be filled
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  There are 1549 employees who are eligible to mentor, each one has to mentor about 58 new employees which might be a  big number considering the age of retiring employee and     its a part time job, company have to employ more resources to make it work, informational videos and seeions might help.
  provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
443305 senior engineer443301
![current_total](https://user-images.githubusercontent.com/84524153/126708630-f20c0c5e-62cb-4671-bdb6-947159fae54b.png)
