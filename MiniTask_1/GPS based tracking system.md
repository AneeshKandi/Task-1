# GPS and GSM based Vehicle tracking System

The project is designed to find out the exact location of any vehicle and intimate the position to the concerned authority about through an SMS. 
This system includes a GPS modem which retrieves the location of a vehicle in terms of its longitude and latitude. This data is fed to the microcontroller which is interfaced with a GSM modem.

Adopting this technology will be highly useful to transport companies to keep tracking their vehicles.

## Components

1. ATmega16 microcontroller
2. iWave GPS Module
3. GSM Modem
4. 9V Battery
5. LCD Display

## What is GPS?

**Global Positioning System** or **GPS** is a space-based satellite navigation system. It provides location and time information in all weather conditions, anywhere on or near the Earth. GPS receivers are popularly used for navigation, positioning, time dissemination and other research purposes. All the GPS satellites transmit radio signals, which are then captured by a GPS receiver and used to calculate its geographical position. A minimum of **four satellites** may be required to compute the four dimensions of X, Y, Z (latitude, longitude and elevation) and time. GPS receiver converts the received signals into position and estimates time and some other useful information depending on the application and requirements.

## GSM Modem

**Global System for Mobile** or **GSM** is a standard developed by European Telecommunication Standards Institute (ETSI) to describe protocols for second generation (2G) digital cellular networks. A GSM modem is a specialised type of modem that accepts a SIM card and operates over a subscription to a mobile operator just like a mobile phone. GSM modems are a cost-effective solution for receiving SMS messages because the sender is paying for the message delivery.  

## The Project

The block diagram for the system is as shown below:

![image](https://user-images.githubusercontent.com/85028192/121785273-803f3d00-cbd6-11eb-8bc7-8b0088077235.png)

The system can be mounted or fitted in our vehiclesin a hidden or suitable compartment. The authorized user has to dial the SIM card present in the GSM modem. This data is fed to the microcontroller which is interfaced with a GSM modem. Microcontroller retrieves the location details from the GPS and sends it to the concerned authority in the form of an SMS over GSM modem on periodical intervals so set by the user. An LCD display is interfaced to the microcontroller for crossing the data received before being sent over GSM.
