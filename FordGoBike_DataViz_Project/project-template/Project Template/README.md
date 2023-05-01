# Analysis of Factors Causing Long Trips in San Fransisco

## by Shadrack T. Adeyemi


## Dataset

This dataset contains information of over 183,000 bike rides of a bike-sharing system in the greater San Fransisco Bay Area. This data set has information about individual rides during the month of February, with features such as durations, member gender, customer type, amongst others.


## Summary of Findings

In this exploration I found that, Weekdays and weekends have different bike riding patterns. On weekdays users are most frequent between 8-9 AM and between 5-6 PM, while on weekends bike rides are most frequent during 1-3 PM. Also when I analyzed the days of week, the highest frequency of bike rides occur on weekdays, with Thursdays having the highest frequency of bike rides than any other day. Interestingly, Customers take significantly longer rides on average than subscribers, despite being only 9% of the total users. With an average bike ride duration of 10 minutes, customers take on average 15 minutes per bike ride, whereas subscribers ride for 9 minutes on average.


## Key Insights for Presentation

For the presentation, I focused on some factors that affect the long trips of bike riders in San Fransisco. The main features of interest are the time and day of the week, the user types and the gender of members.

I started by plotting the trip frequency of the start hour and the start day. To investigate further, I plotted a facetgrid of the trip duration for every start hour at each start day, this was helpful as it give a different insight into the plot. I then went on to plot a histogram to show the frequency distribution of the average trip for each member gender. 