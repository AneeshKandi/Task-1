# Debugging Tutorial for GPS tracking system

## Project

You can find the analysis and description of the project here:

https://github.com/AneeshKandi/Task-1/blob/main/MiniTask_2/GPS%20based%20tracking%20system.md

## Testing the Components

The sequence of the components:

*GSM Modem -> Microcontroller -> GPS Module -> Microcontroller -> GSM Module*

### Testing the GSM Modem

Try testing for the response from the modem by manually by sending a SMS using your phone or **PuTTY**. Check if the SIM in the modem is unlocked and recharged. The configurations and the sim compability checks can be done. Check if the modem is connected to correct COM port. Try dialing the SIM card present in the modem. Also check if the network of the SIM is available in that area. Make sure the antenna is well placed.

### Testing the ATMega 16 Microcontroller

Try the microcontroller with small projects first. Make sure all the connections are properly made. Check the power conneected to it is sufficient to power it up. Make sure no wires or pins are shorted.

### Testing the GPS Module

Take the device to different locations and test it. Compare with your smartphone GPS location. Check if the antenna is properly located. Check all the connections made. Check whether the configurations in the software are correct.

