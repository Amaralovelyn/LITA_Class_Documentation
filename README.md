# LITA_Class_Documentation
A documentation of my class on Data Analysis with the Incubator Hub

## Project Title: 
Data Analysis- Basics of Data Analysis
---

### Project Overview:
The aim and objective of this project is to have a good knowledge and understanding of Data Analysis, Foundations of Data - Data Generation, Data storage, Data Source, Data Structure, introduction to MSExcel, Basic Excel Functions, Reports and Dashboards in Excel, Project/Challenge.

### Data Sources: 
The primary source of Data is from LITA, CSV, and this an open source that can be freely downloaded from an open source online like kaggle.com, data.gov etc.

### Tools Used
- Microsoft Excel [download Here](https://www.microsoft.com)
  1. Data Generation and cleaning
  2. Explore and Visualize Data  
  3. Analyze Data
  4. Tell stories with Data
- SQL - Structured QUery Language for quering of Data
- GitHub for portfolio building
- Power BI

## FOUNDATIONS OF DATA
We need to have some level of Data Litracy, that is how we perceive Data so we can do some certain things or make meaning out of the Data set. These include

- Data Generation: 
The way you generate your data would actually impact some of the things you would do with your Data afterward. The better the generated Data, the more value we get from our Data set.

- Data Cleaning:
This is the process of detecting and correcting corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

- Data Storage:
The generated data must be stored somewhere so that the data set is accessible, else we loose the Data. And this can be done in 2 ways - premises or cloud.

- Data Structure:
 This is a data organization and storage format that is usually chosen for efficient access to data. And this can bee achieved in 3 ways - STRUCTURED DATA, a structured data simply means data is in a table format, also a structured Data is 90% ready for analysis. SEMI STRUCTURED DATA means data is not in a table format but in format like JSON, XML while UNSTRUCTURED DATA comes from audio, video, they are the media files.

 We do what is called ETL- Extract Transform and Load to restructure our data to bring our data to a structure that is reporting or analysis ready. ETL is simply the process of making our data set analysis ready

 ## DATA ANALYSIS LIFE CYCLE
 This is a cyclical process for gathering, analysing, and interpreting data. The phases are as shown below:
 
 - Ingestion: To connect to data source, to socket in
 - Transformation: once data is brought in, you may want to add or drop columns , change the data type etc. This is typically the ETL.
 - Modelling: Data modeling refers to the architecture that makes analysis possible. Here an Analyst brings different data close to one another to be able to bring out a single Report.
 - Visualization: This means simply turning data into visuals, charts, graphs. Visualization is what many people will see
 - Analysis: Data is evaluated and described by applying statistical and Logical techniques.
 - Presentation: Data is ready for presentation.

 
# Data cleaning Using Power BI 
 Recall that Data Cleaning means removing unwanted observations, outliers, fixing structural errors. It is also the process of detecting and correcting corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

 Shown below are some TEXT Cleaning done Using Power BI
  
  ![TEXT Cleaning 2](https://github.com/user-attachments/assets/2d2def68-a39e-4140-b3cb-d76ad77290d0)
TEXT - CLEANING 2. Here I started by:
1. Removing empty 2 top rows, 
2. Replacing all the null values with @lita.org by clicking on REPLACE VALUES, 3. 3. Then removed the bottom 5 rows
4. Promoted the Header using USE FIRST ROW AS HEADERS
5. Removed the bottom 5 rows
6. Duplicated the Name column and SPLITED the Name copy column created by SPACE delimeter, at LEFT-MOST DELIMITER to get the First Name and Surname column having copied and removing the Original First Name and Surname Column
7. I then MERGE the First Name with the Email to form the Email address Column having duplicated the Email column.
9. Then finally renamed the Email Address column.



![TEXT Cleaning 3](https://github.com/user-attachments/assets/141be463-69df-4e90-ae5a-712d8be84e84) 
TEXT - CLEANING 3. Here: 
1. I first removed Top 2 rows
2. Removed an empty column
3. Removed bottom 5 rows
4. Promoted the header using first row as header
5. Then duplicated the First Name and the Surname and creating additional column copy respectively
6. I then copied and Removed the Full Name column
7. and finally MERGED the two column copies by SPACE seperator to get the Full Name.



![TEXT Cleaning 4](https://github.com/user-attachments/assets/47b88bd6-89be-453f-85fc-9e9921743213) 
TEXT - CLEANING 4. Here: 
1. I first removed Top 2 rows
2. Removed an empty column
3. Promoted the header using first row as header
4. Removed bottom 5 rows
5. Duplicated the Email Address column
6. Then SPLITTED the created column copy by @ delimiter at aecch occurence of the delimiter
7. Then removed the unwanted columns (@lita.org) out of the 2 additional created columns
8. Again splitted the remaining column of the previous ctreated column (the first name.surname) by dot (.) seperator at Left-most delimiter
9. And finally, I copied and removed the First Name and Surname column respectively and renamed them respectively.









#### Data Visualization

 

