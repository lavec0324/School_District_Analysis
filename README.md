# School_District_Analysis - Module 4 Challenge

## Overview of Project

This project is intended to analyze school data and student data for the district.  This involves data cleansing activtiies, removing data 
that is deemed questionable, then providing results before and after removing the questionable records.  This data will provide insight into 
the district to make decisions on such things as spending based on school sizes as well as performance.

Only three files are necessary for this analysis:

   * [PyCitySchools_Challenge.ipynb](https://github.com/lavec0324/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) - Jupyter Notbook created for analysis
   * [schools_complete.csv](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/schools_complete.csv) - School data file
   * [students_complete.csv](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/students_complete.csv) - Student data file

All other files in the repo are working data only or images.

## Results

###	How is the district summary affected?

District Summary Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/district_summary_before.PNG)

District Summary After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/district_summary_after.PNG)

####	How is the school summary affected?

School Summary Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/school_summary_before.PNG)

School Summary After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/school_summary_after.PNG)


####	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School's Performance Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/top_five_before.PNG)

Thomas High School's Performance After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/top_five_after.PNG)

####	How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade

* Math - 9th grade math was dropped, all other remained the same

Math Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/math_score_by_grade_before.PNG)

Math After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/math_scores_by_grade_after.PNG)

* Reading - 9th grade math was dropped, all other remained the same

Reading Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_before.PNG)

Reading After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_after.PNG)

Scores by school spending

* While there were residual differences when rounded up there were no changes in spending, size, or type.

Spending Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/spending_before.PNG)

Spending After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/spending_after.PNG)

Scores by school size

Size Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/size_before.PNG)

Size After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/size_after.PNG)

Scores by school type

Type Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/type_before.PNG)

Type After 

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/type_after.PNG)

## Summary

Summary:  Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Overall there doesn't seem to be a large change in percentages, the four most prevalent changes are:
* District math scores dropped from 75 to 73.9
* Disctrict reading scores dropped from 86 to 84.7
* Thomas high school overall passing dropped from 90.95 to 90.63
* Ninth grade scores were dropped from Thomas high school 

This might conclude that the grades that were dropped did not show a material difference overall which could indicate that there was no foul play in those grades.
