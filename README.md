# DO YOU TRUST YOUR DATA?
## COVID-19 comparison analysis utilizing three data sources

## Data comparison of the following states:
* Connecticut
* Florida
* Georgia
* New Jersey
* New York
* Texas


## Questions for analysis:
* How do the three data sets compare?  Do they reveal either consistencies or inconsistencies?
* What % of population was tested and how much does testing vary from state to state? Do the testing percentages correlate to COVID-19 count?
* Did the state shutdown and reopening timings of these six states impact the daily new COVID-19 cases? Did the reopening of specific businesses in certain states cause COVID-19 transmission to skyrocket?

## Answers to our questions:
*  The three data sets selected for this analysis proved to be staistically significantly similar.  The histogram showed the data sets overlayed each other indicating the data sets are similar.  For further analysis, a t-test was performed.  This resulted in t-scores with p-values larger than .05.  Therefore, the difference found is not statistically significanlty different.
* The correlation coefficient between testing percentages and COVID-19 count was only 0.12, which indicates there is no relationship between the two variables. This is also demonstrated in the scatter plot where the data points are spread all over rather than being clustered in a linear fashion. The r-squared value of 0.0136 indicates that only 1.36% of the movements of daily COVID-19 count (dependent variable) are explained by the movements in the testing percentage (independent variable). Thus, there is no relationship between the two at all.
* The t-test produced a p-value that is significantly smaller than 0.05, which indicates that the differences between the average COVID-19 daily cases in the two state groups is statistically significant. This indicates that the reopening of bars, nightclubs, recreational venues, and lax restaurant dine-in policies significantly contributed to higher transmissions of COVID-19.

## Why did we pick those specific states?
*All state data as of 7/22/20

* We chose Connecticut, New Jersey and New York because the governors of these states took collective measures to contain COVID-19.  Their shutdown dates are within a day of each other and all three states are still shutdown.
* We chose Florida, Georgia and Texas because these three states have shelter in place dates and reopening dates that are very close together as well.


### State stats:
* Connecticut was #26 in total positive case counts.  Connecticut's largest spike occurred on 4/22/20 at 2,109 cases per day.  The 7-day average is currently 84.
* Florida was #2 in the total positive cases counts. Florida's cases starting increasing to over 1,000 per day on 6/6/20.  The largest daily spike so far occurred on 7/12/20 at 15,135.  The 7-day average is currently 11,006.  
* Georgia was #8 on the list.  The largest daily spike occurred on 7/18/20 at 4,689 cases per day.  Current 7-day average is 3,495 cases per day.  
* New Jersey was #6  on the list.  The largest daily spike occurred on 4/3/20 at 4,305 cases per day.  The current 7-day average is 324 new cases per day.
* New York was #4 on the list.  The largest daily spike occurred on 4/10/20 at 8,593 cases per day.  The current 7-day average is 200 new cases per day.  
* Texas was #3 on the list.  Texas started seeing daily cases over 1,000 starting 5/5/20.  The largest daily spike so far occurred on 7/17/20 at 14,916 cases per day.  The 7-day average is currently 9,893.



## References:
* https://covidtracking.com/data/download
* https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset?select=us-counties.csv
* https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-states.csv
* https://www.kaggle.com/headsortails/covid19-us-county-jhu-data-demographics/data?select=us_county.csv
* https://www.washingtonpost.com/graphics/2020/national/states-reopening-coronavirus-map/
* https://www.cdc.gov/covid-data-tracker/#cases




