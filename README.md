#Pandas-challenge

This code is an example of data analysis and manipulation using the Pandas library in Python. The goal of this code is to analyze school district data and generate summary statistics and metrics, such as the total number of students, budget, average test scores, and passing rates, for each school in the district.
The code calculates various metrics from the combined data frame:
* Total number of schools
* Total number of students
* Total budget
* Average math score
* Average reading score
* Percentage of students passing math, reading, and both subjects
* District-level summary of key metrics

The code then calculates the following metrics for each school:
* Total student count per school
* Total school budget and per capita spending per school
* Average test scores per school
* Number of students per school passing math and reading with scores of 70 or higher
* Passing rates for math, reading, and overall
Ê
The code begins by importing necessary libraries and loading data from CSV files into Pandas data frames. It then calculates various metrics and statistics using Pandas functions, such as nunique() to count the number of unique schools, mean() to calculate the average test scores, and groupby() to group and aggregate data by school.
After computing the necessary summary statistics, the code formats and displays the results in data frames using the pd.DataFrame() function. The final output includes two data frames: the district summary, which provides an overview of the district's key metrics, and the per-school summary, which breaks down the metrics for each individual school in the district.
Overall, this code demonstrates the power and versatility of Pandas for data analysis and manipulation, making it a popular choice among data scientists and analysts.





