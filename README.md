# Project 1



## Problem Statement
We are Data Scientists from the College Board and we were tasked to find out whether the SAT and ACT are biased towards a state's economic strength.
The objective of this project is to explore if there is a correlation between real GDP per capita and SAT/ACT scores and participation rates, and whether states with higher real GDP per capita produces higher scoring results.

---

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|final|The different states of USA, including the Disctrict of Columbia| 
|2017|float|us_gdp|The GDP of respective states in 2017| 
|2018|float|us_gdp|The GDP of respective states in 2018| 
|2019|float|us_gdp|The GDP of respective states in 2019| 
|pop_2017|int|us_pop|The population of respective states in 2017|
|pop_2018|int|us_pop|The population of respective states in 2018|
|pop_2019|int|us_pop|The population of respective states in 2019|
|act_rate_2017|float|act_2017|Participatioin rate of ACT in 2017| 
|act_comp_2017|float|act_2017|Average composite results of ACT in 2017|
|act_rate_2018|float|act_2018|Participation rate of ACT in 2018| 
|act_comp_2018|float|act_2018|Average composite results of ACT in 2018|
|act_rate_2019|float|act_2019|Participation rate of ACT in 2019| 
|act_comp_2019|float|act_2019|Average composite results of ACT in 2019|
|sat_rate_2017|float|sat_2017|Participation rate of SAT in 2017| 
|sat_total_2017|integer|sat_2017|Average total results of SAT in 2017|
|sat_rate_2018|float|sat_2018|Participation rate of SAT in 2018| 
|sat_total_2018|integer|sat_2018|Average total results of SAT in 2018|
|sat_rate_2019|float|sat_2019|Participation rate of SAT in 2019| 
|sat_total_2019|integer|sat_2019|Average total results of SAT in 2019|
|gdp_cap_2017|float|final|The GDP per capita of respective states in 2017|
|gdp_cap_2018|float|final|The GDP per capita of respective states in 2018|
|gdp_cap_2019|float|final|The GDP per capita of respective states in 2019|

---

## Summary of Analysis
Based on the results of the data exploration and analysis, we have found several things:

1. There is a strong negative correlation between participation rates and scores of both SAT and ACT. This translates to, the lower the participation rate of a state, the higher the state's average score will be. But, this is easily explained by the self selection bias involved.

2. A state's GDP per capita has a moderate positive correlation to its average ACT Composite score. This means that students from states with higher GDP per capita have moderately higher ACT scores.

3. But there is little to no correlation when it comes to SAT scores. This means that a state's GDP per capita has seemingly no influence on SAT scores of students from that state. This seemingly indicates that SAT is a less biased test compared to ACT with regards to GDP per capita.

4. When real GDP per capita increases, ACT participation rate decreases. However, this relationship does not apply to SAT.

---

## Recommendations

More investigation is needed to determine reasons for the observations above.

1. It would be good to determine if policy intervention is needed to make ACT/SAT would make the tests more representative of a student's intellectual strength to reduce bias in testing (e.g. investigating factors that affect students decision making on whether to take ACT or SAT and whether either test should be made mandatory)

2. Further research should be done to identify reasons for this relationship and whether policy intervention is needed (e.g. to lower admission scores for the ACT for students who are from less wealthier states)

3. We should investigate further into the reasons why participation rate in ACT falls as state’s economic wealth increases. (e.g. profile of students who take ACT)

---

## Sources

- https://www.bea.gov/data/gdp/gdp-state
- https://www.census.gov/data/datasets/time-series/demo/popest/2010s-state-total.html#par_textimage_500989927

---
