# bikesharing

**Note:**
I worked with Puneeth N for this challenge. We followed pair-programming methodology and the code and readme were co-created.

# **NY Citi Bike Analysis**

## **Project Overview**

We are performing analysis of bike rental data in NYC. It will be used to start a similar business in Des Moines.

Data includes trip information like user type, gender, trip duration, geo location etc.

**Data Source:** 201908-citibike-tripdata.csv
**Software:** Python 3.9.7, Pandas library, jupyter notebook, Tableau
**Tableau_Public**: [NYC_Citi_Analysis](https://public.tableau.com/app/profile/aman.s.gill/viz/NYC_Citi_Bike_Analysis/CheckoutTimesforUsers?publish=yes)

## **Results**

Following is the summary of different types of analysis that was performed:

### Checkout Times for Users: 
By looking at checkout times for each ride, we notice that most trips are less than a hour.
![Checkout Times for Users](/Data/Checkout_Times_for_Users.png)

### Checkout Times by Gender: 
By looking at checkout times by gender, we notice that Male users outnumber Female and unknown genders.
![Checkout Times by Gender](/Data/Checkout_Times_by_Gender.png)

### Trips by Weekday per Hour: 
By looking at Trips by Weekday per Hour, we notice that 7-9AM and 5-7PM are busiest.
![Trips by Weekday per Hour](/Data/Trips_by_Weekday_per_Hour.png)

### Trips By Gender (weekday per hour): 
By looking at Trips by Gender (Weekday per Hour), we notice a similar trend for Male and Female genders.
![Trips By Gender (weekday per hour)](/Data/Trips_By_Gender_(weekday_per_hour).png)

### User Trips by Gender by Weekday: 
By looking at User Trips by Gender by Weekday, we notice that Thursday is most popular day for bike rentals.
![User Trips by Gender by Weekday](/Data/User_Trips_by_Gender_by_Weekday.png)

### Gender vs usertype: 
By looking at Gender vs usertype, we notice that ratio of subscribers is same for Male and Female genders.
![Gender vs usertype](/Data/Gender_vs_usertype.png)

### Top Starting Stations: 
By looking at Top Starting Stations, we notice that lower Manhattan has busiest stations.
![Top Starting Stations](/Data/Top_Starting_Stations.png)

## **Summary**

NYC Bike data shows us that target audience is Male and most bikes should be available before and after office hours. Locations near offices and business will be busiest. 

Additional analysis can be performed to see:
1. Trip duration from each locations
2. Count of trips by age