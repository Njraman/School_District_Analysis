# **School District Analysis**

## **Overview:**

In this project, we analyze data from schools across a district, to get an insight into performance trends and patterns, which help the district make stragetic decisions about budget allocations. Data available includes student funding information and standardized test scores of students in the district. Data anomalies or errors such as incorrect scores of students of a particular school, have been fixed and the analysis has been repeated.

## **Results:**
Highlighted below are the differences between the original and the updated data analysis after Thomas High School's 9th Grader scores and numbers have been removed from the data.

### District Summary:

- The Average Math and reading scores remain nearly the same with a decrease of less than 0.1 points in the updated dataframe.
- The percentage passing Math and reading have fallen by 0.1% while the Overall passing percentage has fallen by 0.2%. While the difference is pretty small in percentage, the number of students in the district who have not passed overall is actually 107 more than the original analysis. 
- These numbers are larger when we apply the percentages on the actual new Total Count of 38709, after removing the 9th graders from the pool. The numbers indicate a difference of 406 more students that have not passed overall, at the District Level.
- The differences in District Summary can be seen in the following screenshots.

     #### _Original:_
     ![OriginalDistrictSummary](Resources/OriginalDistrictSummary.png)

     #### _New:_
     ![NewDistrictSummary](Resources/NewDistrictSummary.png)


### School Summary:

- In the school summary for Thomas High School, it can be observed that the difference in average scores is very small between the original and new School Summary dataframes.
- The average math score has fallen by 0.07 points, while the average Reading Score has increased by 0.05 points.
- The percentage of students passing Math has reduced by 0.087%.  Reading and overall also does not change much between the original  and the updated dataframes, after changing Thomas High School's 9th Grader scores to NaNs and removing the 9th graders from the Student count.
- The following screenshots can be referred to.

    #### _Original:_
    ![OriginalSchoolSummary](Resources/OriginalSchoolSummary.png)

    #### _New:_
    ![NewSchoolSummary](Resources/NewSchoolSummary2.png)


### School performance vs Other Schools:

- Thomas High School continues to remain in the second position in the Top 5 performing schools, even after the 9th graders' Math and reading scores are replaced.

### Scores

- The Scores by grade remain the same for 10th to 12 grade, between the original and new Scores by Grade summary. The 9th graders' scores are unavailable and replaced by NaNs.
- The scores by spending are not affected by the change in data for 9th graders.
- The scores by school size are not affected by the change in data for 9th graders.
- The scores by school type are not affected by the change in data for 9th graders.



## **Summary:**

In Summary, after replacing the reading and Math scores of 9th graders in Thomas High School to NaNs and removing these students from the total sudent count, the resultant changes are as follows:

- The most significant difference is that the scores of about 461 students belonging to 9th grade had to be replaced by NaNs. So the average scores and passing percentage calculations have actually been made for 1174 10th to 12th graders for Thomas High School, rather than the full total of 1635 students.
- At the District level, the number of students who have not passed overall has increased by 107. This can be seen from the percentage passing Math and reading falling by 0.1% while the Overall passing percentage falling by 0.2% in the newly calculated District Summary. This number is even more significant when considering the new total number of students, after removing the 9th graders of Thomas High. 
- It can been that even though the differences in percentage values between our original and updated analysis are small, the actual numerical difference could tell a different story.




