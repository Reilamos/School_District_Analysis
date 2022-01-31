# School_District_Analysis

Python 3.7.11, Jupyter 6.4.5
Final Upload Completed Project "PycitySchools_Challenge"

# Overview of the school district analysis: Explain the purpose of this analysis.

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We need to replace the math and reading scores of Thomas High School and repeat our schoool analysis.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected? We replced the ninth grader's math and reading scores with NaN this had several affects:
 
    - The Overall Passing % for Thomas HS dropped 65%.
    - The Overall Passing % for the district dropped to 64.9%
    - Thomas HS is no longer in the top five schools.   
    - Data can be seen below

![image](https://user-images.githubusercontent.com/96445453/151736963-16b40876-7490-47df-af0c-46c342ea9952.png)

- How is the school summary affected? Ninth graders' had their scores omitted of Thomas High School:
  -Thomas HS math and reading increased by .06.
  - The overall Passing % of Thomas High School decreased by .11%
  - Thomas HS is the second best high school in the district with an overall passing rate of 90.63%


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
 - 


- Scores by school spending
 - After analsying the data we can see the two lower spending catagories <$584 and $585-629 have a higher Overall Passing %.
 - Mathing Passing % in the more expensive bins is a good amount lower than in the lower ones.


![image](https://user-images.githubusercontent.com/96445453/151738330-0c5775c5-e5ac-4525-9f72-b43786c0592e.png)

- Scores by school size
 - Large schools have the lowest average scores and passing %. 
 - Small and Medium schools perform almost identical.

![image](https://user-images.githubusercontent.com/96445453/151738133-0a48c90e-d3a6-4cce-960e-39b59752d58e.png)

- Scores by school type
 - Charter outperformed district type schools on our analysis.

![image](https://user-images.githubusercontent.com/96445453/151737979-fae24082-0e14-4eaf-9fff-e828be002106.png)


# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
