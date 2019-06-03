---
layout: post
title: Analysis of Ridesourcing Data to Assess Energy and Environmental Impacts in Different Metropolitan Area
featured-img: diqiu
categories: [Research]
---


#### Introduction

Transportation network companies (TNC) provide on-demand ride services through mobile device applications. The services provided by TNCs is referred to as “ridesourcing.” The increasing ridesourcing market is changing the transportation sector in major cities around the world [1] . For example, in San Francisco, ridesourcing has exceeded 15% of all intra-San Francisco vehicle trips in 2016 [2]. Uber, founded in March 2009, is now serving 631 cities worldwide, with approximately 40 million riders, 2 million drivers, and 5 billion completed trips in 77 countries. About 10 million trips are completed by Uber everyday [3]. The robust data collected by these TNCs provides an unprecedented opportunity for spatiotemporal analysis of transportation sectors around the world. In this report, we explore open-source data provided by Uber to assess the energy and environmental impacts of light-duty vehicles in major cities, as well as specific impacts of ridesourcing as a subset of light-duty vehicle trips. The goal of this study is to assess transportation energy trends from ridesourcing data, develop a first-order understanding of ridesourcing energy dynamics, and to quantify potential environmental externalities from these services.



#### Methodology
##### Estimation of total trips
In a past study, the San Francisco County Transportation Authority has analyzed the estimation of the number of ridesourcing trips in San Francisco, based on real data collected over approximately six weeks in 2016, in San Francisco. We apply the results from this previous study to estimate the hourly amount of ridesourcing trips in Washington, D.C. in 2016 [2].


##### Travel time estimation
The hourly travel time is estimated by calculating the average travel time for all Uber travels in a single hour from all initial location to all destinations in the specific city. The hourly results are shown for four quarters in year 2016 for weekdays, weekends and weekly average, individually.

Because the average travel time is static during weekends, we assume there is no traffic jam during weekends. And the additional travel time during weekdays compared to that of weekends is the wasted travel time caused by traffic jam. The hourly wasted travel time because of traffic jam is calculated by:

The daily, monthly, and quarterly average travel time is also calculated by all Uber trips in the city.

#### Results and Discussion

##### Comparison between weekdays and weekends

###### Total trips for ridesharing
The population in 2016 is estimated to be 860,000 in San Francisco, and the population in Washington, D.C. is around 681,170 in 2016. Because the needs for TNC should be positive correlative to with the population, we estimated that the number of TNC in Washington, D.C. is 79.2% of that in San Francisco in 2016. The results show time-of-day characteristics for seven days in a week in Washington, D.C.. On a typical weekday, TNCs make more than 137,000 ride-sharing trips in Washington, D.C.. About 85% trips are between 8:00 a.m. and 24:00 a.m. The total number of TNCs are 103206, 119059, 149815, 176449, 174863, and 102413, respectively for Monday, Tuesday, Wednesday, Thursday, Friday, Saturday and Sunday.

###### Wasted travel time during morning and evening peaks caused by traffic jam 4.1.3 Converting results into environmental impact
Based on the Uber driver requirements, the vehicles are light-duty vehicles from 2007 or newer. We assume during waste time, the TNC vehicles are stuck in traffic jam with idle speed. Based on the previous calculation, the average idle fuel economy 0.275 gallons per hour as the idle fuel economy for Uber vehicles. Thus, the wasted fuel due to traffic jams for all ridesourcing trips in Washington, D.C. are 126,208; 119,018; 139,741; and 137,238 gallons for Quarter 1, Quarter 2, Quarter 3 and Quarter 4 in 2016, respectively. In 2016, the total additional fuel cost during traffic jam for TNC trips in Washington, D.C. is 522,206 gallons. From EIA, CO2 emission from a gallon of gasoline is 8.887 kg [9]. We assume all TNC vehicles consume gasoline. Therefore, additional 4640 metric tons of CO2 is emissioned due to traffic jam for all TNC trips in Washington, D.C. in 2016.


###### Comparison between different quarters
Based on the Uber driver requirements, the vehicles are light-duty vehicles from 2007 or newer. We assume during waste time, the TNC vehicles are stuck in traffic jam with idle speed. Based on the previous calculation, the average idle fuel economy 0.275 gallons per hour as the idle fuel economy for Uber vehicles. Thus, the wasted fuel due to traffic jams for all ridesourcing trips in Washington, D.C. are 126,208; 119,018; 139,741; and 137,238 gallons for Quarter 1, Quarter 2, Quarter 3 and Quarter 4 in 2016, respectively. In 2016, the total additional fuel cost during traffic jam for TNC trips in Washington, D.C. is 522,206 gallons. From EIA, CO2 emission from a gallon of gasoline is 8.887 kg [9]. We assume all TNC vehicles consume gasoline. Therefore, additional 4640 metric tons of CO2 is emissioned due to traffic jam for all TNC trips in Washington, D.C. in 2016.


