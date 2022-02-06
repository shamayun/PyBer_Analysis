# PyBer Analysis on Ride Sharing
## Overview of the analysis:
I conducted an analyses of the a ride-sharing company, PyBer, which operates very similar to Uber. I have had access to two sets of data.
1. Ride data with locations, date and fare for every ride, and 
2. city data which describes type of city and number of drivers.

The goal was to compare number of rides, and rides-fares in every cities based on type, Urban, Suburban and Rural. Also, to create visualizations of rideshare data for PyBer which would help improve access to ride-sharing services and determine affordability of underserved neighborhoods.Based on my analysis, I have addressed disparities among the city types and provided recommendations to the CEO.
![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig1.png)

## Resources:
I’ve utilized Jupyter Notebook, Pandas and various Matplotlib libraries to analyse Pyber data.

## Results:
Once the 2 datasets merged using left join based on the *city column* and formulated one dataset with all required data, I was able to summarize a dataframe for Total Rides, Total Drivers, Total Fares, Average Fare, and Average Fare per Drivert by city type. Table below captured to show my findings:

<img src="https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/PyBer_Summary.png" width="800">

### Followings are my observations based on the summarized data:
* Urban cities have the highest demand for rides while rural cities have the minimum.
* Urban cities have almost 5 times more drivers than suburban cities; suburban cities have 5 timex more drivers than rural areas
* Urban cities have highest total fares, 9 times more revenue than rural cities, while suburban cities stands in the middle, 1/2 revenue than urban cities and almost 4.5 times than rural cities
* Rural cities have the highest average fare per ride and average per driver.
* While urban cities lead in total rides, total revenues, they are at the bottom for average fare per ride and average fare per driver. Rural areas are on top on this 2 category

<img src="https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig6.png" width="450"> <img src="https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig7.png" width="450">
## Summary:
* National average *fare per ride ($26.75)* and *average fare per driver ($21.37)* are lot higher than urban areas. To retain drivers and maintain profitability, a calibration of city fares is very much needed.
Based on the analysis from the various data, charts, my  recommendations to Pyber CEO are: 
* To get more drivers in Rural areas to ensure there are enough drivers to meet ride demand. Rural cities have highest average fare per ride and average fare per driver. This is likely an indication of longer distance trips. This may result most drivers being occupied with longer trips and loss in potential revenue when there are peaks in business.
* I would recommend to optimize the number of drivers in urban cities. There are 2,405 drivers which made only 1,625 rides. Likely there are a lot of part time drivers who works shorter duration in the peak hours. Reducing number of drivers will increase average fare per driver, as now it is almost 3.5 times less compare to rural cities.


<img src="https://github.com/shamayun/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png">
