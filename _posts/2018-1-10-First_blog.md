---
layout: post
title: Project Benson, first assigment during Data Science bootcamp at Metis
---

# Project objectives

As first assignment at Metis, we developed a set of recommendations for Women Yes Woman Tech (WYWT) organization for the Gala event organized for the month of July 2018.

My team and I distinguished the project goal in three main objectives:
1. getting attendees for Gala 
2. build awareness 
3. reaching potential contributors to the organization.

We have looked at the MTA turnstile data combined with other data sources, like census data, with the purpose of providing WYWT marketing team with insights to plan street team activity focused on participation in the gala in the short term, and awareness and fundraising in the long term.

We ended up recommending different lists of MTA stations where to concentrate the marketing effort, depending on strategic goal


# Obective 1: building awareness
To  build awareness, we choose the ten most trafficked MTA stations as places where to develop the street marketing activity. 
 
Assuming that the Gala takes place at mid-July 2018, we analysed 2017 MTA data on a 4 weeks period, from mid-June to mid-July to take seasonality into consideration. 

After data cleansing to drop duplicates, to treat outliers, to manage counter resets, to deal with inconsistencies in line names, we built a list of the top 10 stations with highest traffic as shown in the below figure.


![alt text](https://github.com/MauroGentile/MauroGentile.github.io/blob/master/images/Benson/top%2010%20stations.png "Top 10 traffiked MTA stations in NYC")


An awareness building activity should cover a large period in time. 

FOSTERING PARTECIPATION
To foster the participation, we thought that universities were the places where to concentrate our effort for the higher probability to find tech-savvy and tech-passionate people.
We ended up with the following list:
*	116th St. Columbia
*	8th St. NYU
*	68th St - Hunter
*	Astor Pl.



LOOKING FOR FUNDRISING
We looked at the census data and picked up zip codes of the wealthiest areas in NYC and tech companies, mapping them in the below figure


 
According to the map, a selection of the chosen stations for fundraising objective contains the following stations:

•	86th St.
•	Franklin St.
•	Chambers St.



Obviously, the 3 above-mentioned objectives overlap each other meaning that, for instance, while mainly looking for building awareness, marketing activity in heavily trafficked MTA stations can also foster participation to the gala and possibly fundraising.


TIME BASED PLANS
Regardless the objective, by analysing the MTA data, not unsurprisingly, we soon discovered that the flow of people transiting is very much dependent on both the day of the week and the hour range in the day as shown in the below 2 figures


DAY

HOUR

As such, in order to optimize the marketing effort, both the activity time plan and team dimensioning should be based on weekday/hour flow data.

To better show the idea, in the following it we will go through 3 case studies, one per each objective. The idea is to replicate this analysis for each of the above-mentioned MTA stations.



CASE STUDIES
As first case, we will focus 116th ST station, which is where Columbia university is located. This is representative of the list of stations to foster the gala participation.

As shown in the below graph, the flow of people is concentrated in the mid-week days and in the late afternoons. This is when we should intensify the marketing activity, dimensioning the team accordingly.




FOSTERING FUNDRISING: 86th ST (LINE:456 station) STUDY CASE
From the fundraising list of stations, the 86th ST will be presented as case study. As shown in the below figure, also in this case the traffic is very dependent on day of the week and time of the day.



However this station has a further complexity: while the 116th station only have 1 single control area, i.e. one group of turnstiles through which all the flow must converge regardless the direction, in the 116th case there are 2 control areas, one for each direction of the subway. We consider this is of crucial importance since the 2 control areas leads to different entries and exits of the subway. You need to know which one you want to focus the activity depending on the week day and the time of the day given that, as shown in the below figures, the 2 control areas have a different time distribution of the flow. 


As third case study, 42 ST Port Auth is presented.
This is a huge commuting hub which gives us the opportunity to reach many people and to throw a window also outside the city. The ideal situation to have exposure to a huge number of people, so gaining awareness.

Also in cases of huge hubs like this, traffic is really dependent not only on time and day but also on control areas.


In the following figures, to keep the presentation neat, we just reported the flow through 2 of the 5 possible control areas at the station.



Conclusions and next steps

In order to maximize the effectiveness of a marketing plan, it is important to frame the activity 
according to:
1)	The strategic objective to reach the most appropriate target
2)	Maximum exposure, extracted from data

As such, we looked for 3 different lists of MTA stations, one for each of our strategic objective.
For each of the selected station we then analysed the time distribution of the flow in order to find out the days of the week and time of the day in which the flow was maximum. This analysis was taken at the lowest space granularity possible, i.e. at the control area level demonstrating that the follow is not the same across them. This is important since different control area are 

As for the next steps,  we suggest to bring the activity one step further,  designing a marketing plan and dimensioning both the activity and the team based on control area heatmaps.

We would also recommend increasing size of data to broaden time series making more robust from a statistical stand point




Regardless the objective, by analyzing the 