###### Comparison between different day of the week
With the rapid expansion, TNCs are sharing increasing amount of trips in the cities where they serve. For example, in 2016, on a typical weekday, TNCs make more than 170,000 trips in San Francisco, representing 15% of all intra-city vehicle trips [2]. Thus, the comparison of average travel time between different day of the week could reflect the traffic conditions during a week. Based on the result, the order of the traffic condition from to bad is: Sunday > Saturday > Monday > Tuesday > Friday > Wednesday > Thursday. The traffic conditions on Wednesday and Thursday are worse than other days. Thus, the employers in Washington, D.C. could consider to ask the employee to work from home during these two days to relief the traffic stress and decrease the employee’s time waste on the road.



![ambr1](/assets/img/posts/anmbr1.jpg)


##### Comparison between 7 cities around the world
The increasingly growing of population challenged the metropolitan’s infrastructure, so that transportation are widely recognized as a biggest problem and it’s now being discussed in order cope with the increasing population growth. In this analysis, based on the Uber movement data for 7 global metropolitans, we estimated the travel distance on 2016 first quarter of the whole city, as with the population data, we calculate the whole city’s GHG emission. By comparing the 5 cities’ calculation result, we could analysis the reason of the difference and people can use the result to come up with suggestions on how the city improve the GHG emission, in another word, environment in the perspectives of urban planning, geography, historical and economical. The GHG emission from ridesourcing for each city in Quarter 1 of 2016 is showed in Table 1.
![table1](/assets/img/posts/table1.png)

From the result, we can find that the order of GHG emission per person.These result make sense and could give a support that developed countries does less GHG emission currently than developing countries.
Paris did more GHG emission than other developed countries cities maybe because it using more diesel fuel vehicles. But as we can see that Manila basically
Based on the hourly average travel time during weekdays and weekends for four quarters in 2016,  the average travel time show obvious peaks during morning (7-10 AM) and evening peaks (4-7 PM) in weekdays and the average travel time stays flat on weekends. In addition, the travel time during weekdays ranges from 10.53 to 24.93 minutes, and the travel time during weekends ranges from 10.16 to 17.29 minutes. The average travel time in weekends is 16% lower than that in weekdays in 2016. We assume that the travel conditions in weekends are without traffic jam and the average travel time during weekends are used as the baseline travel time to calculate the effect of morning and evening peaks during weekdays.
Combining with the estimation of total TNC trips during weekdays in Washington, D.C., we calculated the travel time wasted in traffic jam for all TNC trips in a single weekday (Figure 1). The hourly results show similar peaks during morning and evening in four seasons. In addition, 29-32% of the waste travel time is between 7 AM to 9 AM, and 44-52% of the waste travel time is between 3 PM to 7 PM. In total, 76-81% of the waste travel time is during these two periods of time. In a single weekday, the total waste travel time during traffic jam is 423,635, 399,503, 469,061 and 460,660 minutes for Quarter 1, Quarter 2, Quarter 3 and Quarter 4 in 2016, respectively.
![fig1](/assets/img/posts/fig1.png)
Consumed same total gallon of gasoline while Paris still has much less GHG emission per person, it also shows that the developed countries did less GHG emission at this baseline. Besides, Manila is one of the most important coastal port city so that it may has more travel demand per person due to busy business and more congestion, which can cause more fuel consumption as mentioned in previous analysis, from the the data of estimated average speed. The different GHG emission per person also can be influenced by governmental car emission standards. The European Union and Japan have the most stringent standards in the world, and the U.S cars lags behind most other nations [12]. So public transportation condition, people’s travel habit, urban planning and so on.

##### Vehicle-Miles of Travel (VMT) addition sensitivity analysis
To assess the potential energy impact of ridesourcing, a simple sensitivity analysis was conducted with a linear model. A normalized VMT addition or subtraction was calculated as a function of the fraction of ridesourcing customers who would reduce their normal driving behavior. Major assumptions are built into this sensitivity analysis (see SI), but it shows how behavior plays a key role in how ridesourcing may affect total VMT per urban area, which directly affects energy consumption and environmental impact.
In Figure 2, Fred refers to the fraction of total VMT per capita reduced due to his/her ridesourcing use. fB refers to the fraction of ridesourcing customers who alter their driving behavior. The critical fB at which ridesourcing becomes a net benefit in terms of energy consumption is when the line crosses the x-axis, based on the assumption that additional VMT will directly translate to extra fuel consumption. As Fred increases, the critical fB decreases until it hits a limit of 0.5, for the case when a ridesourcing customer completely eliminates personal driving as a transportation option. This sensitivity model suggests that a shift in human behavior is essential for ridesourcing to have a net energy benefit. In this simple case, at least half of the riders would have to shift their behavior, in the best case scenario where Fred equals to one.  

