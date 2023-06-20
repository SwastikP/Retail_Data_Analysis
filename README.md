In this project I worked on end-to-end Retail Data Analysis project. This project is a fully functional automated dashboard using Power BI, where clients can simply upload data in AWS , and the dashboard will update automatically in Power BI.

This is fully functional dashboard involved five major steps: 

AWS > Snowflake > Python > Snowflake > Power BI 



1st Step [in AWS] :

Bucket,folder Creation In S3

Role Assigning

Policy Creation 

2nd step [in Snowflake] :

Create Warehouses, Database, Schema, Table

Storage Integration

File Format and Stage Creation

Pipe-Line Creation

3rd step [in Python] :

Load data from snowflake.

Perform basic EDA using pandas.matplotlib,seaborn.

Modify,drop columns,Create modified tables

Push new tables in snowflake.

4th step [in Snowflake] :

Build KPI's.

Create Stored Procedure for KPI's.

Automate the process using tasks.

5th Step [in Power BI] :

Build Connection and Extract Data from snowflake.

Transform Data & Load Data

Analysis of Data & Create Visualisation

Dashboard Creation 


