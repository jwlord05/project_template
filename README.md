# IDS6145(SimTech 2018) - Research Plan (Template)


> * Group Name: Divide & conquer
> * Group participants names: Chiang, Hsian-Chin; Coad, Jonathan; Lord, John
> * Project Title: How to Ace Green Space

In our proposal, we wish to model a representation of an urban, city block that is turned to green space. We look to answer whether commuters can transition through said city block in an efficient and timely manner while utilizing shared resources. We believe that transitioning cities into car free “green zones” could enhance timeliness and help reduce emissions. This idea is already in progress across the pond and we want to examine how this revolutionary idea could work in America as well.

![**Car Free Cities**](https://github.com/jwlord05/project_template/blob/master/images/qc_spark_smartcity_inline1_113015.png)

(TEASER IMAGE HERE - should wow me to read your work)




* (this Readme should "evolve" over time as you add and edit it)
* (once you are happy with it - copy it into the proposal directory, and remove the obvious sections that should be removed - Future work, etc)


## General Introduction

A smart city, or “eco-city” promotes the health and prosperity of its citizenry. The creation of green space within an eco-city is allowed by eliminating vehicular traffic in urban areas. This idea of transforming areas into green space has several potential benefits. 

•	Reduced carbon emissions mean that the air will be less polluted and cleaner for pedestrians 

•	The removal of independent vehicles on the roadway increases the safety levels of the street

•	An overall boost to public health both mentally and physically and increased social awareness    

                                                             (Kuo & Sullivan, 2001; White, 2013)
                                                             
Cities outside of the United States have already implemented these “car-free” zones and the results speak for themselves. Hamburg, Germany has plans to create a green network by reducing automobiles and crowded traffic systems and replacing them with parks. Hamburg and Oslo saw a 40 percent reduction of NO2 gas emission (Nieuwenhuijsen & Khreis, 2016). Beijing, China is testing ways to decrease smog and environmental pollution by installing large filtration systems (Phillips, 2016). In the past 3 years, American cities like San Francisco, New York, Philadelphia, and Chicago started car free movements hoping to affect climate change and the obesity crisis (Wood, 2007). 

In fact, there appear to be almost no negative aspects of car-free urban areas. The question then is, for cities in the United States of America that were built around the extensive use of vehicular traffic; can modern resources be used efficiently to effectively transition urban city space into green space. 

## Project Goal 

We wish to observe what the best, or average travel time may be for commuters to get through public, urban city property while utilizing shared resources. 

(States your motivation clearly: why is it important / interesting to solve this problem?)
(Add real-world examples, if any)
(Put the problem into a historical context, from what does it originate? Are there already some proposed solutions?)

(You should begin by introducing your topic. In this section, you should define the core terminology specific to the field, introduce the problem statement, and make clear the benefits (motivate!) of resolving that problem statement. The main difference between the ABSTRACT and Introduction sections is that the abstract summarizes the entire project, including results, whereas the introduc-tion only provides the motivation of the problem and an overview of the proposed solution.)

(I tell sutdents to answer the questions, one paragaph each to start if you are lost)

(Problem Statement. One paragraph to describe the prob-lem that you are tackling.)

(Motivation. Why is this problem interesting and relevant to the research community?)

(Proposed Solution. How do we propose to tackle this problem (that has been identified in the previous para-graphs, is interesting to the community, and has yet to be tackled by other researchers)?)

(Contributions. An enumeration of the contributions of the senior design project)

(This project makes the following contributions:)(you must have this!!)
•	(Contribution 1)
•	(Contribution 2)



## The Model

(Provide structural and behavior diagrams of the system you wish to study.) (Why is your model a good abtraction of the problem you want to study?) (Are you capturing all the relevant aspects of the problem?) (Use the model to tell us what is going on.)

(explicitly list your requirements of what the model will have and simulate for the proposal)

## Fundamental Questions
(At the end of the project you want to find the answer to these questions) (Formulate a few, clear questions. Articulate them in sub-questions, from the more general to the more specific. )

## Expected Results
(What are the answers to the above questions that you expect to find before starting your research?) (This changes from Expected (Proposal) to just Results (final report)) (you should verbally define them) (sketch a few graphs of what you are roughly going for - not the data but histogram of this, line graph of that, screenshot of an agent - use paper and pencil sketches)

## Research Methods

We believe that our goal can best be accomplished by using a continuous-based simulation. Specifically, we will use AnyLogic to model the city space and use human-like entities as our agents. Our city space will be representative of an urban city block that has been turned into green space. The continuous-based simulation was chosen because all agent choices are randomized (therefore not agent-based), and nothing within the simulation changes over time (therefore not discrete-event based). The model will need to be simulate multiple times to produce the average wait time for commuters as they travel from point A to point B. 

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

4.	Public interaction random AND set – population (p) size feasible for area (n) of consideration
a)	Random population living within urban area traversing from point A (home) to point B (work)
b)	Random population commute to debarkation point (parking garage) and traversing from point A (parking garage) to point B (work)
c)	Random population utilizing green space with no start or end destination 
d)	All population randomly utilizing one of three modes of transportation
    i. Walking paths
   ii. Bike lanes (rental bikes)
  iii. Public tram

5.	Population movement times set
a)	Small percentage (10%) of population movement constantly between 6:00 a.m. and 11:00 p.m. – represents miscellaneous population
b)	Random percentage (15-30%) of population movement between 9:00 a.m. and 11:00 p.m. – represents population utilizing businesses and green space
c)	Working population (55%) movement between 6:00 a.m. and 9:00 a.m. (morning), 11:30 a.m. and 1:00 p.m. (lunch), and 3:30 p.m. and 6:30 p.m. (evening)

6.	All buildings within area (n) identified
a)	Office buildings
b)	Residential buildings
c)	Restaurant/entertainment building

7.	Must compute and report average time for commuters to traverse from point A to point B


(Cellular Automata, Agent-Based Model, Discrete Event Continuous Modeling...)(Python or Anylogic) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards) (Steps in the process)

## (Other)
(change the title and amount of headers as needed) (mention datasets you are going to use) (mention base code or examples you)

## Discussion
(final only - remove whole section for proposal Readme) (What would you have done differently) (What are the contributions summerize)(what is the big take away)(what did you learn)

## Future Work
(final only - remove whole section for proposal Readme) (if you had 6 more months what would be the next steps in this project.) (What are a few questions you have now)

## References

Nieuwenhuijsen, M.J., & Khreis, H. (2016). Car Free Cities: Pathway to Healthy Urban Living. Environment International, 94, 251-262.

Phillips, B. (2016, July 20). A 23-Foot-Tall Air Purifier Gets a Tryout in Smoggy Beijing. Retrieved from https://www.nytimes.com/2016/07/21/us/a-23-foot-tall-air-purifier-gets-a-tryout-in-smoggy-beijing.html?_r=0

Wood, D. B. (2007, May 2). On the rise in American cities: the car-free zone. Christian Science Monitor, 99, 109.

(Add the bibliographic references you intend to use)  (Code / Projects / blogs / websites / papers...)
