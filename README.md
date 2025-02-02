**STUDENTS MATHS ANALYSIS**


**Project Overview**

This extensive analysis of student math performance is designed to monitor, assess, and interpret academic progress. It highlights critical metrics and trends through a visually engaging and interactive platform, providing school teams with the insights needed to make informed, data-driven decisions that enhance student development and overall performance.

**Key Performance Indicators (KPIs)**
The analysis focuses on the following KPIs:
•	Total Students:  Shows the overall number of students.
•	Total number of male and female students

**DAX Analysis**

Below are some key DAX measures used in the dashboard:
•	Total students
Total student = COUNTROWS('student-mat')

•	**Students by Gender:**
Male = CALCULATE('student-mat'[Total Student], 'student-mat'[sex] = "Male")
Female = CALCULATE('student-mat'[Total Student], 'student-mat'[sex] = "Female")

•	**Student Punctuality**
Added an additional column with a conditional statement to categorize students' school attendance as good, fair, bad, or worse.
0-10	Good
11-20	Fair
21-40	Bad
40 and above  Worse 

•	**Student Grades**
I added an additional column with a conditional statement to display the psychological evaluation of students' grades, using categories such as poor, fair, good, very good, and excellent.
0-4	Poor
5-8	Fair
9-12	Good
13-16	 Very Good
17-20	 Excellent

**Visualizations**
•	Student health status: A clustered bar chart visualization showing the total number of students by their health status.
•	Student romantic relationship: A pie chart visualizing the total number of student by their romantic relationship.
•	Student Punctuality: A clustered column chat visualization showing the total number of student by their punctuality in school.
•	Student Failure: A line chart visualization showing the total number of student by their failures.
•	Student weekly study time and free time after school: A clustered column chart visualization showing the total number of students by their study time and free time.
•	Student interest in higher education: A donut chart showing the total number of student by their interest in higher education.
•	Student family support, extra education support and extra paid class: A clustered column chart showing the total number of student by their family support and extra paid class
•	Slicer to filter data by school and guardian
