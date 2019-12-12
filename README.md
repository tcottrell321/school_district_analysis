PyCitySchool Analysis
The objective of this module was to take 2 CSV files reflecting test results from 14 different schools in the district. The analysis was conducted under the supervision of a Senior Data Scientist - Maria. Maria provided the interface between the Clients - the School District Board - and our work - to answer the questions relevant to the School Board. 

As in real life, new questions -- and required analysis -- emerged as the original requests were completed. These additional analysis requirements were added to the scope of the project - and full-filled. 

# Resources
1) Python 3.6.9 environment
2) School Data File in CSV format
3) Student Data File in CSV format
4) Import Pandas as PD
5) Import OS

# Analysis Report Objectives
The original requirements were to generate:  
* The School District Level Summary
* The School Summary

# Additional Requirements
Maria requested the following additional analysis after the original requirement request: 
* Sorting by Top 5 and Bottom 5 Schools
* Group Scores by School Spending (per capita) per student (<$584, $585-629, $630-644, $645-675)
* Group Scores by Grade (9th, 10th, 11th, 12th)
* Group Scores by School Size (Small <1000, Medium 1000-2000, Large 2000-5000)
* Group Scores by School Type (District, Charter)

# Conclusions Drawn from Data Analysis
* There was a loose inverse relationship between per capita spending and overall school performanceno with the highest spending schools having the worse performance.  
* There was an inverse relationship between school size and performance of students - with the best performing schools being the smallest schools. 
* There was a correlation between school type - with Charter Schools (which were also the smallest populations) showing the best student performance. It is not know if the size of the school or the fact that they are Charter schools which may have contributed to the higher performance. 
* Further drill-down or study might be useful for the board. 

# Challenge 4 
The results for Challenge 4 are contained in the file PyCitySchools_Challenge4.ipynb.

Maria and her supervisor have discovered that the score averages for ninth graders from one high school are incorrect. Maria has asked you to remove the math and reading scores for that high school, but without removing those ninth-grade students from the analysis.

The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.

After assessing the situation with the school superintendent and Maria, you decide the best approach is to:
* Remove the ninth-grade math and reading scores from Thomas High School.
* Keep all other data associated with the ninth-grade students and Thomas High School intact.



