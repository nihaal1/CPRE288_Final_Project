# CPRE288_Final_Project
CPRE 288 Final Project for Group 1 and 4 on Automated Valet parking service
[CyBot Valet Parking - Project Prpopsal.pdf](https://github.com/nihaal1/CPRE288_Final_Project/files/9169762/CyBot.Valet.Parking._.Final.Project.pdf)


Project Group 1: Cybot Valet Service
Group Members: Dana Boor, Varun Advani, Nihaal Zaheer, Kalyan Thapaliya


Problem Statement:
Problem: Vehicle owners need an alternative to manual valet services to park their vehicles.
Application Narrative:
           Businesses have attempted to alleviate the stress of vehicle parking by offering valet services. While it is convenient to have another human park your car, it is not without various disadvantages. Consumers have reported that they are distrustful of the valets that park their vehicles and are worried that their vehicles will be driven carelessly and potentially damaged. Consumers are also concerned that their valuable belongings are not safe being left in their car when a valet is driving, forcing the consumer to take their valuables with them instead of leaving them in their car [5]. Additionally, valets often expect a tip for parking your vehicle, placing an added cost on the consumer.
          The users for our application would be vehicle owners that park their vehicle in the parking lot of restaurants, shopping malls, office complexes, banks, and small businesses, who may find it inconvenient to look for a parking spot and who are not comfortable with a valet driving their car. It is also for vehicle owners who are concerned with personal safety and property damage when utilizing a valet service to park their vehicle. 
          To address these concerns, our team proposes an automated valet service. This will allow the consumer to simply drive to the entrance of a parking lot, exit the vehicle, and command the vehicle to locate a vacant parking spot and park autonomously. The automated valet service will also support the ability to recall the vehicle to the exit of the parking lot remotely, by the press of a button. The automated valet service will utilize infrared (IR) and ping sensor technology to detect surrounding objects and prevent collisions. In the event that an object is below the range of detection for these sensors, bump sensors will detect the object and stop the vehicle from continuing to drive forward. 








Research Summary:
	Valet parking is an integral part of vehicle ownership in the United States. On average, 67 percent of car owners report using valet parking services. In urban areas, this number grows to 75 percent [2]. Because of this, our team has chosen to focus primarily on the needs of vehicle owners and incorporate those needs into the design of our autonomous valet parking system. Our team’s research focused on two types of users: 1) vehicle owners concerned with personal safety, property damage, and theft, and 2) vehicle owners interested in the convenience of valet parking. 
	For vehicle owners concerned with personal safety, property damage, and theft we were interested to find out that several vehicle owners have reported violent crimes committed against them in parking areas [7]. Parking areas are the third most likely place for violent crimes to occur [8]. To combat this, many vehicle owners prefer to have their vehicle parked by a valet service. However, vehicle owners have also reported that they are concerned that their vehicles will be damaged by the valet service drivers or that their personal belongings may be stolen by the drivers [4]. Our autonomous parking system will provide the perfect solution to these concerns. By having vehicles safely park and retrieve themselves, vehicle owners can still enjoy the benefits of valet parking without having to worry about the concerns listed above.
Our research into vehicle owners interested in the convenience of valet parking yielded very interesting information. Vehicle owners believe that valet parking saves time and is worth the cost of paying for the service [4]. The main motivation that we found for utilizing valet parking is that many vehicle owners find it frustrating trying to navigate unfamiliar parking areas, and that many find it difficult to locate their vehicle once they are ready to leave a parking area [5]. Moreover, Vehicle owners are impressed how well autonomous vehicles can park themselves and are trusting in the autonomous parking technology [1] and are interested in being able to remotely recall their vehicles out of a parking area [3]. Our autonomous valet parking system will offer this group of users the ability to enjoy the convenience of valet parking and the ability to park and retrieve their vehicles independent of human-operated valet services. 








Empathy for Users: Vehicle owners concerned with personal safety, property damage, and theft.

Do
Think
-Vehicle owners utilize valet parking to maintain their own personal safety and peace of mind [5]. 
-Vehicle owners have reported violent crimes committed against them in parking areas [7].
-Vehicle owners think that manual valet services are irresponsible when driving their vehicle [4].
-Vehicle owners think that manual valet services are not liable for damages they cause to vehicles [4].
Say
Feel
-Vehicle owners have reported that they are distrustful of valet service attendants driving their vehicle [4].
-Vehicle owners have expressed concerns of potential damage that may occur while manually driving their vehicle into tight parking spaces [1]. 
-Vehicle owners feel afraid of walking through parking areas alone [5].
-Vehicle owners feel more comfortable with a car automatically parking in tight/difficult parking spots [1]





Needs of vehicle owners concerned with personal safety and property damage/theft:
-To feel safe when parking and retrieving their vehicle.
-To trust that their personal belongings will not be stolen from their vehicle.
-To quickly be able to park and recall their vehicle from a parking area.
-To know that their vehicle will not be damaged when being parked/retrieved. 
-To know that their vehicle is parked properly without having to visually verify. 

Point of view statements for vehicle owners concerned with personal safety and property damage/theft:
-Vehicle owners need automated valet parking because they want to feel confident that their vehicle will not be damaged while it is being parked/retrieved. 
-Vehicle owners need the ability to park and retrieve their vehicles without walking through a parking area because doing so makes vehicle owners feel unsafe.
-Vehicle owners need automated valet parking because they feel distrustful of human valets and are concerned about the safety of contents inside their vehicles. 

