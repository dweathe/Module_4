# Module_4

## Overview of the school district analysis:
The purpose of this analysis is to assist the Chief Data Scientist of a school district in showcasing standardized test scores and school funding.  The insights that are shared will be used to make informed decisions.  My task is to aggregate the data and highlight the trends in performance, while keeping the data secure.  The analysis will assist the School Board in making budgetary decisions and identifying priorities.

## Results:
Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?  To begin with, we needed to know the total number of students, the total number of the schools, the total budget, the average math and reading scores,the percentage of students who passed math and reading, and the overall passing percentage in the district.
![DistrictSummaryDF](DistrictSummaryDF.png)
Removal of the ninth graders scores due to suspected cheating, makes the data more reliable.

* How is the school summary affected?  A similar summary is generated for each school in the district. ![SchoolSummaryDF](School_District_Analysis/SchoolSummaryDF.png) [AllSchoolTable](AllSchoolTable.png)
Removal of the ninth graders scores due to suspected cheating, makes the data more reliable.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?  Replacing the ninth graders' math and reading scores affects Thomas High School's performance relative to the other schools in that all school scores throughout the district are reliable.

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade-  By taking out the ninth grade scores, the math and reading scores are now considered for the Board presentation as one of     the measures in which decisions can be made for funding in the 10th, 11th and 12th grades.
  * Scores by school spending-  By taking out the ninth grade scores, funding can be allocated for 10th, 11th and 12th grades appropriately.
  * Scores by school size- By taking out the 9th grade scores, it decreases the size of the school in that there is no ninth grade data.
  * Scores by school type- Replacing the ninth-grade scores, doesn't appear to affect the scores by school type.
  
## Summary:  
In summary, the four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are: 
* Cleans up the data
* Resulting data makes for a more valid and reliable data set.
* Potential for creative problem solving (i.e. budget allocation) increases
* Reporting of standardized test scores are presented without inaccurate data (i.e alleggations of 9th graders cheating)
