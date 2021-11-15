# School District Analysis with Pandas

## Project Overview
The school board has notified that the file "students_complete.csv" file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will repeat the school district analysis that we did in PyCitySchools.ipynb. New analysis notebook is located [here](https://github.com/Takomochi/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb).

## Resources
- Data Source: [student_complete.csv](https://github.com/Takomochi/School_District_Analysis/blob/main/Resources/students_complete.csv), [schools_complete.csv](https://github.com/Takomochi/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Software: Python 3.7.10, Visual Studio Code

## Results
### Analysis

Scores of 9th grade Thomas High School students are removed for the revised district summary data frame.

- How is the district summary affected? <br>
  
  The average math score dropped by 0.1, the percentage of passing math dropped by 0.2 %, the percentage of passing reading dropped by 0.1%, and the percentage of passing both math and reading dropped by 0.3%. Althogh the average reading score stayed the same, overall the numbers decreased compared to the original district summary dataframe.<br>
  
  District Summary Original<br>
  <img width="700" height="60" alt="district_summary_before" src="https://user-images.githubusercontent.com/85041697/141688842-62c74bf7-e2dd-476b-bc82-1d58b3fab847.png">
  
  District Summary Revised<br>
  <img width="700" height="60" alt="district_summary_after" src="https://user-images.githubusercontent.com/85041697/141688603-c13ce86f-86d7-4553-ae00-d4e2b3322620.png">

<br>

- How is the school summary affected? <br>

    Replacing 9th graders' scores from Thomas High School did not impact the school summary so much. Most of the values decreased slightly.
     <br>
    - Average Math Score: 83.42 => 83.35
    - Average Reading Score: 83.85 => 83.90
    - % Passing Math:  93.27% => 93.19%
    - % Passing Reading:  97.31% => 97.02%
    - % Passing Overall:  90.95% => 90.63%
    
    THS Scool Summary Original<br>
    <img width="550" alt="school_summary_before" src="https://user-images.githubusercontent.com/85041697/141697252-2c0f8475-fef6-4244-9ead-26996036507b.png">

    THS School Summary Revised<br>
    <img width="550" alt="school_summary_after" src="https://user-images.githubusercontent.com/85041697/141697257-96b2b356-2d9e-4991-a85c-6f5bb04dc9ac.png">
 

<br>


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?<br>
    It did not affect Thomas High School’s performance significantly. 
<br>


- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    The average scores of Thomas High school for 9th grade become NaN value. Other scores did not change.
    
      **Average math scores<br>**
      Original&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Revised<br><img width="250" height="400" alt="math_by_grade_before" src="https://user-images.githubusercontent.com/85041697/141691300-33128dc5-6982-4e17-9718-9eaadd916469.png"> <img width="250" height="400" alt="math_by_grade_after" src="https://user-images.githubusercontent.com/85041697/141691306-b3e10b7f-a312-4077-8463-986083fd1702.png"> <br>

      **Average reading scores<br>**
       Original&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Revised<br><img width="250" height="400" alt="reading_by_grade_before" src="https://user-images.githubusercontent.com/85041697/141691752-3e9fa3dd-7e33-4739-99ca-a5ce64fe3cae.png"> <img width="250" height="400" alt="reading_by_grade_afterpng" src="https://user-images.githubusercontent.com/85041697/141691759-a437a730-7a80-48db-8c3e-b40a9eb86016.png"><br>
       <br>
      
    There is not significant difference regarding the following measurements between the two data sets.

    - Scores by school spending <br>
      <img width="613" alt="spending_after" src="https://user-images.githubusercontent.com/85041697/141698215-3aa29cfd-d4d2-48d8-9ac8-7cf1ea8e28b0.png">


    - Scores by school size<br>
      <img width="613" alt="size_afterpng" src="https://user-images.githubusercontent.com/85041697/141698228-a07a6492-f0a7-4e61-a23e-0f54b733de61.png">

      
    - Scores by school type<br>
      <img width="613" alt="type_after" src="https://user-images.githubusercontent.com/85041697/141698241-dc54dbb9-59e4-4585-b33a-55db020bc72f.png">

## Summary

Replacing the 9th-grader's scores did not show a significant impact on our analysis. However, there are four changes in the updated district summary analysis. 
The average math score dropped by 0.1, the percentage of passing math dropped by 0.2 %, the percentage of passing reading dropped by 0.1%, and the percentage of passing both math and reading dropped by 0.3%.
