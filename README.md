# Predicting-Bike-Rentals-In-DC
Predicting Bike Rentals in Washington, DC based on Historical Data

In many American cities, there are communal bicycle sharing stations where you can rent bicycles by the hour or by the day. Washington, D.C. is one of these cities, and has detailed data available about how many bicycles were rented by hour and by day.

Hadi Fanaee-T at the University of Porto compiled this data into a CSV file, which we'll be working with in this project. The file contains 17380 rows, and each row represents the bike rentals in a single hour of a single day.

Here are explanations of the relevant columns:

1. instant -- a unique sequential id number for each row.
2. dteday -- the date the rentals occurred on.
3. season -- the season the rentals occurred in.
4. yr -- the year the rentals occurred in.
5. mnth -- the month the rentals occurred in.
6. hr -- the hour the rentals occurred in.
7. holiday -- whether or not the day was a holiday.
8. weekday -- whether or not the day was a weekday.
9. workingday -- whether or not the day was a working day.
10. weathersit -- the weather situation (categorical variable).
11. temp -- the temperature on a 0-1 scale.
12. atemp -- the adjusted temperature.
13. hum -- the humidity on a 0-1 scale.
14. windspeed -- the wind speed on a 0-1 scale.
15. casual -- the number of casual riders (people who hadn't previously signed up with the bikesharing program) that rented bikes.
16. registered -- the number of registered riders (people who signed up previously) that rented bikes.
17. cnt -- the total number of bikes rented (casual + registered).

In this project, we'll try to predict the total number of bikes rented in a given hour. We'll predict the cnt column using all the other columns, except casual and registered. To do this, ywe'll create a few different machine learning models and evaluate their performance.
