# School_District_Analysis

## Project Overview
The school board has notified Maria and her supervisor that the "students_complete.csv" file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Anaconda 4.10.3, Python 3.7.10, Git version 2.33.0.windows.2, Jupyter notebook.

## Results
### How is the district summary affected?
- The data contained 461 9th graders at Thomas High School which needed to be turned into null data. This movement recalculated the percentages of math, reading, and overall  passing.  The total count of students maintained the same as the original total student ids was not turned into null data. 
- The change between the original and adjusted repestendes less than 100 bp on averages, which ends on a similar whole number per value.
- ![District_Impact](https://github.com/Jcreye75/School_District_Analysis/blob/88293afe53152bd1b5cc2ae966671a6a45883c8d/Resources/District_Impact.png)

### How is the school summary affected?
- In the original analysis, Thomas High School started with a 91% overall passing rate.
- Removing the 9th grade students from the data set had an impact from 91% to 65% for the overall passing rate. 
- ![School_Impact](https://github.com/Jcreye75/School_District_Analysis/blob/d23ec2f576fbb8d596ad107df05028133125fe50/Resources/School_Impact.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board. 

- After adjusting the 9th grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom. 

## How does replacing the ninth-grade scores affect the following:

### Adjusted Averages using the Math and Reading Scores 
- In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. 
Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts. 

### Scores by school spending
Thomas High School falls in the $630-$644/student spending range.  However, the hundredths place was needed to see the nominal changes. 

There was very little spending impact by changing the 9th grade scores. 

### Scores by school size
Thomas High School is defined as a medium sized school.  The hundredths place was needed to see the nominal changes.

There was very little impact by campus size due to changing the 9th grade scores. 

### Scores by school type
Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.

There was very little impact by school type by changing the 9th grade scores. 

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed dramatically from 91% to 65%. 
2. Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses. 
3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School  
4. In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.  
The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.
