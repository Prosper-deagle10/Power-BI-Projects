# Power-BI-Projects

INTRODUCTION:

The Dover Insurance Dashboard dataset offers a treasure trove of employee’s data, presenting a unique opportunity to uncover insights that can guide strategic business decisions and increase workers performance. This analysis revolves around Dover Insurance Company, a nationwide insurance provider whose staff are split into three (3) main product areas/divisions.
1.	Car and Home Insurance
2.	Pet Insurance
3.	Commercial Insurance for Businesses and Organizations.  
Our goal is to journey through this comprehensive dataset using Power BI to identify patterns and trends, uncover insights that will empower the company to enhance its operations and better serve its diverse customer base. Through this tool, this project delves into the company’s numbers to reveal the stories they tell, linking the data back to our shared love of insurance companies and the joy they bring.

PROBLEM STATEMENT:

Recently, there have been an under-performance in the organization from the employees and as a result, a performance analysis, tracking the progress towards a more diverse and inclusive workplace was needed to checkmate absenteeism and turnover which was viewed to be relatively high, low customer turnover and complaints, and employee’s engagement throughout the company. 


DATA ANALYSIS PROCESS:
For an in-depth analysis of employee’s performance trends, it was critical to Clean and Transform the data first. This was carried out using Power Query, to ensure the data was well-structured and ready for analysis in Power BI.


DATA EXTRACTION:
The ETL (Extract, Transform, Load) Process began by importing the table into Power BI. Power Query was used to handle this process enabling us to clean and reshape the data before analysis.
Power Query used for ETL processes.
Data Transformation (Cleaning and Integration):
Removing Duplicates: Duplicate entries were removed from the dataset to ensure accurate analysis. Using Power Query, duplicate rows based on specific keys were filtered out.
Handling Null or Missing Values: For some columns, missing values were replaced with defaults or averages. Null values in “key” columns were removed using filters, though there was none. 
Data Type Conversion: To ensure data consistency, all columns were converted to appropriate data types. Dates were converted to Date type, numerical columns to Decimal or Whole Number, and text columns to Text.
Standardizing Date Formats: All date columns were formatted consistently to facilitate time-based analysis. This step was important for ensuring accurate time-series analysis in Power BI.

Data Load
The cleaned and transformed data was loaded into Power BI’s data model, ensuring that the table and calculations were accurately reflected.


Key Discoveries and Insights:

Employee’s Analysis:
· Most Active employee on wellness App 2022: employees with the ID number 11927479 and 14213618 spent the most hours on the wellness App, with maximum of 85 hours each. This proves that they are likely a high-value, loyal employees who frequently makes sure that the company’s success is a priority. They are also an example of a target persona for the HR to reward.
. · Most Absent Employee: Employee with the ID 15150052 spent 180 days absent from work in the last 12 months which approximately 6 months off work. Since HR is not all about hire and fire, considerations should be made on such as absenteeism. 


· Most Absent Employee by Age Group: The Young Adults and Midlife Adults spent most days absent from work. This means that employees’ performance is not entirely based on position or division but by age categories. 
· Gender Proficiency: Female employees contribute much more than the Male employees. This suggests that regulation policies should be inclusive, highlighting ethnicity, position and age group that resonate with both genders to maximize reach and company’s objectives. 
.   Age Group and Wellness App patterns: Midlife Adults and Mature Adults show less time spent on the wellness App. Suggesting they either spend more time on non-work contents and show less interest in the company’s progress. Understanding the specific behavior and habits of these groups could unlock further employee’s potential. 

Work ethics Analysis:
. Employer and Employee’s Relationship: 397 of the Admins, 53 Supervisors, 32 senior Mgt staff are not cared for, suggesting the possibility of absenteeism and low performance from them. As the HR of Dover Insurance, workers welfare is key in increasing performance within an organization. 
. Stress Ratio among Employees: Most of the employees found the company’s task very stressful and the stress ratio is abject in promoting low performances among workers. 
. Salary Satisfaction and Work Flexibility Ratio: If higher percentage of the employees can be satisfied with the salary they receive, then the tendency for more proficiency is certain. The more the salary satisfaction, the more the performance. Most of the employees also found the job not flexible.  
	

Based on the findings in this report, here are a few recommendations:

Enhance Employee Engagement and Feedback: Using existing segmentation based on position and age group, Dover Insurance should refine its engagement strategies to personalize employee interactions. HR should regularly solicit feedback from employees to identify areas for improvement and implement changes to boost engagement, motivation and job satisfaction.

Employee Wellness and Support: HR should provide access to wellness programs and support resources to reduce stress, improve work-life balance, and promote overall well-being. 

Clear Communication and Goal Setting: Ensure clear communication of company goals, expectations, and performance metrics to employees, providing regular progress updates and feedback.

Employee Training and Development Program: HR is not all about hire and fire workers. Dover Insurance should implement targeted training initiatives to enhance employee’s skills in areas like Wellness App usage, data analysis, risk assessment and policy optimization. 

