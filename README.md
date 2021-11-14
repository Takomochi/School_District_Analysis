# School District Analysis with Pandas

## Project Overview
The school board that the file "students_complete.csv" file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will repeat the school district analysis that we did in PyCitySchools.ipynb.


## Results
### Analysis

Scores of 9th grade Thomas High School students are removed for the revised district summary data frame.

- How is the district summary affected? <br>
  
  District Summary Original<br>
  <img width="700" height="60" alt="district_summary_before" src="https://user-images.githubusercontent.com/85041697/141688842-62c74bf7-e2dd-476b-bc82-1d58b3fab847.png">
  
  District Summary Revised<br>
  <img width="700" height="60" alt="district_summary_after" src="https://user-images.githubusercontent.com/85041697/141688603-c13ce86f-86d7-4553-ae00-d4e2b3322620.png">


  The average math score dropped by 0.1, the percentage of passing math dropped by 0.2 %, the percentage of passing reading dropped by 0.1%, and the percentage of passing both math and reading dropped by 0.3%. Althogh the average reading score stayed the same, overall the numbers decreased compared to the original district summary dataframe.<br>
<br>

- How is the school summary affected? <br>
    
    THS Scool Summary Original<br>
    <img width="700" height="60" alt="school_summary_before" src="https://user-images.githubusercontent.com/85041697/141690163-d9f33e66-ea44-4ef0-b43b-a1f4ee2c5f9a.png">

    
    THS School Summary Revised<br>
    <img width="700" height="60" alt="school_summary_after" src="https://user-images.githubusercontent.com/85041697/141690168-65aea675-f715-4858-92a0-f58999e11bb6.png">


    The average score for math and reading did not change so much. However, the percentage of passing math, reading, and overall dropped significantly. While the original school summary shows that each passing rate is between 90% and 97%, the revised school summary shows that each passing rate is between 65% and 69%.
<br>


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    
    The Thomas High School's performance was affected obviously by replacing the 9th grader's scores. Mainly, it impacted the percentage of passing rate, as we can see in the images above. 

    - % Passing Math: 93.3% => 66.9%
    - % Passing Reading: 97.3% => 69.6%
    - % Passing Overall: 90.9% => 65.1%
<br>


- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    The average scores of Thomas High school for 9th grade become NaN value. Other scores did not change.
    
    **Average math scores<br>**
    Original&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Revised<br><img width="250" height="400" alt="math_by_grade_before" src="https://user-images.githubusercontent.com/85041697/141691300-33128dc5-6982-4e17-9718-9eaadd916469.png"> <img width="250" height="400" alt="math_by_grade_after" src="https://user-images.githubusercontent.com/85041697/141691306-b3e10b7f-a312-4077-8463-986083fd1702.png"> <br>

  **Average reading scores<br>**
   Original&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Revised<br><img width="250" height="400" alt="reading_by_grade_before" src="https://user-images.githubusercontent.com/85041697/141691752-3e9fa3dd-7e33-4739-99ca-a5ce64fe3cae.png"> <img width="250" height="400" alt="reading_by_grade_afterpng" src="https://user-images.githubusercontent.com/85041697/141691759-a437a730-7a80-48db-8c3e-b40a9eb86016.png">




    - Scores by school spending 

    - Scores by school size
    - Scores by school type
