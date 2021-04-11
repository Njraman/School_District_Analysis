# **School District Analysis**

## **Overview:**

In this project, we analyze data from schools across a district, to get an insight into performance trends and patterns, which help the district make stragetic decisions about budget allocations. Data available includes student funding information and standardized test scores of students in the district. Data anomalies or errors such as incorrect scores of students of a particular school, have been fixed and the analysis has been repeated.

## **Results:**

### District Summary:

-  The District Summary has very small differences in data between the original analysis and the corrected analysis after Thomas High School's 9th Grader scores and numbers have been removed from the data.  
- The Average Math and reading scores remain the same.
- The percentage passing has very minute differences after the 9th graders are removed from the Student count with the new percentage being slightly less.
- The same can be seen in the following screenshots.

     #### _Original:_
     ![OriginalDistrictSummary](Resources/OriginalDistrictSummary.png)

     #### _New:_
     ![NewDistrictSummary](Resources/NewDistrictSummary.png)


### School Summary:

- The average scores remain nearly the same between the original and new School Summary dataframes.
- The percentage of students passing Math, Reading and overall also does not change much between the original  and the updated dataframes, after changing Thomas High School's 9th Grader scores to NaNs and removing the 9th graders from the Student count.
- The following screenshots can be referred to.

    #### _Original:_
    ![OriginalSchoolSummary](Resources/originalSchoolSummary.png)

    #### _New:_
    ![NewSchoolSummary](Resources/NewSchoolSummary2.png)


### School performance vs Other Schools:

- Thomas High School continues to remain in the second position in the Top 5 performing schools, even after the 9th graders' Math and reading scores are replaced.

### Scores

- The Scores by grade remain the same for 10th to 12 grade, between the original and new Scores by Grade summary. The 9th graders' scores are unavailable and replaced by NaNs.
- The scores by spending are not affected by the change in data for 9th graders.
- The scores by school size are not affected by the change in data for 9th graders.
- The scores by school type are not affected by the change in data for 9th graders.






