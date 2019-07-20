# State_wise_Dev_Analysis_India

Project: State-wise Development Analysis Solution

1. Executive Summary 
1.1 Project Overview 
To develop the System to analyze the log data (In XML format) of government progress of various development activities. 
1.2 Purpose and Scope of this Specification 
The purpose of this project is to capture the data for analyzing the progress of various activities. 
In scope 
This following requirement will be addressed in phase 1 of Project: 
•	Developing system to handle the incoming log feed and store the information in Hadoop Cluster(Flume) 
•	Analyze the data and understand the progress 
•	Store the results in hbase/RDBMS 

2. Product/Service Description 
2.1 Assumptions 
Log will be generated in XML format and stored in a server 
2.2 Constraints 
Describe any items that will constrain the design options, including 
•	This system may not be used for searching for now. But it will be used for analysis and saving the relevant information as of now 
•	System will be using mysql as a database 

3. Requirements 
•	The FLUME job which will place format the data and place the data to HDFS 
•	Pig/Mapreduce job for parsing the XML data. 
•	Create pig scripts/Mapreduce jobs to analyze the data 
•	Create the sqoop job to store the data in database 

Priority Definitions 
The following definitions are intended as a guideline to prioritize requirements. 
Priority 1 – Create FLUME job for fetching log files from spool directory into HDFS 
Priority 2 – Mapreduce/pig job to preprocess 

Download the dataset using the below link: 
Link: https://drive.google.com/file/d/0Bxr27gVaXO5sUjd2RWFQS3hQQUE/view?usp=sharing
