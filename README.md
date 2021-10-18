# School_District_Analysis

## Overview of the school district analysis

### The purpose

#### This analysis tried to find the funding student and grad test scores for math and reading and all school information which they attend. Also, overall passing percentages of students and the relationship with the budget per student. The school district determined that the graded test scores for ninth-grade students at Thomas High School were incorrect, and they asked for updated data summaries. After more analysis, it was best to replace the ninth-grade math and reading scores at Thomas High School while holding all other data associated with this student group whole.
We replaced both math and reading scores with NaN, representing a Nan--Number value, for 461 student records. However, this may look like a significant number; these score replacements did not change data summaries largely overall.

### Result

### How is the district summary affected?
#### After looking at both district summaries from PyCity Schools and Py City Schools_challenge, there is no change.

![district s](https://user-images.githubusercontent.com/90746609/137676021-e4d753e2-b0ce-4e22-8946-e6a1b068ac3b.jpg)


###How is the school summary affected?
####The overall passing for Thomas High School was 90.94% in Py City Schools, with the ninth-graders got out the general passing get smaller by 0.3 %.

![school s](https://user-images.githubusercontent.com/90746609/137676071-f22a0f18-cd20-45ba-b844-9dbff9e818d3.jpg)


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### Overall it does not alter either the reading scores or math scores. We are searching because we assume they do not include most of the 9th graders' scores because they might bring the school further down in test scores.

![ninth](https://user-images.githubusercontent.com/90746609/137676222-8b451c6a-893b-409f-b979-5963f62a3fef.jpg)

### How does replacing the ninth-grade scores affect the following:

- ### Math and reading scores by grade
   #### The only difference between the scores is the under 9th graders who attended Thomas High School; it shows a NaN.
   
   ![math by greag](https://user-images.githubusercontent.com/90746609/137675176-b753b96b-95ac-48ea-8017-58298e38ab5a.jpg)
![reading by grade](https://user-images.githubusercontent.com/90746609/137675191-e2bce03e-b85d-4c7b-88a7-5d3c99af1892.jpg)

   
- ### Scores by school spending
   #### The numbers stay nearly the same since the 9th graders are nullified from the statistics.
   
 ![school sp](https://user-images.githubusercontent.com/90746609/137675777-873a7b4f-d858-42a8-95af-bbfab174fc40.jpg)


-### Scores by school size
  #### Overall passing percentage does not change.
  
  ![size](https://user-images.githubusercontent.com/90746609/137675554-383b7053-5fdb-4e4d-9529-e1a0699085fe.jpg)

  
-### Scores by school type
  #### Scores by school type are not change at all.
  ![type](https://user-images.githubusercontent.com/90746609/137675616-34714117-203c-4fb0-a6d2-bc71b29f3d8b.jpg)

  
  ### Summary
  #### Summarize four significant changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. The four changes are reflected in the Average Math & Reading scores,percentage of  Math Passing and Reading scores, Overall Passing marks, and each student's funding. The average markings were slightly affected, but we can see the difference in each student's financing. Thomas High School 2nd stops as the top school doe not change at all.
