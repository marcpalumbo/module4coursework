# Module 4 Challenge

## Overview of School District Analysis 
The purpose of this analysis was to take a raw CSV file containing data of a school districts performance and analyze based on scores. We initially had to go through the process of cleaning the data so that we could use it and gain accurate insight, as tedious of a process as this is, it is an essential part as unclean data can lead to inaccurate analysis and bad decisions in the future. After cleaning, we sorted this information by school, grade level, and district and tried to find some insightful data there. A lot of the code was reusuable from what we were using in the module, so once we got one concept down it was easy to apply the filtering and sorting onto newer dataframes. 

## Results
* It became immediately apparent that the district summary was not wildly effected after removing the 9th graders from the dataset. After some thoughtful consideration I realized that this may mean that the biggest indicator of student success would be what high school they attended, and not what grade they were in. However, we only eliminated 461 rows of data, this may not have been enough out of th3 31,000 to have any substantial impact. 
* School summary ultimately was unaffected by the removal of the 400 rows as well. There wasn't any substantial or eye catching changes between the initial analysis and the second analyis performed on this challenge. 
* Getting rid of the 9th grade data for Thomas High School had a very large impact on that school's performance. Their math score jumped by about 26% while their reading score jumped up by about 27%. This may lead one to question the methods of education being used at the ninth grade level at that high school. This jump in percentage vaulted Thomas High school into the top 5 schools in the district! If they could manage to boost their academic performance amongst 9th graders, they will likely be able to consistently be a top school in the district. 
* The majority of the information was unaffected on a grade by grade cases, as only Thomas high school data was removed, thus leading to their data being shown as "NaN." Math and reading score averages by grade were unaffected outside of Thomas High School. Scores by school spending was minimally altered, as average math score for the $631-645 range fell slightly as well as the overall passing percentage. For the results filtered by school size, the only schools effected was overall passing % of medium schools, which fell slightly by .05%. For the school type data, charter school average math score and overall passing % fell slightly, each by less than 1%. 

## Summary
In summary there are small differences that are noteworty:
* Thomas high school is a top ten school without their 9th grade data
* Scores by school spending saw the average math score in the $631-645 range fall slightly 
* Scores by school spending saw the overall passing percentage in the $631-645 range fall slightly 
* Medium schools saw overal passing % fall slightly 
* Charter school average math score and overall passing percentage fell by less than 1%
