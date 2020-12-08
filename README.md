## HR_Excel_Dashboard

Introduction:
Human resource management as a department in an organisation handles all aspects of employees and has various functions like  human resource planning, Conducting Job analysis, recruitment and conducting job interviews, selection of human resources, Orienting , training, compensating, Providing benefits and incentives, appraising, retaining, Career planning, Quality of Work Life, Employee Discipline,  black out Sexual Harassments, human resource auditing, maintenance of industrial relationship, looking after welfare of employees and safety issues , communicating with all employees at all levels and maintaining awareness of and compliance with local, state and federal labour laws.
 
Importance of Human resource department:
Behind production of every product or service there is a human mind, effort and man hours (working hours). No product or service can be produced without help of human being. Human being is fundamental resource for making or construction of anything. Every organisation desire is to have skilled and competent people to make their organisation competent and best.
Among the five Ms of management, i.e., men, money, machines, materials, and methods, HRM deals about the first M, which is men. It is believed that in the five Ms, "men" is  not so easy to manage. "every man is different from other" and they are totally different from the other Ms in the sense that men possess the power to manipulate the other Ms. Whereas, the other Ms are either lifeless or abstract and as such, do not have the power to think and decide what is good for them.
Purpose of HR Management:
The purpose of the Human resource management is to make the job and deal with the job holder (employee). To perform a job in an organisation, one needs to be identified. In order to identify right person for particular job, notification should be issued which contains job description (duties and responsibilities) and specifications (academic qualifications and physical qualifications). So as to verify the correctness of the candidates invited, they should be tested by the suitable selection methods for picking-up right person. Subsequently selected candidates should be provided with the proper training for performing his duties & responsibilities mentioned in the notification. Later, assessment of employees' performance should be done to know whether employees are performing to the desired standards set by the management. According to employees should be rewarded or paid for the job they did in the organisation and their safety in the job is the responsibility of Hr manager or safety officer who should instruct safety measures for the employees and see that they are scrupulously followed. Healthy and welfare measures are so-so important to keep employees happy and motivated which has direct impact on their productivity. Doing so all, maintaining proper and healthy relationships between employees and management avoids conflicts which will affect the overall performance of the organisation. Most important thing is adherence and not to ignore employment and labour laws which govern all the above said activities for a job. Contravenes of employment laws will cost to the organisation and its branding. Hence the Human resource management is like a guardian angel for the organisation to sail smoothly and long live.
Data Science: Data science is the field of study that combines domain expertise, programming skills, and knowledge of mathematics and statistics to extract meaningful insights from data. Data science practitioners apply machine learning algorithms to numbers, text, images, video, audio, and more to produce artificial intelligence (AI) systems to perform tasks that ordinarily require human intelligence. In turn, these systems generate insights which analysts and business users can translate into tangible business value.
Objectives/Scope of the Analysis:
HR dashboards have come to play a critical role for data-driven HR departments. Besides providing stakeholders with important information at a glance, HR dashboards also give HR personnel the quick insights they need to make important talent management decisions, through things such as data visualizations.
If you’re overwhelmed by data and looking for an HR dashboard to make sense of it, you’re in luck: These days, most HR software systems have dashboards that don’t require a business intelligence pedigree to use.
But with so many options to choose from, it can be difficult to discern which dashboards will actually aid in your decision-making and which ones will lead to even more confusion than before.
The quickest and easiest way to come up with an HR dashboard shortlist for your business is to compare dashboard reviews from current and past users.
That’s why we’ve analyzed real user reviews of HR software products on Capterra to determine the best-reviewed HR dashboards.
Users of these products mentioned the dashboard functionality positively in their reviews more often than any other. The products are listed alphabetically.
Source of dataset:
The data used for the software is compiled by the company named as obvience and this is four years of HR data available on Kaggle. This data contains 48 excel files of four years starting from January 2015 to December 2018.
 
This workbook contains a modified version of dataset provided by Obvience.
 
www.obvience.com
 

Obvience is an ISV and an Intellectual Property (IP) Incubator focused on Microsoft Business Intelligence.  Obvience works closely with Microsoft to develop best practices and thought leadership for jump-starting and deploying Microsoft Business Intelligence solutions.
This file and associated data is property of obviEnce llc and has been shared solely for the purpose of demonstrating Power BI functionality with industry sample data.
Any uses of this workbook and/or data must include the above attribution. The workbook and any visualization pages must be accompanied by the following copyright notice: obviEnce ©.
ETL process:
ETL is defined as a process that extracts the data from different RDBMS source systems, then transforms the data (like applying calculations, concatenations, etc.) and finally loads the data into the Data Warehouse system. ETL full-form is Extract, Transform and Load. 
It's tempting to think a creating a Data warehouse is simply extracting data from multiple sources and loading into database of a Data warehouse. This is far from the truth and requires a complex ETL process. The ETL process requires active inputs from various stakeholders including developers, analysts, testers, top executives and is technically challenging. 
In order to maintain its value as a tool for decision-makers, Data warehouse system needs to change with business changes. ETL is a recurring activity (daily, weekly, monthly) of a Data warehouse system and needs to be agile, automated, and well documented. 
 
Need of ETL Process 
•	ETL process allows sample data comparison between the source and the target system. 
•	ETL is a predefined process for accessing and manipulating source data into the target database. 
•	Allow verification of data transformation, aggregation and calculations rules. 
 
When it comes to the implementation of the ETL process, the itinerary of tasks can be divvied up into the full form of its acronym. 
1.	E – Extraction 
2.	T – Transformation 
3.	L – Loading
As the Data is already cleaned and available in the cleaned form so I did not use ETL Process using tableau in this project.
Analysis on dataset (for each analysis):
Introduction:
An HR dashboard is an advanced analytics tool that displays important HR metrics using interactive data visualizations. It helps the HR department to improve recruiting processes, optimize the workplace management as well as to enhance the overall employee performance.

