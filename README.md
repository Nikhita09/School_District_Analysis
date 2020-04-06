# School_District_Analysis

## Project Overview

We are analysing school and student data to achieve the following outcomes:
    - District summary dataframe
    - School wise summary
    - High and low performing schools
    - calculate scores by grade, scores by school spending, scores by school size, and scores by school type.
    
The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.

After assessing the situation with the school superintendent and Maria, you decide the best approach is to:
   a) Replace the ninth-grade math and reading scores from Thomas High School.
   b) Keep all other data associated with the ninth-grade students and Thomas High School intact.
   
We will recalculate all outcomes after replacing the scored with NaN.

## Resources

Data Source : schools_complete.csv , students_complete.csv

Software : Python 3.7.7, Anaconda 2019.07, Conda 4.11.7, Jupyter Notebook, Pandas

## Summary

1) How is the district summary affected?
    - The average Math scores went down from 79 to 78.9
    - The average Reading scores remained the same
    - The % of student passing Math reduced from 75% to 74%
    - The % of students passing Reading reduced from 86% to 84%
    - The % of students passing both Math and Reading went down from 65% to 64%
    
2) How is the school summary affected?
    - The school summary for all schools except Thomas High School remain the same.
    - For Thomas High School, the average math and reading scores remain almost the same, however the % of student who passed math decreased from 93% to 67%. The % of students passing reading reduced from 97% to 70%. The % of students passing both math and reading reduced from 91% to 65%.

3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
    By replacing all math and reading scores of ninth graders in Thomas High School the following changes in the schools performance were noticed:
    - For Thomas High School, the average math and reading scores remain almost the same.
    - However the % of student who passed math decreased from 93% to 67%.
    - The % of students passing reading reduced from 97% to 70%.
    - The % of students passing both math and reading reduced from 91% to 65%.

4) How does replacing the ninth grade scores affect the following:
    
    - Math and Reading Scores by Grade
        - The math and reading scores for nith grade in Thomas High School is replaced with nan. No other changes are observed.

    - Scores by School Spending
        - Only the spending bracket $630-644 saw any changes which were:
            - The % of students who passed in math reduced from 73% to 67%.
            - The % of students who passed in reading reduced from 84% to 77%.
            - The % of students who passed both math and reading reduced from 63% to 56%.
    - Scores by School Size
        - Only medium school size (1000 - 2000) saw changes which were:
            - The % of students who passed in math reduced from 94% to 88%.
            - The % of students who passed in reading reduced from 97% to 91%.
            - The % of students who passed both math and reading reduced from 91% to 85%.
            
    - Scores by School Type
        - Only Charter school type saw changes which were:
            - The % of students who passed in math reduced from 94% to 90%.
            - The % of students who passed in reading reduced from 97% to 93%.
            - The % of students who passed both math and reading reduced from 90% to 87%.