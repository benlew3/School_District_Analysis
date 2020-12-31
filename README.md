# School District Analysis
## Overview
### Description:
In this project, we are looking at high schools, identifying school funding based on how their students perform on standardized tests. We will be looking at the student's tests scores on reading and math to help provide some insight on how they perform and identify any trends.

### Purpose:
The purpose of the analysis will be to provide information to a school board on how various schools are doing in math and reading while maintaining privacy per student. 

### Situation
The School Board has noticed that there has been evidence of academic dishonesty coming from Thomas High School, particularly from the 9th grade class. We will be removing their data from this analysis while keeping the rest of the data. 

### Approach:
We will be using Python and Pandas in order to clean, merge and analyze the data and provide statistical information.

## Analysis and Results
### District Summary:
As per request from the School Board, we have removed the 9th graders from Thomas High School in this report. Prior to removing them from our analysis, the school disctrict performaces were as such: <br>
![old school info](https://github.com/benlew3/School_District_Analysis/blob/main/img/old_school_data.PNG)

In comparison, after removing the 9th grader data set, the data set now looks like as such: <br>
![new school info](https://github.com/benlew3/School_District_Analysis/blob/main/img/new_school_data.PNG)

In looking at the 2 images, we noticed that the % passing math went down by 0.2% and the average score went down by .1 point. The passing % for reading went down by 0.3% but the average point remained the same. As for overall passing, the average passing went down by 0.1%.

### School Summary:
Here we can view the full data from before and after removing the 9th grader's data. 

This is the statistics prior to removing the THS (Thomas High School) 9th grade information: 
![old model](https://github.com/benlew3/School_District_Analysis/blob/main/img/school_summary1.PNG)

In the chart before the removal, we can see that THS has an average passing % of 93.272171% for math, 97.308869% for reading, and overall passing at 90.948012%.

This is the statistics post removal for THS: 
![new model](https://github.com/benlew3/School_District_Analysis/blob/main/img/School_summary2.PNG)
Here we can see that the new math percent is 93.18569%, which is a negative difference of .086481%; reading is now at 97.018739%, which is a .29013% decrease; overall passing is at 90.630324%, which is a lower value by .317688%.

### Analysis
In the following data statistics, we can see that in a majority of the schools, the students across the grades will have higher scores in reading over math. We can also note that moving across each year, the improvement per each category remails somewhat of a flat line.

![math](https://github.com/benlew3/School_District_Analysis/blob/main/img/math_scores.PNG) ![reading](https://github.com/benlew3/School_District_Analysis/blob/main/img/reading_scores.PNG)


In the following chart, we are looking at a fiscal relation to the scores. We can see that the highest rating is on the lower fiscal spending. which out performs the highest by 36%. This indicates a negative coorelation from spending and cost per student spending.

![money chart](https://github.com/benlew3/School_District_Analysis/blob/main/img/spending.PNG)


Next we will look at the school size comparisons. We can note that the largest pool size has done more poorly than compared to the <2000 student school size. 

![school size](https://github.com/benlew3/School_District_Analysis/blob/main/img/size_chart.PNG)


Finally we will look at how charter schools compare with district schools. We notice that overall the charter schools out perform district on all levels.
![charter vs district](https://github.com/benlew3/School_District_Analysis/blob/main/img/charter.PNG)


## Summary
