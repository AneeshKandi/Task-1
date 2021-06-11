# Fingerprint Based Door Lock System

Biometric systems have overtime served as robust security mechanisms in various domains. Fingerprints are the oldest and most widely used form of biometric identification. The use of fingerprint for identification has been employed in law enforcement for about a century. A much broader application of fingerprint is for personal authentication, for instance to access a computer, a network, an ATM machine, a car or a home.

Human fingerprints are detailed, nearly unique, difficult to alter, and durable over the life of an individual, making them suitable as long-term markers of human identity. This fact can be utilized in the security systems. In this project, we will be creating a door lock system using Fingerprint technology.

## Hardware Components

1. Arduino Mega
2. Servo Motor
3. Fingerprint Sensor
4. 9V Battery
5. LED
6. LCD Display
7. Buzzer
8. DHT Sensor(Temperature and Humidity)
9. Potentiometer
10. Push Buttons

## What is a Servo Motor?

A servomotor is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback. It also requires a relatively sophisticated controller, often a dedicated module designed specifically for use with servomotors.

![image](https://user-images.githubusercontent.com/85028192/121732560-06448080-cb10-11eb-8888-1f902e0af581.png)

## How exactly a Fingerprint Sensor works?

A fingerprint is an impression left by the friction ridges of a human finger. Optical fingerprint sensors have been around for a while. The way an optical scanner works is by shining a bright light over your fingerprint and taking a digital photo. The light-sensitive microchip makes the digital image by looking at the ridges and valleys of the fingerprint, turning them into 1’s and 0’s, and creates the user’s own personal code. 

<img align = "center" height = 500 width = 500 src = "https://user-images.githubusercontent.com/85028192/121733613-5708a900-cb11-11eb-85a9-0ddb72fcf322.png">

## The Project

The block diagram for the entire process:
![image](https://user-images.githubusercontent.com/85028192/121734475-718f5200-cb12-11eb-8ca3-16b07a24206c.png)

With the help of the push buttons, we can select the options. We can either "enter" new fingerprints, "Del" old fingerprints, etc. Once the authenticated user's fingerprint is stored, the user can try to open the door lock using his fingerprint now. The optical scanner will produce a personal code made up of 0s and 1s. Then the code is checked with authenticated users' fingerprint codes. Depending on the code, a suitable message is sent to the user via the LCD Display and the microcontroller sends a signal to the servo motor for the required action to be done.
