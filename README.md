# Communicate Data Findings - Ford_Go_Bike_Trip_Project

## By Oluwadamilare Shiji


### Dataset
>A bike sharing program called GoBike was launched in the San Francisco Bay Area in 2017. This dataset had 17 characteristics and 174,952 observations was analysed and cleaned for the month of February 2019. The dataset can be found here. [GoBike](https://www.lyft.com/bikes/bay-wheels/system-data)

>Each trip is anonymized and includes:
>- Trip Duration (seconds)
>- Start Time and Date
>- End Time and Date
>- Start Station ID
>- Start Station Name
>- Start Station Latitude
>- Start Station Longitude
>- End Station ID
>- End Station Name
>- End Station Latitude
>- End Station Longitude
>- Ride ID
>- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)


### Summary of Findings
> ####   1. Univariate Exploration: 
The trip's average duration in seconds and minutes is 11.7 minutes and 704 seconds, respectively. I was required to use the logarithm function on the duration_min variable to generate a normal distribution with a right long tail since the initial distribution of duration_min was not providing a useful visual. Thursdays were the busiest day of the week, according to time usage analyses. It has also been found that the majority of users use the services more frequently on weekdays than on weekends. The busiest hours were between 8 and 5 pm. Between 10am and 3pm, there is a significant decline in bike services users; the rise in temperature may be to factor. The hourly bike plot is a bimodal distribution.I noticed that the majority of starting stations and ending stations were same. The age distribution revealed that the majority of users were between the ages of 30 and 40. The majority of users are subscribers, according to the distribution of user types. The gender distribution indicates that most users are male. The others in the gender may be the LGBTQ people.
> ####   2. Bivariate Exploration: 
Age and duration min have a negative correlation with each other. This is because fewer people use the bike rental services as age increases. Additionally, compared to subscribers, more customers spend longer time on their duration trips. On Thursdays, the majority of subscribers and customers use the bike services. During peak times, both customers and subscribers use the bike services. female longer time on their duration trips than other gender.
> ####   3. Multivariate Exploration:
The majority of users (subscribers and customers) that use the bike services do so at four in the morning. Weekends are when users (subscribers and customers) spend more time considering trip duration than weekdays.


### Key Insights for Presentation
> Trip duration is a normal distribution after performing logarithm transformation.
> surprising that users over age 40 years uses the bike services at 4am.
> The drastic use in thehourly bike services from 10AM to 3PM maybe due to increase in temperature.
> Compared to Customers, Subscribers often have more stable duration usage pattern.
