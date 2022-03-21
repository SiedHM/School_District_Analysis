# Report for Module-4 Challenge

# 1.	Overview the task.
This task is about replacing the 9th grade Thomas High School math and reading scores to missing values, NaN. The reason for the replacement was due to evidence of academic dishonesty. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the replacement is done, we need to repeat the school district analysis that we did in this module and write up a report to describe how these changes affected the overall analysis.

# The purpose of the report is
- To write a python code script in jupyter notebook that replace the 9th grade math and reading scores to NaN
- To compute the percentage of students that pass math, reading and both from Thomas High school based on the number of 10th -12th students from the school
- Update the school district results and analysis based new number of students
- 
# Code for replacement
I used the loc method on the student data and inside the loc method,I used the ‘&’ logical operator to select the rows of 9th grade Thomas Highschool students. Outside the loc, I used the equal operator and set it to NaN using ‘numpy  nap.nan’ method. The following code replace the reading scores to NaN.

