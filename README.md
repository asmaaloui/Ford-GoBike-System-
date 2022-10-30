# (Ford GoBike System Data)
## by (Asma Aloui)


## Dataset

>Data consists of info about trips taken by service's members, their types, their age, their gender, stations of starting and ending trips, duration of trips etc.

>documentation available here : https://www.kaggle.com/datasets/chirag02/ford-gobike-2019feb-tripdata
This data set is taken from https://www.fordgobike.com/system-data and represents trips taken by members of the service for month of February of 2019.

## Summary of Findings
>Univariate exploration: the number of trips gradually decreases when the weather becomes colder. During the day, there are more trips in the morning and afternoon than the night. Also, there are more trips during the weekdays and less trips during the weekends. It makes sense that there are more subscribers than customers pricing. For the gender groups, the number of trips in male riders is 3 times more than the number of trips in females. It needs to be investigated more. Most of riders are 30 to 40 years old and the duration of trips is around 650 seconds.

>Bivariate exploration: there is a slightly negative correlation between age and duration of trips. After separation the top 8 stations, half of stations have the most trips in the morning and another half of stations has the most trips in the afternoon. Weekdays have the most trips than weekends. In each month, besides July (the program just launched), from August to October, the number of trips gradually increases and it decreases in the winder (November and December). Biking is definitely correlated with the weather. It needs more weather forecast data to support the assumption.

>Multivariate exploration: separating user types, customers and subscribers, gives more insights. Customers like to bike during the weekend and in the summer. Also, the number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers. Both of them have the longest trips at night and in December. I am guessing because of holiday seasons but not sure about why night trips are longer so still need more data to prove my point.
## Key Insights for Presentation

>The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. For customers, there are more trips in the weekends and in August. They also have longer trips. On the other hand, for subscribers, there are more trips during the weekends and the number of trips is influenced by the climate change. Thus, collecting more information individually from these two user types is important for the future analysis.