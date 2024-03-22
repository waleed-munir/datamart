# Final Datamart
In the zip file, the datamart_db file contains the final datamart comprised of all data inserted into the schema with all data cleaned and preprocessed. This file is a PostgreSQL backup file that can be loaded using pgAdmin.

# Data Mart zip file 
The zip file also contains the source code used to process the raw data and insert it into a PostgreSQL database instance. The data mart uses 2 databases and only 1 of them (the WEO dataset) is in the zip file as the other dataset (GTD) is too large even after zipping and github does not support that large file sizes. You can download the dataset yourself here: https://www.start.umd.edu/gtd/contact/download

The zip file contains the following files:
SQLTableCreationQueries - Contains the PostgreSQL squeries to create the tables and dimensions, 
GTD.py - Code to process the Global Terrorism Database raw data and insert it into PostgreSQL
WEO.py - Code to process the WEO Database raw data and insert it into PostgreSQL, 
WEOApr2021all.csv - CSV file of the raw WEO data

