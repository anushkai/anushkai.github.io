---

permalink: /projects/
title: "Projects"
excerpt: "Projects list"
last_modified_at: 2023-06-25T15:46:43-04:00
toc: true
search: true
list-style-type: square
font-size: 12px
---

### Privacy Preserving Machine Learning
(Mar 2023- Now)

This work is done with the focus on federated learning and improving the scalability and efficiency of personalized federated learning. I am studying several applications in federated learning including image processing and NLP which have a higher privacy concerns as well as efficiency.
- Technical Stack: python, Git

---

### Evaluating Alias Analysis methods
(Jan 2023- May 2023)

This project aimed to study the scope of alias analysis methods in LLVM and its impact on performance of overall compiler optimization. I experimented with various factors including  considered application (program), level of the optimization and the implementation of AA method and through extending that I could show combining alias 
analysis methods improved the precision. In terms of execution time, the optimality of alias methods became insignificant. Advanced optimizations provided a 10% performance gain compared to basic alias analysis, but optimal alias analysis was not crucial due to negligible variance.
- Technical Stack: C++, Bash

---

### Hyper Parameter Evaluation
(Aug 2022- Dec 2022)

The project was to study the how the hyper parameters effect on the different machine learning algorithms. A range of algorithms where studied from logistic regression, SVM to convolutional neural networks.
Intention of the study was to evaluate the tradeoff between bias and variance through accuracies and loss for the considered algorithms against different parameters.
- Technical Stack: python

---
### Novatti Payment Gateway
(June 2021- Aug 2022)

Working on Novatti payment gateway which is the legacy product of Novatti acquiring. One of the early members of Novati Acquiring and have played a full-stack role contributing to every key components of the payment gateway which followed a serverless architecture.
- Implementation of reconciliation manager and third party clients to systems such as Starrez and Manoowa to reconcile transactions.
- Orchestrating Merchant Onboarding through Step function
- End to end implementation of PayXCrypto, which is a secure and compliant real-time crypto payment system
- AWS Stack: Lambda, DynamoDb, Api Gateway, SQS, SNS, Secret Manager, App Config, S3, CloudFront
- Other Stack: Java, Spring Boot,  Javascript, Maven, React, GraalVM, PHP, Git, Bash



---

### Conversation Based Indoor Localization
(May 2020- Dec 2020)

The aim of the system was to address the low accuracy problem of indoor positioning. Our proposition was to develop a chatbot
based system where first the useris localized through the landmark details provided by the user. In the second phase, the useris
navigated to the destination through continuous instructions. Within the development problems such as entity resolution, the
ambiguity of landmarks and flawed data had been solved using various approaches and the effectiveness has been measured from
a simulation at each step.
- Technical Stack:  Python, Docker, Git

---

### Driver Guidance System
(Oct 2019- Apr 2020)

Based on our studies on the taxi industry in Tokyo, a taxi guidance system was built for drivers in Tokyo, Japan. Real-time data
analytic and large-scale multi-agent optimization is done for suggesting a driver with a recommendation. The complete system is consists of two main components. One is the recommendation engine which considers both current vehicle supply historical
demand and provides each vehicle with a suggested region. And the other one is the Point of Interest(POI) suggestion where
POIs with the lowest queue time for hire (upon realtime data) in the suggested region are offered to the drivers. The
implementation has been able to reduce the roaming time fortaxis by a significant percentage.
- Technical Stack:  Java, Docker, Git, Bash, SQL

---

### Sysco Shop Ordering Platform
(Feb 2019- Oct 2019)

In the beginning, I implemented a complete prototype of a point of sale system to get a broad understanding about the
infrastructure where technologies including React, NodeJs and MongoDb were used. Then as a member of a development team
in a World’s largest food services company, I worked with a team of 8 engineers that managed some of the core services in the
Ordering platform where I involved in developing features required for the platform and worked on fixing bugs reported within
the system. In fact, as a software engineerI had to work on a range of tech stack including Java, Spring Boot, SQL and dockerfor
the the backend development and React forthe bug fixes needed in the front end.
- Technical Stack: Java, Springboot, React, Javascript, NodeJS, Git, Bash, SQL


---

### Vehicle Clustering system for Highways
(Jan 2018- Dec 2018)

Final year project was a simulation study for development of dynamic vehicle clustering algorithms for highways, where each
clusteris driven by the leading vehicle.The vehicles where vigorously swapped among clusters to increase the convienience of
drivers while minimizing total travel time.The simutation has been done on omnetpp framework where vehicles where simulated
as independent nodes which are capable of communicating with each other.Design was implemented using C++. Two algorithms
were developed where one is centralized and otheris decentralized and did a comparison between them.
- Technical Stack: C++, Omnetpp

---
### Internet Traffic Shaper
(June 2017- Dec 2017)

This is a internet traffic shaperimplementation, which shares available internet bandwidth fairly within a hierarchical network
,upon preconfigured min.max and weight values while maintaining suitable QoS for each tcp connection.All of this has been
attained by calculating a sheduel time for each packet.Though this requirement has been tried to addressed through ”Hierarchical
fair service curve algorithm” previously, traffic shaping was not smooth and failed for higher number of connections.So a modern
algorithm was designed which dynamically shared bandwith through the hierarchy.This was supported with another development
to keep track of active/inactive state of each connection.The project was designed on software domain using C++.This was also
implemented on FPGA and total calculation time could have been significantly reduced through a parallel architecture.
- Technical Stack: C++, Git, Bash, Verilog, FPGA

---
### Hardware Accelerator for CRC Calculation
(June 2017- Dec 2017)

This is a project done for a local competition forfast CRC calculation which marked the best time in the competition.The
implementation was a hardware acceleration through FPGA.A new parallel algorithm was designed which generates an advanced
look up table for a given CRC key.Hardware accelertor has been used as a slave of a procesor, so processor could hand-over entire
calculation when there is a need of CRC calculation.Coded using verilog.
- Technical Stack: Verilog, FPGA

---
### Maze solving and colour arrow following robot
(July 2016- Aug 2016)

The robo was implemented for a robo competition(Robofest - SLIIT 2016) where first the robot explores and maps a maze.Then robot arrives to a given
location through shortest path.Afterthe robot exits it grabs a box and follows set of arrows using image processing and place the
box.Arduino and Rasberypie platforms were used forthe development.
- Technical Stack: Arduino, Robotics, 