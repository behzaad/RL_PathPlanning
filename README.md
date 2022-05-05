# Path Planning for the Robots Using Reinforcement Learning

We have a robot that aims to collect data of several low-powered IoT sensors. The robot starts its mission from the start terminal. There is a charging station in the environment so that the robot can recharge its battery if it is running out of energy. Also, there are several obstacles in the environment. 

The task of the robot is to collect data of all sensors in the shortest possible time while it avoids any collisions to the obstacles.


In the following image, we have depicted the environment:


<img width="296" alt="Env" src="https://user-images.githubusercontent.com/37718565/167018071-d82d1445-17e9-4b01-9604-d7c2339bbd8e.png">

red square: starting position

green square: charging station

Black circles: IoT sensors

Blue blocks: obstacles


In this project, we define the state as a four channel image, shown below

<img width="865" alt="img" src="https://user-images.githubusercontent.com/37718565/167021810-200d8550-21e6-4540-ab24-c8fac41e23ef.png">

Based on this definition, we can use CNNs to solve the MDP. 








A sample result:


<img width="296" alt="res" src="https://user-images.githubusercontent.com/37718565/167018611-38facc53-ab32-42f8-99b9-014151581baa.png">



## Reference

This project is part of my PhD thesis at University of Toronto. If using this code for research purposes, please cite:

Khamidehi B. Aerial Robots for Wireless Coverage, Traffic Monitoring, and Transport Applications: A Path Planning and Fleet Management Perspective (Doctoral dissertation, University of Toronto (Canada)). [[Link]](https://www.proquest.com/openview/254c7d1708540fec5e9c8f8a62f541a5/1?pq-origsite=gscholar&cbl=18750&diss=y)
