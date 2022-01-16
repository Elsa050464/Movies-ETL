# Movies-ETL
The purpose of this project is to introduce us to the EXTRACT, TRANSFORM, and LOAD process. This report came from three Movies data sources - Wikipedia, Kaggle, and Ratings were used. The process also involves cleaning rows that are redundant and formatting data types, joining into a SQL database 
##Overview
Create an ETL pipeline using Jupyter Notebooks and PostgreSQL from raw data to SQL database.
###Extract: 
•	Data is transformed into Pandas data frames.
•	Data is extracted from the website in JSON and CSV formats.
•	JSON file requires -Wikipedia
•	CSV files Kaggle: - 2 files (format: .csv)
o	a metadata file from The Movie Database containing movie details with 45.5 thousand entries. (File size: 34.4MB)
o	a dataset from MovieLens containing over 26 million movie ratings/review. (File size: 709.6MB)
###Transform:
•	Clean and structure data using Pandas/Jupyter Notebook and regular expressions (RegEx) to achieve desired form. (i.e. using RegEx to parse data and transform text into numbers.
o	Removing duplicate rows and consolidating columns.
o	Using RegEx to parse data and transform text into numbers.
###Load:
•	The function in its final step connects to the database by Sqlalchemy library and to_sql method 
Results
As presented by the images below it was indeed a huge files of data 
##Challenges
Loading/committing the files to Github is very cumbersome as I made too many unsuccessful attempts 
