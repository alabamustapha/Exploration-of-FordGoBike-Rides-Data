# Exploration of Ford GoBike System Data
## by [Mustapha Olalekan Alaba](https://twitter.com/alaba_mustapha)


## Quick Links

1. [Presentation of Findings](https://alabamustapha.github.io/Exploration-of-FordGoBike-Rides-Data/Part_II_slide_deck_fordgobike_tripdata.slides.html)
1. [Code - Notebook output](https://alabamustapha.github.io/Exploration-of-FordGoBike-Rides-Data/Part_I_exploration_fordgobike_tripdata.html)


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset used contains on data for February 2019. A copy of the dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv),

## Summary of Findings

In this exploration my focus was to find out what time of the day and day of week more rides are taking considering the duration used and how user_type and member gender affects ride time and duration.

I found out that the rides are dominated by male genders, but during the weekends other gender have an increase in percentage of the overall rides for the weekend. The peak period during the weekdays happens in the morning hour of 8am-9am and in the evening 5pm to 6pm. There is also slight increase in rides count between midday and 1pm. Although the major rides are done by the subscriber with roughly average of 10mins ride duration, the rides done by customers have higher average duration of ride for weekday and even more during the weekends.


## Key Insights for Presentation

For the presentation, my focus was on displaying insights of how the start_time, ride duration, member_gender and user_type are represented in the dataset. 

I started by creating helper features, then proceed to plot the weekdays rides count for the dataset. Also, an histogram showing how all the the rides are distrubuted accross each hour of the day was plotted.

To see gender distribution, I represented the missing gender record as Not APplicable(NA), then created a bar chart to see how much each gender took rides for the whole month. 

Further exploration was then done producing a breakdown how each gender took rides for each day of the week, this is to know maybe a particular gender rides more relatively on sepecific day of the week.

To dig futher, I explored the relationship between ride duration in minutes using violin plot, box plot and an adapted bar chart and finally presented how the user_type affects the average ride duration for each day of the week
