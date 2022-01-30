# PyBer with Matplotlib

## Overview of the analysis

For this project, we are analyzing data for a ride-sharing app company named PyBer. Using a couple of CSV data sets and leveraging Python scripts, Pandas, and Matplotlib, we will help to tell the story using summary tables and chart visualizations. We will bucket the data based on city type (urban, suburban, rural), and look to understand ride counts, driver counts, and fares over this period (January-May 2019). We will also visualize weekly trends in fares from January through April, for each city type. Using our findings, we will present a summary and recommendations to our manager, Omar, and the company’s CEO, V. Isualize. These recommendations will be used to improve the company’s fare revenue, while also aiming to improve access and affordability for underserved cities.

## Results

In our analysis, we developed a couple of informative visuals: a summary DataFrame and a multiple-line chart showing weekly fare trending.  

### Summary DataFrame

As expected, there’s a relationship between population density and the use of ride-sharing services. More people means more ride demand and more driver availability. On average, fares are more expensive per ride in rural areas ($34.62) than in suburban ($30.97) and urban cities ($24.53). Based on the data and period reviewed, drivers made more on average in rural cities ($55.49) versus in suburban ($39.50) and urban cities ($16.57).

![DataFrame Summary](/analysis/PyBer_summary_df.PNG)  

### Weekly Fare Trending

We also developed a multiple-line chart showing weekly fare trends from January to April 2019, by city type. We noted a few findings based on this visual:

- Fares are at their lowest the first week of January. Perhaps this is due to colder weather, and a post-holiday lull.  
- Rural weekly fare trends are flatter than urban and suburban trends where there’s more variation over this stretch.  
- All 3 lines see a peak toward the end of February and a subsequent dip the following week.  
- Urban fares are more susceptible to weekly swings than the other 2 city types, especially during weeks in March.  
- Suburban fares trend up over the course of April, whereas urban and rural fares trend down over the month.  

![Weekly Trend Summary](/analysis/PyBer_fare_summary.png)  

## Summary

Based on our analysis, we offer three recommendations for consideration, to help understand and address disparities among the city types:

1. Further review driver data to understand the prevalence of drivers with little or no ride activity during this period. For instance, within urban cities there are more drivers than rides which means that not every driver was engaged. Stripping these drivers out would help us to better understand true fares by driver over this period, and to highlight opportunities for driver engagement.  

2. There’s an opportunity to improve accessibility and affordability in rural areas by increasing the driver base. This could be accomplished via targeted marketing efforts to hire drivers in these rural cities. Average fares per ride are also higher in rural cities, which could be an indication that riders are using ride-sharing services for longer distances. There could be an opportunity here to promote ride-sharing services for shorter drives, such as trips to the doctor’s office for appointments or sober cab rides.

3. It would also be helpful to overlay ride requests and driver availability over this period to understand if the peaks and valleys in weekly fare trending are a factor of demand (riders requesting rides), supply (available drivers), or both.
