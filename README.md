# ETL-and-Reporting-Using-Snowflake-and-Tableau-Cloud

In pursuit of understanding the world of Data Engineering in depth I stumbled upon this amazing workshop.
Through this workshop I was able to learn a ton especially about Snowflake. Following were my key learning and takeaways. 

# SNOWFLAKE
1.	Creating database in snowflake
2.	Creating schema in snowflake followed by creating tables that acta as staging area which sourced the “TRIP DATA” in the form of JSON file from external staging area in AWS S3 bucket. This trip data is a semi-structured data from IoT enabled bikes.
3.	Creating a Datawarehouse in snowflake
4.	Extracting data from Snowflake marketplace “GLOBAL WEATHER & CLIMATE DATA FOR BI” into a database, followed by querying, transforming (“Convert Kelvin to Celsius “) and analyzing (“Is there precipitation or snowfall in NY zip codes”) it.
5.	Accessing “GEOSPATIAL STATION DATA” from AWS API Gateway to enrich existing station ids. Loading data from API into a snowflake table and flattening this data.
6.	Transforming to get an integrated data by combining data from all these different sources.
7.	Creating a Reader account on Snowflake that can be shared with the client who themselves do not have a snowflake account so that they can access the data.


# TABLEAU CLOUD
8.	Connecting Tableau cloud to access the integrated data in Snowflake using the Snowflake connector.
9.	Applying multiple data source filters to avoid hindering performance.
10.	Visualizing the integrated or complex spatial data. Understanding about the indexing and cache storage of Tableau.
11.	Adding KPIs to the tooltip and reformatting it using the rich text editor to have a more intuitive information, followed by formatting the map layers and enhancing map using custom backgrounds.
12.	Publishing the dashboard as a workbook and embedding it into an external web application.
13.	Leveraging Tableau’s JavaScript API to translate any selections that are made in the external webpage into filters within tableau.


# SNOWSIGHT
14.	Creating a reader account for clients who do not have snowflake account and clients can access data using snowsight.
Ensuring data is shared securely with the client while creating this reader account.

# SNOWFLAKE DevOps
15.	Exploring DevOps in Snowflake by deleting all the databases, schema, tables, data warehouses and reader account that were created during this workshop and were part of the demo account.

