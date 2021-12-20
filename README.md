# School District Analysis

## Overview
The school board has discovered evidence of academic dishonesty in a data file containing math and reading performance for 39170 students of 15 schools within the district.  It appears that alterations were made to the grades of ninth graders of Thomas High School. This data sheet has been used for extensive analysis of the factors contributing to school performance, and there is reason to believe this indiscretion has impacted the results of the analysis. To investigate this impact, the analysis has been repeated without the altered data. To do so, all grades by ninth graders of Thomas High School have been replaced by NaN for the repeated analysis.

## Results
- The district summary is very slightly affected by the replacement of THS ninth graders' grades with NaN's. Average Math Score drops 0.1%, Average Reading Score does not change, % Passing Math drops 0.2%, % Passing Reading drops 0.1%, and the % Overall Passing is 0.3% lower.

![image](https://user-images.githubusercontent.com/93882635/146710445-f65d8d7d-ef32-4de7-b928-35fdee67d6ea.png)

![image](https://user-images.githubusercontent.com/93882635/146708694-369474f4-882a-4764-b1bc-3ee7b24833fe.png)

- Slight changes are visible in the School Summary as well.

![image](https://user-images.githubusercontent.com/93882635/146709893-115e0d51-d134-4886-a37f-e3faa58c1c93.png)

![image](https://user-images.githubusercontent.com/93882635/146709787-a0ebac36-1cbd-4659-9111-192621ef51d5.png)

- Rounded up or down to the nearest percent, the numbers stay the same for Thomas High School before and after the repeated analysis. The differences are very small, and have no significant impact on THS's performance relative to other schools.

- In the original analysis, THS's ninth graders' average score of 83.6 was good for a shared second place within the district, and their average reading score of 83.7 also took the second spot in the rankings. No comparison to other schools can be made based on the results of the repeat analysis, as the values for both math and reading show NaN for THS ninth graders. 

- Because the impact of replacing ninth graders' grades is so small, THS's performance based on size, budget, or type, was unaffected.

## Summary
Overall, replacing the grades with NaN, has a minimal impact on the analysis. 
- Impact was biggest on passing percentages, because students with NaN were considered fails by the logic in the code. This was compensated for by replacing the passing scores with scores based on data from grades ten, eleven, and twelve only.
- Changes in performance of the overall district are 0.3% or less for the performance indicators used. 
- Changes in performance within the school summary are very small.
- Information on THS's ninth grade performance is no longer available.

