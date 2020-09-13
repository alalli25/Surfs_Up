# Surfs Up
Using Python, SQLite & SQLAlchemy to analyze local weather data in the area we would like to open a surf shop.

## Overview of Surfs Up Data Analysis
The purpose of this analysis was to use python, SQLite & SQLAlchemy to pull temperature data for both June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. In a previous analysis, we prepared key insights to our business partner, W. Avy, regarding a new business venture in Oahu. The business is a surf shop / ice cream shop hybrid. Our task was to extract weather data from Oahu, run queries using SQLite/SQLAlchemy, and provide analysis about the precipitation and temperature to determine if it is feasible to open the business.

## Surfs Up Results & Summary
### Results: Differences between weather in June & December

***Oahu June Weather***

![](/Resources/Screenshots/June_Weather.png)

***Oahu December Weather***

![](/Resources/Screenshots/Dec_Weather.png)

- The average temperature in the month of June is roughly 4 degrees warmer than the temperature in the month of December. 
- 99.7%, or three standard deviations of the mean, of the June temperature data ranges from 73 degrees to 77 degrees. 99.7% of the December temperature data ranges from 69 degrees to 74 degrees. The greater standard deviation in December temperatures could suggest more volatile temperature swings than June.
- There is a large discrepancy between the minimum temperature of June and December (64 degrees vs 56 degrees respectively). There is not a large discrepancy between the maximum temperature of June and December (85 degrees vs 83 degrees respectively)

### Summary & Additional Data Requests
Though the warmer temperatures in June suggest it more pleasurable eat ice cream, I believe this shop is sustainable for year-round operation. Though sales may dip in the winter, the December average temperature of 71 degrees is still suitable to consume ice cream.

To strengthen my recommendation, I would like to supplement temperature data with average precipitation data. If December happens to be a "rainy" month, it may make more sense to close the store and save on certain operating expenses. I would also like to analyze both temperature and precipitation data by year. If there is a trend of temperature increases, which is likely given global warming projections, it would boast positively for our shop to remain open year round.
