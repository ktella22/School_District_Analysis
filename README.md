# School_District_Analysis
## Overview of the school district analysis
In this project, we learnt how to format DataFrame column, determine data types of row values, retrieve data from specific columns, use groupby( ) function to filter out the data in interest and perform mathmatical calculation on columns of DataFrame and Series. The purpose of this Module challenge is to update a new analysis based on the original school district data after removing ninth-graders' Math and Reading score at Thomas School from school district and investigate the changes on the summary analysis due to the removal.  

## Results
In the current analysis, most of the values from the original analysis did not change and remained the same. That looks reasonable because only small portion of students from Thomas High School was removed from the very large datasets and the changes did not have major impact on most of the remaining values. Below is the screenshot of district summary from original analysis. 

<img width="526" alt="original_district_summary" src="https://user-images.githubusercontent.com/92502292/142676743-9021450c-f0ff-40ed-882e-aa295dfc62f9.PNG">

The table below is the screenshot of new analysis after removing Thomas High School nth-graders from datasets. There were a slight decrease in average math scores, % passing math and reading and % of overall Passing in new district summary but the drop are pretty insignificant.
 
<img width="513" alt="district_summary_screenshot" src="https://user-images.githubusercontent.com/92502292/142676869-85ca5226-d794-4c44-8db2-0bc20513bfb4.PNG">

The values in the updated school district analysis remained intact even after the scores are grouped by different categories such as grade, school spending budget, school size and the type of school on the current analysis. 

## Summary
After replacing ninth grade at Thomas High School with NaNs, the new scores including Math, Reading, and Overall passing rate are updated based on the school budget spending per student, school size and school type in the new analysis. The four major changes are the total number of students at Thomas high school, total number students in the entire district, their average math score and reading score, and the overall percentage of the passing rate. Removing the number of students from Thomas High School affects a drop in the total students in the whole district which leads to a change in their math, reading scores and the percentage of the overall score. However, the amount of ninth-grade removal from Thomas High School is realatively small compared to total numver of students in the district, the changes are not as obvious as we imagined.  