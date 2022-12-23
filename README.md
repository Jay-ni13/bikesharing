# NYC Citi Bike Analysis
## Project Overview
Analysis of Citi Bike's public NYC information to discover applicable data and key costs for the creation of a bike-share proof of concept in Des Moines, Iowa. 

## Resources
- Data Source: [Citi Bike Trip Histories](https://s3.amazonaws.com/tripdata/index.html); file: 201908-citibike-tripdata.csv.zip
- Software: Python v3.7.13, Jupyter Notebook v6.4.8, Tableau Public v2022.4

## Results
Tableau Site: [NYC Citi Bike Analysis](https://public.tableau.com/app/profile/jennifer.cockerill/viz/NYCCitiBikeAnalysis_16717661651610/NYCCitiBikeStory)

The following story is designed to answer these questions: 
- How many trips were recorded in the month of August? What is the breakdown of short-term customers vs. annual subscribers? What is the average trip duration by age?
- What is the average trip duration for a rental?
- What are the highest-traffic locations?
- What is the gender breakdown of active riders?
- What are the peak hours for bike rentals? How variable is bike utilization? What bikes are most likely due for repairs?

<img src="https://github.com/Jay-ni13/bikesharing/blob/main/images/bike_rentals_and_membership.png" width=75%>

1. August is one of the busiest months for Citi Bike's rentals. In August 2019, there were 2,344,224 trips recorded on Citi's bikes; 1,900,359 of these rides were taken by Citi Bike's subscribers. Trips were taken by individuals of all ages, though younger individuals tended to take the rentals out for longer periods of time.

<img src="https://github.com/Jay-ni13/bikesharing/blob/main/images/checkout_times_and_trips.png" width=75%>

2. Most of the trips taken are under an hour in duration--with the most frequent rental length being 5 minutes (146,752)--but 95 trips were over 2 hours in duration. The peak times for bike rentals occur during weekday morning and evening rush hours, and midday on the weekends.

<img src="https://github.com/Jay-ni13/bikesharing/blob/main/images/top_start_and_end_locations.png" width=75%>

3. The most frequently utilized start and end locations are in Manhattan, where both tourists and workday commuters are concentrated.

<img src="https://github.com/Jay-ni13/bikesharing/blob/main/images/bike_trips_and_times_by_gender.png" width=75%>

4. While one-time customers include twice as many men as women, Citi Bike subscribers who regularly use bikes throughout the week are three times as likely to be men on average.

<img src="https://github.com/Jay-ni13/bikesharing/blob/main/images/bike_usage_and_repairs.png" width=75%>

5. With bike upkeep being an important expense to consider, regular maintainence should be scheduled for non-peak hours (2-5am), and the bikes most in need of repairs are likely the ones with the longest accumulated usage. 
- BikeIds 39570 and 17551 are overdue for maintainence.

## Summary
The prevalence of annual subscribers over short-term customers indicates that the locations for bike stations should be based on regular access for commuters in/around Des Moines' business centers--frequent tourist destinations and college campuses will also influence station location. 

Once these stations are created, usage during peak times will determine the number of bikes that should be available at each station, and maintainence will be regularly performed during non-peak hours. After beta testing the inital locations, subscribers will be able to offer input on the creation of additional stations and ammenities.

### Recommendations
Two additional visualizations that would assist the beta testing phase would be 1) the relationship of high-traffic locations to trip duration, and 2) the relationship of high-traffic locations to the gender breakdown of active riders.
