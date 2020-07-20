# School_District_Analysis

## Project Overview
In this project we're helping Maria, the chief Data Scientist at Py City School District, with analyzing data on student funding and student standardized test scores. Our analysis will help the School Board and Superintendent in making decision regarding school budgets and priorities. More importantly, we're tasked with analyzing the impact of replacing the 9th grade math and reading test scores from Thomas High School with NaN while keeping the rest of the data intact due to evidence of academic dishonesty found in the students_complete.csv file.

### Resources
- Data Sources: clean_students_complete.csv, schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Anaconda 4.8.3, Jupyter Notebook 6.0.3

: Using bulleted lists and images of DataFrames as support, address the following questions.

##Results
The analysis of the Py City School District shows the following:
- How is the district summary affected?
	- The average math score dropped slightly from 79.0 to 78.9 while the average reading scores remained the same at 81.9.
	- The % passing for math dropped 1% from 75% to 74% and the % for reading also dropped 1% from 65% to 64%.
	- The % Overall Passing dropped 1% from 65% to 64%.
- How is the school summary affected?
	- The average math and reading scores remained almost identical, average math score at 83.4 for both before and after and average reading score at 83.8 before and 83.9 after.
	- The % of passing math dropped from 93% to 67% and the % of passing reading dropped from 97% to 65%.
	- The % overal passing also saw a significant drop from 91% to 65%.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	- The Thomas High School was previously ranked 2nd overall, after replacing the 9th grade scores it dropped out of the top 5 ranking.
- How does replacing the ninth-grade scores affect the following:
	- The only impact on Math and reading scores by grade was Thomas High School. The 9th grade class did not get an average score because their scores were replaced with NaN. 
	- Scores by school spending
	- Scores by school size
	- Scores by school type
	
##Images
-Before NaN replacement
	- [Scores by School Type](Scores_by_School_Type_BF.png)
	- [Scores by School Size](Scores_by_School_Size_Bf.png)
	- [Scores by Spending](Scores_By_Spending_BF.png)
	- [Average Reading Score by Grade](Ave_Reading_Score_By_Grade_Bf.png)
	- [Average Math Score by Grade](Ave_Math_Score_By_Grade_bf.png)
	- [Top and Bottom 5 Schools](Top_Bottom_5_School_BF.png)
	- Thomas High School Summary](Thomas_School_Summary_bf.png)
	- [Scholl Summary dataframe](school_summary_df_before.png)
	- [District Summary dataframe](dist_summary_df_before.png)
-After NaN replacement
	- [Average Reading Score by Grade](Ave_Reading_Score_By_Grade_After.png)
	- [Average Math Score by Grade](Ave_Math_Score_By_Grade_After.png)
	- [Top and Bottom School](Top_Bottom_5_School_After.png)
	- [Thomas High School Summary](Thomas_School_Summary_after.png)
	- [School Summary Dataframe](school_summary_df_after.png)
	- [District Summary Dataframe](dist_summary_df_after.png)

## Summary
Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


