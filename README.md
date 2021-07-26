# American Airlines Flight on-time performance in 2005

This is an exploration of  Airline on time performance

This dataset is taken from the American Statistical Association (ASA) [website](https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009). Every year the ASA organizes a data science challenge called Data Expo where a raw dataset is provided for analyses. This dataset is from the Data Expo 2009 challenge where the dataset represents Airline on-time performance. It is a collection of all domestic US flights operated by major carriers and collects data points such as: actual departure time, scheduled departure time, airline carrier, flight number, air time, origin airport, destination airport, was the flight cancelled, reason for cancellation and so on. The data provided starts from the year 1987 and goes up to 2008. For this project, only year 2005 will be analyzed. The zipped file for all years can be downloaded [here](http://ww2.amstat.org/sections/graphics/datasets/DataExpo2009.zip)

## Main Findings
1. This analysis found that the hour of day, the day of the week and the month of the year have an effect on arrival and departure delays. We find that the later a flight is during the day, the more delays we can expect. Delays generally pick up around 5 PM and get longer towards the end of day. The best times to avoid flight delays is 6 AM, where in fact you can expect to arrive or depart earlier than scheduled.
2. Next we find that Saturday nights are the worst times to catch an American Airlines flight departing from Dallas Fort Worth Airport, where you can on average expect a delay of 40 minutes.
3. Finally, the most delays occur during the months of June, July, August, December and January; with July experiencing the longest delays

## Resources
Some visualization ideas came from [Shawn P Emhe II](https://shawnemhe.github.io/udacity-data-analyst/p6/python_eda/python_eda.html) GitHub Repo
