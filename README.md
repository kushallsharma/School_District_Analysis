# School District Analysis

## Overview 
Maria, chief data scientist for city school system is looking to analyze schools’ data about student funding and students’ standardized test scores.  Once the data is analyzed, she will be presenting insights on schools’ performance trends and patterns to school board and Superintendent. This will help to take informed decisions on school budget and priorities. 

## Purpose
The purpose of this analysis is to understand the trends and patterns of historical school data for student funding and standardized test score to make informed decision on setting up school priorities and budget.

## Results

Once the analysis was done, it was found out that there were some discrepancies in the data of Thomas High School for Ninth grade. Hence data for ninth grade for Thomas High School was purged and analysis was repeated. Certain differences are noted as below:
•	Effect on District summary
 
Image 4.1.1 District Summary without replacing ninth grade score for THS
 
Image 4.1.2 District Summary after replacing ninth grade score for THS
As it is visible from the above screenshot, after replacing ninth grade score for Thomas High School, Average Math Score, % passing Math and % passing reading got decreased by .1, .2% and .1%. Overall passing percentage has been reduce by almost .3%. 
•	Effect on School summary
 
 
Image 4.2.1 School Summary (THS) without replacing ninth grade score for THS
 
Image 4.2.2 School Summary (THS) after replacing ninth grade score for THS
As it is evident from above comparison that the performance for Thomas High School is decreased by .3% as we purged scores for ninth grades for THS
•	Change in Thomas High Schools performance as compared to other schools
 
Image 4.3.1 High performing schools before replacing ninth grade score for THS
 
Image 4.3.2 High Performing Schools after replacing ninth grade score for THS
For Thomas High School, percentage for overall passing is reduced by 0.3%, percentage passing for math and percentage passing for reading are dropped by .1% and .2% respectively after we removed the scores for ninth grade. However average score for reading is showing a small increase but it may be due to some significant low scores for the ninth grade, which are now removed. 
•	Effect of replacing ninth grade scores
o	Math & Reading scores by grade
          
Image 4.4 Math & reading scores before and after replacing Ninth grade score for THS
The ninth-grade scores are no longer visible for Thomas High school as we have replaced the scores with NAs. 
o	Scores by school spending 
Image 4.5.1 Spending Summary before replacing ninth grade score for THS
 
Image 4.5.2 Spending Summary after replacing ninth grade score for THS
There has been no change in the spending summary after removing scores for ninth-grade of Thomas High School. 
o	Scores by school size
 
Image 4.6.1 School Size Summary before replacing ninth grade score for THS
 
Image 4.6.2 School Size Summary after replacing ninth grade score for THS
There is no impact on scores when tabulated by school size after replacing scores for ninth grade of Thomas High School
o	Scores by school type
 
Image 4.7.1 School Size Summary before replacing ninth grade score for THS
 
Image 4.7.2 School Size Summary after replacing ninth grade score for THS

	There is no change in the school type summary as well due to change in ninth grade scores for Thomas High School.
## Summary

The overall impact after purging ninth grade scored for Thomas High School are not significant but definitely made impact on the results. 
After removing the scores for ninth grade, we can see that at district level, Thomas High School overall passing percentage are decreased by .3%. Since the impact is at district level, which is an aggregated level, hence the impact is important to be calculated and considered for future purpose. 
For Thomas High School, percentage for overall passing is reduced by 0.3%, percentage passing for math and percentage passing for reading are dropped by .1% and .2% respectively after we removed the scores for ninth grade. This means that the scores from ninth grade are almost in line with the scores from other grades as the changes are not bringing big difference. However average score for reading is showing a small increase, which signifies that there may be some significant low scores for the ninth grade, which are now removed, were causing the data to change and need to be verified.  
The performance for Thomas High School is decreased by .3% and as we compare it with other schools, it is one of the highest performing school. However, THS is on second number in the tally, while after removing ninth grade the distance between 2nd and 3rd position is narrowed down. This could be a state of concern for the school administration and they have to work towards it. 
As we replaced ninth-grade scores by NAN in the Thomas High school, it is no longer comparable with other high schools specifically for the ninth grade because the data for ninth grade is showing NAN.
