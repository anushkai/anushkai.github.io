---

permalink: /projects/
title: "Projects"
excerpt: "Projects list"
last_modified_at: 2022-08-31T15:46:43-04:00
toc: true
search: true
list-style-type: square
font-size: 12px
---



### Evaluating Alias Analysis methods
As alias analysis is a compulsory analysis for a sturdy compiler optimization, this project is conducted to study the scope of alias analysis. 
The performance of alias analysis depends on the considered application (program), level of the optimization and the implementation of AA method. Therefore, within the first
stage I experimented varying all three factors where I took the “may” percentage as the indicator for precision. Through this, I
could bring back many insights and most importantly I could see Steens work well for lower levels of optimizations while Globals do well at higher levels. Moreover, I could see that combining
AA methods reduces the “may” percentage which suggests the precision is increased. For the second stage I planned the
experiments to observe how the performance of different optimizations change with the alias method using execution time as the indicator. Though different alias methods gave the optimal performance for different optimizations , when it comes to
execution times that optimality is negligible. That is verified through the final experiment which was performed with different AA methods against a combined optimization. Though the
advance optimizations gave a performance gain about 10% compared to basic alias analysis, optimal alias analysis is not needed in most cases as their variance is negligible.

---

### Hyper Parameter Evaluation



---
### Novatti Payment Gateway





---

### Conversation Based Indoor Localization
The aim of the system was to address the low accuracy problem of indoor positioning. Our proposition was to develop a chatbot
based system where first the useris localized through the landmark details provided by the user. In the second phase, the useris
navigated to the destination through continuous instructions. Within the development problems such as entity resolution, the
ambiguity of landmarks and flawed data had been solved using various approaches and the effectiveness has been measured from
a simulation at each step.


---

### Driver Guidance System
Based on our studies on the taxi industry in Tokyo, a taxi guidance system was built for drivers in Tokyo, Japan. Real-time data
analytic and large-scale multi-agent optimization is done for suggesting a driver with a recommendation. The complete system is consists of two main components. One is the recommendation engine which considers both current vehicle supply historical
demand and provides each vehicle with a suggested region. And the other one is the Point of Interest(POI) suggestion where
POIs with the lowest queue time for hire (upon realtime data) in the suggested region are offered to the drivers. The
implementation has been able to reduce the roaming time fortaxis by a significant percentage.


---

### Sysco Shop Ordering Platform
In the beginning, I implemented a complete prototype of a point of sale system to get a broad understanding about the
infrastructure where technologies including React, NodeJs and MongoDb were used. Then as a member of a development team
in a World’s largest food services company, I worked with a team of 8 engineers that managed some of the core services in the
Ordering platform where I involved in developing features required forthe platform and worked on fixing bugs reported within
the system. In fact, as a software engineerI had to work on a range of tech stack including Java, Spring Boot, SQL and dockerfor
the the backend development and React forthe bug fixes needed in the front end.



---

### Vehicle Clustering system for Highways
Final year project was a simulation study for development of dynamic vehicle clustering algorithms for highways, where each
clusteris driven by the leading vehicle.The vehicles where vigorously swapped among clusters to increase the convienience of
drivers while minimizing total travel time.The simutation has been done on omnetpp framework where vehicles where simulated
as independent nodes which are capable of communicating with each other.Design was implemented using C++. Two algorithms
were developed where one is centralized and otheris decentralized and did a comparison between them.

---
### Internet Traffic Shaper
This is a internet traffic shaperimplementation, which shares available internet bandwidth fairly within a hierarchical network
,upon preconfigured min.max and weight values while maintaining suitable QoS for each tcp connection.All of this has been
attained by calculating a sheduel time for each packet.Though this requirement has been tried to addressed through ”Hierarchical
fair service curve algorithm” previously, traffic shaping was not smooth and failed for higher number of connections.So a modern
algorithm was designed which dynamically shared bandwith through the hierarchy.This was supported with another development
to keep track of active/inactive state of each connection.The project was designed on software domain using C++.This was also
implemented on FPGA and total calculation time could have been significantly reduced through a parallel architecture.
---
### Hardware Accelerator for CRC Calculation
This is a project done for a local competition forfast CRC calculation which marked the best time in the competition.The
implementation was a hardware acceleration through FPGA.A new parallel algorithm was designed which generates an advanced
look up table for a given CRC key.Hardware accelertor has been used as a slave of a procesor, so processor could hand-over entire
calculation when there is a need of CRC calculation.Coded using verilog.
---
### Maze solving and colour arrow following robot
The robo was implemented for a robo competition(Robofest - SLIIT 2016) where first the robot explores and maps a maze.Then robot arrives to a given
location through shortest path.Afterthe robot exits it grabs a box and follows set of arrows using image processing and place the
box.Arduino and Rasberypie platforms were used forthe development.