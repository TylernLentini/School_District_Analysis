# School_District_Analysis
Funding and Standardized Test Analysis with Pandas and Jupyter Notebook

## Overview
I analyzed school data and provided the following:

-A high-level snapshot of the district's key metrics, presented in a table format
-An overview of the key metrics for each school, presented in a table format
-Tables presenting each of the following metrics:
-Top 5 and bottom 5 performing schools, based on the overall passing rate
-The average math score received by students in each grade level at each school
-The average reading score received by students in each grade level at each school
-School performance based on the budget per student
-School performance based on the school size 
-School performance based on the type of school

## Challenge Prompt
"The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis."

The challenge prompted me to remove the test scores for 9th graders at Thomas High School and repeat the school analysis utilizing the new data set.

## Results: 

* How is the district summary affected? We see a shift in the stats due to the removal of 9th grade test scores from Thomas Highschool.
for example, 
![District_Summary_2](https://user-images.githubusercontent.com/84756166/125181170-2e3b0880-e1d0-11eb-836d-d519249cfec9.png)

![District_Summary_!](https://user-images.githubusercontent.com/84756166/125181116-963d1f00-e1cf-11eb-9bb0-c9a1437a941e.png)

Overall passing percdentage decreased by 1% with the removal of students. 

*How is the school summary affected?

We see a major shift in Thomas High's overall scores when we look at the school summary. 

![Per_school_Analysis_before](https://user-images.githubusercontent.com/84756166/125181288-76a6f600-e1d1-11eb-8d6c-b32420aada75.png)

![Per_School_Summary_Adjusted](https://user-images.githubusercontent.com/84756166/125181293-7dce0400-e1d1-11eb-893b-69605072c3ba.png)

When we adjust the scores to elminate Thomas High Freshman we can see the overall %Passing Math 66.9%, %Passing Reading 69.6% and %Overall Passing 65% become 
93%, 97% and 91% respectively (roounded to the nearest whole number).

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

After replacing ninth graders' math and reading scores Thomas High School entered the #2 spot in ranking. 

![Thomas_top_5](https://user-images.githubusercontent.com/84756166/125181384-2ed49e80-e1d2-11eb-8745-6d966bf84734.png)

*How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade
 On most of the data, replacing math and reading scores for one school has little effect except that for Thomas High school those outputs read NaN. 
 The math and reading scores remain the same for other grades and schools. 
*Scores by school spending
Scores by spending are unchanged.
*Scores by school size
Scores by school size are unchanged 
*Scores by school type
Scores by school type are unchaged. 

##Summary

After Analyzing the data it is clear that removing test scores for one grade in one school is most visible in the district analysis. 
This makes sense since the district analysis is fixxed on the individual districts and provides a picture of what going on within them. 
Comparatively, other changes are felt on a smaller scale. Above, we saw a major shift in Overall Percentage Scores including %Passing Math 66.9%, %Passing Reading 69.6% and %Overall Passing 65% becoming 93%, 97% and 91% respectively (roounded to the nearest whole number). We also see an adjustment in Thomas High's overall performance whe compared with other schools, as it now sits in the top 5.





