# School_District_Analysis


## Project Overview
School board expected academic dishonesty amongst Thomas High School's 9th grade, this project is inteeded to verify if there is evidence of this in the data for grades with those who passed in math and reading. To do so we first did an analysis that included Thomas High School's 9th grade scores and then we replaced the data with NaN repeating the analysis and compare the results. If there is indeed academic dishonesty we should see some changes changes in the two analysis.

[The first analysis (with Thomas High School's 9th grade)](PyCitySchools.ipynb)

[The second analysis (without Thomas High School's 9th grade)](PyCitySchools_Challenge.ipynb)

## Resources
- Data sources: [Student Data](Resources/students_complete.csv), [School Data](Resources/schools_complete.csv)
- Software: python 3.7.6, Pandas 1.3.4

## Results

- How is the district summary affected?
  - Looking at the below pictures you can see that removing Thomas High School's 9th grade has reduced the average scores across the board. Which implies higher grades in Thomas High School's 9th grade than the average.
  - ![District Summary first analysis](https://github.com/drruff/School_District_Analysis/blob/main/Resources/District_summary_first.PNG)
  - ![District Summary second analysis](https://github.com/drruff/School_District_Analysis/blob/main/Resources/District_summary_second.PNG)

- How is the school summary affected?
  - We can see a 0.1-0.3% decrease in grades after Thomas High School's 9th grade. We do not see much change in other schools if any at all.
  -  [School Summary First](https://github.com/drruff/School_District_Analysis/blob/main/Resources/Per_School_Summary_first.PNG)
  -  [School Summary Second](https://github.com/drruff/School_District_Analysis/blob/main/Resources/District_summary_second.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - There is no change to Thomas High School's performance relative to other schools. Thomas High School is number two in both analysis.
  - ![Top Scoring School first](https://github.com/drruff/School_District_Analysis/blob/main/Resources/Top_schools_first.PNG)
  - ![Top Scoring School second](https://github.com/drruff/School_District_Analysis/blob/main/Resources/Top_schools_second.PNG)

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: This has no change beyond Thomas High School's 9th grade changing to NaN in the second analysis. This is what is expected as we did not change the other grades data.
  - Scores by school spending: There are no changes to the analysis. 
  - Scores by school size: There are no changes to this analysis.
  - Scores by school type: There are no changes to this analysis.

## Summary

- We saw only a few minor changes overall. We saw the grade scores in reading and mathematics decreased within only the decimal places when looking at Thomas High School's grades overall, and when looking at the average scores of all schools. While this does imply Thomas High School's 9th grade is doing well, since the results over all the analysis was relatively insignficant and the fact that Thomas High School is second across all schools in the School Board it easily could be explained that these grades have no academic dishonesty and that these are the proper grades. If there was academic dishonesty we would expect more dramatic changes across the board, especially when comapring Thomas High School to other schools. The conclusion is that the investgation through these means is inconclusive and we cannot say this is evidence for academic dishonesty by itself. 

