# School_District_Analysis

## Overview of School District Analysis
The purpose of this analysis is to summarize at a district and school level, math and reading scores as a measurment of school performace. Factors that are considered in this assessment include type of school, school spending and the size of the student population. During the course of the analysis concerns were brought forward regarding Thomas High Schools 9th grade class. These concerns resulted in the removal of the Thomas High School 9th graders being removed from this analysis. 

## Resources
  * Data Source: schools_complete.csv, students_complete.csv. Both files are saved in the resources section of the GitHub repository.
  * Software: Juypter Notebook 6.3.0, Python Virtual environment 3.7.10 named PythonData. Pandas and Numpy libraries were also used in this analysis. 

## Results
  The following is the final district summary results with the modification of removing the ninth graders from Thomas Charter High School. 
  
  District results by student spending.
  
  <img width="443" alt="District_scores_by_spending_final" src="https://user-images.githubusercontent.com/90878901/137827665-5b5451f5-8458-44ca-aa6d-68106fcca53d.png">

  District results by school size.

<img width="391" alt="District_score_by_school_size_final" src="https://user-images.githubusercontent.com/90878901/137827754-a45dd555-d967-414c-a74b-88d3a3ebe37c.png">

  District results by school type
  
  <img width="372" alt="District_score_by_school_type_final" src="https://user-images.githubusercontent.com/90878901/137827796-97bc11bc-ae22-4e8c-80a6-cd55ed9793e3.png">

 

The per school performace adjusted for removing Thomas High school is as follows:

<img width="495" alt="school_summary_final" src="https://user-images.githubusercontent.com/90878901/137828239-c375569a-780f-461d-8f90-cf5f962ece3b.png">

 *The highest performing school was Cabrera Charter High School with a medium student population of 1858, and an overall passing score of 91% the per student cost was in the under $584 per student. 

 *The lowest performing school was Rodriguez High School with a high student population of 3999. The overall passing score was 53% and the cost per student spending was in the $630 to $644 category. 

 
 ## Summary
 There was very little impact removing Thomas Charter High School ninth graders. 
 
  * Math percentage moved from 93.3% to 93.2%
  * Reading percentage moved from 97.3% to 97.0% 
  * Overall passing percentage moved from 90.9% to 90.6%

Overall performace based on math and reading testing showed the following:

  * Charter schools performed better on testing than district schools.
  * Student scores were best when the students were in a medium sized (1000-2000 student) population. 
  * As school spending decreased overall passing increased.

Thank you for your time to review this analysis. 
