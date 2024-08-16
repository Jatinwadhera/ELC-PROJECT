# ELC-PROJECT


# Self-Balancing Robot

This repository contains the c documentation, and resources for a self-balancing robot project developed during a summer electronics lab course. The robot is designed to autonomously maintain its balance using real-time sensor data and a control algorithm.

The main objective of this project is to create a robot that can remain upright on its own, even when disturbed. By leveraging sensors like a gyroscope and accelerometer, the robot detects its tilt and adjusts its motors accordingly to stay balanced.

# HARDWARE COMPONENTS 
1)  MICROCONTROLLER :  ARDUINO UNO , TEENSY
2) IMU SENSOR 6050
3) LIPO BATTERY 5500mah
4) DC PLANETARY MOTOR 4nm torque each
5) BTS7960 MOTOR DRIVER

# CONTROL SYSTEM 
The self-balancing robot is powered by a control system designed to maintain balance using sensor feedback and a control algorithm.

1. Sensors
The robot uses a combination of sensors, such as a gyroscope and accelerometer, to determine its tilt angle and rate of change. These sensors provide critical data that feeds into the control system.

2. Control Algorithm: PID Control
The Proportional-Integral-Derivative (PID) control algorithm is at the core of the balancing mechanism. It processes the sensor data and determines the necessary adjustments to the motor speeds.

Proportional(P): Reacts to the current tilt angle and tries to correct it proportionally.

Integral(I): Accounts for past errors (drift) and corrects any accumulated imbalance over time.

Derivative(D): Predicts future error based on the current rate of change and applies correction to prevent overshooting.

3. Motor Control
Based on the output from the PID algorithm, the robot adjusts the speed and direction of its motors to counteract any tilt, helping it stay balanced.

4. Feedback Loop
The control system works as a closed feedback loop, where the sensors continuously monitor the robot’s position, and the PID controller adjusts the motors in real-time to maintain balance.



# APPILCATIONS

1)Personal Transportation

2)Robotics Research

3)Assistive Devices

4)Education and Training

5)Logistics and Delivery

6)Entertainment and Robotics Competitions

# WHY PID ?
 Simple and Effective Tuning
The PID parameters are relatively easy to adjust, allowing for precise control and adaptability to different conditions.

 Proven Effectiveness
PID control is extensively used in various applications, including rocket trajectory stabilization. Its effectiveness in handling dynamic systems like rockets and balancing robots is well-documented.





