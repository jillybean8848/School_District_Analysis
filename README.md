# School_District_Analysis

## Overview

The school board has noticed that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have reached out for assistance. I was asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After replacing the math and reading scores, the process was repeated to show how the changes affected the overall analysis.

## School District Summary
![School Summary](https://user-images.githubusercontent.com/110632671/189501127-d4849677-3a79-446a-a022-d627c083a624.png)

After reviewing the average scores and passing percentages among high schools within the district the average math score dropped 0.1 and the average reading score was unaffected. The percentage of those passing math dropped 1% and the percentage of those passing reading also dropped 1%.

## School Summary 
![School District Summary](https://user-images.githubusercontent.com/110632671/189501786-2c0f9f28-adf1-4ae7-a341-528b38809537.png)

## Top Five Performing Schools
![Top Five Performing Schools](https://user-images.githubusercontent.com/110632671/189501872-31d19d3b-5c3c-47c9-b7d1-4fc1fd2bc7c2.png)

## Bottom Five Performing Schools
![Bottom Five Performing Schools](https://user-images.githubusercontent.com/110632671/189501915-d47af31e-cc70-4cb3-b6e2-0eaa6e3ec52a.png

After reviewing the school summaries as well as the highest and lowest performing schools we can see that the score corrections affected the ranking of the top five performing schools. Previously, Thomas High School ranked second place in the top five performing schools with a 91% overall passing percentage. However, once revisions were made for the math and reading scores, Thomas High School was no longer in the top five now with a 65% overall passing percentage. Interestingly, the five lowest performing schools remained the same.

## Average Reading Scores by Grade/School
 ![Reading Scores](https://user-images.githubusercontent.com/110632671/189502342-23abe8e8-18da-47b2-b57a-fc9f63c964d7.png)


## Average Math Scores by Grade/School
![math](https://user-images.githubusercontent.com/110632671/189513015-e5e59dad-b02a-48aa-a6af-5796cb50097a.png)

Math and Reading scores were not affected by grade after making our corrections. However, "NaN" is still displayed for ninth grade at Thomas High School for both math and reading. 

## Scores by School Spending
![School Spending Summary](https://user-images.githubusercontent.com/110632671/189513283-9a12fc3d-53ea-4e81-82e6-6faf9230ecd4.png)

When reviewing the School Spending summary, this data change did not affect the spending range for the average math scores or average reading scores. However, it did impact the spending ranges for passing percentages. Looking at this output, there was a six percent decrease in passing math percentages, a seven percent decrease in passing reading percentages, and a six percent decrease in the percentage of overall passing in the $630-644 spending range.

## Scores by School Size
![Scores by School Size](https://user-images.githubusercontent.com/110632671/189513573-174ba13d-83a1-4ae3-8fba-0aeb14aee815.png)

When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores. However, it did affect the passing percentages for medium sized schools for passing math percentage, passing reading percentage and the percentage of overall passing dropped six percent. Before altering the data the School Size summary showed that medium-sized schools had a high performance with 91% overall passing compared to small schools with 90% overall passing and large schools with 58% overall passing. Given the data change, medium size school are the second in performance with 85% passing.

## Scores by School Type
![Scores by School Type](https://user-images.githubusercontent.com/110632671/189513731-a4e63df3-51d8-4278-915f-8a51060737e6.png)

Our final analysis on the summary based on school types shows that our code also affected the passing percentages across charter and district schools. Removing the scores resulted in a decreased passing percentage for charter schools. Previously, charter schools had very high passing percentages with  94% passing math, 97% passing reading and 90% passing overall. It has now changed charter schools  to show a 90% passing math, 93% passing reading and 87% passing overall. 











