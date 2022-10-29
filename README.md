# Data-Analytics-On-Medical-Appointments
#### Dataset consists of 100,000 medical records of patients' medical appointments in Brazil. 
## Data analytics was performed using the stated process below
###### ASK QUESTIONS PERTAINING THE DATASET.
###### DATA WRANGLING.
###### EXPLORATORY DATA ANALYSIS (EDA).
###### CONCLUSIONS.
###### COMMUNICATE RESULTS.

# DATA ANALYSIS PROCESS
## ASK QUESTIONS PERTAINING TO DATASET: 
This process involved asking the following questions below pertaining the dataset
<br> * Can patients' age decide if appointments will be made?
<br> * Can the scheduled day have an impact on patients' inability to show up for appointments?
<br> * Can patients' gender determine if they attend the medical appointment?
<br> * Can hospitals' location have an impact on patients showing up for appointments?
      
## DATA WRANGLING: 
This process involved data gathering and cleaning which involved inspecting the dataset and the following below were observed for cleaning.      
<br> * It was detected that column names begins with a capital letter.This will be changed to small letter for easy referencing.
<br> * Columns which are not needed for analytics such as "PatientId" and "AppointmentID" will be deleted.
<br> * There are duplicate columns which are "AppointmentID" and "ScheduledDay". AppointmentDay will be deleted.
<br> * "ScheduledDay" will be converted to date data type for analytics.
<br> * The column names "Hipertension" and No_show will be renamed to "Hypertension" and "no_show".
<br> * The values on column "No-show" will be changed from "No" to "Yes and vice-versa based on the error in the dataset.
<br> * The minimum age is -1 which is not possible. As a result the row will be deleted from the dataset.

## EXPLORATORY DATA ANALYSIS (EDA)
EDA provides analytics based on statistics and visualisation to answer the questions generated from the dataset.

## CONCLUSIONS
This process involved analysing the answers based on the visualisations to derive conclusions. 
      
           
       