Just like so many of today’s business departments, human resources is slowly but surely evolving into a data-driven function. Filled with numerous HR KPIs, the purpose is to go from simple reporting to smarter use of analytics, enabling companies and managers to track and predict employees’ performance, make better-informed talent decisions, and have the opportunity to operate advanced workforce planning with the help of modern HR analytics software. Turning to a professional online dashboard, HR professionals can keep a close eye on employee performance, recruiting, and talent management processes.
General Description:
As the data contains many files of similar formate I used a power query tool of Excel in my Project.
Power Query is a business intelligence tool available in Excel that allows you to import data from many different sources and then clean, transform and reshape your data as needed. It allows you to set up a query once and then reuse it with a simple refresh. It’s also pretty powerful. Power Query can import and clean millions of rows into the data model for analysis after. The user interface is intuitive and well laid out so it’s really easy to pick up. It’s an incredibly short learning curve when compared to other Excel tools like formulas or VBA.
The best part about it, is you don’t need to learn or use any code to do any of it. The power query editor records all your transformations step by step and converts them into the M code for you, similar to how the Macro recorder with VBA.
If you want to edit or write your own M code, you certainly can, but you definitely don’t need to.
For that large dataset I used power query in my Project.
Specific Requirements, functions and formulas:
As we have to represent the dashboard for the company Analysis. So we need to represent the dashboard in the very simple manner. I used different charts for my project. My project contains two dashboards. Actives dashboard and Separations Dashboard.
Dax Formulas:
DAX is a collection of functions, operators, and constants that can be used in a formula, or expression, to calculate and return one or more values. Stated more simply, DAX helps you create new information from data already in your model.
I used different DAX formulas for the different analysis based on Power BI As It’s easy to create a new Power BI Desktop file and import some data into it. You can even create reports that show valuable insights without using any DAX formulas at all. But, what if you need to analyze growth percentage across product categories and for different date ranges? Or, you need to calculate year-over-year growth compared to market trends? DAX formulas provide this capability and many other important capabilities as well. Learning how to create effective DAX formulas will help you get the most out of your data. When you get the information you need, you can begin to solve real business problems that affect your bottom line. This is the power of Power BI, and DAX will help you get there.
Dax Formula text file is available on GITHUB.
Charts:
Different charts are used which will cover all the information of the data.
1.	Actives Sheet: Actives sheet  will tell the information about the new hires of the company and currently active Employees of the company. Clustered column chart is used for this purpose which contain all the information of particular month of each year from 2015 to 2018.
 
2.	Ethinicity Sheet: Ethnicity sheet contains the information of Each group from Group A to Group G that the how much Employees are part time or full time and also distinguish between male and female Employees. Clustered column chart is best suitable to represent this data. 
  
3.	Tenure Sheet: Tenure sheet contains the data of Average tenure salary per month of each employee and distinguish them by Group of employees and whether they are male or Female.
 
4.	Separations Sheet: This Sheet contains the information of Bad hires and good hires of particular year.
 
5.	Term Reason Sheet: This sheet contains the chart containing the information of Voluntary and non voluntary employees per year wise used in Actives Dashboard .
 
6.	Headline Sheet: Headline Sheet contains the data of headline made in actives dashboard ehich particularly tells the percentage of male and female in company, Avg turnover of the Employees and Full time Part time percentage of the Employees in the Company.

 
 
7.	Active Employee Sheet: This sheet is used in the Separations Dashboard and contain the information of active employees in the form of line chart and pie chart.
 
8.	Group Separation Sheet: Group Separation sheet contains the employee’s group wise and according to gender information. This sheet contains the bar chart which help to distinguish between Male and Female active employees.
 
9.	Region Sheet: This sheet contains the information according to region, how much male and females are active according to region.
 
10.	Sparklines Pivot Sheet: Sparklines pivot sheet contains the information of Full Time or Part time region wise employee sales and with the help of line chart it tells the information whether the data is increase at which rate.

 
 
11.	Average Tenure: This sheet contain the information of average tenure per month of the information.
 
12.	PayType Sheet:  This sheet contains the information of Paytype whether it is hourly or monthly of each employee whether they are Full time employees or part time employees.
 


  
Analysis Result: The Result of the analysis is shown in the Dashboard. The Excel sheet Contains two different Excel Dashboard Actives Dashboard and Separations Dashboard.
Actives Dashboard: 
 
Separations Dashboard:
 
Visualization: For visualization of dataset or working of dashboard different slicers are too be used.
Slicers based upon Annual year, Group wise Ethinicity, Region slicer for Region wise sales, Gender for seeing male and female employee, Part/Full time slicers is too be used.
Dashboard contain some buttons to move to different dashboard and to move to the file index.
GITHUB LINKS: The full Project is also available on the Github.
https://github.com/Er-Vishal-Kathpalia/HR_Excel_Dashboard.git
DATA SET:
https://github.com/Er-Vishal-Kathpalia/HR_Excel_Dashboard/tree/main/HR%20Data







References:
1.	ObviEnce company Employee Dataset
 
www.obvience.com
2.	Youtube for understanding of different Excel charts.
3.	https://en.wikipedia.org/wiki/Dashboard_(business)
4.	https://en.wikipedia.org/wiki/Human_resource_management



















Bibliography:
1.	ObviEnce company Employee Dataset
 
www.obvience.com
2.	Youtube for understanding of different Excel charts.
3.	Wikipedia for Information about HR management.
4.	Github for the Project management.











 












 














