# School_District_Analysis

## Overview

### The original school dirstrict analysis

8 School District Metrics was calculated
- School-based Metrics
  - Total Students
  - Total School Budget
  - Per Student Budget
- Student Performance-Based Metrics
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - % Overall Passing

Lastly, the schools were groupped by three ways to examine how students perform based on those characteristics. 

### Purpose of repeating dirstrict analysis
After the evidence suggests that the integrity have been jeapordized, the scores of Thomas High School's 9th graders must be changed to null values. 
The above anaylsis have been repeated. With new percentages and averages calculated for Thomas High School (using only 10th to 12th graders).
Below details any changes to the original analysis. 


## Results

### Thomas High School's Adjust Performance Scores

Thomas High School's Scores in original analysis.
<img width="996" alt="Screen Shot 2022-07-16 at 6 16 07 PM" src="https://user-images.githubusercontent.com/18197449/179373787-baa1d172-994f-4b1e-87f2-93ea4ce9be63.png">

Thomas High School's Scores after replacing 9th grade scores with NaNs. 
<img width="902" alt="Screen Shot 2022-07-16 at 6 21 54 PM" src="https://user-images.githubusercontent.com/18197449/179373747-3493bd2f-cc74-4cc3-a460-3503f4ddfb6e.png">

Thomas High School's adjusted scores using only 10th to 12th grades.
<img width="901" alt="Screen Shot 2022-07-16 at 6 22 26 PM" src="https://user-images.githubusercontent.com/18197449/179373779-4633d921-2c04-4816-ab5d-0c51ff359540.png">


#### School Spending
Schools were categorized into 4 bins: ["<$586", "$586-630", "$631-645", "$646-675"]
The parameters of the bins were choosen so that the groups were fairly even when distributed. 

![BySpend](https://user-images.githubusercontent.com/18197449/179374015-52cf8b0a-f8e6-4d57-94fc-e21cfb82dbc4.png)

The is a significant drop in Overall Passing Percent

![BySpend2](https://user-images.githubusercontent.com/18197449/179374106-5d4d6094-2981-4a71-89cf-d9906cb5537f.png)


#### School Size
Schools were categorized into 4 bins: ["Small (<1000)", "Medium (1000-1999)", "Large (2000-5000)"]
The parameters of the bins were choosen represent where the school sizes cluster. 

![BySize](https://user-images.githubusercontent.com/18197449/179374041-e797456a-1f49-4fcc-80de-48686f9cccdb.png)



![BySize2](https://user-images.githubusercontent.com/18197449/179374100-2f81b83f-c924-4cdc-ab46-c050ccf47752.png)


#### School Type
Below is the results when comparing charter schools to district schools. 
![ByType1](https://user-images.githubusercontent.com/18197449/179373982-9b4ec64f-cea2-46b4-bbae-3cdee80f81f6.png)
Thomas High School is a charter school
![ByType2](https://user-images.githubusercontent.com/18197449/179374102-94ce2c09-42a6-46d3-a749-64746bc08192.png)

## Highest Performing School

![ByHigh2](https://user-images.githubusercontent.com/18197449/179374191-59c0c000-585c-450a-93aa-cd9b3a86397d.png)

Thomas High's position as the second top performing school does not change. Canbrera still doe sbetter with a score of 91.33%. 
And Griffin High School's score of 90.599% still does not pass Thomas High's adjust score of 90.6%.

## Summary

Because Thomas High School's 9th grade scores were already similar to those of their 10th, 11th, and 12th grade counterparts, we see little change in the results. 

