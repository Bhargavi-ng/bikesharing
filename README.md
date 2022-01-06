# bikesharing

## Overview of the analysis:
The purpose of this project is to come up with a business proposal using Tableau to start bike rental business in Des Moines, Idaho based on the data from an existing bike rental business "Citi Bike" that is operating in New York City.

Tableau was used to create visualizations needed for the proposal/story.

## Results:
### Deliverable 1: Change datatype of TripDuration column data to DateTime format.
Pandas was used to achieve this. I created a new column TripDuration_dt to save the converted values.
#### Screenshot showing the new column:
![New column](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/New_TripDuration_Column_DateTime.PNG)

#### Screenshot showing the value in new column in DateTime format:
![Data in DateTime format](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/TripDuration_Datetime.PNG)

Complete code can be found here [Link to file](https://github.com/Bhargavi-ng/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

### Deliverable 2: Create Visualizations in Tableau

#### Checkout Times for Users
![Checkout Times for Users](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Checkout_Times_for_Users.PNG)

#### Checkout Times by Gender
![Checkout Times by Gender](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Checkout_Times_by_Gender.PNG)

#### Trips by Weekday for Each Hour
![Trips by Weekday for Each Hour](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Trips_by_Weekday_per_Hour.PNG)

#### Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Trips_by_Gender_Weekday_per_Hour.PNG)

#### User Trips by Gender by Weekday
![User Trips by Gender by Weekday](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/User_Trips_by_%20Gender_by_Weekday.PNG)

#### Dashboard for Summary
![Dashboard for Summary](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Summary_Dashboard.PNG)

#### Top Start and End locations Dashboard
![Top Start and End locations](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Top_Starting_Ending_Locations_Dashboard.PNG)

#### Bike Utilization - Trip Duration per Bike ID
![Bike Utilization - Trip Duration](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Bike_UT_Trip_Duration.PNG)

#### Bike Utilization - Number of Rides per Bike ID
![Bike Utilization - Number of Rides](https://github.com/Bhargavi-ng/bikesharing/blob/main/Resources/Bike_UT_Number_of_Rides.PNG)

### Deliverable 3: Create a story using in Tableau
#### Key findings:
1. Subscribers User Type forms the majority (81%) of the customers.
2. 65% of the customers (rides taken) are male.
3. Over weekends, Saturdays have more rides than Sundays.
4. During Weekdays, Mornings (Work start time) and evenings (work end time) have more rides than any other time of the day.
5. Peak trip duration is 5 minutes. And for rides in the range of 2 to 13 minutes have atleast 80k users.
6. 99% of the rides are less than 60 minutes.
7. Manhattan has the most start and end locations. Manhattan has both companies as well as tourist destinations. So this data doesn't help us identify if residents or tourists are major users.
8. There are only few bikes that get rented for longer duration when compared to the number of times a bike is rented. So there are some outliers in Trip Duration per Bike ID.

#### Link to Tableau
[Link to Tableau Story](https://public.tableau.com/app/profile/bhargavi2379/viz/Bike_Sharing_Analysis_Proposal/BikeSharingBusinessProposal)

## Summary:
The data analysis provides good insight for the investors about the demand for bikes in New York City. There is clearly demand both during weekdays and weekends and also that subscribers form the majority of the customers. One can conclude that bikes appears to be the preferred method of transportation in New York City. 

We can do some additional analysis to see if the trip duration by User type and also if a Subscriber has common starting and end locations. This will help us determine if the subscribers are residents or tourists.

Some additional analysis can be done by expanding the data to consider winter months to see how the bikes are utilized during cold months.
