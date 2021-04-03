# PyBer_Analysis

## Overview of Analysis
Ride sharing data for a company that was originally in CSV format was accessed using Pandas dataframes and merged. Charts were created using matplotlib consisting of scatter plots, line graphs, bar charts, and pie charts. Charts were customized to include titles, different colours, and legends. Measures of central tendency were calculated using numpy on data such as the total number of rides for each city type (suburban, urban, and rural), the average fare for each city type, and total number of drivers for each city type. Box and whisker plots were also used to determine any outliers. Pie charts helped visualize percent of total fares, % of total rides, and % of total drivers per city type.

The purpose of the analysis was to determine what city type has the highest fares, the average fare per driver, and average fare per ride. Total rides per city type were calculated using groupby function and count. To find weekly fares, the resample function was used to convert dataframe from daily to weekly. 

## Results
As shown by [total fares by city type graph](https://github.com/MuddassirR/PyBer_Analysis/blob/main/PyBer_fare_summary.png), urban cities have the highest fare and rural cities have the lowest fare. 

In addition, the highest average fare per ride and average fare per driver were in rural cities and lowest in urban. Urban cities had the most rides and drivers while rural had the least. 


## Summary

From the graph, we see that rural and urban cities total fares decrease from April while suburban fares increase. This implies that the company should hire more drivers and/or promote to more drivers in suburban cities in the Spring, as it implies there are more rides in the Spring in suburban cities.

Also, we that in the beginning of January, urban and suburban fares increased while rural fares decreased, implying that more rides are occuring in suburban and rural cities at the start of January. This could used to implement more marketing policies in these city types during this time and less in rural.

Finally, overall, suburban and urban total fares are far greater than rural total fares, implying that greater focus should be on those 2 city types. 


