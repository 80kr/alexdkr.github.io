---
layout: page
title: Coffee Shops
permalink: coffee
---

We've just come across the opportunity to open a coffee shop in New York!

How can we provide suggestions for locations to place a new coffee shop?

This post details the data analysis performed for the selection of prime locations for coffee shops in NYC.  
  

### Summary
Our team executed the following approach to provide recommendations for prime locations for coffee shops in NYC.  
  
1. Analyzed MTA data and coffee shop traffic  
2. Analyzed U.S. Census Data  
3. Estimated demand populations  
4. Ranked locations by demand  
  
Feel free to skip down to the very end to find out the results!  
  
  
### MTA and Coffee Shop Traffic Analysis  
MTA data includes the number of riders entering and exiting the stations in 4-hour increments. We decided that riders exiting the station would be good potential customers for the new coffee shop.  

Based on coffee shops that are already established in the area, we noticed that coffee shop traffic was highest around 11AM to 3PM.  
  
![an image alt text]({{ site.baseurl }}/images/1_coffee/0_times_for_coffee.png "Coffee Traffic During the Day")  

We noticed that the following stations had the highest number of riders exiting the MTA stations.  
  
![an image alt text]({{ site.baseurl }}/images/1_coffee/2_2016_mta_exit_data.png "2016 MTA exit data")  

We also wanted to include the amount of growth in number of riders from 2015 to 2016.  
  
![an image alt text]({{ site.baseurl }}/images/1_coffee/3_2015_2016_growth.png "2015-2016 exit growth")  
  
We combined both the list of stations with the highest number of exiting riders and the list of stations with the most growth in number of exiting riders. This resulted in 24 stations that had both attributes, high traffic volume and high growth in traffic volume.  
  
We now have a sense of MTA station locations with with high traffic volume and high growth in traffic volume.  
  
### U.S. Census Data  
It was found that single people with post-graduate degrees that earned more than $75k are more likely to frequent coffee shops.  
  
Using this knowledge with U.S. Census data, we now have population data based on location, education, income, and marital status.  

### Estimated Demand Populations  
MTA rider traffic data and U.S. Census demographic data were combined to provide an estimated demand population.  

The demand population is described below.  

![an image alt text]({{ site.baseurl }}/images/1_coffee/4_estimated_demand_population.png "Estimated demand population")  
  
Well-educated people and high earners are more likely to frequent coffee shops, even more than singles. The previous formula takes this into consideration and averages the populations based on their likelihood to frequent coffee shops.  
  
We also wanted to consider coffee shops already established in potential locations for the new coffee shop. The number of coffee shops within a 4-block radius of potential locations were tallied.  

![an image alt text]({{ site.baseurl }}/images/1_coffee/5_competitive_coffee_analysis.png "Competitive coffee analysis")  
  
Now it is possible to provide an estimated demand population per coffee shop in each location.  

![an image alt text]({{ site.baseurl }}/images/1_coffee/6_estimated_demand_per_coffe_shop.png "Estimated demand per coffee shop")  
  
MTA station locations from the MTA study are shown on the very left.  
  
Populations that fit the desired demographic are shown in the middle 3 columns. The estimated demand population is calculated from these 3 columns.  
  
Competitive coffee shops located near the MTA stations are tallied in the Competitive Cafes column.  
  
The final column, Demand per Cafe, is delivered by taking the estimated demand population and dividing that by the number of competitive cafes to provide a final metric that describes demand population per cafe.  
  
### Recommended Coffee-Shop Locations  
We can now recommend prime locations with the most amount of demand per cafe.  
  
![an image alt text]({{ site.baseurl }}/images/1_coffee/7_prime_locations_for_coffee_shops.png "Prime locations for coffee shop")  
  
Based on our study, we recommend opening a coffee shop near the following stations.

1. 167th Street
2. 86th Street
3. Crown Heights- Utica


<!-- - _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

 --><!-- ```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
``` -->
