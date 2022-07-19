# Airlines Delay Storytelling
Among the many problems faced by airlines and carriers in the United States, flight delays are a serious, widespread problem. 
A delay may be caused by airline operations, air traffic congestion, weather, or air traffic management actions

The project is based on airline delays in the US and it is a capstone project for the #30DaysOfLearning program

The project focuses on analyzing the data and building a stunning storytelling dashboard using PowerBi

## Data Source
Link to the dataset used https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay


With the original dataset, the aim was to predict whether a flight would be delayed. However, my task is to 
analyze this data and tell a story about the entire flight experience.

The Airlines dataset has 539,383 rows and 9 different features column

The different Feature names and description are:

##### Id: Serial No

##### Airline: Different types of commercial airlines

##### Flight: Types of Aircraft

##### Airport From and Airport To: code attributed by IATA to identify the source and destination airport

##### DayOfWeek: Week day of the flight

##### Distance: distance

##### Time: Time Taken to reach the destination

## Data Transformation
Data was transformed and prepared using PowerQuery editor.

Ensuring the right data types

Creating new measures (total flight distance, total flight duration, average flight distance, count of delayed and non-delayed flights) 
The percentage of delayed and non-delayed flights, etc.

Extraction of flight location for the 'airport from' and 'airport to'

## Insights
![Card_summary_#30](https://user-images.githubusercontent.com/40744059/179220523-732f6d1a-267b-4131-b59c-19a7e015f24d.png)

A summary of the overall card can be seen above in order to determine the total flight distance, total flight duration, average time 
and distance, as well as 45% of the flight being delayed and 55% not being delayed.


![Airline summary](https://user-images.githubusercontent.com/40744059/179222139-2f702487-67b1-49bb-b31e-e6669160b11e.png)

...WN,Southwest Airline has the highest delayed flight of all airlines compared to flights not delayed


![weekday summary](https://user-images.githubusercontent.com/40744059/179227212-98181483-e2b8-44d2-83fa-82fc77236cee.png)

Among the days with the most delayed flights, Tuesday has the highest number

More insight can be derived by interacting with the dashboard using the 'Location from' and 'Airlines' slicers.


## Conclusion and Recommendation

Consequently, passengers lose time, miss opportunities for business or leisure, resort to higher lodging costs, and are stressed. 
Airlines are forced to consume more fuel to make up for the delay, which negatively impacts the environment. In addition, passengers have a low level of trust in airlines.

In conclusion, airline companies should take adequate measures to plan flights accordingly and reduce the impact of flight delays.

![DOCUmentation3](https://user-images.githubusercontent.com/40744059/179188213-2edd66dd-a779-48c5-bb1b-ece85a877059.png)
![DOCUmentation](https://user-images.githubusercontent.com/40744059/179188194-2c59c3a5-e343-457d-8d88-8b9670ab56a4.png)
![DOCUmentation2](https://user-images.githubusercontent.com/40744059/179188205-222f4b40-0d24-47f2-8c18-bb46dd0fa730.png)
