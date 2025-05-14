Dataset used:

Ford GoBike System Data


Main findings 
Average trips in general, regardless of the rider or trip features, take 726 seconds.
The males share of trips in this dataset is more than 50% of the females.
If a user is a subscriber they tend to take more trips than customers, however, customers take longer trips than subscribers, it could be related to the cost of the trips but this is beyond the data we have here to validate.
Longer trip durations are popular between 30-40 years old.
Riders age in this dataset is more between 30-40 years old for both genders
Higher trips durations are a combination between male gender and 30-45 years old. In the case of females, 30-35 is the most popular age.
 
List of resources:
https://matplotlib.org/api/_as_gen/matplotlib.pyplot.axis.html?highlight=pyplot%20axis#matplotlib-pyplot-axis
https://www.statology.org/seaborn-title/
https://seaborn.pydata.org/generated/seaborn.boxplot.html
https://seaborn.pydata.org/tutorial/color_palettes.html
https://stackoverflow.com/questions/58610787/how-to-zoom-in-out-seaborn-boxplot-using-plt-figure-and-add-subplot
https://stackoverflow.com/questions/17604789/using-ggplot2-create-faceted-scatterplot-with-scaled-and-moved-density
 
Conclusions:
I have started with exploring the data with statistical exploration, I then came up with the questions I am going to explore in my analysis. Based on the questions, I conducted a cleaning on data to make it ready for analysis.
Then I started exploring the questions using visuals, starting the univariate questions, then bivariate, and finally the multivariate. 
During the visual exploration, I had to take some corrective action regarding the plots I used, some features needed more engineering to be more descriptive and reflective of the data. For once, I had to do some adjustments to the data (convert trip duration from second to minutes).
The conclusions finally started being clear.
The surpriseing thing is that there is no certian correlation between age and trip duration, it can be expected that as age increase duration decreases, how the duration is the longest at a certain age range, and it isn't necessarily the youngest(20 years old) among users, and then it lowers as you go up
Most trip durations are below 30 minutes, and are done by age between 25-35.

Summary:
The characteristics of riders can influence to an extent the trip duration, the mid age of 25-40 in general is a prime bracket when it comes to longer durations, males and females have a slight difference in a way that males continue to maintain longer trip at higher age. The one thing that is also a great influnce which should be kept in mind and maybe explored furrther is the fact that customers tend to take longer trips than subscribers. Which means that a huge factor for the trip duration is the fact that customers make use of their less frequent trip than subscribers who take shorter trips but more frequently.

Key Insights:

- Trip duration distribution is right-skewed, less number of trips are on the longer duration side. 
- Gender distribution is examined, looks like male are dominating the user database.
- Customers Versus Subscribers trip behavior is explored, in terms of trip duration and trips frequency. It looks like the user type influence the trip behavior.
- Age have a relation with trip duration, it is not necessarily a correlation, but there is definetely a pattern.
- A comindation of age and gender is explored to see its effect on trip duration.


```python

```
