# Ford GoBike Trip Data Exploration
## by Chidinma Ononuju


## Dataset

The Ford GoBike dataset used contains 183412 observations gathered about individual rides made in a bike sharing system covering the greater San Francisco Bay area in February 2019. There are 16 features present in the dataset, with main feature focus on duration of the trip, user type, days most trips were taken, gender, age and if gobike was used for all trips.


## Summary of Findings

After performing an exploratory analysis on this dataset, I discovered a number of things worth noting.

1. More men have made trips with the ford bike in 2019
2. The trips in the dataset provided only covered trips taken in the month of February. The occurances of trips in March were trips that started on the last day in February and ended on the first of March.
3. Most of the users in the dataset provided are subscribers, however, we discovered that on average, customers took longer trips than actual subscribers.
4. Majority of the users do not use fordbike for all their trips
5. People usually start and end trips on the same day.
6. Thursdays seem to be the day of the week having most trips taken, followed by Tuesdays while Saturdays and Sundays have the least trips taken, however, longer trips were taken on Saturdays and Sundays.
7. The average age of users was 34 years.
8. The average trip took about 669 seconds, which is approximately 11 minutes.

For the duration variable, a log transformation was performed on the scale because of the large range of values present. The distance column was calculated the longitude and latitude columns provided and we could see a positive correlation between the duration and distance covered which clearly shows that longer time is taken to cover father distances.
The Age column was derived by subtracting the member_birth_year column from 2019 since the scope of our data was gathered in the year 2019.

## Key Insights for Presentation

For this presentation, I focus on when most trips are taken in terms of days in the week, how long the average trip taken was, if it is dependent on the user type or the gender as well.

I show the duration distribution as well as the age distribution in the dataset. 
Next I move to showing the distribution of the categorical variables and then it's relationship with the numerical variables, ié, the age and duration distribution.
