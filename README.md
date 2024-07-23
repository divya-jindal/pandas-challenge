# PyCity Schools Analysis
This repository contains Python code for analyzing school district data from PyCity Schools. The analysis covers various metrics such as school performance, student scores, and passing rates based on different categories.

## Getting Started
To run the analysis, ensure you have Python installed along with the following dependencies:

* pandas
* pathlib


## Data Files
The analysis uses two main data files located in the Resources folder:

* schools_complete.csv: Contains information about each school.
* students_complete.csv: Contains information about each student.

## Running the Analysis
Data Loading: The script loads the school and student data into Pandas DataFrames.

District Summary: Calculates key district metrics including total schools, total students, total budget, average math score, average reading score, and overall passing rate.

School Summary: Computes metrics for each school including school type, total students, total school budget, per student budget, average math score, average reading score, and passing rates for math, reading, and overall.

Top Performing Schools: Lists the top 5 schools based on overall passing rate.

Bottom Performing Schools: Lists the bottom 5 schools based on overall passing rate.

Math and Reading Scores by Grade: Displays average math and reading scores for students in each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending: Breaks down school performance based on per student spending ranges, showing average scores and passing rates.

Scores by School Size: Analyzes school performance based on size categories (small, medium, large) using average scores and passing rates.

Scores by School Type: Examines school performance based on school type (charter vs district) using average scores and passing rates.

# Conclusion
This analysis provides insights into school performance within the PyCity district, highlighting factors that may contribute to student success such as school size, spending, and type. For detailed code implementation, please refer to the Jupyter Notebook or Python script in this repository.
