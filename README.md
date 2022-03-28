# School Distric Analysis: Using Jupyter Notebook

## Overview
Maria is the chief data scientist for the city school system is responsible for analyzing information from various sources. For this project, she was tasked with organizing data from standard tests throughout the district to provide insights, performance trends, a patterns. This information will be used to make more informed decisions for further success at both the school and district levels. 

Unforunately, the school board notified Maria of academic dishonesty that could impact the results of her analysis, and therefore we were recently tasked with removing all ninth grader reading and math grades from a single school, Thomas High School. Following this update, we will review the school district analysis to determine how the removal of Thomas High School's ninth grade scores impacted the overall analysis.

## Results
There were 461 students within Thomas High School's ninth grade classes, which accounted for 1.2% of the students within the district, and took the the total student count down to 38,709 after they were removed. Based on this, it's unlikely that the change will have a significant impact on the overall analysis.
### Impact On District Summary
##### Original District Summary 
![District Summary Before](https://github.com/lilydionne/school_district_analysis/blob/main/district_summary_complete.PNG)

##### District Summary After Removing THS 9th Graders
![District Summary After](https://github.com/lilydionne/school_district_analysis/blob/main/district_summary_challenge.PNG)

When reviewing the change in the district summary, we can see that the scores do drop with the removal of this class, however the change was only between 0.0 to 0.3 percent decline. 

### Impact On School Summary
##### Original Top Schools Summary 
![School Summary Before](https://github.com/lilydionne/school_district_analysis/blob/main/top_schools_complete.PNG)
##### Top Schools Summary After Removing THS 9th Graders
![School Summary After](https://github.com/lilydionne/school_district_analysis/blob/main/top_schools_challenge.PNG)
When comparing the performance of Thomas High School to other schools, we can see that the removal of the 461 9th graders from the school summary did not impact their overall ranking, as they remain 2nd among the top schools in the district, as the overall passing scores dropped less than one percent.

While we do see changes in the district summary and school summary, we do not see any changes in performance based on: 
- School Spending Summary, which shows average scores and percentage passing based on the average spending per student grouped into 4 bins
- School Type Summary, which shows average scores and percentage passing based on charter or district school types
- School Size Summary, which shows average scores and percentage passing based on small, medium and large school sizes
However, we can see a change to the math and reading scores by grade as Thomas High School no longer shows an average for 9th grade.

## Summary
In conclusion, the changes made to the school district data where not significant enough to change insights gained from the original analysis, as most changes were within 1 percent of the origianl school district results. As a reminder some of the changes we made were: 
 - Updating the Thomas High School ninth grade math and reading scores to NaN
 - Calculating the new student count total
 - Calcuating updated overall percentages of students who passed reading and math
 - Passing new values for reading and math scores, and passing percentages into the "per_school_summary" data frame
 
