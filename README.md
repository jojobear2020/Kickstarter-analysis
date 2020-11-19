# Kickstarter-analysis
# Overview of Project:
We were tasked with providing an insightful analysis of all campaigns in category theater and subcategory plays. The goal is to help Louise make the right decisions, as well as have realistic expectations for the timing, location, goals and pledged amounts for her upcoming project.


# Analysis:
Overall, we have data on 1369 cases in the theater category. 76% (1047 cases) out of that is plays. This is a good sample size that allows us to see and analyze trends:
* outcome analysis
* location impact
* trends by year and month
* average days running etc.


# Challenges:
While we have a very good amount of information, we do not have enough insight into what potentially caused campaigns/plays to fail or be canceled. We can only make assumptions based on geolocation and seasonality. 

As to the data overall, it was organized well and relatively easy to work with.


# Results:
From the data we have, we can make assumptions based on the:

## *1. Launch date*:
* spring is the best time to run a campaign with May being the best month
* winter/December are the worst
* This trend is seen in theater overall and plays specifically

![](https://github.com/jojobear2020/Kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)


## *2. Goals/Donations*:
* Smaller goal’s campaigns up to $5,000 tend to have a higher success rate
* average successful campaign/play had a goal or $4.1K and pledged $4.5K
* average donation for all successful campaigns was $81 per backer

![](https://github.com/jojobear2020/Kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

Note: we see a spike for plays with $35,000-$45,000 target. This is driven primarily by 6 US campaigns. Average donation for these campaigns was $218 per backer.

 
## *3. Category/Subcategory*: 
* plays represent 76% of all data for theater
* plays also have the highest success rate (83% of all successfully executed projects) and no cancellations

![](https://github.com/jojobear2020/Kickstarter-analysis/blob/master/Theater_outcome_by_subcategory.png)

## *4. Geolocation*:
* 1253 projects (92% of all theater) happened in two countries – US and GB
* 900 (66%) of all projects were in the US with the highest success rate 
* 353 (26%) - in Great Britain
* the highest failure rate is in MX, NL, and AT (100% of all campaigns that ran there)

## *5. Historical trend by year*:
* 2014-2016 has the most successfully executed campaigns
* 2017 we see a rapid decline

![](https://github.com/jojobear2020/Kickstarter-analysis/blob/master/Theater_outcome_by_year.png)

## *6. Average days running*: 
31 days (32 for the whole theater group)

![](https://github.com/jojobear2020/Kickstarter-analysis/blob/master/Average_Days_Pledge_Goal.png)


# Conclusion:
The best time to start a campaign is spring months/early summer. Depending on the final goal, be aware that starting 2016 we see a decline in success rate with January-March 2017 being very slow. Also, the higher the goal, the smaller are chances to see a positive outcome. 


# Recommendations:
Collect more data about failed and canceled campaigns (cause, reasons, feedback). This would help immensely in choosing the right strategy for running a truly successful campaign.
