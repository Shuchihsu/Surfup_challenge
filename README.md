# Surfsup_challenge

## Overview of the analysis
  The analyst would like to open a shop in Hawaii Oahu, and he can sell surfing equipment and ice cream. The analyst would like to create a series of analysis of the weather condition to show to his investors. He is using sqlite and python to extract and calculate the weather data.

### Results

Here are the two sets of the statistics for June and December:

June

![june](https://github.com/jkmom/Surfup_challenge/blob/main/Resources/temp_june_stats.png)

December

![dec](https://github.com/jkmom/Surfup_challenge/blob/main/Resources/temp_dec_stats.png)

* When we look at the 50%, we can see December is 75 and June is 71. So overall, most of the time the temperature falls between 71 and 75. This means it will not be too cold for winter in Oahu. The business should not be affected by the temperature too much.
* The count for December is almost 200 less than June. We can investigate which station is not providing the stats. Maybe some of the data from the specific station we might consider.
* The min temperature of December is 56 degrees. We can probably get another dataset to see the temperature trend through out a day for December and June. If the lower temperature is always happening in the night, we probably can assume the lower temperature should not be the main concern of the business.

### Summary

From the stats, we can see the temperature should be good through out the year since the temperature is stable for most of the days. I would like to recommend querying the precipitation for the four seasons which would be the months – March(spring), June(summer), September(fall) and December(winter) to see if there is a raining season for Oahu and how it might impact the business. Another query will be the stations. From the counts from the stats, we know some of the stations might not function at the best, so we can investigate some of the stations which are fully functioning throughout the year.  	
