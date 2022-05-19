# ETL_Stocks_Data_Pipeline_AWS_EMR_Cluster_Hive_Tables_Tableau_Dashboard

This project covers the end to end implementation of building an ETL batch data pipeline with Dynamic Tableau Dashboard Visualisation using Python and AWS Services for the Capital Markets Stocks Trade Transactions in the various sectors.

The persisted batch stocks data is stored in the AWS S3 Bucket and ingested into the AWS Elastic MapReduce (EMR) Cluster. This ingested data is further transformed using Apache Hive Tables and finally consumed by the Tableau application for displaying the stocks statistics and the summary for the various sectors as a dashboard.  There is also a real-time interface with the SPY Yahoo Finanace Public Website to retrieve the real-time dynamic stocks status updates and display in the Tableau Dahsboard.

Tools & Technologies: 
Python, Boto3, AWS CLI, AWS S3, AWS EMR, Apache Hive, Tableau Desktop Dashboard

Project Architecture:

![](architecture/project_architecture.jpg)

Stocks Trade Transactions Tableau Dashboard:

![](images/Capital_Markets_Stocks_Transactions_Tableau_Dashboard.jpg)
