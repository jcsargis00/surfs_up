# Surfs Up
## Overview of the statistical analysis:
### Purpose
Investor W. Avy, is considering investing in a surf shop and ice cream business on the island of Oahu, Hawaii.  Before making a final decision, he has requested information about temperature trends in the months of June and Decemeber, to
help decide if the business will be sustainable year round.
### Methodology
Summary Statistics for June
#
By using Python, Pandas functions, and SQLAlchemy, data for the month of June in multiple years was extracted and prepped from the Measurements table in the hawaii.sqlite database.  Summary statistics were generated from the June Dataframe and are shown below.
#
![Junestats](https://github.com/jcsargis00/surfs_up/blob/main/junestats.PNG)
#
Summary Statistics for December
#
By repurposing the June Dataframe, data for the month of December in multiple years was extracted and prepped from the Measurements table in the hawaii.sqlite database.  Summary statistics were generated from the June Dataframe and are shown below.
#
![Decstats](https://github.com/jcsargis00/surfs_up/blob/main/decstats.PNG)
#
## Results:
#
Three key differences between the weather in June and December
   * The mean temperature in June was 75, while the mean temperature in December was 71, fairly close.
   * The high temperature in June was 85, while the high temperature in December was 83, also fairly close.
   * The low temperature in June was 64, while the low temperature in December was 56.  On either of these lowest temperature days, it would be unlikely anyone would want to buy ice cream after surfing, just too cold. 
#  
## Summary:
#
In summary, the average temperature in June and the average temperature in December were warm and moderate enough to suggest customer surfing and ice cream buying would be a good possibility.  In looking at the temperature for the 75th percentiles in June (77 degrees), and December (74 degrees), a majority of days in either month were pleasant enough for customers to surf and enjoy buying ice cream.
#
Additional queries to help make the decision for W. Avy could include plotting a temperature versus frequency histogram
and taking a look at rainfall for each of these months, 
