# Ford GoBike Data Exploration

## Dataset

The data used in this project is for Feb 2019. The data consisted of ride durations and attributes of approximately 183412 rides. The attributes included start time, end time, user type, birth year, start station , end station. The dataset can be found in the project details tab of Communicate Data Findings project under Data Visualization module.


## Summary of Findings

In the exploration,Duration_sec has a long tailed distribution with lot of durations at lower end and a few at higher end. When plotted on a log scale, the duration has normal distribution with peak around 500 seconds. I was interested in knowing if age could have an impact on ride duration but there seems to be no correlation between them.
Other important findings that I came across are:
* Most of rides are happening between 6am - 6pm.That's how it mostly should as more people are their on the road on different avenues of commute.
* During weekdays more rides are happening which also totally makes sense.
* Subscriber are more using bikes than customer.
* Males are also using more bikes than other genders 
* Interestingly, although more subscribers are riding on go-bikes but their average ride duration is less than those of non-subscribers.For subscribers their average duration is 613 sec and for non-subscribers its 1125 sec.
* 25-35 years of people are mostly riding the bikes with males predominant in gender section.

## Key Insights for Presentation

For the presentation, I focused on answering the questions posed while starting this project.
These are:
* When plotted on a log scale, the duration has normal distribution with peak around 500 seconds.
* Subscriber base is riding more bikes than other customers
* 25-35 years of people are mostly riding the bikes with males predominant in gender section.
* During weekdays more rides are happening which totally makes sense.
* We observed that weekdays has more bike demand over weekends and mean riding duration in weekends is more than weekdays. Now i further broke it into hour of day and day of week and applied a heatmap to it As seen from heat plot weekends have more mean trip duration spread throughout the day. However for weekdays there is a spurt in demand for few hours in the mornings and evenings