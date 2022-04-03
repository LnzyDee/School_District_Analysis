# School District Analysis

## Overview
Preparing all standardized test data for analysis and providing insights into performance trends across different schools to help inform decisions on funding based on these trends. Adjusting the original analysis--through the [PyCity Schools](PyCitySchools_Challenge.ipynb) code--to account for Thomas High School's ninth graders reading and math grades appearing to have been altered.

## School District Analysis Results

How is the district summary affected? 
- The district summary didn't change much from the original analysis; only a slight drop in the average math score (79 down to 78.9), the percentage passing math (75 down to 74.8), percentage passing reading (86 down to 85.7), and the overall percentage (65 down to 64.9) as shown below, the original results first and the results after accounting for the change of ninth grade scores to NaN:
![District Summary Original](/Images/district_summary_original.png)
![District Summary After NaN](/Images/district_summary_thsnan.png)

How is the school summary affected? 
- Schools other than Thomas High School were not affected. Thomas High School showed a change in the math, reading, and overall percentage (see below, original results first followed by the updated scores).
![School Summary Original](/Images/school_summary_original.png)
![School Summary After NaN](/Images/school_summary_afterthsupdate.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
- Not much difference; their math and reading percentage went up slightly (a few tenths of a percent, as shown above after the update); the overall percentage dropped slightly, but still they landed 2nd in performance among all the schools, as shown below:
![Top Schools Original](/Images/top_schools_original.png)
![Top Schools After Update](/Images/top_schools_afterthsupdate.png)

How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - 9th graders scores are replaced with nan's to reflect their score removal from the analysis. Caused no effect to other grades scores, as shown below; original results followed by the updated scores.

![Math Scores by Grade Original](/Images/math_scores_by_grade_original.png) ![Math Scores by Grade After NaN](/Images/math_scores_by_grade_aths.png)
![Reading Scores by Grade Original](/Images/reading_scores_by_grade_original.png) ![Reading Scores by Grade After NaN](/Images/reading_scores_by_grade.png)

- Scores by school spending
  - There was no change whatsoever in scores after the ninth graders adjustment, as shown below:
![Spending Summary Original](/Images/spending_summary_original.png)
![Spending Summary After NaN](/Images/spending_summary_afterthsupdate.png)

- Scores by school size 
  - Rounded scores show no discernible change in the size summary after adjustment, as shown below:
![Size Summary Original](/Images/size_summary_original.png)
![Size Summary After NaN](/Images/size_summary_afterthsupdate.png)

- Scores by school type
  - There were no changes seen in the charter and district school scores after adjustment, as shown below:
![Type Summary Original](/Images/type_summary_original.png)
![Type Summary After NaN](/Images/type_summary_afterthsupdate.png)


## School District Analysis Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The reading percentage went up slightly for Thomas High School.
2. The math percentage went up slightly for Thomas High School.
3. The overall percentage went down slightly for Thomas High School.
4. The district summary showed a slight drop in the reading, math, and overall percentage.

## Resources
- Data Source: [Student Data CSV](Resources/students_complete.csv),
[School Data CSV](Resources/schools_complete.csv)
- Software: [Python](https://www.python.org/), 3.7.6, [Visual Studio Code](https://code.visualstudio.com/), 1.65.2, [Anaconda](https://www.anaconda.com/), [Jupyter Notebook](https://jupyter.org/)
