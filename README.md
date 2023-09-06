# SQL-NYC-Public-Schools
SQL Project for querying SAT from NYC public schools provided by Datacamp

## Introduction
Every year, American high school students take SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. This project focuses on analyzing the performance of public schools in New York City based on their SAT scores. Understanding school performance is crucial for various stakeholders, including education professionals, researchers, government officials, and parents.

## Data Description
The project uses a PostgreSQL database containing one table: schools. Here are the columns in the table:

`school_name`: Name of the school
`borough`: The borough in which the school is located
`building_code`: Code for the building where the school is situated
`average_math`: Average math score for SATs
`average_reading`: Average reading score for SATs
`average_writing`: Average writing score for SATs
`percent_tested`: Percentage of students completing SATs


## Analysis Highlights
1. Finding Missing Values
There are 20 schools with missing data for the percent_tested column, indicating schools that did not report the percentage of students tested. This accounts for 5% of all rows in the database.

2. Schools by Building Code
Out of 375 schools, only 233 (62%) have a unique building_code, indicating that some schools share a location.

3. Best Schools for Math
Only ten public schools in New York City have an average math score of at least 640 out of 800.

4. Lowest Reading Score
The lowest average reading score across schools in New York City is 302, which is less than 40% of the total available points.

5. Best Writing School
Stuyvesant High School has the highest average writing score with a score of 693.

6. Top 10 Schools
The top 10 schools with the highest combined average SAT scores (across reading, writing, and math) are listed, with Stuyvesant High School leading with a total score of 2144.

7. Ranking Boroughs
Performance by New York City borough is analyzed, including the number of schools and the average SAT score per borough.

8. Brooklyn Numbers
The top five schools for math performance in Brooklyn are listed, with Brooklyn Technical High School leading with an average math score of 682.
