# HR-Dashboard
1. Introduction
In today’s competitive business environment, organizations are increasingly recognizing the importance of data-driven Human Resource (HR) decision-making. Traditional HR reporting methods are often static and time-consuming, providing limited insights.
The HR Analytics Dashboard developed in this project aims to visualize, analyze, and interpret employee data to uncover key workforce trends, especially focusing on employee attrition, job satisfaction, and workforce demographics.
This interactive dashboard helps HR professionals monitor performance indicators, identify problem areas, and implement targeted employee retention strategies.
________________________________________
2. Objectives
The main objectives of this project are:
1.	To design a data-driven HR dashboard that consolidates multiple HR metrics into one interactive view.
2.	To analyze attrition patterns across various dimensions such as department, age, gender, and education field.
3.	To evaluate job satisfaction across different job roles.
4.	To provide management with actionable insights for reducing attrition and improving employee engagement.
5.	To demonstrate data visualization and analytical storytelling using Tableau.
________________________________________
3. Tools and Technologies Used
Component	Description
Software	Tableau Desktop
Dataset Source	HR Employee Dataset (CSV / Excel file)
Data Attributes	Employee ID, Age, Gender, Department, Education Field, Job Role, Job Satisfaction, Attrition, etc.
Visualization Techniques	Pie Charts, Donut Charts, Bar Graphs, KPI Cards, Heat Maps, Filters, and Dashboards
System Requirement	Windows 10/11 with Tableau Desktop
Data Size	170 employee records
________________________________________
4. Dataset Overview
The dataset used in this dashboard consists of 170 employee records with the following attributes:
Field Name	Description
Employee ID	Unique identifier for each employee
Age	Age of the employee
Gender	Male / Female
Department	Department (e.g., HR, R&D, Sales)
Education Field	Academic background (Medical, Life Sciences, Technical Degree, etc.)
Job Role	Specific job title
Job Satisfaction	Rating from 1 (Low) to 4 (High)
Attrition	Whether the employee left the organization (Yes/No)
________________________________________
5. Methodology
The project was carried out in multiple stages:
Stage 1: Data Import and Cleaning
•	The dataset was imported into Tableau from an Excel/CSV file.
•	Missing values were handled and data types were corrected (e.g., numerical vs categorical).
•	Calculated fields were created for Attrition Rate and Active Employees.
Stage 2: Visualization Development
Multiple worksheets were created to analyze data from different perspectives:
•	Department-wise Attrition
•	Education Field-wise Attrition
•	Attrition by Gender and Age Group
•	Job Satisfaction by Job Role
•	Age Group Distribution of Employees
Stage 3: Dashboard Design
•	Combined individual worksheets into an interactive dashboard layout.
•	Added filters (e.g., Education Field) and color legends for interactivity.
•	Enhanced readability using bold KPIs, color codes, and tooltips.
Stage 4: Story Creation
•	Developed an interactive story in Tableau to narrate HR insights sequentially — enabling data-driven storytelling for HR professionals.
________________________________________
6. Dashboard Description and Insights
A. KPI Section
Employee Count: 170
Attrition Count: 31
Attrition Rate: 18.24%
Active Employees: 139
Average Age: 32 years
📊 Insight: The attrition rate of 18.24% suggests moderate employee turnover, warranting a closer look at causes and affected demographics.
________________________________________
B. Department-wise Attrition (Pie Chart)
•	HR: 1 (3.23%)
•	R&D: 11 (35.48%)
•	Sales: 19 (61.29%)
📊 Insight: The Sales department exhibits the highest attrition (over 60%), indicating high pressure, performance-based stress, or lack of incentives.
________________________________________
C. Employees by Age Group (Bar Graph)
•	Majority employees are aged between 24–32 years, peaking at 70 employees around 24 years.
•	Fewer employees above 40 years of age.
📊 Insight: The workforce is predominantly young, suggesting potential for growth but also higher early-career turnover risk.
________________________________________
D. Attrition by Gender (Horizontal Bars)
•	Male Attrition: 20
•	Female Attrition: 11
📊 Insight: Male attrition is slightly higher, possibly indicating different engagement or work-life balance challenges between genders.
________________________________________
E. Job Satisfaction Rating (Heat Map)
•	Research Scientists (37 employees) and Laboratory Technicians (35) show generally high satisfaction (ratings 3–4).
•	Managers and Sales Executives show more dissatisfaction.
📊 Insight: Improving management and sales job conditions could reduce attrition significantly.
________________________________________
F. Education Field-wise Attrition (Bar Chart)
Education Field	Attrition Count
Medical	10
Life Sciences	8
Technical Degree	6
Marketing	4
Other	2
Human Resources	1
📊 Insight: Employees from Medical and Life Sciences backgrounds tend to leave more frequently — likely due to better external job offers.
________________________________________
G. Attrition Rate by Gender for Age Groups (Donut Charts)
•	Under 25: 14
•	25–34: 12
•	35–44: 2
•	45–54: 1
•	Over 55: 2
📊 Insight: Attrition is concentrated among younger age groups, especially under 25, where turnover exceeds 25%.
________________________________________
7. Key Findings and Interpretation
1.	Attrition Concentration: Sales and R&D departments face the highest turnover.
2.	Age Impact: Younger employees are more likely to leave.
3.	Job Role Sensitivity: Sales and managerial roles need satisfaction improvements.
4.	Gender Variation: Slightly higher attrition among males.
5.	Educational Trends: Technical and Medical field employees show greater job mobility.
________________________________________
8. Challenges Faced
•	Data inconsistencies (missing values, inconsistent job titles).
•	Managing color balance and dashboard layout for readability.
•	Ensuring KPI accuracy during calculated field creation.
•	Filtering interactions affecting multiple worksheets simultaneously.
________________________________________
9. Conclusion
The HR Analytics Dashboard provides a comprehensive and interactive overview of the organization’s workforce structure and attrition behavior.
By consolidating multiple performance indicators, this dashboard empowers HR managers to make strategic, data-informed decisions that enhance employee satisfaction, retention, and organizational productivity.
It bridges the gap between raw data and actionable insight, enabling quick detection of issues in departments, demographics, or education categories.
________________________________________
10. Learning Outcomes
After completing this project, the following skills and knowledge were gained:
1.	Practical experience with Tableau data visualization and storytelling.
2.	Understanding of data cleaning, transformation, and calculated fields.
3.	Ability to build interactive dashboards and parameterized filters.
4.	Knowledge of interpreting HR metrics like attrition, satisfaction, and demographics.
5.	Experience in data-driven decision support systems for HR analytics.
6.	Strengthened analytical thinking and presentation skills.
________________________________________
11. Future Scope
•	Integrate real-time HR database connections (e.g., MySQL, SQL Server).
•	Add predictive analytics models (attrition prediction using ML).
•	Include metrics like salary, experience, and performance ratings.
•	Automate periodic reporting using Tableau Server or Tableau Public.
•	Extend to interactive dashboards for recruitment and training analytics.
________________________________________
12. References
•	Tableau Official Documentation: https://www.tableau.com/learn/training
•	IBM HR Analytics Employee Attrition Dataset — Kaggle
•	HR Analytics Best Practices — SHRM Reports, 2024
•	Data Visualization in HR — McKinsey Research, 2023
