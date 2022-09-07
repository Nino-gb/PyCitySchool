# School_District_Analysis

## Overview of School District Analysis:

City School District need all standardize school test data for analysis, reporting and presentation providing school performance, trends and pattern to make strategic decisions. School district data include school name, budget, students grade , math and reading test scores. Because the original analysis contain untrusworthy data, the school board request us to replace some math and reading scores from Thomas High School and replace them with NaNs while keeping the rest of the data intact along with a written report to describe how these changes affected the overall analysis. This insight will assist the School Board and Superintendent in making decisions regarding schools budget and priority.


### Purpose

Determinate how the new data will affect original school showcase trends and performance using a variety of programmming language tools to create codes to replace 9th grade math and reading scores from Thomas High School.


Tools used to imported , merged, cleaned, transformed and modified data;

- Jupyter Notebook
- Pandas library 
- Phyton 
- VS Code
- GitHub

## Results

### Comparing the original District Summary Analysis vs the replaced Disctrict Summary Analysis :

- Replaced analysis math score average decrease by .1%
- Replaced analysis passing math % decreases by .2%
- Replaced analysis passing reading % decreases by .3%
- Replaced analysis overall passing % decreases by .1%
- Schools total students, total budget, total budget for students, math and reading average score didn't have any changes, therefore their numbers were not affected.


> *School District Analysis*
![Screen Shot 2022-09-07 at 10 04 55 AM](https://user-images.githubusercontent.com/110786136/188913298-1b3ef3ba-4b69-4648-9a71-a9f715d8bb61.png)

> *Replaced School District Analysis*
![SUMD CHALLENGE](https://user-images.githubusercontent.com/110786136/188914257-bb517d28-2124-454a-8958-b13af02909e0.png)


### Overall impact in School Summary Data Frame when Thomas High School 9th grade math and reading score were replaced with NaNs :

- Thomas High School passing math % decrease by 27%
- Thomas High School passing reading % decrease by 28%
- Thomas High School overall passing % decrease by 25%
- Schools total students, total budget, total budget for students, math and reading average score didn't have any changes, therefore their numbers were not affected.

> *School District Analysis "School Summary Data Frame"*
![School Summary Analysis](https://user-images.githubusercontent.com/110786136/188947416-9bb8eb63-4d9a-4c39-baee-2ec2eed2c6c4.png)

> *Replaced School District Analysis School Summary Data Frame with Thomas High School 9t grades scores as NaNs*
![Replaced School Summary with 9th](https://user-images.githubusercontent.com/110786136/188947490-909b31d5-224e-4748-8e4d-a00a9821f6cb.png)


### Overall Impact removing 9th grade Thomas High School math and reading scores from the School Summary Data Frame

- Thomas High School passing math %, passing reading % and overall percentage increase and come closer to the percentages of the original School District Analysis
- Only Thomas High School 9th grade scores were affected in this report, the other graded remain the same
- There were not significant changes in school size , Thomas High school school size remain medium size
- School spending by score was not affect because there were not significant changes in score percentages 

> *Replaced District Analysis "School Summary" without Thomas High School 9th grade scores*
![Replaced School Summary Analysis without 9th grade](https://user-images.githubusercontent.com/110786136/188953737-9b733679-e922-43f4-b2f2-2bfd23f30c78.png)

## Summary

Updating the School Discrict Analysis with the new data requested by the board school have created significant changes through the report. You can see some the changes embodied in the first district summary where the scores percentage dicrease by almost 26% . With this scores Thomas High School overall performance would have rank as one of the bottoms school for overall passing. However, because Thomas High Grade 9th score were invalid ,the act of removing their scores from the school summary provide a more substantiate data that it bring a better view of Thomas High school scores performance. Doing so we can conclude that dissimilarity between the two report numbers is from decimals to 1%. School summary, size,type, budget, top bottom , scores and spending frames discrepancies are minimal.



