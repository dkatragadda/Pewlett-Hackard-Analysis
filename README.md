# Pewlett-Hackard-Analysis

## Overview of the Pewlett-Hackard-Analysis Analysis
The purpose of this analysis was to use our skills in creating an employee database for Pewlett-Hackard by ingesting the csv files into tables and creating new tables to determine the number of employees who are nearing retirement. This exercise will help the company plan better by recruiting workforce to replace the retiring workforce. We used PostgreSQL and pgAdmin to create the database, tables and run queries on the database.

## Results

* Pewlett-Hackard has 300024 employees out of which 90398 employees are due to retire soon who constitute 30% of the total workforce

* More than 60% of the employees who are retiring have two main titles - 'Senior Engineer' and 'Senior Staff' - The table below shows the count of employees who are retiring by title

![Retiring_Titles](https://github.com/dkatragadda/Pewlett-Hackard-Analysis/blob/main/Retiring_Titles.png)

* 1549 employees have been identified as eligible for the mentorship program

* 70% of the employees eligible for mentorship have the titles 'Senior Engineer' and 'Senior Staff' - the table below shows the count of employees by title who are eligible for mentorship

![Mentorship_Eligibility](https://github.com/dkatragadda/Pewlett-Hackard-Analysis/blob/main/Mentorship_eligibility_count.png)

## Summary

* More than 90398 employees are retiring as part of the upcoming silver tsunami. This can cause a shrinkage in the workforce for Pewlett-Hackard as the silver tsunami accounts for 30% of the total employee pool. However, as the company keeps up with the times and focuses on automation, some of these roles may be replaced with technology. However, to maintain business continuity, my recommendation would be to hire replacements for at least 80% of the headcount. The remaining 20% may be addressed to robotic process automation if the tasks can be programmed. 

* There are more than enough retirement ready employees who can mentor the next generation of Pewlett-Hackard employees. The pool eligible for mentorship is 1549 employees and there are more than 90K employees as a part of the silver tsunami. 

Two additional tables that would help in overcoming the silver tsunami are:
1. Create a table which helps in maintaining the count of employees by dept who are due to retire - This will help the company create department specific strategies that will fill the void. 
2. Create a table which helps in maintaining a distribution of the employees due to retire over the next 4 years (employees born between 1952 and 1955) in bins of 6 months to ensure a time bound strategy to fill the void and also develop training programs for the workforce eligible for mentorship. This helps in breaking down the task at hand in a phased manner.  
