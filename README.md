# snapchat-electiondata-petebuttigieg

## Background

Advertisements are necessesary for political candidates to get their names and agendas out there. While it is crucial to have a good ad with good content, it is also necessary to look at how well the ad is doing by studying how many people have seen and interact with it to potentially increase this number. This study looks at Snapchat ads for Pete Buttigieg's campaign between Jan and Feb 2020. In the end, I found that Spending was the variable influencing number of Impressions. A bigger dataset would make the test more precise.

![alt text](https://github.com/btran305/snapchat-electiondata-petebuttigieg/blob/master/plot-spendingvsimpressions.png "Plot showing correlation between spending and how many impressions ads get)

## Data Source

1) https://www.snap.com/en-US/political-ads/
File: PoliticalAds.csv

## Data Analysis

We will look at:
1) Which variables impact impressions
2) Predicting impressions based on variables where impact proves to be statistically significant
3) Test statistics: R squared, standard error, coefficients, p-value, and F significance, and what they mean in this study

## Data Manipulation

The following methods and commands were used:
1) Data summary: MIN, MAX, AVERAGE, QUARTILE (1 and 3)
         - Command + range > OK
2) Used IF statements to sort non-arithmetic variables (location, age range)

3) Used Excel Data Analysis ToolPak correlation and regression functions to analyze sample
         - Data tab > Data Analysis > Regression (or correlation) > insert range to collect data > OK
4) Used HLOOKUP and VLOOKUP to consolidate data summary and break down
         - HLOOKUP/VLOOKUP + cell to look up + table to look in + row/column to look in > OK
      
