# DELMICH-DATA-CLEANING-AND-VISUALIZATION  
-------------------------------------------

## Overview
The Dataset is for a consulting company that specializes in providing consulting services to individuals and businesses in the finance industry and also trains undergraduate 
students and company staff. Dataset was extremely dirty and needed thorough cleaning as it was full of inconsistencies and errors before it would be able to be analyzed. 


## Data Source 
Data was obtained from a google drive link posted on X (Twitter). -[DOWNLOAD HERE](https://t.co/eFcaQbfoOk).  
At the time of acquiring the dataset, it was full of inconsistencies, outliers, errors, etc. which were later cleaned to make sure analysis wouldn't return errors  

##  Data Cleaning
![Image](https://github.com/user-attachments/assets/f7ff0cd7-4b6e-473a-83e4-5d0d85431e46)

* Correction of mispelt words  
* Properly apportion metadata to proper column 
* Correction of  wrong currency symbol
* Replacing an outlier with an average value

### LANDING PAGE: Column name/(Data type)/Info
* AGE (int)
Individual ages of students
* AGE BRACKET (nvarchar)
  Collective age of students (Under 20 or Above 20)
* COURSE (nvarchar)
 Courses offered by students
* ENROLLMENT_DATE (date)
  Dates of enrollment
* FIRST NAME (nvarchar)
  First names of students
* GENDER (nvarchar)
  Genders of students
* LAST NAME (int)
Last names of students
* MONTH (nvarchar)
  Month of enrollment
* PAYMMENTS (int)
  Payments made by students
* STUDENT_ID (int)
 Student ID code
* YEAR (int)
 Year of student enrollment





## TOOLS

* Data Cleaning : Power Query
* Visualization: PowerBI  





## KEY PERFORMANCE INDICATORS


* Sum of payments
  
* Total number of students
  
* Average age
  
* Courses offered
  

  ### THE DASHBOARD
 >  Summarises the given dataset and also get insights based on courses offered, amounts paid, enrollment dates,  tc.as stated to have been recorded in Year 1999, 2005, 2016, 2020-2024
>> ... The dash board was built using the following parameters.
>> 

 | HEADER  |  VISUAL  |
 | :---: | :---: |
| AGE BRACKET |PIE CHART |
| COURSES BY STUDENTS| BAR CHART|
| ADMISSION BY YEAR | LINE CHART|
| GENDER | DONUT CHART|


## ANALYSIS AND INSIGHTS

* TOTAL NUMBER OF STUDENT RECORDED: The dataset gave an aprox. enrollment of 133 students within stated period.

* COURSES OFFERED- Courses offered were a given range of IT courses that totalled 6 WITH "DATA SCIENCE" as the most populated with 36 students and "DATA ANALYSIS" as the least populated with 1 student.

* GENDER- Enrolled 76 Males, 54 Females and 3 misrecorded details about their gender.

* AGE BRACKET- 121 peresons are "above 20 years" while 11 persons are "under 20 years".
  
* YEAR - 2022 had the most enrollment activities with a count of 65 students.



## SUMMARY 
The dataset is free of errors as outliers, inconsistencies, mispelt words and everything that posed as threats to proper analysis were thoroughly cleaned
