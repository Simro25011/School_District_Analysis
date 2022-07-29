# School_District_Analysis
## Purpose
The school board has notified Maria and her supervisor that the students_complete.csv file contains evidence of academic dishonesty; in particular, there appear to be changes in the reading and math scores of Thomas High School ninth graders. Although the school board didn't know the full extent of academic dishonesty, they wanted to uphold state testing standards and turned to Maria for help. We were asked to replace Thomas High School math and reading scores with NaNs, while leaving the rest of the data unchanged. Once you replace the math and reading results, we need to conduct a district analysis and write a report describing how these changes affect the overall analysis.


In order to conduct our analysis, the datasets used will be found in the Resources folder and the softwares  used Python 3.7, Anaconda, Jupyter Notebook

## Analysis

As explained previously, in order to run our analysis we had to used Python 3.7, Anaconda, Jupyter Notebook.
https://github.com/Simro25011/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb

the mission was to see the impact of  potential academic dishonestyto the ninth grade students of Thomas High School. Therefor 
The entire ninth grade class of Thomas High School have had their scores replaced with NaN. The DataFrames below are  summaries  representing the District before and after replacing the ninth graders' scores with NaN.


https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/original_%20district_summary.png

https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/district_summary_less_9th_graders.png

Base on those DataFrames , we noticed the following changes  for Thomas High School :

- Average Math Score = 78.9  
- Average Reading Score = 81.9
- % Passing Math = 74.8
- % Passing Reading = 85.7
- % Overall Passing = 64.9


### School Summary
The DataFrames below will showcase the drop  in the % Overall Passing  for Thomas High School.

#### Before

https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/Original_Per_school_summary.png

##### After
https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/Per_school_summary_after.png


## Scores by School Size

### Before 
https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/original_%20Score_by_School_size.png

###  After

https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/_%20Score_by_School_size_after.png


Removing Thomas High School  9th graders  reduced the % Math Pass Rate, % Pass Reading Rate, % Overall Pass Rate
 , math pass percentage and reading pass percentage
 
## Scores by School Type

### Before

https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/original_%20Score_by_School_type.png

### after

https://github.com/Simro25011/School_District_Analysis/blob/main/Resources/Score_by_School_type_after.png

In this analysis, charter schools generally outperformed district schools. As the chart below shows, charter schools have an overall pass rate that is 36 percent higher than district schools.




## Summary

Equating ninth graders' scores with NaNs caused Thomas High School's overall grades and average scores to decrease. Average math and reading scores and overall student pass rates also fell across the district. Although the school board didn't know the full extent of academic dishonesty , this analysis showcase how important it's ideal to have full datasets in order to have the most accurate results
