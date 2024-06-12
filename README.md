# Assignment
#Data set: Netflix shows 
#Importing dataset into my SQL log bench 
1.*Open my SQL workbench
-Launch my SQL workbench and connect to my SQL server. 
2.*Create a new schema
-Go to the schemas tab,right click to create a new schema;which is the netflix_shows
3.*Make it the default schema
-Right click on the netlfix_shows and select Default schema
4.*Table data input wizard
-Right click on the netflix_shows and select Table Data Import Wizard
-Click Browse
-Select the CSV file and click next whereby you'll be importing the file that you'll have downloaded.
5.*Specify the target table
-Enter the new name of the new table(netflix_titles) and click next to import the data
6.*Verification 
-Run the SELECT query
   SELECT * FROM netflix_titles LIMIT 10; 
-Check table structure
     DESCRIBE netflix_titles;
7.*Difficulties
-Encountered issues with character encoding and data types
9.*Observation
-This data has a lot of movies and series that i have watched and i like.
8.*Conclusion
-This repository will be used for further assignment and analysis all further updates will be documented here
