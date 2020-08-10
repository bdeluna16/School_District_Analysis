# School_District_Analysis
## Overview
The school board has notified Maria and her supervisor that the student data shows evidence of academic dishonesty. The school board believes that the reading and math grades among 9th graders at Thomas High School have been altered. Although the board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. In turn, Maria has asked us to assist with her task. She wants us to replace the math and reading scores for all 9th graders at Thomas High School with "NaNs" while keeping the rest of the data intact. After that we are to run the school analysis again to see how the omission of the 9th grader data at Thomas High School has affected the overall analysis.
## Results
1. How is the district summary affected?
    * district summary BEFORE changing 9th grade Thomas High School data:

![image](https://user-images.githubusercontent.com/67936161/89754462-d44a3400-da90-11ea-9fe7-958aa0ab5a22.png)

    * district summary AFTER changing 9th grade Thomas High School data:

![image](https://user-images.githubusercontent.com/67936161/89754520-15424880-da91-11ea-99f4-13e4af972140.png)

        * % Passed reading decreased from 86% to 85%
        
2. How is the school summary affected?
    * school summary BEFORE changing 9th grade Thomas High School data:

![image](https://user-images.githubusercontent.com/67936161/89755313-d9f54900-da93-11ea-91e6-698e97acdbc2.png)

    * district summary AFTER changing 9th grade Thomas High School data:

![image](https://user-images.githubusercontent.com/67936161/89755324-e24d8400-da93-11ea-8490-47d70d391619.png)

        * % Passing Reading decreased from 97% to 83%
        * % Overall Passing decreased from 90% to 77%

3. How does replacing the ninth_grade scores affect the following:
    * Math and reading scores by grade
        * The only changes from replacing the 9th grade scores was in the 9th grade reading scores for Thomas Higschool. The reading score decreased from 83.72 to 83.58.
![image](https://user-images.githubusercontent.com/67936161/89756725-35c1d100-da98-11ea-8a8f-cb0462ac3054.png)
![image](https://user-images.githubusercontent.com/67936161/89756758-44a88380-da98-11ea-9fe9-f0d455044070.png)

    * Scores by School Spending
        * % Passing reading decreased from 84% to 81% for schools that spend $630-$644
        * % Overall passing decreased from 53% to 60% for schools that spend $630-$644
![image](https://user-images.githubusercontent.com/67936161/89757147-4aeb2f80-da99-11ea-8c6e-576e604effee.png)
![image](https://user-images.githubusercontent.com/67936161/89757158-50e11080-da99-11ea-8191-81656f9c999c.png)

    * Scores by School Size
        * % Passing reading decreased from 97% to 94% for medium sized schools
        * % Overall passing decreased from 91% to 88% for medium sized schools
![image](https://user-images.githubusercontent.com/67936161/89756936-b680cd00-da98-11ea-8873-4eed4a801560.png)
![image](https://user-images.githubusercontent.com/67936161/89756959-c5677f80-da98-11ea-9c87-0fd7d4e097d0.png)

    * Scores by school type
        * % Passing reading decreased from 97% to 95% for charter schools
        * % Overall passing decreased from 90% to 89% for charter schools
![image](https://user-images.githubusercontent.com/67936161/89757316-b6cd9800-da99-11ea-946d-1c6e3b0d0522.png)
![image](https://user-images.githubusercontent.com/67936161/89757411-03b16e80-da9a-11ea-8de5-344354014b38.png)

## Summary
* 4 major changes in the updated school district analysis:
    1. The percentage of 9th graders at Thomas High School who passed reading decreased. 
    2. The percentage of overall students at Thomas High school who passed math and reading decreased.
    3. The performance of medium sized schools in the reading category decreased.
    4. The performance of schools that spend $630-$644 in the reading category decreased.