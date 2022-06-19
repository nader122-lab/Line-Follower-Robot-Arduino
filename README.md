# Line-Follower-Robot-Arduino

This device detects a black line on a white surface, it estimates whether the line under it is moving towards the left or right as it moves over it. Based on that estimation signals are sent to the motors to turn left or right so that they can maintain a steady centre in accordance with the line. An appropriate communication between the software and the hardware enables the robot car to achieve its objectives successfully. The complete procedure of how this robot car works is explained in detail further in the report.

In order to achieve our objectives we used an Arduino UNO, Robot Chassis, 2 wheels along with the 2 stepper motors to make the car, and for sensing we incorporate Infra-Red sensors which accurately detects the reflectance of the surface so that it can follow the line whereas to detect any obstacles  in the path ultrasonic sensors are used. The Arduino is coded such that it signals the motors to vary its speed and perform sharp turns hence following the line and stopping when an obstacle is detected Infront of it.

![image](https://user-images.githubusercontent.com/72204063/174479436-cf4bacd9-eaa7-4341-b9c9-4ae9e34b6c46.png)
