# School_District_Analysis

# Project Purpose
Construct a summary and statistics of both district and individual school standardized testing scores that will be used to create a report for stakeholders.

## Background
Using a virtual environment, Jupyter Notebook, and Python programming language, this project explores the utility of the Pandas library for high-performance data reading and analyzing of raw excel files. Using Jupyter Notebook, the learning module began by navigating through readin and importing raw data from CSV files, inspecting and clianing  data, merging datasets, performing mathcalculations, and producing charts and graphs for visualization. The dataset consisted of municipal district high school standardized testing scores.

### Deliverables
1. High-level snapshot of district's key metrics for each school, presented in a table format
2. Overview of key metrics for each school, presented in table format
3. Tables presenting:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - Average math score for each student of each grade level at each school
  - Average reading score for each student of each grade level at each school
  - School performance based on the buget per student
  - school performance based on the school size 
  - School performance based on the type of school

## Resources
- Software/applications:  Anaconda, Jupyter Notebook, Pandas
- Language:  Python 3.7.9
- Data Sources:  ![students_complete.csv](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/students_complete.csv)
![schools_complete.csv](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/schools_complete.csv)

## Project Overview
### Explore The Data
- Find and handle missing or incorrect values
- Determining Data types
- Removing strings
- Replacing substrings
### Generating School District Summary and DataFrame
- Merging DataFrames
- Tally students and schools
- Deriving the total budget buget per student
- Establing categorical spending ranges by bin
- Computing score averages and passing percentages by school and by grade
- Finding Highest and lowest-performing shools
- Formatting 
## Results
Stakeholders were provided insight into school and grade performance and how school factors like size and spending affects average reading and math scores and passing percentages. The school board will use this information to plan the upcoming academic year.

# Challenge

## Challenge Purpose
Evidence of acedemic dishonesty regarding math and reading scores for ninth grade Thomas High School students has come to light. The extent of altered grades in not yet known, therefore the board would like the PyCitySchool analysis to exclude the suspect scores all together and a report written about how the changes affect the overall analysis.


Revisit previous PyCitySchool analysis. Modify previous script and report how academic dishonest regarding altered reading and math grades for Thomas High School nineth graders affected overall analysis

## Resources
- Software/applications:  Anaconda, Jupyter Notebook, Pandas
- Language:  Python 3.7.9
- Source code: ![PyCitySchool_Analysis.ipynb](https://github.com/Quinneth/School_District_Analysis/blob/main/PyCitySchools.ipynb)
- Data Sources:  ![students_complete.csv](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/students_complete.csv)
![schools_complete.csv](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Repsitory: GitHub

 ## Challenge Overview and Analysis
 
 **Create three deliverables:**
 1. ***Replace Thomas High School ninth-grade reading and math scores with NaNs using Pandas loc method and NumbPy module. Use conditional statements and comparison and logical operators.***

![Nan](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/NaN.png)

2. ***Repeat the school distric analysis:***
  - **District Summary**
  ![district_summary_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/District_summary_original.png)
  ![district_summary_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/District_Summary_updated.png)
  
  - **School Summary**
  ![school_summary_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/school_summary_original.png)
  ![school_summary_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/school_summary_updated.png)
  
  - **High/low performing schools**
  ![top_schools_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/top_schools_original.png)
  ![top_schools_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/Top_schools_updated.png)
  ![low_schools_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/low_schools_original.png)
  ![low_schools_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/low_schools_updated.png)
  
  - **Average Math Score**
  ![Ave_math_score_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/ave_math_score_original.png)
  ![Ave_math_score_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/ave_math_scores_updated.png)
  
  - **Average Reading Score**
  ![Ave_reading_score_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/ave_reading_scores_original.png)
  ![Ave_reading_score_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/ave_reading_scores_updated.png)
  
  - **Scores by school spending per:**
  *student
  ![student_spending_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/student_spending_original.png)
  ![student_spending_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/student_spending_updated.png)
  school size
  ![size_spending_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/size_spending_original.png)
  ![size_spending_updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/size_spending_updated.png)
  school type*
  ![spending_type_original](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/spending_type_original.png)
  ![spending_type updated](https://github.com/Quinneth/School_District_Analysis/blob/main/Resources/spending_type_updated.png)

3. **Results**
Using the comparison above, the following conclusions were made
1. District summary: Updated statistics are marginally lower than original analysis (<1%).
2. School Summary:  Thomas High School which saw a significant drop in passing percentages (25%-27%) was the only school affected.
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Relative to other schools, Thomas High School subject specific and overal passing scores were significanly impacted. 

4. How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade:

  Score decline limited to Thomas High School. No impact was detected when aggregated with other schools.

- Scores by school spending:
  There was no significant change detected becasue of the small sample size of nullifed scores compared to the general population within the spending range.
  
- Scores by school size
  There was no significant change detected.
  
- Scores by school type
  There was no significant change detected.
  
5. Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

# Conclusion

  The four major changes that occured between the two analyses were:
  1. Thomas High School in Math and Reading scores were nullified.
  2. Thomas High School passing percentage for Math declined more than 20%.
  3. Thomas High School passing percentage for Reading declined more than 20%.
  4. Thomas High School overall passing rate dropped significantly.
