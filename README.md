# School_District_Analysis
---
## Overview of Project
A School Board has asked for analysis of regional school test scores with a focus on math and reading scores. They are looking to determine next years budget for each school and therefore require summary metrics of each school in order to make this decision. This summary was completed when the school board learned of academic dishonesty happening among the ninth grade students at Thomas Highschool (THS). A new summary has to be constructed for the school board.

### Purpose

Construct a summary analysis of the school in the region for the school board with the updated data - excluding the ninth graders from THS.

## Analysis

The Jupiter Notebook used to complete this analysis is:

[PyCitySchools_Challenge.ipynb](https://github.com/ClaudAMC/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## School District Analysis Results

## District Summary

Below is the results of the new district summary.

![New District Summary](https://user-images.githubusercontent.com/103139895/171781291-4e9c1b9b-5cce-4d77-bdaf-1928c3304d15.PNG)

Below is the results of the old distric summary.

![Old District Summary](https://user-images.githubusercontent.com/103139895/171781457-9025062c-af53-498d-a5de-e0f400899a87.PNG)

Fromn this we can see that the Average Math Score, the % Passing Math, the % Passing Reading and the % overall passing were all affected by removing the data from the ninth grade students of THS.

### School Summary

We can see here the new school summary where THS is 2nd from the top.

![New School Summary](https://user-images.githubusercontent.com/103139895/171782878-73c3dd63-e1f2-49e3-a27d-71c80435ee9e.PNG)


Below we see the old school summary where THS is still 2nd from the Top.


![Old School Summary](https://user-images.githubusercontent.com/103139895/171788814-fb763867-8e22-4443-9b4e-03a4545e4bfd.PNG)

We can see from this that there is a difference in the  Average Math Score, Average Reading Score, the % Passing Math, the % Passing Reading and the % overall passing for THS however the differences are in the order of 0.1 or 0.01 in some cases.

### Effect on THS performance relative to the other schools

We can see that compared to other schools their position did not get affected.

### Effect on Math and reading scores by grade

Below we see the new math scores by grade.

![New math by grade scores](https://user-images.githubusercontent.com/103139895/171783949-b801395d-dc5a-4f40-913b-2ac74daf0d52.PNG)

Below we see the old math scores by grade.

![Old math by grade scores](https://user-images.githubusercontent.com/103139895/171783955-420deb72-63ba-4e48-a588-330859144056.PNG)

As we can expect the difference here is that the scores for THS 9th grade student have been removed and replaced by "nan".

Below we see the new reading scores by grade.

![New reading by grade scores](https://user-images.githubusercontent.com/103139895/171784472-611f484f-32b9-4184-917e-53a4d51cf1d2.PNG)

Below we see the old reading score by grade.

![Old reading by grade scores](https://user-images.githubusercontent.com/103139895/171784483-f2e49eb6-8be1-4724-b591-81dffd5cd4b3.PNG)

Again as we can expect the difference here is that the scores for THS 9th grade student have been removed and replaced by "nan".

### Effect of Scores by school spending

Below we see the new scores by school spending.

![New Scores by school spending](https://user-images.githubusercontent.com/103139895/171784919-d7dad748-00a7-430e-920a-21085ac3cc1e.PNG)

Below we see the old scores by school spending.

![Old Scores by school spending](https://user-images.githubusercontent.com/103139895/171784927-cef8fa3c-e2ab-48db-90f7-980e9962a7ca.PNG)

From this we can see that THS spent between $631-645; the only noticable effect was for the % Passing Reading and the % Overall Passing. These differences are in the order of 0.01. Due to formatting any effect at a less magnitude to that (i.e. changes to the order of 0.01) would not be visible.

### Effect of Scores by school size

Below we see the new scores by school size.

![New Scores by school size](https://user-images.githubusercontent.com/103139895/171785677-f66ccb86-3f6f-435f-a6ba-5ba318d014fe.PNG)

Below we see the old scores by school size.

![Old Scores by school size](https://user-images.githubusercontent.com/103139895/171786103-a01a1d60-12d3-42ef-a259-8ac9ff438564.PNG)

From this we can see that THS has a Medium (1000 - 1999) size population; the only noticable effect was for the % Passing Reading and the % Overall Passing. These differences are again in the order of 0.01. Due to formatting any effect at a less magnitude to that (i.e. changes to the order of 0.01) would not be visible.

### Effect on scores by school type

Below we see the new scores by school type.

![New Scores by school type](https://user-images.githubusercontent.com/103139895/171786519-59ac4799-1737-419a-8be9-24a18bec56ae.PNG)

Below we see the old scores by school type.

![Old Scores by school type](https://user-images.githubusercontent.com/103139895/171786526-b6c604d2-7873-4965-b4a7-34ea2c92cad7.PNG)

Knowing THS is a charter school we can focus on that data, however, we see that there is not difference between the new and old data. Again due to formatting any effect at a less magnitude to 0.01 (i.e. changes to the order of 0.01) would not be visible.

this is clearer when we look at the un-formatted data:

NEW:

![New Scores by school type - no formatt](https://user-images.githubusercontent.com/103139895/171786837-abe352c2-7977-43a7-9eed-253850e6c8dc.PNG)

OLD:

![Old Scores by school type - no formatt](https://user-images.githubusercontent.com/103139895/171786855-7da77d75-48c0-4f7b-8418-4e327df20b45.PNG)

Here we see there are slight difference in the charter school scores for all 5 metrics: Average Math Score,	Average Reading Score,	% Passing Math,	% Passing Reading, and	% Overall Passing.

## School District Result Summary

The largest differences we can see when we replaced the ninth grade data from THS is in the district summary where the % of students passing both reading and math decreased to 64.9% from 65.2%. The diference is in the magnitude of 0.3% therefore it is possible in the grand scheme this may not have a big effect, however, school board committies may rely on these metrics to gain funding from any overseeing body. This might mean that they may get more or less funding if the do or dont meet certain cuttoffs - in this case if the cuttoff was 65.0% then with the adjusted data they would no longer meet this cutoff. Another metric in this district summary reflects this potential: % Passing Math where previously the percent was 75.0% and the new percentage is 74.8%.

Another change is of course in the math and reading scores by grade charts where the THS 9th grade score is replaced by nan. Here it is clear something happened to the scores and they therefore needed to be removed.

Another change can be seen when looking at the charts comparing the scores by school spending where the % Passing Reading and the % Overall Passing scores decreased by 0.1% : 84.4% to 84.3% and 62.9% to 62.2% respectively.
