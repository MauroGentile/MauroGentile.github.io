---
layout: post
title: Project Benson, first assignment during the Data Science boot camp at Metis
---

# Project objectives

As first assignment at Metis, we developed a set of recommendations for Women Yes Woman Tech (WYWT) for the Gala event organized for the month of July 2018.

My team and I distinguished the project goal in three main objectives:
1. building awareness for Gala
2. getting attendees  
3. reaching potential contributors to the organization

In order to maximize the effectiveness of a marketing plan, it is important to frame the activity according to:
1)	The strategic objective to reach the most appropriate target
2)	Maximum exposure to targets

We therefore have looked at the MTA turnstile data combined with other data sources, like census data, with the purpose of providing WYWT marketing team with insights to plan street team activity focused on participation in the gala in the short term, and awareness and fundraising in the long term.

We ended up recommending different lists of MTA stations where to concentrate the marketing effort, depending on strategic goal.

Once defined where to implement the street activity, we gave to the analysis a step further to understand when to do it in order to make it as effective as possible.

We therefore looked at the time distribution of passengers’ flow at each single station we recommended, noticing that such a flow is not uniform in time, neither by weekday nor by hour ranges.  

We also noticed that within the same station, turnstiles belonging to different control areas, which are generally associated with different bounds in the station, have a completely different time distribution of flow. 

As a consequence, to maximize the exposure to the predefined targets, it is crucial to plan the team activity and dimensioning based on this data.

In what follows, we first will have a look to the criteria used to build the 3 different lists of stations according to the strategic goal to achieve. We then analyse 1 station from each list to show how to plan and dimension the team activity based on a non-uniform time distribution of flow thus making the effort more effective

## Objective 1: building awareness
To build awareness, we choose the ten most trafficked MTA stations as places where to develop the street marketing activity. 
 
Assuming that the Gala takes place at mid-July 2018, we analysed 2017 MTA data on a 4 weeks period, from mid-June to mid-July to take seasonality into consideration. 

After data cleansing aimed to treat duplicates, outliers and errors and to manage counter resets and inconsistencies, we built a list of the top 10 stations with highest traffic as shown in the figure below.



   
   


***

![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/top%2010%20stations.png "Top 10 trafficked MTA stations in NYC")

***





## Objective 2: getting attendees for Gala 
To foster the participation, we thought that universities were the places where to concentrate our effort for the higher probability to find tech-savvy and tech-passionate people.
We ended up with the following list:
*	116th St. Columbia
*	8th St. NYU
*	68th St - Hunter
*	Astor Pl.



## Objective 3: reaching potential contributors to the organization 
For the fundraising objective, we looked at the census data and picked up zip codes of the wealthiest areas in NYC and tech companies. We then choose those station located in areas with the highest average income including, among others the following:

*	86th St.
*	Franklin St.
*	Chambers St.



The 3 above-mentioned objectives overlap each other meaning that, for instance, while mainly looking for building awareness, marketing activity in heavily trafficked MTA stations can also foster participation to the gala and possibly bring fundraising. In addition to that, stations from different lists are often very close each other as shown in the map below

***

![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/Picture1.png "Tech and uni")

***

# Dimensioning the activity plan on time distribution of flow
Regardless the objective, by analysing the MTA data, not unsurprisingly, we soon discovered that the flow of people transiting is very much dependent on both the day of the week and the hour range in the day as shown in the below figures.

***

![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/by%20day.png "Flow by day")

***

***

![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/by%20hour.png
 "Flow by hour period")
 
***
 
In order to optimize the marketing effort, both the activity time plan and team dimensioning should be based on weekday/hour flow data.

To better show the idea, we will now go through case studies, one per each list we built before. These are to be considered as show examples. The same analysis has to be replicated for each of the recommended MTA stations.



# Case studies

## CASE STUDY 1: Maximizing Participation – 116th St.
As first case, we will focus on 116th ST station, which is where Columbia university is located, as an example of station where to look for participants to the event.

As shown in the below graph, the flow of people is concentrated in the mid-week days and in the late afternoons. This is when we should intensify the marketing activity, dimensioning the team accordingly.


***

![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/116%20th%20over%20all.png "116th overall flow")
 
***


## CASE STUDY 2: Reaching potential contributors: 86th ST (LINE:456 station)
From the fundraising list of stations, the 86th ST will be presented as case study as an example of station where to look for potential donors. As shown in the below figure, also in this case the traffic is very dependent on the day of the week and time of the day.


***

![alt-text-1](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/86%20overall.png "86th by ca") 

***


However, this station has a further complexity: while the 116th station only have 1 single control area, i.e. one group of turnstiles through which all the flow must converge regardless the direction, in the 116th case there are 2 control areas, one for each direction of the subway. We believe this is of crucial importance to understand where to place the street team since the 2 control areas leads to different entries and exits of the subway and, as shown in the below figures, the 2 control areas have a different time distribution of the passengers flow. 

***

![alt-text-1](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/86%20by%20ca.png "86th by ca") 

***

## CASE STUDY 3: Building awareness: 42 ST Port Auth 
As third case study, 42 ST Port Auth is presented.
This is a huge commuting hub which gives us the opportunity to reach many people and to throw a window also outside the city. The ideal situation to have exposure to a huge number of people, so gaining awareness.

Also in cases of huge hubs like this, traffic is really dependent not only on time and day but also on control areas.
The first figure amonge the below ones represents the overall flow in the station. The succesive ones represnet the flow through 2 out of the 5 possible control areas at the station. We preferred to show just 2 instead of 5 to keep the presentation neat.

***

![alt-text-1](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/46%20overall.png "86th by ca") 

***

***

![alt-text-1](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/42%20by%20ca.png "86th by ca") 

***


# Next steps


We suggest bringing the activity one step further, designing a marketing plan and dimensioning both the activity and the team based on control area heatmaps.

We would also recommend increasing size of data to broaden time series making more robust from a statistical stand point



