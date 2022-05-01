# School_District_Analysis
Pandas and Jupyter

## Overview

The purpose of this analysis is to address the school boards notice that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We will be assisting Maria, the chief data scientist for the school district, with the standardized test results data that has been collected from schools in the district. We are tasked with replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
  
  While the average reading score saw no change, the percent of students passing reading increased by 1 point. The percent of students passing math increased by 0.9 points while the average math score dropped by 0.1 points. The overall percentage of passing increased by 0.8 points.

- How is the school summary affected?

  Thomas High School was the only school affected by the change. The average math and reading scores increased by less than 0.1 percentage point.The percent passing math decreased by less than 0.1 points.Both the percent passing reading and the overall passing The % passing reading decreased by 0.3 percentage points.
  
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  Thomas High School performance didn't change.  

- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade

![image](https://user-images.githubusercontent.com/93399107/166156767-4c2eeb51-2c03-4adc-9cac-4deb6a2390b7.png)

    - Only the 9th grade Math and Reading scores for Thomas High School are affected.
    
  - Scores by school spending

![image](https://user-images.githubusercontent.com/93399107/166156680-9afa70ab-471b-48ed-ab40-292f40e54cbd.png)

    - There were no changes for the spending range 630 - 644 USD when the 9th grade math and reading scores for Thomas HS were replaced with NaN.
    
  - Scores by school size
  
  ![image](https://user-images.githubusercontent.com/93399107/166156654-466b0f3c-15e6-4dae-9939-9fe18befe0bb.png)

    - For the scores by medium school size, there were no changes for the medium size schools when the 9th grade math and reading scores for Thomas HS were replaced with NaN.
    
  - Scores by school type

![image](https://user-images.githubusercontent.com/93399107/166156861-51c79fbb-fa95-408c-ac72-62ff023e5759.png)

    - No change occured for the charter schools when the 9th grade math and reading scores for Thomas HS were replaced with NaN.

## Summary
Most of the data showed increase and decreases, although within the ranges of a percentage point, with very few showing no changes, There was a reduction in charter school's passing percentages.The district saw avaerage reading and math scores decrease. The overall passing perentage decreased as well. 

