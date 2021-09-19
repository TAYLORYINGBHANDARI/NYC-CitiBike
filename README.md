# NYC Citi Bike sharing

A bike sharing analysis and Data Exploration of New York Citi Bike data. 
## Resources

- Data Source: converted 201908-citibike-tripdata, 201908-citibike-tripdata.csv

- Language&Software: Python, Jupyter Notebook, Tableau Public 

## Project Overview
Perform an data analysis of bike trips during the month of August in NYC. This will help and convince  investors that a bike-sharing program in Des Moines is a solid business proposal.

### completing tasks
* Change Trip Duration to a Datetime Format.
    1. Using Python and Pandas functions,convert the "tripduration" column from an integer to a datetime datatype to get the time in hours. 

    2. export the DataFrame as converted 201908-citibike-tripdata CSV file without the index column.

* Using Tablew to create Visualizations for the Trip Analysis.

    How long bikes are checked out for all riders and genders.
    How many trips are taken by the hour for each day of the week, for all riders and genders.
    A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

* Create a Story and Report for the Final Presentation


## Results
### New York Citi Bike data visualizations for August 2019

![image](https://user-images.githubusercontent.com/85265816/133943753-a6a49f28-befa-42a1-9537-1064f5908ec4.png)

- There were over 2.3 million rides for the month of August 2019.
- 81% of the users were subscribers. Majority users are males.

#### Average Trip Duration By age
![image](https://user-images.githubusercontent.com/85265816/133943771-eb6a79d9-e98e-423e-84cb-32716e581ff1.png)

- There is a wide range of the age of the users. Younger users tend to use the service for longer rides.

![image](https://user-images.githubusercontent.com/85265816/133943810-2c9f1d6e-3f5b-428f-b07b-8160892efc85.png)
- In NYC, the Top Starting Location are also the Top Ending Location for users to finish their riding trip.
- Top ride locations are in the most touristic and busy areas, as we see here in Manhattan.


![image](https://user-images.githubusercontent.com/85265816/133943824-28efdfbb-2127-4a95-b367-3e20506956de.png)
- Most of the bike checkout within one hour,most check times for user are 6 minutes.All genders share almost the same checkout timeframe range.


![image](https://user-images.githubusercontent.com/85265816/133943837-0db2fb57-340d-4e5a-a2b8-75f8eeb14848.png)
- During weekdays,most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM. Weekend rides are highest from 10:00 AM to 7:00 PM



![image](https://user-images.githubusercontent.com/85265816/133943854-73db8b2d-8810-40c3-924a-8cebac8a8e14.png)
![image](https://user-images.githubusercontent.com/85265816/133943966-cb2dd12f-073d-4de4-bcad-73b57b48f116.png)

- Trips by Gender. Male users use more during rush hours. The peak usage day is Thursday
- Trips by gender by weekdays. Male subscribers uses CitiBikes more obviously. THe most  peak hour is 8am and 5 pm.The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.


## Summary

For the data provided, it appears that most CitiBike Users in NYC subscribed their bike renting service.There are more male custmer than others.The top start and ending areas are the same,all happens in the most touristic and busy areas. Users use more during weekdays.Peak day is Thursday. The peak usage occur daily at 8 am and 6 pm.The CitiBike is a very convient and popular transportataion method for short distance travel.All those analysis implied that the bike service is an alternative transportation tool for workers who need to commute during office hours.

However, I thnk our data is limited. We need to find more date to compare bike sharing date in other month. Also, find if there is some impacts by weather by analyzing weather data and bike sharing data.








