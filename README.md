## Overview of school district analysis

The purpose of the school district analysis is to correct data that was assumed to be correct. After evidence of academic dishonesty was discovered and data within *students_complete.csv* was known to be incomplete; further analysis was needed to accurately provide information about the school district analysis.

The audit is looking to correct the data by:
- remove Thomas High School ninth graders from data set
    - replace math and reading scores with NaN
- repeat school district analysis

## School District Analysis Results
**How is the district summary affected?**
There was a negligible drop after removing THS ninth graders from the data set.  
**How is the school summary affected?**
The figures below shows the changes before and after the Thomas High School ninth graders were removed from the data set.

- Before THS ninth grade removal
    - ![Before THS Ninth grade removal](https://github.com/HappyM0f0/School_District_Analysis/blob/main/Resources/Before_removal.png)

- After THS ninth grade removal
    - ![Before THS Ninth grade removal](https://github.com/HappyM0f0/School_District_Analysis/blob/main/Resources/After_removal.png)

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
Removing the ninth graders' scores improved the school ranking from fourth to second overall based on *% Overall Pass*. 
**How does replacing the ninth-grade scores affect the following:**
    - **Math and reading scores by grade**
        - No changes to other grades
    - **Scores by school spending**
        - No changes to school spending
    - **Scores by school size**
        - No changes to school size
    - **Scores by school type**
        - No changes by school type

## Election Audit Summary
**Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.**

In the new analysis, Thomas High School ninth graders Math and Reading scores were replaced with NaN values so as to not significantly alter the results. % Reading Pass, % Math Pass, and % Overall Pass were adjusted to only account from grades 10 - 12.
