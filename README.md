# School District Analysis

## Overview of School District Analysis
Preparing all standardized test data for analysis and providing insights into performance trends across different schools to help inform decisions on student funding based on trends in school performance. Adjusting the original analysis to account for Thomas High School's ninth graders reading and math grades appearing to have been altered.

## School District Analysis Results

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected? 
- The district summary didn't change much from the original analysis; only a few dropped percentage points in the average math score (79 down to 78.9), the percentage passing math (75 down to 74.8), percentage passing reading (86 down to 85.7), and the overall percentage (65 down to 64.9) AS SHOWN [insert pics]

How is the school summary affected? 
- Schools other than Thomas High School were not affected.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
- Not much difference; their math and reading percentage went up slightly (a few tenths of a percent); the overall percentage dropped slightly, but still they landed 2nd in performance among all the schools.

How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - 9th graders scores replaced with nan's to reflect their score removal from the analysis. Caused no effect to other grades scores. AS SHOWN [INSERT PICS]

- Scores by school spending
  - no change whatsoever in scores after the ninth graders adjustment.

- Scores by school size 
  - rounded scores show no discernible change in the size summary after adjustment.
- Scores by school type
  - no changes seen in the charter and district school scores after adjustment.


## School District Analysis Summary
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Reading percentage went up slightly
2. math percentage went up slightly
3. overall percentage went down slightly
4. overall, replacing the ninth grade math and reading scores with nans had no affect on other schools results, only on thomas high school, which again, showed only a slight change.

## Resources
- Data Source: [Student Data CSV](Resources/students_complete.csv)
[School Data CSV](Resources/schools_complete.csv)
- Software: [Python](https://www.python.org/), 3.7.6, [Visual Studio Code](https://code.visualstudio.com/), 1.65.2, Anaconda, Jupyter Notebooks
