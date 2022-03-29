# Overview of the Project :
This project is an analysis of New York Citi Bike data, using data visualization tools to explore the viability of a bike-sharing business in Des Moines.
The NYC data  analyzed to show trends for times of day, days of the week, gender, starting locations, and ending locations. This analysis required analysts to used Pandas to change the 'tripduration' column from an integer to a datetime datatype. Using the converted datatype, visualizations were created to show the length of time the bikes are checkout for all riders and genders, show the number of bike trips for all riders and genders for each hour of each day of the week, show the number of bike trips for each type of user and gender for each day of the week, top starting locations, and top ending locations.

# Result :

[Link to dashboard](https://public.tableau.com/app/profile/shrilaxmi.hegde4270/viz/NYCCitibikeAnalysis_16485130724590/NYCCitibike?publish=yes)

 Dataframe:
 
![citibikedataframe)](/Resources/citibike_dataframe.png) 
1. Number of records by trip duration. 

3. Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 20  to 30 minutes  and that the bigger majority of rides are less than one hour. We also see that this pattern is the same regardless of gender.

![CheckoutTimeforUsers)](/Resources/Checkout_Time_forUsers.png) 

2. Trips by weekday per hour, Heatmap clearly shows in evening useage 4 to 7 pm  is the more then morning and weekend.
 
![Tripbyweekdayperhour)](/Resources/Tripby_weekday_per_hour.png) 

3. The 'Trips by Gender (Weekday per Hour)' heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.
 
4. The 'User Trips by Gender by Weekday' heatmap demonstrates the following points: Here two types Users, ***Customer*** and  ***Subscriber*** and also divided by gender.
Customer usage Male,Female and Unknown here not much difference in  weekdays and weekend. But this map showing subscribers are *** Male*** user  most of the weekdays used other then Female and unknown. 

## NYC Citibike Dashboard :
 
![NYCDashboard)](/Resources/NYC_Dashboard.png) 

## NYC Citibike Stroy :

![NYCStory)](/Resources/NYC_Story.png)


# Summary:

The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender. Utilization rates can now be predicted based on time of day and location. Weekday useage is heavily concentrated around the morning and afternoon commute. Weekend useage is more evenly spread through the day.

Two Additional maps 
   1. Top Ending Location.

 ![Topendinglocation)](/Resources/Topending_location.png) 

   2. Bike Repairs.

![BikeReparis)](/Resources/Bike_Reparis.png) 
