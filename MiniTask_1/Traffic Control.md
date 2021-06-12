# Density Based Traffic Control System

Nowadays, controlling the traffic becomes major issue because of rapid increase in automobiles and also because of large time delays between traffic lights. So, in order to rectify this problem, we will go for density based traffic lights system. This project is a prototype of the Density based traffic control system.

In this system, we will use IR sensors to measure the traffic density. We have to arrange one IR sensor for each road; these sensors always sense the traffic on that particular road. All these sensors are interfaced to the microcontroller. Based on these sensors, controller detects the traffic and controls the traffic system.

## Components

1. ATmega8 microcontroller
2. IR Sensors
3. LED lights (replacing traffic lights)
4. 12V Battery

## IR Sensors

An infrared (IR) sensor is an electronic device that measures and detects infrared radiation in its surrounding environment. Active IR sensors have two parts: a light emitting diode (LED) and a receiver. When an object comes close to the sensor, the infrared light from the LED reflects off of the object and is detected by the receiver. Based on the intensity of the reception by the IR receiver, the output of the sensor defines. Active IR sensors act as proximity sensors, and they are commonly used in obstacle detection systems.

![image](https://user-images.githubusercontent.com/85028192/121785869-014c0380-cbda-11eb-8278-61e76bc8b927.png)

## The Project

All the sensors and traffic lights are connected to the Microcontroller. If there is a traffic on a particular road, then that particular sensor output becomes logic 0 otherwise logic 1. By receiving these IR sensor outputs, we have to program the microcontroller to control the traffic system. If you receive logic 0 from any of these sensors, we have to give the green signal to that particular path and give red signal to all other paths. Here continuously we have to monitor the IR sensors to check for the traffic.

The current system follows traffic lights according to time delays. For every 1 minute delay, the traffic lights are changed irrespective of the traffic at that location. In this proposed system, the place which has higher traffic density is preferred first than the others. In this way traffic is lessened in all the directions. If the density of traffic is same in all directions, then it works according to the current time delay system itself.
