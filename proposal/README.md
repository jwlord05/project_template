Divide & Conquer
Team Members: John Lord, Jonathan Coad, & Hsiao-Chin, Chiang
Project Title: Analyzing how to Decrease Commuters Transition Time While Utilizing Shared Resources
A smart city, or "eco-city" promotes the health and prosperity of its' citizenry. The creation of green space within an eco-city is possible by eliminating vehicular traffic in urban areas. This idea of transforming areas into green space has several potential benefits. 
"	Reduced carbon emissions mean that the air will be less polluted and cleaner for pedestrians 
"	The removal of independent vehicles on the roadway increases the safety levels of the street
"	An overall boost to public health both mentally and physically and increased social awareness                
                                                                                                       (Kuo & Sullivan, 2001; White, 2013)
Cities outside of the United States have already implemented these "car-free" zones and the results speak for themselves. Paris, France has already reduced overall emissions by thirty percent. This was done by reducing the number of cars on the streets and converting those spaces to green space. Hamburg, Germany has plans to create a green network by reducing automobiles and crowded traffic systems and replacing them with parks. And Chengdu, China is promising their reduced traffic in urban areas will decrease traffic stalls, and they enable pedestrians to complete their commute in only fifteen minutes. (References?)
In fact, there appear to be almost no negative aspects of car-free urban areas. The question then is, for cities in the United States of America that were built around the extensive use of vehicular traffic; can modern resources be used efficiently to effectively transition urban city space into green space. 
Project Goal: We wish to observe what the best, or average travel time may be for commuters to get through public, urban city property while utilizing shared resources. 
We believe that our goal can best be accomplished by using a continuous-based simulation. Specifically, we will use AnyLogic to model the city space and use human-like entities as our agents. Our city space will be representative of an urban city block that has been turned into green space. The continuous-based simulation was chosen because all agent choices are randomized (therefore not agent-based), and nothing within the simulation changes over time (therefore not discrete-event based). The model will need to be simulate multiple times to produce the average wait time for commuters as they travel from point A to point B. 
Requirements: 
Overcrowding, pollution, and lack of recreation are all problems that a major city must face. To help alleviate these issues, green space(s) have been implemented, and somewhat successfully. This paper proposes the following experiment to see how well cities can transition from their current situation into eco-friendlier green zones. Requirements are as follows:
1.	Given an urban area of size (n), wherein all the streets are closed to public traffic

2.	Given public transportation is available (scalable) in the same area
a)	Public tram with variable routes through the area

     i. Tram includes three cars (can vary)
    ii. Tram carries up to twenty-five passengers per car
   iii. Tram travels fifteen mph

b)     Public bike rentals available at various locations through the area
            i. Bikes can only carry ONE passenger
           ii. Bikes travel at a constant of five mph
          iii. Bikes can only travel one path.

c)     Public bike/pedestrian paths delineated through the area
            i. Pedestrians can only travel on pedestrian area
           ii. Pedestrians travel at two and a half mph

3.	Commuter debarkation points are set; no more than four

4.	Public interaction random AND set - population (p) size feasible for area (n) of consideration
a)	Random population living within urban area traversing from point A (home) to point B (work)
b)	Random population commute to debarkation point (parking garage) and traversing from point A (parking garage) to point B (work)
c)	Random population utilizing green space with no start or end destination 
d)	All population randomly utilizing one of three modes of transportation
    i. Walking paths
   ii. Bike lanes (rental bikes)
  iii. Public tram

5.	Population movement times set
a)	Small percentage (10%) of population movement constantly between 6:00 a.m. and 11:00 p.m. - represents miscellaneous population
b)	Random percentage (15-30%) of population movement between 9:00 a.m. and 11:00 p.m. - represents population utilizing businesses and green space
c)	Working population (55%) movement between 6:00 a.m. and 9:00 a.m. (morning), 11:30 a.m. and 1:00 p.m. (lunch), and 3:30 p.m. and 6:30 p.m. (evening)

6.	All buildings within area (n) identified
a)	Office buildings
b)	Residential buildings
c)	Restaurant/entertainment building

7.	Must compute and report average time for commuters to traverse from point A to point B
