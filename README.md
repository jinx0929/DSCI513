# DSCI 513: Databases and Data Retrieval

How to retrieve data stored relational and non-relational database systems. Overview of how to create and modify database objects.

Course webpage: https://pages.github.ubc.ca/mds-2021-22/DSCI_513_database-data-retr_students/

## Teaching team

- Instructor: Arman S. Ahmadi
- TAs: Pouya Ahmadvand, Melika Farahani, Shimming Gu, Alireza Iranpour, Tiffany Leung, Shanny Lu

## Lectures

**[Panopto link for lecture recordings and live streams](https://ubc.ca.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=c6e57cf8-43be-4795-8d29-ad89010d16ba)**

| #    | Topic                                                                    |
| :--- | :----------------------------------------------------------------------- |
| 1    | Introduction to databases, the relational model, SQL, basic queries      |
| 2    | Data types, filtering, derived columns and aliases, functions            |
| 3    | Aggregations, grouping, joins                                            |
| 4    | Creating, modifying, and dropping tables and rows, integrity constraints |
| 5    | Transactions, ACID, subqueries, set operations                           |
| 6    | Views, CTEs, window functions, indexing, query optimization              |
| 7    | Semi-structured data, non-relational databases, basic queries in MongoDB |
| 8    | Intro to big data, advanced queries in MongoDB, aggregation pipelines    |

## Lab assignments

There will be one lab assignment per week. We will follow the standard MDS lab deadlines.

## Quizzes

Quizzes will be **open book**, meaning you may consult course materials, online sources, etc. However, communication with other people during the quiz is strictly forbidden. See the MDS quiz instructions [here](https://ubc-mds.github.io/resources_pages/quiz/). For the dates/times of the quizzes, see the [MDS calendar](https://ubc-mds.github.io/calendar/).

## Installation

- The first step to setup the course's conda environment is to run `conda install -c conda-forge nb_conda_kernels` in your **base** environment, but if you have done so already for another MDS course, skip this step.

- The conda environment file for the course is [here](https://github.ubc.ca/mds-2021-22/DSCI_513_database-data-retr_students/blob/master/dsci513env.yml). To create the environment, run `conda env create -f dsci513env.yml` (you only need to do this once). Finally, launch Jupyter Lab from your **base** environment, and select the `dsci513env` kernel from within Jupyter.

## Course learning objectives

- Explain and justify the need for storing data in a database
- Describe tables, tuples, and attributes in the relational model
- Construct basic and advanced SQL statements to query relational databases
- Define and manipulate tables and tuples using data definition language
- Understand the usage of integrity constraints in relational databases
- Describe the concept of transactions and concurrency control
- Construct basic and advanced queries in a NoSQL DBMS

## Suggested material

Recommended:

- [Fehily, Chris. SQL: Visual QuickStart Guide, 3rd ed., Peachpit Press, 2008.](https://go.exlibris.link/tWGGwhRf)
- [DeBarros, Anthony. Practical SQL: A Beginner's Guide to Storytelling with Data, 1st ed., No Starch Press, 2018.](https://www.practicalsql.com/)
- [Matthew, Neil and Stones, Richard. Beginning Databases with PostgreSQL: From Novice to Professional, 2nd ed., Apress, 2005.](https://link.springer.com/book/10.1007/978-1-4302-0018-5)
- [Khan Academy's Intro to SQL course](https://www.khanacademy.org/computing/computer-programming/sql)
- [Software Carpentry's SQL tutorials](https://librarycarpentry.org/lc-sql/)
- [PostgreSQL Exercises](https://pgexercises.com/)

More advanced:

- [Ramakrishnan, Raghu and Gehrke, Johannes. Database Management Systems, 3rd ed., McGraw-Hill, 2002.](http://pages.cs.wisc.edu/~dbbook/)
- [Karwin, Bill. SQL Antipatterns: Avoiding the Pitfalls of Database Programming, The Pragmatic Bookshelf, 2010.](https://go.exlibris.link/JWzLR6ZL)
- [Celko, Joe. Joe Celko's SQL for Smarties: Advanced SQL Programming, Morgan Kaufmann, 2010.](https://go.exlibris.link/PGql723M)

## Covid safety at UBC

**Masks:** Masks are required indoors, inlcuding in classrooms, as per the [BC Public Health Officer orders](https://www2.gov.bc.ca/gov/content/covid-19/info/restrictions#masks). For the purposes of this order, the term “masks” refers to medical and non-medical masks that cover our noses and mouths.  Masks are a primary tool to make it harder for Covid-19 to find a new host.  You will need to wear a medical or non-medical mask anytime you are indoors at UBC, for your own protection, and the safety and comfort of everyone else in the class. Please do not eat in the classroom. If you need to drink water/coffee/tea/etc, please keep your mask on between sips. 

**Vaccination:** If you have not yet had a chance to get vaccinated against Covid-19, vaccines are available to you, free, and on campus: http://www.vch.ca/covid-19/covid-19-vaccine. The higher the rate of vaccination in our community overall, the lower the chance of spreading this virus.  You are an important part of the UBC community. Please arrange to get vaccinated if you have not already done so. 

**COVID-19 testing:** UBC will require COVID-19 testing for all students, faculty and staff, with exemptions provided for those who are vaccinated against COVID-19: https://news.ubc.ca/2021/08/26/ubc-implements-vaccine-declaration-and-rapid-testing-for-covid-19/

**Your personal health:**
If you’re sick, it’s important that you stay home – no matter what you think you may be sick with (e.g., cold, flu, other).  
A daily self-health assessment is required before attending campus. Every day, before leaving home, complete the self-assessment for Covid symptoms using this tool: https://bc.thrive.health/covid19/en 

Stay home if you have Covid symptoms, have recently tested positive for Covid, or are required to quarantine. You can check this website to find out if you should self-isolate or self-monitor: http://www.bccdc.ca/health-info/diseases-conditions/covid-19/self-isolation#Who. 
