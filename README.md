# Pewlett-Hackard-Analysis_folder
## Overview of the Analysis
The comapny Pewlett Hackard is approaching an important milestone - The Silver Tsunami. The company wants to provide the retiring generation with a nice retirement bonus so they are set up for the rest of their days. Since many individuals will be retiring, the company will have to hire a variety of people to support the company. That being said, the company also wants to implement a mentorship program to ensure that the new employees have enough guidance to be productive members of the Pewlett-Hackard family!

To successful complete the analysis I built an entity relationship diagram (ERD) to capture the relationships that I found in the supplied data. 
![ERD](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/blob/main/Resources/Screen%20Shot%202021-04-13%20at%205.57.36%20PM.png)

### Resources
Software: Pg Admin - PostgreSQL 11, VS Code

[Data](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/tree/main/Data)

[Queries](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/tree/main/Queries)

## Results
### Part 1
The first part of the anaylsis was to create a table that held all of the unique individuals that were retiring, along with their job titles. Finally, I found the amount of each of the unique job titles that were retiring.

![Deliverable 1](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/blob/main/Resources/Deliverable_1.png)

Above is a snapshot of the table of all of the unqiue people that are retiring.

![Deliverable_yes](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/blob/main/Resources/Deliverable_1.2.png)

Above is the completed deliverable. As it can be seen from this snapshot:

- There are 90,398 people that are retiring soon (individuals that were born between 1952 and 1955). 
- More than 50% of the employees retiring are senior staff or senior engineers (talk about a brain drain!)

### Part 2

All of this institutional knowledge leaving would be a problem, but smart executives at Pewlett-Hackard have decided to create a mentorship program to train the next generation of employees. Below is the completed second deliverable.

![Deliverable_2](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/blob/main/Resources/Delv_1.png)

Additionally, I wanted to find the count of each of the unique job titles for the mentorship list. Below is a snapshot of that table

![Mentorship_count](https://github.com/jackogross123/Pewlett-Hackard-Analysis_folder/blob/main/Resources/mentorship_count.png)

As it can be seen from these two tables:

- There are 1,549 employees that are eligible to be a mentor.
- 675 these people are Senior Staff or Senior Engineers.

## Summary:

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are currently 240,124 employees that are working at the company. Over 90,000 of these individuals will be retiring within the next years. More specifically, over 37% of the company is on the retirment path. Even more shockingly, the majority of those leaving are senior employees with years of knowledge. To replace the old generation, over 90,000 people have to be hired in order to support the either out-sourcing or in-house promotions of people.

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There are not enough of retirement-ready employees in each of the departments to mentor the next generation of employees. There are only 1,549 people that are elidible to mentor the sum 90,000 new people that will need to be hired in order to support the retirement at the top of the company. 
