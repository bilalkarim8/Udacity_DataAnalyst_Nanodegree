# Ford GoBike System Data Exploration
## by Bilal Karim


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. It was provided as one of the data set options by Udacity and can be found on the Project Details page. The provided csv file contains 183412 records.


## Summary of Findings

I focused on identifying the best predictors of trip duration. I found that date/time variables such as the time of day and day of week were very strong predictors of trip duration. Trips on weekends were much longer than those on weekdays, as were trips later in the day as compared to early morning ones.

Another important finding was the difference in trip duration between customers and subscribers. Customers used the service for longer across the entire data set as compared to subscribers, who had predictable usage patterns during popular commute hours and had a very marginal increase on the weekends.

Trip duration and user age were negatively correlated at first, but upon further investigation alongside day of week, I found that average trip duration was actually higher for older users than younger ones on the weekends until the age of about 55. After that age, the difference in trip duration between weekdays and weekends was less pronounced.

As for the trip-specific characteristics, I found that trips to or from a transit station were shorter than those that did not involve a transit station at all.


## Key Insights for Presentation

For the presentation, I want to focus on conveying the best predictors of trip duration: the various user characteristics - user type, gender, and age, along with 'transit station trip'. I will organize the presentation as follows:
1. Introduce the trip duration variable,
2. Summarize the user characteristics found in the data,
3. Visualize trip duration by day of week, user type and gender, and by 'transit station' boolean feature,
4. Close out by describing the finding related to trip duration by user age.

I will leave out all the other interactions.

When describing the user distribution in the dataset, I will use subplots of user type, age and gender as that will form a cohesive picture of all users.