# NYC_CitiBike_Challenge

## Purpose

1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in Tableau.
3. Use Tableau worksheets to display data in a professional way.
4. Portray data accurately using Tableau dashboards.

## Overview

Des Moines requested data for a business proposal. August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines. Other data points include usage durations, peak usage times, and the key target market.

## Tableau Story

### Cleaning the Data:

Jupyter Notebook was used to change the trip duration data to a datetime field.

![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/before_transformation.PNG)

![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/after_transformation.PNG)

### Results of the NYC Citibikes Analysis:

For NYC, some trips were outside the main city center. Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Checkout Times for All Users
Checkout Times for All Users The Citibikes usage reaches a top of 3000 minutes per user. 
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/0_User.PNG)
### 2. Checkout Times by Gender
Checkout Times by Gender Males are significantly higher users than others. 
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/1_Gender.PNG)
### 3. Trips (Weekday per Hour)
Trips (Weekday per Hour) 6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends. 
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/2_Trips.PNG)
### 4. Trips by Gender (Weekday per Hour)
Trips by Gender (Weekday per Hour) Males are high users during the peak hours. 
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/3_TripGender.PNG)
### 5. Trips by Gender and User Type (Weekday per Hour)
Trips by Gender and User Type (Weekday per Hour) Males subscribers are the highest users followed by female subscribers. 
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/4_UserType.PNG)
### 6. Number of Rides per Hour
Number of Rides per Hour Non-peak hours are 1-5 am.
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/5_Rides.PNG)
### 7. Number of Rides with Bike ID
![alt text](https://github.com/harryhua2021/NYC_CitiBike_Challenge/blob/main/Challenge/images/6_Repairs.PNG)
### Summary:

    Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am. Male subscribers are the highest users and follow the traditional high use times of travel to and from work. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services.
