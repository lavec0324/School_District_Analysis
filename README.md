# School_District_Analysis - Module 4 Challenge

## Overview of Project

This project is intended to analyze school data and student data for the district.  This involves data cleansing activtiies, removing data 
that is deemed questionable, then providing results before and after removing the questionable records.  This data will provide insight into 
the district to make decisions on such things as spending based on school sizes as well as performance.

Only three files are necessary for this analysis:

   * PyCitySchools_Challenge.ipynb [Jupyter Notbook created for analysis] (https://github.com/lavec0324/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)
   * schools_complete.csv - ([School Data] https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/schools_complete.csv)
   * students_complete.csv - ([Student Data] https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/students_complete.csv)

All other files in the repo are working data only.

## Results
Results: Using bulleted lists and images of DataFrames as support, address the following questions.

###	How is the district summary affected?


####	How is the school summary affected?
####	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
####	How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type


![here](https://github.com/lavec0324/Module3_Election/blob/main/Election%20Analysis/Resources/Election_Results_County.PNG)


## Summary

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.






Based on how this script was designed it can be used for almost any election where vote counts are provided in the same format as the current csv file (ballot id, county and candidate).  Number of candidates or counties do not impact the current scripts ability to use in the future as it will add unique candidates and counties are they are encountered.  There is also no hardcoding present in the script that would need to be modified.  The only real modification required is the name of the input file and the path.  This can either be replicated for every run or can be updated on these lines of code:

![here](https://github.com/lavec0324/Module3_Election/blob/main/Election%20Analysis/Resources/file_name_code.PNG).