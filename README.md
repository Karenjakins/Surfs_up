# Surfs Up

To conduct an analysis on weather data collected by several stations for a future business owner looking to run a surf shop from Oahu.  

## Overview of the Analysis

The purpose of this analysis is to compare the weather data from June and December to determine if running a surf shop is sustainable year-round. We ran the queries separately and turned the results into a data frame which we will discuss below, we also gathered the statistics through the function .describe() to better understand and compare the data for the two months. 

## Results 

- After conducting the analysis, we gather the following statistics for the months of June and December. 

	- June had a min of **64.00**, max of **85.0** and a mean of **74.9**. 
		![alt text](https://github.com/Karenjakins/Surfs_up/blob/main/Resources/June%20Temperatures.png "June Temperatures")


	-December had a min of **56.00**, max of **83.0** and a mean of **71.0**. 
		![alt text](https://github.com/Karenjakins/Surfs_up/blob/main/Resources/December%20Temperatures.png "December Temperatures")

- The difference in the standard deviation between June and December was only **0.49** since the standard deviation for June is "**3.25**" and "**3.74**" in December, showing there is not a significant difference in the two months. 

## Summary 

Overall, running a surf shop from Oahu seems like a profitable business as the weather during the winter is not too cold. Since there are only two seasons in Hawaii, fall and winter, it would be insightful to run a query on precipitation data as this can severely influence conditions for surfing. Depending on how much data is collected by the stations we could also run a query on areas of the island that have better tides or are located closer to tourist spots that can guarantee more customers and revenue for the business. 

## Resources

**Data Source:** hawaii.sqlite

**Software:** Python 3.6.1, Visual Studio Code, 1.38.1, Jupyter Notebook, SQLite