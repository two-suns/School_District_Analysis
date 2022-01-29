# School District Analysis
## Overview
The school board believes that the original file shows evidence of academic dishonesty in the reading and math grades for ninth graders at Thomas High School.  The grades appear to have been altered.  The school board does not know the full extent of the academic dishonesty and they have turned to Maria for help.  She has asked me to replace the math and reading scores with NaNs while keeping the rest of the data intact.  After replacing the values, Maria would like the school district analysis repeated.  

## Results  
  * How is the district summary affected?
    * Original district summary.
    <img width="697" alt="original_district_summary" src="https://user-images.githubusercontent.com/59906657/151677668-f7c8f305-0a63-45e5-bcbf-15686443a187.PNG"> 
    
    * Updated district summary.  
    <img width="697" alt="updated_district_summary" src="https://user-images.githubusercontent.com/59906657/151677703-6187cb19-44d0-4ac4-8c76-c2d4bcbce28f.PNG">  
  
    * The district summary did not show significant change.

  * How is the school summary affected?
    * Original school summary
    <img width="750" alt="original_school_summary" src="https://user-images.githubusercontent.com/59906657/151677876-fe852eef-43ed-4526-b1bb-27f743e42c00.PNG">  
  
    * Updated school summary
    <img width="751" alt="updated_school_summary" src="https://user-images.githubusercontent.com/59906657/151677892-b2119483-9cf8-4181-96f6-b85bf6e348d9.PNG">

    * The percentage scores for reading, math, and overall showed significant changes. They went from being in the 90% range down to the 60% range.

    * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
      * Based on percentages, Thomas High School went from one of the best performing schools, to one of the worst.

  * How does replacing the ningth grade scores affect the following:
    * Math and reading scores by grade
      * Original Math (Left) and Reading (Right)  

      <img width="232" alt="oringinal_math_by_grade" src="https://user-images.githubusercontent.com/59906657/151678119-3a6ceb7f-c23c-4582-b4bf-069c508f466e.PNG"> <img width="233" alt="oringinal_read_by_grade" src="https://user-images.githubusercontent.com/59906657/151678152-486154aa-a2e3-4d29-ae22-29de91eb8a35.PNG">  
      
      * Updated Math (Left) and Reading (Right)
      
      <img width="227" alt="updated_math_by_grade" src="https://user-images.githubusercontent.com/59906657/151678231-a554ea34-ca80-4181-ba9a-5d55b29be4b7.PNG"> <img width="227" alt="updated_read_by_grade" src="https://user-images.githubusercontent.com/59906657/151678238-88454eea-01e7-46ce-9c44-fcd8eeece419.PNG">  
      
      * No significant change other than reading scores being replaced with NaNs for the updated analysis.
    * Scores by school spending
      * Original by school spending.  
       <img width="621" alt="original_spend_per_student" src="https://user-images.githubusercontent.com/59906657/151678342-aac99ef3-d688-4b5b-a6a3-45cc8704577f.PNG">  
      
      * Updated by school spending.
      <img width="619" alt="updated_spend_per_student" src="https://user-images.githubusercontent.com/59906657/151678356-a7341456-b431-4eaf-9eb4-f504d218940e.PNG">

      * Again, no significant change.

    * Scores by school size.
      * Original by school size.
      <img width="570" alt="original_by_school_size" src="https://user-images.githubusercontent.com/59906657/151678426-f74a32db-61a6-480e-8a5e-428731cfccb8.PNG">  
      
      * Updated by school size.
      <img width="565" alt="updated_by_school_size" src="https://user-images.githubusercontent.com/59906657/151678439-eb30f5ae-fd76-47c1-82c3-a8fa0f1c81b3.PNG">

      * No change.

    * Scores by school type.
      * Original by school type.
      <img width="533" alt="original_by_school_type" src="https://user-images.githubusercontent.com/59906657/151678463-fcc59f50-a6b2-4910-bac5-1424fe1c68ba.PNG">
      
      * Updated by school type.
      <img width="534" alt="updated_by_school_type" src="https://user-images.githubusercontent.com/59906657/151678472-54429514-3459-4ccc-8f71-8684ffb01c15.PNG">

      * No change.

## Summary
After analysis, most charts showed no significant change.  The school summary showed the most change after the scores were updated for ninth graders at Thomas High School (THS).  The math, reading, and overall percentages dropped from 93.2%, 97.3%, and 90.9% respectively, to 66.9%, 69.6%, and 65.1% respectively.  This is to be expected since an entire group of students was removed cuasing there to be less showing as passing.  There was a .2% change in the district summary for "% Passing Math" column.  The "% Overall Passing" dropped by .1%.  Finally, the "Average Math Score" lowered by .1%.
