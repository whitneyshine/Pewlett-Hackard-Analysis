# Pewlett-Hackard-Analysis

**Background**<br><br>
Bobby's manager has given both of you two more assignments: determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. Pewlett-Hackard would like to launch a new mentoring program with employees eligible to retire in the near future. Instead of having a large chunk of their workforce retiring, they want to introduce a mentoring program: experienced and successful employees stepping back into a part-time role instead of retiring completely. Then, summarizes your analysis in order to help  Bobby’s manager prepare for the “silver tsunami” as many current employees reach retirement age.  Since Pewlett-Hackard has no real database or data management system in place, understanding the data we are working with and finding the connections within is a huge step.<br><br>
**Overview of the Analysis**<br><br>
Our first assignment is to create a Retirement Titles table that contain all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Some employees have had multiple titles in the database—for example, due to promotions—we will need to create a table that contains the most recent title of each employee. Then, we will create a final table that has the number of retirement-age employees by most recent job title.<br><br>
The second leg of our assignment will be to create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.  The current employee pool will be extracted from the nine departments that Pewlett-Hackard allocates their employees in respectively.<br><br>
![PH_Departments](Data/PH_Departments.png)<br><br>
**Results**<br><br>
•	**Employees Eligible for Retirement**<br><br>
The first major point we can draw from the Retiring Titles report we created is that 30% of the employees are eligible for retirement.  That is an astounding number to digest as well as plan an effective succession plan.  <br>
[Retiring_Titles](https://github.com/whitneyshine/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)<br><br>
What the data also tells us is that 64% of the Retiring Titles are comprised of Senior Level Employees and if we look at it from the big picture of Pewlett-Hackard, that is total represents 19% of their current workforce.<br><br>
•	**Years of Service with Pewlett-Hackard**<br><br>
There are duplicate entries for some employees because they have switched titles over the years.  With the Unique Titles table we created, I believe we left off some valuable information that management would love to digest.  The main objective in presenting this analysis is to create a correct lens of data that the intended audience needs to view.  When we eliminate the dates that show the eligible retiring employee and held all their unique positions, we are not thoughtfully planning for the impact that Pewlett-Hackard will endure since we have minimized the total years of service given by each retirement eligible employee.  For example, Sumant Peac has had an extraordinarily successful career at Pewlett-Hackard based on his two promotions and 36 years of service.  We lose this analysis in the Unique Titles table because we altered the true line of progression of how the employees career began as an Assistant Engineer, promoted to Engineer, and will commence as a Senior Engineer.  If we look at the criteria of the Unique Titles query, we wanted to retrieve the most recent title and because of that simple enhancement, we skew the data regarding what we are truly losing regarding Pewlett-Hackard institutional knowledge.  The amended data tells us we are just losing a Senior Engineer but in truth, we are losing what we are trying to create or maintain in our Mentorship Eligibility report.  I would stand to say that we need to reevaluate our criteria as Sumant Peac is certainly an employee who has earned their eligibility for retirement but one we would like, and need, to serve as a mentor for our next generation of employees.<br><br>
![retirement_titles_date](Data/retirement_titles_date.png)<br><br>
•	**Employees eligible for Mentorship**<br><br>
A major point we can draw from the Mentorship Eligibility table we created is that 1% of our employees are identified in the mentorship eligibility query – or put another way, a total of 1,549 employees.  That is an exciting number to see as we plan to launch of Mentorship Program.  What the data does tells us is that 45% of the eligible Mentors have Senior in their titles.  The bright side of having such a small sample size but filled with senior level expertise is that the mentorship process can be more in-depth since this is going to be a critical and crucial implementation. More than likely, we have identified most of the employees who will mature into the agents of change and future leaders within the Pewlett-Hackard organization.<br><br>
![mentorship_eligibility_results](Data/mentorship_eligibility_results.png)<br><br>
•	**Departments with the most eligible for Mentorship**<br><br>
As we enter the phase of implementation for the mentorship program, one of the most important aspects we need to consider in our recommendation is how are we going to launch this program efficiently and effectively.  This table brings to light an interesting approach since we need to analyze our data to chart our productive course forward.  I wanted to see from our Mentorship Eligibility report what departments contained the most employees eligible for mentorship as well as from what departments contained the least amount of eligible employees.  This tells us for the departments that contain a high concentration of eligible employees, we should highly consider a team’s approach that involves a trickle-down approach training style.  In this approach, the highest tenured employees can work together to develop a best approach method and then eventually work as a team to bring the next employment generation up to their level of expertise by the time their retirement date vest.  For departments that are smaller in size is when you need to focus the help of not only the department experts but also Human Resources as well as consider retaining more retirement eligible employees that are centers of influence and experts.  The departments with lower levels of expertise will need a higher level of resources and time concentration during the initial mentorship.<br><br>
![PH_Mentorship_Departments](Data/PH_Mentorship_Departments.png)<br><br>
**Summary**<br><br> 
•	How many roles will need to be filled as the "silver tsunami" begins to make an impact?<br><br>
•	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett-Hackard employees?<br><br>

Pewlett-Hackard has fallen behind in the database department, so it will be a huge achievement to get personnel data organized for the company.  They are using their leading indicator data as a lagging indicator and it is paramount that they implement an HR software that houses professional certifications as well as industry training that the employee has attended and earned proper credit to properly manage future retirement dates.   Also, Pewlett-Hackard should created their own internal trainings or certifications that are geared towards their industry specialties as well as establish an in-house HR training that they are required to take as they gravitate towards becoming leaders or senior staff in their careers.  Data integrity is the quality of the data we are working with and that also needs to be applied to their employee data to maximize their return on investments as a company since their employees are their greatest investments. Clean data will yield better results during their analysis and maintaining the data integrity ensures greater accuracy, reliability, and highest return on the employee investment. With that being said, I recommend implement Workday as their source of truth for when it comes to employee and employment data.  Workday will significantly improve HR and Payroll compliance, reduce risk, provide better data for decision making, and increase efficiencies across the institution. It will also enable employees to work more efficiently by having consistent, streamlined, and modern practices.  I have attached the five benefits of using Workday here in the Pewlett-Hackard [WORKDAY](https://www.workday.com/en-us/pages/infostudy-bredin-fast-track-to-growth-hr.html) recommendation.
