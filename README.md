# pandas-challenge


## PyCity Schools Analysis

* First, we will import Pandas as a dependency and load in the CSV files necessary for our analysis as a Pandas DataFrame

* Merge the data from both CSVs into a singular DataFrame

## District Summary

* Calculate some variables that we will need to use for future analysis:
    * The total number of unique schools
    * The total number of students
    * The total budget
    * Average math score
    * Average reading score 
    * The percentage of students who passed math 
    * The percentage of students who passed reading 
    * he percentage of students who passed both math and reading 
    * inally, format all these key metrics into a DataFrame (district_summary)

## School Summary

* Next, we're analyzing the data by school

* Set the index as the school name, and calculate:
    * Total student count
    * Budget per school
    * Total school budget and per capita spending
    * Average test score (per_school_math and per_school_reading)
    * Number of schools with a math score of 70 or higher (passing)
    * Number of schools with a reading score of 70 or higher (passing)
    * Number of schools passing both reading and math
    * Create a DataFrame with all the metrics calculated per school 
    
## Highest Performing Schools (by % Overall Passing)

* Sort the schools to display the top 5 highest overall passing rate percentage out of all schools 
    
## Bottom Performing Schools (by % Overall Passing)

* Sort the schools to display the bottom 5 lowest overall passing rate percentage out of all schools 
      

## Math Scores by Grade

* Separate the math scores by grade

* Group by school name and take the mean of each, which we will select and put into an indvidual DataFrame

## Reading Scores by Grade

* Separate the reading scores by grade

* Group by school name and take the mean of each, which we will select and put into an indvidual DataFrame

## Scores by School Spending

* Next, categorize the spending per school in groups with various ranges

* Calculate the average scores for math, reading, passing math, passing reading, and overall passing and assemble into a DataFrame to display spending and compare it to score 

## Scores by School Size

* Do the same process to categorize scores by school sizes in 3 different groups: small, medium, and large

* Display in a DataFrame

## Scores by School Type

* Finally, place metrics into a DataFrame grouped by school type (Charter vs District)

## Conclusions

* Overall, the highest performing school is Cabrera High School and the lowest performing school is Rodriguez High School 

* Cabrera High School was the second highest spending school in the district, which may have correlated with it's high performance 

* However, higher spending per student actually did not correlate positively to overall passing rate

* Medium and smaller sized schools did have a positive correlation with overall passing rate, with larger schools having the lowest rate

* School type was the largest contributing factor to overall passing rate, with Charter schools having a 90% passing rate and District schools having a 54% passing rate

    
    
    
    
    
    
