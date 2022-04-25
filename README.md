# PyBer_Analysis
## Overview
How do different city types differ when it comes to weekly fares? How can we use this data to adjust how PyBer uses its resources to better manage drivers and fares?

## Results
#### Part One: Comparing drives, rides, and fares between city types
Predictably, the more urban a city got, the more rides, drivers, and total fares were earned:

![Fig8](/analysis/Fig8.PNG)

However, something interesting crops up when looking at the Average Fares numbers. Both average fares increased as the urbanization decreased, from $24.53 to $34.62 for the fare per ride and from $16.57 to $55.49 for the fare per driver. This indicates different strategies would be effective in different areas, depending on the goal of the company. If the goal is to maintain low average fares, then investment in drivers in Rural and Suburban districts could be fruitful, while attracting more riders in Urban districts could bring the average fare up to the level of the other district types
#### Part Two: A weekly fare chart comparing city types
How does the fare amount vary from week to week? Let's look at January 2019 to April 2019:

![Total Fare Graph](/analysis/total_fare_graph.png)

In this three month window, the fares for each city type increased slightly from January to April, though it wasn't a consistent increase. Week to week numbers varied wildly for each type, making a true analysis of this window difficult. Consistently, the Urban cities outperformed the Suburban and Rural cities, which matches our intuition and what Part One showed. 
## Summary
This analysis is limited in scope, and is best at confirming intuition: that the more customers there are in an area, the more business the company would get. However, finding out how specific urban density affects business (analyzing city density vs. total fare), how ride cost affects demand, and how driver availability affects total fares in addition to the analysis here would provide a more complete view of what strategies going forward would be most successful. 

I would guess in the areas where rides outnumber drivers: Suburban (625 rides to 490 drivers) and Rural (125 rides to 78 drivers) encouraging more drivers would be profitable, where as in Urban areas (1625 rides to 2405 drivers) there is potential value in encouraging more riders, as there are plenty of available drivers.
