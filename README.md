# Bikesharing

## Overview of the Project
The purpose of this project was to perform an analysis of the data of a bike service in New York City. The information was obtained from the web site: *https://ride.citibikenyc.com/system-data*. The date from which the data was extracted was August 2019.

<p align="justify">The analysis and the visualizations were created using Tableau.</p>
<p align="justify">The objective was to analyze the data of the bike service in New York in order to implement the same service in another place called: Des Moines. For this it was necessary to review and graph the peak hours in which the service was used, the number of trips, among other visualizations.</p> 

## Results

The Tableau story can be seen and reviewed in the Tableau Public page: *https://public.tableau.com/views/Bikesharing_Challenge_16711345891950/NYCCityBike?:language=es-ES&:display_count=n&:origin=viz_share_link*

<p align="justify">First with the data downloaded from CityBike NYC the data type for the trip duration field had to be changed from an integer to a daytime type in order to perform the rest of the analysis later in Tableau. Pandas was used to make this change.</p> 

<img width="595" alt="0" src="https://user-images.githubusercontent.com/111388644/207955591-8629d636-f33a-4ea7-b098-c639fd114a27.png">

<p align="justify">Then, the visualizations were created using Tableau Public. After creating the graphs, a story was made. In this story 8 charts were created. 
The first one shows the peak hours in which the bikes were used in the month of August. From this visual we can gather that the top riding hours in that month were from 17:00 to 19:00 hours.</p> 

<img width="502" alt="1" src="https://user-images.githubusercontent.com/111388644/207953951-28b00ff2-7237-460f-bc6a-d1239d7fc550.png">

<p align="justify">The second image displayed below shows the Gender Breakdown. It is clear that from the three genders, the one that uses this service the most is the “male” one.</p>

<img width="505" alt="2" src="https://user-images.githubusercontent.com/111388644/207954011-87799b2e-428c-4f3e-807b-a71374a89d81.png">

<p align="justify">The third graph displays the Trips per Weekday per Hour. When looking at this chart it can be concluded that the weekdays in which the bikes are used the most are Mondays and Thursdays.</p>

<img width="502" alt="3" src="https://user-images.githubusercontent.com/111388644/207954093-4cf00b97-2297-4b82-8ccf-e8dcb8c4a5d3.png">

<p align="justify">The next visualization complements the two above since it shows the Trips by Gender per Hour and Weekday. In this graph it is easier to see that males use the biking service more than the other genders, as well as the peak time and weekday of the use of bikes.</p>

<img width="504" alt="4" src="https://user-images.githubusercontent.com/111388644/207954161-1765bafe-6d3e-475b-9377-fcd490f9613b.png">

<p align="justify">In the fifth story point the Customers and Subscribers pie chart is displayed. This visualization is helpful because it is important to know the difference between the regular users, and the people who are subscribed to the service. Is it clear that the ones that are subscribed, which are 1,900,359 annually, use the service more than just the regular customers.</p> 

<img width="499" alt="5" src="https://user-images.githubusercontent.com/111388644/207954223-abcd74c4-c19b-4138-8131-9101584e4554.png">

<p align="justify">The next visualization shows the Trips by Gender and Weekday. It also separates the data from customers and subscribers. This chart confirms that subscribers use the bike significantly more that customers.</p> 

<img width="504" alt="6" src="https://user-images.githubusercontent.com/111388644/207954289-ff0a2946-f50d-4390-876a-608ce7887998.png">

<p align="justify">The last two visualization display the Checkout Time for users and the Checkout Time for each gender. In both graphs is clear that most users bike for less than an hour. Also it is noticeable that even though males are the ones that use the service the most, all three: “unknown”, “females”, and “males” bike for les than 60 minutes.</p>  

<img width="496" alt="7" src="https://user-images.githubusercontent.com/111388644/207954348-0fec5f52-2c2c-47f8-93e7-28e4674347d3.png">

<img width="500" alt="8" src="https://user-images.githubusercontent.com/111388644/207954406-c2745c9b-2004-466b-8f4e-4c639c2e45e1.png">

## Summary
<p align="justify">With all the visualizations explained above it is safe to conclude that the population that uses more the service are males, and that the most popular days are Mondays and Thursdays. With this information the people in charge of the marketing could target the advertisement to the other two gender types to promote the use of the bike service so that the company can have more customers.</p>

<p align="justify">It is important to remark that the subscribers use this service more than regular customers. So, if this same service was to be implemented in Des Moines, the option for people of becoming a subscriber should be taken into consideration.</p> 

<p align="justify">Another chart that could be used on this analysis is one that displays the most popular locations in which the bikes are used. This could be achieved using the starting and ending spots of the latitude and longitude.</p>

<p align="justify">Finally, the second graph that could be added to the story is one that compares the user type with the trip duration. It could be expected that the subscribers trips last longer, but knowing for sure could be a nice addition to the analysis.</p>
