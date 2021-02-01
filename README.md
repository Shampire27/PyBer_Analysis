# PyBer_Analysis

Challenge 5 - Performing analysis on PyBer data with Jupyter Notebook under PythonData environment with Pandas, NymPy, SciPy statistics and Matplotlib using Python.


## Overview of the analysis

### Background

This analyzing for PyBer is a overview of the ride-sharing data.  the CEO from Pyber would like to see a sumarry of the detail combined analysis on the city data and ride datas.  Multiple tables and charts was created for summarizing and visualizing:
- the total number of rides for each city types, the average ares and the total number of drivers for each city types; 
- the range of number of rides, fares, and number of drivers by city types;
- the precentage of the total fares, rides and drivers by city types with pie chart.


### Analysis Overview

In this project, following analyzations were provided: 
1. Converted the CSV files to Pandas DataFrames;
2. Defermined mean, median, and mode using NumPy, and SciPy statistics;
3. Using Matplotlip, created different kinds of charts for visualization the analyzing results for PyBer dara.


## Results


 - **PyBer Ride-Sharing Data(2019)**: In Urban area, the cost on average PyBer rids-shareing is the cheapest with the largest number of rides than other city types.  The larger of the population in a area will occure a chearper cost on ride-sharing.

![PyBer Ride-Sharing Data(2019)](Analysis/Fig1.png)


- **Ride Count Data**: The largest number of ride in 2019 is 39 rides, which happened in urban city.  Averagely, residents in the urban cities are more willing to take sharing-rides (4 times more than the lowest rural cities ride count).  Rural cities are not good targets to promote on sharing-rides.

![Ride Count Data](Analysis/Fig2.png)


- **Ride Count Data(2019)**:  The average cost for the rural cities sharing-ride customers ($34.62)  are 41% more than the average cost in urban cities ($24.53).  With the city type being more rural, the cost on fare for rides gradually increased.

![Ride Count Data(2019)](Analysis/Fig3.png)


- **Driver Count Data(2019)**: There are more drivers in urban citires for the sharing-drive.  Only a few drivers would like to work with sharing drive in rural cities (averagely under 5 drivers for rural cities, and no more than 10 sharing-ride drivers in each rural cities).  

![Driver Count Data(2019)](Analysis/Fig4.png)


- **% of Total Fares by City Type**: The main fares of sharing-rides are from the urban cities (62.7%), and the number of fares from sububan cities are also considerable (30.5%).  However, there is only 6.8% of the fares are from the rural cities. 

![% of Total Fares by City Type](Analysis/Fig5.png)


- **% of Total Rides by City Type**: For the numbers of rides, urban cites still contributed the most with 68.4% on the total number of rides in 2019.  Rural cities only takes the 5.3% on the total rides, which remains the weakest consumption power on sharing-rides.

![% of Total Rides by City Type](Analysis/Fig6.png)


- **% of Total Drivers by City Type**: For the numbers of drivers by city types, the percentage of drivers in the urban cities are 80.9%, which is more than 10% on the numbers of rides in the urban cities.  These means, in the urban cities, there are more competitive between the drivers to take more rides.

![% of Total Drivers by City Type](Analysis/Fig7.png)


- **Total fare by City Type**: For the first quater of the year of 2019, generally, people was paying more for sharing-rides during the beginning days of March.  

![Total fare by City Type](Analysis/Challenge_5.png)


## Summary

1. For the urban cities, sharing-ride could be the main promoting product. For the rural cities, sharing-drive may not be profitable, furthure analysis on additional data should be provide for further analysis.

2. During the first quater of the year of 2019, March is the most popular month that people would like to choose sharing-rides for transporting.  For the years after, PyBer should prepare for this hot season to ensure the customer experience by controling the number of drivers that PyBer could provide.

3. In the urban cities, there are too many drivers if to consider the rate of available rides for each driver.  Additional analysis should be made for the decision on keeping a stable rate of avarage number of rides that each drivers able to get for each periods.  The total number of driver could be deductive for a more efficient management if there is a further number shows many drivers are not able to get rides in a certain periods. In suburban cities, more drivers may be necessary to be hired.
