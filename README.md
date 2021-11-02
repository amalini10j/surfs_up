# surfs_up respository
Weather analysis using jupyter notebook, VS Code and SQLLite

## Overview of Weather data Analysis in Oahu
W. Avy, the sponsor of the surf shop business wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


## Resources
**Data Source:** Temperature and Precipitation measurements from a SQLite file
**Software:** Python 3.8, Visual Studio Code 1.59, Pandas, SQLite, Jupyter Notebook


## Results of June and December Temperature analysis
The following points can be deduced from the two datasets:
- The total number of points in the two datasets are comparable (1700 vs 1517) and so these can be compared well statistically
- There is not much difference between the average tempetarue of June  (74F) and average temperature (71F) of December which indicates that the temperature will be warm all year round. This indicates that the surf shop and ice cream shop business can flourish all through the year
- The min and max temeperatures of the two datasets are also close to each other indicating not too much temperature variation between the hottest and coldest months of the year 
- The standard deviation in June is 3.2 and in December it it 3.7. Looking at the mean, the variability in temperature between the two months is similar

**June weather statistics**

![June](/Resources/June Temp Stats.png)

**December weather statistics**

![December](/Resources/Dec Temp Stats.png)

## Summary

The surf and ice cream business could flourish more in warm tempeartures. As the temperature in Oahu is fairly warm and similar between the hottest and coldest month (June and December respectively) it is an ideal place for the surf and ice cream shop as it would profit all year round.

Two additional helpful queries would be to find the precipitation data in June and December as excessive rain could hinder the business. If the preceipation remains fairly low then the business would flourish throughout the year.


