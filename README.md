# No-Show-Appointment-Analysis
A person makes a doctors appointment, recieves all the instructions and doesn't show up, WHO IS TO BLAME? 

## PROJECT INTRODUCTION/OBJECTIVE
The purpose of this project is to find out the factors that could possibly make a patient miss his/her appointment even after he/she scheduled for the appointment. 

## METHODS USED 
* Data Wrangling 
* Data Cleaning
* Data Analysis and Visualization 
* Correlation analysis

## PROJECT DESCRIPTION 
The dataset was gotten from kaggle. [HERE](https://www.kaggle.com/datasets/joniarroba/noshowappointments) is a link to the dataset. For this analysis, python programming language was used. 

### IMPORTING LIBRARIES AND LOADING DATAFRAMES
All the necessary libraries needed for this project such as pandas, numpy, seaborn etc were imported and the dataframe was also loaded. A copy of the dataframe was made for the analysis in order to avoid loss of the original data. 

### DATA WRANGLING 
In this section, the dataframe was assessed properly using methods like .info(), .describe(), .shape. This was to get a clear overview of it. 

### DATA CLEANING 
Here, columns not needed for the analysis were dropped, some columns were renamed, formats of some of the columns were changed to the most appropriate format etc. At the end of this section, the dataframe was clean and ready for analysis and visualization. 

### DATA ANALYSIS AND VISUALIZATION
In this section, the questions below were answered amongst others 
* Does gender have any impact on how patients show-up for their appointments? (Do males show up more than females or vice-versa?)
* Does being diabetic affects how males or females show up for their appointment differently? 
* Does the increase in the number of wait days affect how patients show-up for their appointments? 
* Does setting appointments on some particular days increase the chances of the patients showing up? (Are there days of the week when patients keep to the appointments most often?)

Based on the results gotten from the analysis, some recommendations were made. The limitations of the dataset were also stated. 
