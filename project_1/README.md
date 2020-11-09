# Project 1: SAT & ACT Analysis (2017-2018)  
  
    
## Problem Statement

The SAT's and ACT's are two popular college entrance tests in the United States, and the participation rates for both tests are some of the top concerns that educational boards often grapple with. In this project, we aim to study the 2017 and 2018 data on both tests to have a better understanding of what most affects their participation rates. Based on our analysis and research we will then provide subtantiated recommendations on what educational policies can best improve participation rates in the entrance tests.  
  
  
## Executive Summary

**Data Import and Cleaning**

The first step in any Data Analysis is to first import and clean the data. We ensure that all the data is complete, accurate, and in the correct format before moving on to the analysis portion.
  
**Data Dictionary**

| Feature | Type | Dataset | Description |
| ------- | ---- | ------- | ----------- |
| state | *Object* | combined1718 | The state from which the 2017-2018 SAT and ACT data was collected |
| ACT17_part | *float64* | combined1718 | The percentage participation rate of the students in a specified state in the 2017 ACT's|
| ACT17_eng | *float64* | combined1718 | The average english score of the students in a specified state in the 2017 ACT's |
| ACT17_math | *float64* | combined1718 | The average math score of the students in a specified state in the 2017 ACT's |
| ACT17_read | *float64* | combined1718 | The average reading score of the students in a specified state in the 2017 ACT's |
| ACT17_sci | *float64* | combined1718 | The average science score of the students in a specified state in the 2017 ACT's |
| ACT17_comp | *float64* | combined1718 | The average composite score of the students in a specified state in the 2017 ACT's |
| SAT17_part | *float64* | combined1718 | The percentage participation rate of the students in a specified state in the 2017 SAT's |
| SAT17_read/write | *int64* | combined1718 | The average score for the "Evidence-Based Reading & Writing" test of the students in a specified state for the 2017 SAT's |
| SAT17_math | *int64* | combined1718 | The average score for the "Evidence-Based Reading & Writing" test of the students in a specified state for the 2017 SAT's |
| SAT17_total | *int64* | combined1718 | The average total score of the students in a specified state for the 2017 SAT's |
| ACT_part_change | *float64* | combined1718 | The change in the percentage participation rate of the students in a specified state from the 2017 to the 2018 ACT's |
| SAT_part_change | *float64* | combined1718 | The change in the percentage participation rate of the students in a specified state from the 2017 to the 2018 SAT's |  


There are some similar data-columns reflecting the scores and participation rate of the ACT's and the SAT's in 2018.

**Exploratory Data Analysis**

With a cleaned and properly prepared dataset, we carry out our initial data analysis. We look at the spread and distribution of the data, the average values, as well as the range of our data measurements.

**Visualise the Data**

Visualising the data helps us to understand them better. Distributions are much easier to see in graphs, and correlations can be better explored as well. Comparisons between related data measurements (for example, participation in the ACT compared to the SAT in any given year) can also be more clearly made through data visualisation.

**Descriptive and Inferential Statistics**

We take a deeper look into the data distribution. Statistical concepts like Central Limit Theorem and Hypothesis Testing are considered as we try to infer patterns from our data analysis.

**Outside Research**

Other than the data we have, there are also other factors which may not have been captured in the dataset. One example is the policy of having a nationwide "SAT School Day" - where students are allowed to take their SAT's during curriculum hours, at the school that they usually attend.  


## Conclusion and Recommendations

Our analysis shows that the simplest, most effective way to improve participation rates is through state funding of exam fees for **all** students. This is especially so for the SAT's, where we see huge improvements in the states of Illinois, Rhode Island and West Virginia.

The second recommendation is to facilitate the test-taking for the students **during school hours** and **within the same school that the student normally goes to**. We see this with the 'school SAT day' which basically allows students to take the SAT's in the same school that they go to, during normal school hours.

These are two simple but highly effective ways of encouraging high school seniors to sit for the ACT's or SAT's. Going forward, we have to look for what other barriers that are preventing students from taking their tests? The two measures mentioned above erases the two largest barriers: financial and logistical. If state educational boards are able to identify what other barriers their students face, that may help them facilitate student participation in such tests.