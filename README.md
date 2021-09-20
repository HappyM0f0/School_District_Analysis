## Overview of school district analysis

Overview of the school district analysis: Explain the purpose of this analysis. 

The purpose of the school district analysis is to correct data that was assumed to be correct. After evidence of academic dishonesty was discovered and data within students_complete.csv was known to be incomplete; further analysis was needed to accurately provide data about the school district analysis.

The audit is looking to correct the data by:
- remove Thomas High School ninth graders
    - replace math and reading scores with NaN
- repeat school district analysis

## School District Analysis Results
Results as followed

![Election_Results](https://github.com/HappyM0f0/UTBootcamp/blob/main/Election_Analysis/Resources/Screenshot%202021-09-12%20230423.png)

**How is the district summary affected?**
There was a small drop after removed THS ninth graders from the data set, in % Overall Passing fell by 0.3%.  
**How is the school summary affected?**
Thomas High School analysis shows significant changes in % Passing Math, % Passing Reading, and % Overall Passing. Provided below are two figures that show the changes from before and after the removal of THS.

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

**How does replacing the ninth-grade scores affect the following:**

**Math and reading scores by grade**

**Scores by school spending**

**Scores by school size**

**Scores by school type**

## Election Audit Summary
**Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.**


We have created a script that can be used for any election and modified to provide different information. For example, we can modify the script to analyze per precinct/district by adjusting some labels to reflect precinct/district. This script can also include information for the number of votes a candidate received from each county, which can help with future election campaign focuses.
