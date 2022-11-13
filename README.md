# surfs_up

## Overview of the analysis: Explain the purpose of this analysis.

Before opening up a surf shop in Oahu, W. Avy has tasked me with creating an analysis of tempurature trends during the months of June and December in order to determine if their surf and ice cream business is susytainable year-round. To accomplish this, I have used python, pandas, numpy, and sqlalchemy to create an statistical analysis of the tempuratures in Oahu during these 2 months.

## Results: 
### Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

The results of this analysis are demonstrated in the following 2 DataFrames:

![June Temperatures](https://github.com/waciciarelli/surfs_up/blob/main/Screenshots/june_temps.png?raw=true)
![December Temperatures](https://github.com/waciciarelli/surfs_up/blob/main/Screenshots/december_temps.png?raw=true)

From these DataFrames I can conclude the following:
* The average temperatures in Hawaii only drops 3.903 degrees from June to December. June has a standard deviation of around 3.257 degrees and December has a standard deviation of around 3.746 degrees. This would suggest that overall, the temperature in Hawaii does not change much throughout the year. However, in December there is a slightly wider range of temperatures that are likely to occur.
* The maximum temperature for June is 85 degrees and the maximum temperature for December is 83 degrees. On such days, a surf shop with ice cream would certainly thrive.
* The minimum temperature for June is 64 degrees and the minimum temperature for December is 56 degrees. This would suggest that December is potentiallu prone to having notably colder days than June.

## Summary: 
### Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

Based purely on temperature, the data suggest that there is enough evidence to justify opening a surf shop with ice cream year-round. The temperature does not drop significantly during the Winter months and as such, the shop would be able to thrive. Howver, with a higher standard deviation and lower minimum temperatures, there is still the risk of having poor business on the coldes of the days in December.

However, temperature is only one of many factors that people would consider when choosing to visit the beach and surf. Were I to run this analysis again, I would suggest looking at weather patterns during the months of June and December to determine if there are more sunny days in June than December. Additionally, with access to other data sources, looking at the swell sizes during June and December would help determine if there is a drop in optimal surfing days during the Winter.
