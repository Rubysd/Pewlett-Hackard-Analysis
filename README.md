# Pewlett-Hackard-Analysis

# Overview of Project
Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

Deliverable 1: The Number of Retiring Employees by Title
Deliverable 2: The Employees Eligible for the Mentorship Program
Deliverable 3: A written report on the employee database analysis README.md.


# Deliverable 1: The Number of Retiring Employees by Title
Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, use the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title.


# Results with detail analysis:

1. A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.

![Captura de pantalla (653)](https://user-images.githubusercontent.com/86340630/129698865-96ed6844-d310-4ab2-96c7-0b4c963ea046.png)

2. Export the Retirement Titles table from the previous step as retirement_titles.csv and save it to your Data folder in the Pewlett-Hackard-Analysis folder.

![image](https://user-images.githubusercontent.com/86340630/129699888-6a72722b-9509-4364-a733-ca0b7a5b4bde.png)

3. Export the Unique Titles table as unique_titles.csv and save it to your Data folder in the Pewlett-Hackard-Analysis folder.

![Captura de pantalla (656)](https://user-images.githubusercontent.com/86340630/129700169-d24cbc92-643e-479e-ade9-e32d41a2355f.png)
![Captura de pantalla (658)](https://user-images.githubusercontent.com/86340630/129700987-40ba4973-7063-449b-ac9b-ba9a7c17d1d3.png)

4. Export the Retiring Titles table as retiring_titles.csv and save it to your Data folder in the Pewlett-Hackard-Analysis folder.

![![image](https://user-images.githubusercontent.com/86340630/129703127-6c5143a2-fce7-4fbd-9b7b-fedc48e9ae0f.png)

# Deliverable 2: The Employees Eligible for the Mentorship Program
Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

1. A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965

![Captura de pantalla (667)](https://user-images.githubusercontent.com/86340630/129711966-2d4e7224-b148-43e2-b412-d9284e3f90df.png)

2. The Mentorship Eligibility table is exported and saved as mentorship_eligibilty.csv

![Captura de pantalla (664)](https://user-images.githubusercontent.com/86340630/129712073-a1702c18-0ec6-46a9-aa7c-55fb08a95228.png)

# Deliverable 3: A written report on the employee database analysis 
Deliverable 3 Instructions
For this part of the Challenge, you’ll write a report to help the manager prepare for the upcoming "silver tsunami."

The analysis should contain the following:

Overview of the analysis: Explain the purpose of this analysis.
Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami.":

1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?.

90,398 roles are in urgent need to be filled out as soon as the workforce starts retiring at any given time.

2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

No, we have 1,940 employees who are eligible to participate in a mentorship program.



















































