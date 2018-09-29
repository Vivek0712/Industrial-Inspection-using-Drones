# Industrial-Inspection-using-Drones

Industrial Inspection Aerial Drones using Deeplearning Techniques
Problem Statement: 
Involvement of workers in hazardous working conditions using industrial inspections for long hours.
Objective:
To build UAV Drones to streamline and standardize routine industrial inspection for better inspection viewpoints, safer working distances and improved worker safety.
Overview of the solution:
An UAV Drone is fitted with camera which sends the live feed to the operator and notifies if any anomalies are detected using deep learning techniques during industrial inspections.
Technical Specifications:
1.	Drone Specifications:
•	The drone (DC powered) satisfies basic requirements.
•	The user is provided with RC controller to control the drone. A video display is also provided in the drone for viewing the live feed.
•	A high quality camera is fitted in the drone which captures.
•	Wi-Fi module ESP8266 is used to establish Wi-Fi link between user and drone.
•	It is used to send the live feed to the user.
•	The control signals to the motors were supplied to them through an Arduino UNO R3  board as it is programmed to supply under each circumstance.

2.	Anomaly Detection using Deep Learning
•	The live feed is sent to cloud.
•	A deep learning model using CNN is deployed in cloud and it is pre-trained with dataset of anomaly and faults 
•	The deep learning model detects the anomaly in the live feed and notifies the operator by marking the place of anomaly and flashing of lights fitted in drone.
Working Schema:
Our solution consists of two main modules:
1.	Control of UAV drone fitted with camera
2.	Detection of anomalies using deep learning techniques.



Advantages:
•	The workers can work in safe environment.
•	The human error in lack of ability to detect the anomaly can be avoided.
•	The time taken for inspection can be drastically reduced.




