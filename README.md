# PyBer Analysis
## Overview of the analysis
V. Isualize requested additional analysis of their ride-sharing data by city type. In this new analysis, we look to understand:
- Total weekly fares for each city type.
- Variability of key data points for each city type.
Finally, based on the new findings, we will provide the company with a few action items to consider putting in place.

## Results Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
From the below summary table, we can conclude the following:

![Summary Table](https://github.com/msevillano89/PyBer_Analysis/blob/main/analysis/Screen%20Shot%202022-06-11%20at%204.47.12%20PM.png)

- Urban cities have the highest volume of activity (rides and drivers) while having the lowest average fare per driver.
- Rural cities have the lowest volume of activity while having the highest average fare per driver. 
- Based on the points above, we can determine a negative correlation between the number of drivers/riders and the average fare per driver.

Using the '.groupby()' function, I created a new data frame to analyze the activity and fares per city in a specific timeframe: '2019-01-01':'2019-04-29'

![Chart](https://github.com/msevillano89/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

From the chart generated above, we can conclude the following:
- Activity volume is relatively steady, with minor upticks in late February and downticks in late March and early April.
- All city types experienced an increase in fares in late February. There might be an opportunity to understand the driver behind this behavior.
- Overall, as the summary table discussed shows previously, Urban activity outpasses Suburban and Rural by almost 2:1 and 9:1, respectively. This outcome is somewhat expected due to the difference in population density in each city type.

## Summary
### Recommendations
1. **Increase fares in Urban cities:** High demand should lead to higher profit margins.
2. **Increase the number of drivers in Suburban and Rural cities:** these cities have higher average fares than urban cities, so more drivers should lead to higher revenue.
3. There's an opportunity to expand the analysis to a full year to understand activity behavior. If there are repeated patterns where total fares are at their highest regardless of the city type, the company might consider adding a surcharge. Moreover, in the seasons when activity is at its lowest, the company can add a promotion to encourage people to utilize the service. 
