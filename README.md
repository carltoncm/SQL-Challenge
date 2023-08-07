# SQL-Challenge
This is my submission for the DA Bootcamp Module 9 Challenge-SQL

I began this challenge by creating an Entity Relationship Diagram (ERD) for the data presented. This allowed me to determine the relationships between the data and make clearer choices moving forward regarding the queries. Please note-there is a small error in the diagram picture that I later corrected in the code itself. The data type for the hire_date variable on the employees table should be DATE, not VARCHAR. I saved the diagram as a PNG file and used it for reference moving forward in the assignment.

Next, I used QuickDBD's (https://app.quickdatabasediagrams.com/#/) export feature to pull the diagram I created into SQL code format. After some minor formatting adjustments, I entered the code into pgAdmin to create the tables. Once I verified they were created correctly using SELECT statements, I imported the information from the provided CSV files-making sure to import them in an order that would not disturb any foreign key references. Once the tables were created and populated correctly, I was able to start addressing the queries. I used several functions and statements to achieve the requested results, such as JOIN, GROUP BY, WHERE, AND, and LIKE. Finally, I saved all of my work and pushed the files into this repository. 

I referenced class information and activities provided by instructor Brett Barnes and TA Ally Qi for this challenge. I also used the ERD creator found at https://app.quickdatabasediagrams.com/#/ and referenced them within my schema code as well.
