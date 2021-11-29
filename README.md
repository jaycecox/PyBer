# PyBer_Analysis

## Purpose of the Analysis
Using Python and Panda, create a summary DataFrame of the ride-sharing data by city type. Then create a multiple-line graph using Matplotlib, that shows the total weekly fares for each city type. 

## Results:

The majority of ride sharing occurs in the urban areas, where the lowest amount of ride sharing happens in rural areas. 

![image](https://user-images.githubusercontent.com/92542382/143794423-5038c57f-b878-46d9-b7b0-69918fa46e9a.png)


The average overall fare is $26.75 with minimum fare of $4.05 and maximum fare of $58.55.  As you can see the distribution of fares is relatively symmetrical with a slight skew to the right. 

![Histo](https://user-images.githubusercontent.com/92542382/143794686-e60a4b6c-6d38-414c-a18b-8f866d56fd0b.png)


![Stats](https://user-images.githubusercontent.com/92542382/143794473-5c98cabd-3f34-43b5-b590-385ed78d9ab2.png)


Overall, the urban city types have higher 'Total Rides', 'Total Drivers', and 'Total Fares'.  Rural city types have the lowerst 'Total Rides', 'Total Drivers', and 'Total Fares'. 

We notice that the rural type cities have the highest 'Average Fare per Ride' and highest 'Average Fare per Driver', whereas urban type cities have the lowest 'Average Fare per Ride' and 'Average Fare per Driver'.  This suggests that rural areas tend to have longer ride times than urban areas, as the longer the ride the higher the trip fare. 

Suburban city types are in the middle for are metrics measured. 

![DataFrame Summary](https://user-images.githubusercontent.com/92542382/143794529-42ccf763-bb73-4d3f-8737-fcab6be2ec86.png)


As you can see below, the amount of fares are steady for each city category, except in April where the weekly fares for Urban and Suburban cities drop condsiderably.  This drop for both types return to pre-April levels as we move later in the month. 

![Line Graph](https://user-images.githubusercontent.com/92542382/143794577-26304095-2d24-4556-9df5-fed2501aed28.png)


## Summary 
To address the disparities among the city types I recommend:

* In order to bring 'Total Fares' for rural and suburban areas up, I recommend increasing the nummber of drivers for these areas. This will increase the 'Total Rides' in these areas and thus increase the 'Total Fares' for the rural and suburban areas. 

* In order to increase 'Average Fare per Ride' and 'Average Fare per Driver' for urban areas, I recommend increasing the fare cost per ride. 

* In order to increase 'Average Fare per Driver' for urban areas, one could decrease the amount of drives on the road. The number of drivers for the urban area greatly outways the number of total rides. Therefore if we decrease the number of drivers, we should have the same amount of rides leading to the same 'Average Fare per Ride', however the 'Average Fare per Driver' will increase as there would be less drivers to compete with each other. 
