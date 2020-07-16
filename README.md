# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) &nbsp; Project 1: Act and Sat Analysis

## Problem Statement
There has been a change in SAT and ACT participation rates in the of year 2017 and 2018. This project aims to make a recommendations to improve participation rates in SAT test. The ultimate outcome is to find solutions/recommendations to overtake ACTS participation rate and gain market share.


## Summary
The goal of this project is to improve SATS participation rate in 2018.

In order to achieve it, 2017 and 2018 data were merge into one file. Errors such as extra characters were remove, percentages were removed to convert all numerical data in numbers with decimal points and data were arranged in the state level.

Next is to analyse the data and give insights with visualisation such as Heatmap, Historgraph and Scatterplot.

Lastly, with the combination of insights and outside research, recommendations will be suggested to increase the overall SATS participation rate.

### Key Takeaways ACT on average has a higher participation rate.
Total mean scores for SAT & ACT are negatively correlated with each other in 2017 data.

Reason could be, as there is a higher percentage of students taking the ACT which could be more popular choice, for most average scoring students, they would probably be taking just one exam.

Therefore, higher scoring students will take part in SAT to challenge themselves, pushing the score of SAT's average total score to higher.


### Conclusion and Recommendation
State Chosen: California
Based on my research California has the highest population among US state. It will be best to target the state with the highest population as this will greatly increase our market share which will increase our overall participation rate.
Data source: https://worldpopulationreview.com/states/

First recommendation is to create more awareness use SAT fee waiver as only 25% of the students are using it.
Data source (page 3): https://reports.collegeboard.org/pdf/2017-total-group-sat-suite-assessments-annual-report.pdf
We would like to increase the number of student using the SAT fee waiver to 40% to increase the participation rate.

Second recommendation is to increase the number of states that has mandatory testing of SATS, currently we only have 10 states.
Data source: https://blog.prepscholar.com/act-vs-sat
We would like to increase the number to states to take SATS exam mandatory to 12 which in turn increase our participation rate.


### Additional Data
Additional data such as collecting more granular data on each county or school district in each state, this will help us to identify those low participation rates schools and with that, we can focus more to each individual schools and put in more effort to encourage higher participation rate and awareness of SATs examination.

## Data

##### Data of SAT & ACT 2017
- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)


|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|ACT/SAT|location|
|**percentage_of_act_students_tested_in_201**|float|ACT|participation rate for ACT student|
|**percentage_of_sat_students_tested_in_201**|float|SAT|participation rate SAT student|
|**act_avg_english_score_in_201**|float|ACT|average english score|
|**act_avg_math_score_in_201**|float|ACT/SAT|average math score|
|**act_avg_reading_score_in_201**|float|ACT|average reading score|
|**act_avg_science_score_in_201**|float|ACT|average science score|
|**act_avg_composite_score_in_201**|float|ACT|average composite score|
|**sat_avg_evidence-based_reading_and_writing_in_2017**|int|SAT| average evidence based reading and writing score|
|**sat_avg_math_score_in_2017**|int|SAT| average math score|
|**total_avg_score_for_sat_in_2017**|int|SAT|average total score|