![fig2](/assets/img/posts/fig2.png)

#### Conclusion
●	The traffic jam in cities could cause additional fuel cost In 2016, the total additional fuel cost during traffic jam for TNC trips in Washington, D.C. is 522206 gallons. The additional CO2 emission is 4640 metric tons.
●	The failure of public transportation could induce more traffic pressure and TNC might exacerbate this. During Quarter 1 of 2016 in Washington, DC, in total, 88,179 gallons of gasolines are wasted, which cause 783.6 tons of additional CO2 emissions. The metrorail shutdown is a possible reason for this.
●	Developed countries release less GHG emission per person currently than developing countries. And the additional CO2 emissions per year could be used to a 10E8 order of magnitudes miles travel.


##### Reference:
[1] Rayle, L., D. Dai, N. Chan, R. Cervero, and S. Shaheen. Just a Better Taxi? A Survey-Based Comparison of Taxis, Transit, and Ridesourcing Services in San Francisco. Transport Policy, Vol. 45, 2016, pp. 168-178.
[2] San Francisco County Transportation Authority (SFCTA), 2017. “TNCs Today: Data Explorer.” http://www.sfcta.org/tncstoday
[3] Uber. Uber Newsroom, 2017. https://www.uber.com/newsroom/company-info/
[4] L.P. Alexander, M.C. Gonzalez. Assessing the Impact of Real-time Ridesharing on Urban Traffic using Mobile Phone Data. Transportation Research A (In Review), 2016.
[5] Nicola Bicocchi, Marco Mamei. Investigating ride sharing opportunities through mobility data analysis. In Pervasive and Mobile Computing, Volume 14, 2014, Pages 83-94, ISSN 1574-1192.
[6] Yuche Chen, Lei Zhu, Jeffrey Gonder, Stanley Young, Kevin Walkowicz. Data-driven fuel consumption estimation: A multivariate adaptive regression spline approach. In Transportation Research Part C: Emerging Technologies, Volume 83, 2017, Pages 134-145, ISSN 0968-090X.
[7] Regina R. Clewlow, Gouri Shankar Mishra. Disruptive Transportation: The Adoption, Utilization, and Impacts of Ride-Hailing in the United States. Research Report, UC Davis Institute of Transportation Studies, October 2017.
[8] Uber. Uber vehicle requirements in Washignton, DC, 2017. https://www.uber.com/drive/washington-dc/vehicle-requirements/
[9] U.S. Department of Energy. Idle fuel consumption for selected gasoline and diesel vehicles, 2017. https://energy.gov/eere/vehicles/fact-861-february-23-2015-idle-fuel-consumption-selected-gasoline-and-diesel-vehicles
[10] U.S Environmental Protection Agency. Green Vehicle Guide: Greenhouse gas emission from a typical passenger vehicle, 2017. https://www.epa.gov/greenvehicles/greenhouse-gas-emissions-typical-passenger-vehicle-0
[11] Uber. Uber movement: Using Uber movement to understand the effects of DC metrorail service disruptions on traffic congestion, 2017. https://movement.uber.com/use-case/dc?lang=en-US
[12] F. An, A. Sauer. Comparison of passenger vehicle fuel economy and greenhouse gas emission standards around the world.  - Pew Center on Global Climate Change, 2004
[13] Stacy C. Davis, Susan E. Williams. Transportation Energy Data Book: Edition 35. Table 4.21: Car Corporate Average Fuel Economy (CAFE) Standards versus Sales-Weighted Fuel Economy Estimates, 1978–2016a (miles per gallon).
[14] European Automobile Manufacturer's Association (ACEA), 2017 http://www.acea.be/statistics/tag/category/share-of-diesel-in-new-passenger-cars
[15] Jonathan Norman, Heather L. MacLean, M.ASCE, Christopher A. Kennedy. Comparing high and low residential density: life-cycle analysis of energy use and greenhouse gas emissions. Journal of Urban Planning and Development, Volume 132, Issue 1, 10-21
[16] Australian Bureau of Statistics (ABS), 2017. http://www.abs.gov.au/ausstats/abs@.nsf/mf/9309.0
