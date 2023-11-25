# PostgreSQL-Library

This PostgresSQL Repository library is created for the demonstration of PostgreSQL environment, data creation, and manipulation. PosgreSQL allows users to simply create and upload the necessary tables of up to around 32TB, 
use ubiquitous Structural Query Language commands, and perform verious dypes of joins which simplify typical Excel vlookup methods for big data table size consolidations. Most importantly in this context, it allows even non-technical business users to support the 
development and maintenance of relational databases of various sizes for the technical stakeholders.

The files uploaded above relate to World geography data on cities, currencies, economies, languages, and populations of countries around the world. The relevant data is split between the various csv files. The csv files are then 
subsequently imported into the PostgreSQL database through 'create Table' SQL command one by one. 

The pictures below demonstrate SQL Inner Join Statement command executed for Data exploration within Countries and Languages csv tables.



Step 1 - Creation of Languages and Countries tables
![Create Table Languages](https://github.com/VnumpyZ806/PostgreSQL-Library/assets/93555279/063bb16b-d671-4741-84bd-150edb9e166e)




![Create Table Languages 2](https://github.com/VnumpyZ806/PostgreSQL-Library/assets/93555279/a8c14e25-5d98-464e-b0fe-e5ae1e68c14c)




Step 2 - Import of data to the created Countries and Languages tables from the csv relevant files
![Import of Data from CSV Files for Countries and Languages](https://github.com/VnumpyZ806/PostgreSQL-Library/assets/93555279/199b1eb7-ce69-43c9-a2fd-ecf21e827180)




Step 3 - Inner Join SQL command to join Countries table on Languages table using Code (Code column is being used as a Primary Key column in both Countries and Languages tables). 
![Inner Join Countries on Languages](https://github.com/VnumpyZ806/PostgreSQL-Library/assets/93555279/607af5dc-4c3a-40cf-a849-6cf686bb8bbe)
