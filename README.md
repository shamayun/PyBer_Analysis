# PyBer_Analysis

Overview of the analysis
I conducted the analyses and visualization of the ride-sharing data very similar to Uber. I had two datasets: ride data with location, date and fare for every ride, and city data which describes type of city and number of drivers. The goal was to compare quantity and fares of rides in every city type: urban, suburban and rural; create clear visualization with matplotlib library and provide recommendation to the CEO for addressing any disparities among the city types.

During the analysis I’ve used Jupyter Notebook, pandas and matplotlib libraries.

Results
In order to perform the analysis, I merged datasets using left join based on the city column and got a one dataset with all available data. First of all, I created summary dataframe by city type. It has revealed first insight - there are few drivers and rides in rural cities with higher average fares compare to urban cities:

There are 13 times more rides in urban cities compare to rural cities (1,625 vs 125 rides)
The average fare per ride is 1.4 times less and average fare per driver is 3.4 times less in urban cities compare to rural cities ($24.53 vs $34.62 and $16.57 vs $55.49)
The total fares in urban cities is 9 times higher than in rural cities and 2 times higher than suburban cities. ($39,854.38 vs $4,327.93)
![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig1.png)

![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig2.png)

![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig3.png)

![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig5.png)

![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig6.png)

![](https://github.com/shamayun/PyBer_Analysis/blob/main/Resources/Fig7.png)
