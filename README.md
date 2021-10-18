# School_District_Analysis

## Project Overview
The school board has notified Maria and her supervisor that the "students_complete.csv" file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
- Data Source: students_complete.csv
- Software: Anaconda 4.10.3, Python 3.7.10, Git version 2.33.0.windows.2, Jupyter notebook.

## Summary
The analysis of the election (Election-Audit Results) shows that:

Election Results
Total Votes: 369,711
County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

## Chalenge Overview
The election commission has requested some additional data to complete the audit:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

## Challenge Summary
Using repetition statements, conditional statements with logical operators, and print statements, print out the candidate and county election results to the command line.
The additional analysis and statements written in Python (Script) per the instructions receved shows that:

- Largest County Turnout: Denver
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

## Election-Audit Summary:
As business proposal. This Python script can be modified as follows in order to be use on any election:
1. Between lines 8 and 11, it is obtained the name and path onf the file used with the original data "cvs file" and the outcome "txt file", if you have other election excerise, you can select the new data only changign the name nad path on the script.
- ![Path_Change](https://github.com/Jcreye75/Election_analysis/blob/436566b7c28658232f3fe1117f64b276014cf79c/Resources/Path_Change.png) 

2. Please be aware that input data must be on cvs format (this is separated by commas), and the file must contain the following infor in this order:
- ![Req_CSV](https://github.com/Jcreye75/Election_analysis/blob/3cdb59739f7adb5abba8831104b149fae53345de/Resources/Req_CSV.png)

3. Lastly, the script does not have any finite loop counting, so there is no current limit for quantity of rows, therefore, any new database can be use as the script will fit it.

Regards
JC
