## About
## Mainia Her - Data Analysis Portfolio
### Hi there 👋
I'm Mainia (my-nya)! I'm a proud graduate of Toccoa Fall College where I received my Bachelor of Science degree in Christian Education. This degree focuses on creating, organization, and reviewing the efficacies of ministries within the church organization. I am currently a senior disclosure analyst for a mid-size mortgage lender for 12 years. I am looking for a new challenge and want to dive deeper into data using different tools and techniques.
</p>
<p></p>
This curiosity and thirst for knowledge led me to enroll as a student in the Goodwill Data Analytics programs where I have learned to extract, load, and transform data to derive meaningful insights using various tools and programs. Check out what I have been up to! This repository serves to showcase my skills and as a platform to share my projects, and a way to track my progress in Data Analytics related topics. Asides from learning to use different tool and techniques, I get to help others with my skills which brings me personal satisfaction! 
</p>
<p>
I would love to connect to see what I can do to help you, or if you have any feedback, I would love to learn and grow together as I truly believe in being a life long learner!
</p>


## Table of contents
- [About](#about)
- [Table of contents](#table-of-contents)
- [Portfolio Projects](#portfolio-projects)
  	+ [Employee Report](#employee-report)
  	+ [Video Games Sales Dashboard](#video-games-sales-dashboard)
  	+ [HR Dashboard P2](#hr-dashboard-P2)
  	+ [HR Dashboard P3](#hr-dashboard-P3)
  	+ [HR Dashboard P4](#hr-dashboard-P4)
- [Self Paced Study Projects](#self-paced-study-projects)
	+ [Learning SQL](#Learning-SQL)
- [Resources](#resources)	
- [Connect with me](#connect-with-me)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to perform analysis and analytics to generate insights.

### Employee Report
**Code:** [`Employee Salary Report`](https://github.com/mher12/ExcelSalesReport/tree/main)    
**Description:** The dataset contained two tables. One table contains Employee department and salary information with 50 records. The second contains the bonus amount in which are associated to each employee with 44 records. The task was to clean up the data set and perform statistical analysis and create a relationship between two tables using X-Lookup.   
**Skills:** data cleaning, data analysis, descriptive statistics  
**Technology:** Excel.  
**Results:** Review Employee demographics and assigned appropriate bonus percentage accordingly.  
**Quick View:**  

<img src="https://github.com/mher12/ExcelEmployeeReport/blob/main/excel-report.PNG" alt="dark themed dashboard with employee demographics" width="150" height="100">  

[Back to table of contents](#table-of-contents)

### Video Games Sales Dashboard
**Code:** [`Video Game Sales Dashboard`](https://github.com/mher12/VideoGameSalesDashboard)    
**Description:** The dataset contains 16597 records as of May 2024. There is a list of video games with sales (by region), year of release, platform, critics and users score. The project includes the following steps: data loading, data cleaning and preprocessing, filling missing values, EDA (exploratory data analysis), analyzing region based user profiles, and measuring statistical factors.  
**Skills:** data cleaning, data analysis, descriptive statistics, and data visualization.  
**Technology:** Excel, PowerQuery, PowerBi  
**Results:** Review and created dashboards showing global and regional video games markets sales.  
**Quick View:**  

<img src="https://github.com/mher12/VideoGameSalesDashboard/blob/main/video-game-dashboard.PNG" alt="light marble themed dashboard with employee demographics" width="150" height="100">  

[Back to table of contents](#table-of-contents)


### HR Dashboard P2
**Code:** [`HR Dashboard P2`](https://github.com/mher12/HR-Dashboard-P2.git)    
**Description:** The dataset was a combination of two CSV files. 
First CSV file, EmployeeSampleDataCSV.CSV consisted of Employee information such as their full name, ethnicity, hire date, department they work under, salary and if they were eligible for bonus. It has 1000 records with various data type such as text/varchar, currency, numbers, and date.     
The second CSV file, DepartmentSampleDataCSV.CSV consisted of the department information such as code, name, address. This CSV file contained 7 records with various data types such as text/varchar and numbers.     
The main focus for this project was method of data import. The two CSV files were uploaded directly into PowerBI, cleaned and transformed. Relationship between the two tables were then established using PowerBi Model window.  
The project includes the following steps: data loading, data cleaning and preprocessing, filling/ reviewing for missing values, EDA (exploratory data analysis), analyzing demographics, and creating statistical measures such as Average and Sum of Annual Salary of Employees.   
**Skills:** Data upload (CVS to PowerBI, establish relation PowerBI Manage Relationship through Model window, data cleaning, data analysis, descriptive statistics, and data visualization.  
**Technology:** PowerQuery, PowerBi  
**Results:** Reviewed and created dashboard on employee demographics.  
**Quick View:**  

<img src="https://github.com/mher12/HR-Dashboard-P2/blob/main/hr-db-p2.PNG" alt="dark themed dashboard with employee demographics" width="150" height="100">  
[Back to table of contents](#table-of-contents)

### HR Dashboard P3

**Code:** [`HR Dashboard P3`](https://github.com/mher12/HR-Dashboard-P3.git)    
**Description:** The dataset was a combination of two CSV files. 
First CSV file, EmployeeSampleDataCSV.CSV consisted of Employee information such as their full name, ethnicity, hire date, department they work under, salary and if they were eligible for bonus. It has 1000 records with various data type such as text/varchar, currency, numbers, and date.     
The second CSV file, DepartmentSampleDataCSV.CSV consisted of the department information such as code, name, address. This CSV file contained 7 records with various data types such as text/varchar and numbers.     
The main focus for this project was method of data import.
The two CSV files were uploaded as flat files to SQL Database. Cleaned and transformed. Once imported, the tables were created within a designated database and table altered to include foreign key to establish relationship between the two tables.  
A SQL query was then created to join the two tables. A new measure was also added to the joined table. 
The SQL query was then used to upload the table into PowerBI via the SQL Direct Query option.
The project includes the following steps: data loading, data cleaning and preprocessing, filling/ reviewing for missing values, EDA (exploratory data analysis), analyzing demographics, and creating statistical measures such as Average and Sum of Annual Salary of Employees.   
**Skills:** Data upload (CVS to SQL, establish relation via inner join, uploaded data to PowerBI using SQL Direct query option), data cleaning, data analysis, descriptive statistics, and data visualization.  
**Technology:** SQL, PowerQuery, PowerBi  
**Results:** Reviewed and created dashboard on employee demographics.  
**Quick View:**  

<img src="https://github.com/mher12/HR-Dashboard-P3/blob/main/Hr-DB-P3.PNG" alt="light google themed dashboard with employee demographics" width="150" height="100">  

[Back to table of contents](#table-of-contents)

### HR Dashboard P4

**Code:** [`HR Dashboard P4`](https://github.com/mher12/HR-Dashboard-P4.git)    
**Description:** The dataset was a combination of two CSV files. 
First CSV file, EmployeeSampleDataCSV.CSV consisted of Employee information such as their full name, ethnicity, hire date, department they work under, salary and if they were eligible for bonus. It has 1000 records with various data type such as text/varchar, currency, numbers, and date.     
The second CSV file, DepartmentSampleDataCSV.CSV consisted of the department information such as code, name, address. This CSV file contained 7 records with various data types such as text/varchar and numbers.     
The main focus for this project was method of data import.
The two CSV files were uploaded as flat files to SQL Database. Cleaned and transformed.
Data was then uploaded to PowerBI via SQL Import Database option. Once the data were uploaded into PowerBI, a new measure was added to showcase revised salary in which was made up of the Annual Salary and Bonus combined. 
The project includes the following steps: data loading, data cleaning and preprocessing, filling/ reviewing for missing values, EDA (exploratory data analysis), analyzing demographics, and creating statistical measures such as Average and Sum of Annual Salary of Employees.   
**Skills:** Data upload (Uploaded data to PowerBI using SQL Import Database option), data cleaning, data analysis, descriptive statistics, and data visualization.  
**Technology:** SQL, PowerQuery, PowerBi  
**Results:** Reviewed and created dashboard on employee demographics.  
**Quick View:**  

<img src="https://github.com/mher12/HR-Dashboard-P4/blob/main/HR-DB-P4.PNG" alt="light hillside themed dashboard with employee demographics" width="150" height="100">   

[Back to table of contents](#table-of-contents)


## Self Paced Study Projects
In this section I will provide links to my github repositories containing assigments I created while passing online courses or while just having fun with data and code.  
[Back to table of contents](#table-of-contents)

### Learning SQL
**Covid Population Impact by Region**  
**Description:** SQL queries for tasks from [AlexTheDataAnalyst](https://www.youtube.com/watch?v=qfyynHBFOsM&list=PLUaB-1hjhk8H48Pj32z4GZgGWyylqv85fttps://karpov.courses/simulator-ab).  
This self-paced course explores topics covering the basics to intermediate syntax of SQL and how to generate insight using SQL syntax.   
**Repository:** Check the repository ---> [go to repo..](https://github.com/mher12/PortfolioProjectsSQL/tree/main)   
**Status:** Some courses are still in progress  
[Back to table of contents](#table-of-contents)

## Resources
Resources to help you kick start your journey in Data Analytics!  
- [Free Data Analyst Bootcamp](https://www.youtube.com/watch?v=rGx1QNdYzvs&list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF)
- [Goodwill University Data Analytics Program](https://goodwillsp.org/services/goodwill-university/it-training/data-analytics-training/)
- [O'reilly Resources for Public Libraries](https://www.cmlibrary.org/research-and-learn/oreilly-public-libraries)
- [LinkedIn Learning through Public Libraries](https://www.linkedin.com/learning-login/go?original_referer=https%3A%2F%2Fwww.google.com%2F)
- [Google Data Analytics Program](https://www.coursera.org/google-certificates/data-analytics-certificate?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_google-data-analytics_google_FTCOF_professional-certificates_country-US&campaignid=12504215975&adgroupid=122709142687&device=c&keyword=google%20analytics%20certification%20free&matchtype=b&network=g&devicemodel=&adposition=&creativeid=696354661336&hide_mobile_promo&gad_source=1&gclid=Cj0KCQjw3tCyBhDBARIsAEY0XNmwwHzNr2zj_DzFwnhIPMygfhHjb0m7gYJgqrDAc6m4dOQ8fr2Y4XUaAnh6EALw_wcB)  

[Back to table of contents](#table-of-contents)

## Connect with me <a href="https://www.linkedin.com/in/mainia-her-399aa72b4/" target ="blank"> <img align="left" alt="mainia her | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" width=”100″ height=”132″></a>


Here are some ideas to get you started:

- 🔭 I’m currently working on ...SQL projects
- 🌱 I’m currently learning ...Data analytics
- 👯 I’m looking to collaborate with ... like minded individuals
- 🤔 I’m looking for help with ...Bootstrap required framework
- 💬 Ask me about ...my other hobbies! Photography and coding!
- 📫 How to reach me: ...linkedin/google site
- 😄 Pronouns: ...she/her
- ⚡ Fun fact: ...I love to plan outreach and fellowship gatherings for my church group and work with children  

[Back to table of contents](#table-of-contents)