Empathy for Users: Vehicle owners interested in the convenience of valet parking.

Do
Think
-Vehicle owners report that they often have a difficult time remembering where they parked [5].
-A large majority of vehicle owners have reported that they utilize valet parking services for the convenience they provide [2].
-Vehicle owners believe that valet parking saves time and is worth the cost of paying for the service [4].
-Vehicle owners think it can be difficult to find their vehicle in an unfamiliar parking area [5].
-Vehicle owners think that parking garages can be difficult to navigate on foot [5].
Say
Feel
-Vehicle owners are impressed how well vehicles can park themselves and are trusting in the autonomous parking technology [1].
-Vehicle owners are interested in being able to remotely recall their vehicles out of a parking area [3].
-Vehicle owners feel frustrated when trying to find their vehicle after they have parked it [5]. 
-Vehicle owners feel upset when trying to navigate unfamiliar parking areas (entering, exiting, and finding parking spots) [5].




Needs of vehicle owners Vehicle owners interested in the convenience of valet parking:
-To be able to park and recall their vehicle remotely.
-To drop themselves off and pick up their vehicle at a convenient location.
-To have a reliable autonomous parking feature that will park and recall their vehicle without incident. 

Point of view statements for vehicle owners Vehicle owners interested in the convenience of valet parking:
-Vehicle owners need autonomous valet parking because they want to save time parking their vehicle.
-Vehicle owners need autonomous valet parking because they are frustrated when parking their vehicle in unfamiliar parking areas.
-Vehicle owners need autonomous valet parking because they want to avoid navigating confusing parking areas on foot.
-Vehicle owners need autonomous valet parking because they want to independently be able to remotely park and retrieve their vehicle.

Test Field:


Test Field Summary: 
The test field illustrates a parking lot for Cybots. The parking lot has 4 parking spaces, a designated entry and exit, and a single marked path that Cybots will follow. Each parking space would have a tape marker in front of it to indicate a parking space, and the Cybot would use object detection software and the ping/IR sensors to find an empty parking space. The single marked path will have tall objects that the Cybot will detect with the ping and IR sensors and sound a horn until the object is moved. Small objects will also be present and will be detected using the Cybot’s bump sensors. On bumping a small object, a horn is sounded and a parking attendant will be notified to press button 4 on the Cybot, for resuming motion. A user interface will be used to communicate a recall feature, that will return the cybot to the exit of the parking lot. The Cybot will use the single marked path  to make the necessary turns. 









Technical Sketch for Functional Requirements:


Lotus Blossom Diagram for Functional Requirements:

(Diagram typo: PWM*)
The Diagram above shows the functionalities of the cybot we will be using for various purposes such as object and boundary detection, user interface, etc…, and how they will be implemented in context to our project. 

Team Member Contributions:
Dana Boor: research summary, empathy maps, needs consideration, and POV statements for both groups of vehicle owners researched.

Varun Advani: Test field setup and summary, application narrative

Nihaal Zaheer: Sketched the Prototype Test Field and a few other features of the Cybot Valet, including the working of the boundary detection and park feature.

Kalyan Thapaliya: Problem statement, technical sketch and lotus blossom diagram for functional requirements





Works Cited
[1] “2013 Ford escape: Man vs machine self-parking challenge & tech review,” YouTube, 24-Oct-2012. [Online]. Available: https://www.youtube.com/watch?v=qaukp2kI44s. [Accessed: 24-Jun-2022].
[2] “5 reasons autostacker benefits valet parking service,” Autostacker Parking Lift. [Online]. Available: https://www.autostacker.com/digest/valet-parking/. [Accessed: 23-Jun-2022].
[3] B. Global, “Automated Valet Parking,” Bosch in the USA, 2022. [Online]. Available: https://www.bosch.us/news-and-stories/automated-valet-parking/. [Accessed: 24-Jun-2022].
[4] “Best valet parking - garden grove, CA,” Yelp. [Online]. Available: https://www.yelp.com/biz/best-valet-parking-garden-grove-3?sort_by=rating_asc. [Accessed: 24-Jun-2022].
[5] L. Caluori, “Advantages of Automated Valet Parking Systems,” Parking Network, 25-Sep-2013. [Online]. Available: https://www.parking.net/parking-news/skyline-parking-ag/automated-valet-parking. [Accessed: 24-Jun-2022]. 
[6]Tsz-Chiu Au, "Gridlock-free Autonomous Parking Lots for Autonomous Vehicles", 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp.4881-4887, 2021.
[Accessed: 24-Jun-2022]
[7] K. Moore, “ Parking lot liability and the hidden hazards - don't overlook the risk exposures,” NKyTribune , 24-Mar-2022. [Online]. Available: https://www.nkytribune.com/2022/03/keven-moore-parking-lot-liability-and-the-hidden-hazards-dont-overlook-the-risk-exposures/. [Accessed: 24-Jun-2022]. 
[8] “Parking lot safety tips: Strategies for safe facilities,” PalAmerican Security, 20-Jan-2021. [Online]. Available: https://palamerican.com/safety-security-tips/parking-lot-safety-tips/. [Accessed: 24-Jun-2022]. 



