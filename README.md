# PyBer_Analysis

## Overview of Project
The PyBer_Analysis project aims to analyze ride-sharing data from the provided files, [city_data.csv] and [ride_data.csv]. Using Python and the Pandas library, the analysis involves creating a summary DataFrame of the ride-sharing data by city type. Additionally, with the help of Pandas and Matplotlib, a multiple-line graph is generated to visualize the total weekly fares for each city type. The project concludes with a written report summarizing the differences in data across city types and how these differences can inform decision-making at PyBer.
## Results

The analysis of the ride-sharing data revealed the following key findings:

- The combined data from 2019 showed that urban cities had the highest number of rides and fares, followed by suburban and rural cities. Urban cities also had a significantly higher number of drivers. However, the average fare per ride and average fare per driver were lower in urban areas compared to suburban and rural areas.
![Summary Date Frame](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/Screenshot%202022-12-15%20at%205.28.30%20PM.png)

- The line chart representing the total fares per city type on a weekly basis from January to April 2019 demonstrated that urban cities consistently had the highest fare totals each week, followed by suburban and rural cities. Notably, all city types exhibited similar peak and dip patterns.
![Fares per City Type](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/PyBer_fare_summary.png)

- The visualization depicting the relationship between ride fare and the number of rides in each city type showcased that rides tended to be cheaper in urban areas, resulting in a higher volume of rides in those locations.
![fig1](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/Fig1.png)

- The pie charts illustrating the total number of fares, rides, and drivers by city type indicated that urban cities had the largest share in each category, followed by suburban and rural cities.
![Fig 5](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/Fig5.png) ![Fig6](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/Fig6.png) ![Fig7](https://github.com/heatherhutchinson211/PyBer_Analysis/blob/main/Fig7.png)



## Summary
Based on the analysis, the following recommendations are proposed for PyBer's decision-makers:

1. Consider the relationship between the number of drivers and fare prices: The higher number of drivers in urban areas correlates with lower fare prices. This information can be utilized to optimize the number of drivers in each city type, balancing supply and demand.

2. Leverage peak periods: The analysis revealed a significant surge in total rides during the latter part of February and the beginning of April. PyBer can capitalize on these peak periods by offering promotions or incentives to increase ride usage during other months, boosting business throughout the year.

3. Target rural cities: As rural cities demonstrated the lowest total fares across all metrics, PyBer should explore strategies to increase ride frequency in these areas. This could involve targeted promotions or enhanced marketing efforts to raise awareness and encourage rural residents to utilize ride-sharing services as a viable transportation option.

By implementing these recommendations, PyBer can enhance its operational efficiency, optimize pricing strategies, and expand its customer base across various city types.
