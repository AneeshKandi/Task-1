**Project:** https://github.com/AneeshKandi/Task-1/blob/main/MiniTask_1/GPS%20based%20tracking%20system.md

## Problem Statement

Tracking Vehicles to get the exact location of the vehicle and inform the user of the same via an SMS. 

## Ideation and Planning

Mechanism:
- _User -> GSM Modem -> Microcontroller -> GPS Module -> Microcontroller -> GSM Modem -> User_
- Pipeline:

| **Part of Pipeline** | **Feasibility** | **Advantages** | **Disadvantages** |
| --- | --- | --- | --- |
| GSM Modem | Uses Mobile phone technology. Identical to ordinary mobile phone. Requires a SIM card. | Easy to use as it is identical to mobile phone. User can communicate using SMS. GSM Signals are strong so no network problems. | There is no end-to-end encryption of user data. Little expensive. |
| Microcontroller ATMega16 | Usually hard, unless very, skilled and experienced | It is the advance version of 8051 microcontroller so it is capable of many things. High Performance. It has huge memory and less power consumption. | Speed is good but not as fast as many other chips. Hard for beginners |
| GPS Module | Easily available. | It works altogether weather so you would like to not worry of climate as in other navigating devices. | Sometimes signals are blocked by obstacles resulting in less accurate readings. Lot of power is consumed. |

- Choosing Pipeline:

We will be using iWave GPS module which has decent power consumption. It is based on SiRF StarIII chipset, which has the ability to capture weak satellite signals even in urban settings, canyon and thick foliage. 20 channel GPS receiver enables fast acquisition and reacquisition. GPS module design is flexible to accommodate various RF interference scenarios.

ATMega16 is an advanced microcontroller with lot of applications. It has a huge memory unit which is very sufficient to do a lot of operations in a within a short time and we can interface it with GPS Modules and GSM Modems.

GSM Modems which is compatible with our microcontroller and sims is to be chosen.

## Prototype

It requires  
- ATmega16 microcontroller
- iWave GPS Module
- GSM Modem
- 9V Battery
- LCD Display
- Max232 Convertor

The prototype needs to assembled according to this diagram:

![image](https://user-images.githubusercontent.com/85028192/121785273-803f3d00-cbd6-11eb-8bc7-8b0088077235.png)

After the setup, the system should be installed inside the vehicles in a hidden compartment or somewhere.

## Application of the Project and Improvements

This project can be utilized by travel companies to track all their vehicles. 

This project can be extended to theft control as well. The authorized user can control the car by SMS in case of theft and emergencies. 
