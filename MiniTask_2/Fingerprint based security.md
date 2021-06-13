**Project**: https://github.com/AneeshKandi/Task-1/blob/main/MiniTask_1/Fingerprint%20based%20security.md

## Problem Statement

This project aims at creating a door lock system with a Fingerprint technology. The device first stores the authorized user's fingerprint data and then tries to match with the users' fingerprint with the stored data to unlock the door.

## Ideation and Planning

Mechanism:
- _Fingerprint sensor -> Arduino -> Servo Motor + Buzzer_
- Pipeline:

| **Part of Pipeline** | **Feasibility** | **Advantages** | **Disadvantages** |
| --- | --- | --- | --- |
| Fingerprint Sensor | Commonly used and easily available. | Power consumption is low. Stores upto 200 fingerprints. Provides a reliable security | Performance can be fluctuate to dry, wet, dirty fingers. Little expensive. People with skin problems and old age, fingerprint pattern changes |
| Arduino Mega | Usually hard, unless very, skilled and experienced | Easily programmable, as it has many libraries to work with. | Limited executions. Hard for beginners |
| Servo Motor | Most commonly used motor. Easily available at cheap cost. | There is no out-of-step condition, as heavy load placed on the motor the driver will increase the current to the motor. High-speed operation is possible. | Require tuning to stabilize feedback loop. Poor motor cooling. Motor can be damaged by sustained overload. |

- Choosing Pipeline:

The servo motor have few disadvantages but it is good enough for door opening project as it doesn't require much precision in the angle rotation. 

For fingerprint sensors, using advanced and latest sensors which can detect even with dry and wet hands is to be used. 

## Prototype

The components required are:
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

Schematics:

![image](https://user-images.githubusercontent.com/85028192/121735961-7bb25000-cb14-11eb-85fc-de5eca571e7b.png)

## Code

https://github.com/AneeshKandi/Task-1/blob/main/MiniTask_2/fingerprint_code.ino
