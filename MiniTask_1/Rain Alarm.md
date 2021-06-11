# Rain Alarm

We dry our clothes under the bright Sun during the day. Imagine if it rains all of a sudden and we being a busy person dwelled with our works, may not notice the rain and by the time we realize, our clothes might have gone wet again! Also, water is a basic need in every one’s life. Saving water and proper usage of water is very important. So we have to utilize rain water by saving them to use later or by harvesting them. This simple project helps us by alarming us about the Rain.

## Components required

1. Rain sensor
2. Buzzer
3. Transistors and Diodes
4. Resistors and Capacitors
5. 555 Timer IC
6. 12V power supply
7. LED

## How does a Rain Sensor works?

It is a simple sensor, made up of Bakelite or Mica board with Aluminium wires. This is how it looks:

<img align = "center" height = "400" width = "400" src = "https://user-images.githubusercontent.com/85028192/121739774-b5398a00-cb19-11eb-8bd0-fbf7e228b4d0.png">

If there is no rain, the resistance between the contacts will be very high as there will be no conduction between the wires in the sensor. If there is rain, the water drops will fall on the rain sensor, which will form a conductive path between the wires and it also decreases the resistance between the contacts. So the sensor basically acts like a switch which is open when no rain and closed when it starts raining.

## What is 555 Timer IC?

The 555 timer IC is a very cheap, popular and useful precision timing device which can act as either a simple timer to generate single pulses or long time delays, or as a relaxation oscillator producing a string of stabilised waveforms of varying duty cycles from 50 to 100%. The basic 555 timer gets its name from the fact that there are three internally connected 5kΩ resistors which it uses to generate the two comparators reference voltages. A 555 timer has 3 modes - Monostable, Bistable and Astable modes.

![image](https://user-images.githubusercontent.com/85028192/121743052-575b7100-cb1e-11eb-986f-a2eafdb9063f.png)

## The Project

When it starts raining, the rain sensor gets switch ON and it triggers the 555 timer. The 555 timer is configured in Astable mode. As a result of the triggering, it will make the output pin high which makes the Buzzer to ring and the LED to light up. Depending on the values of Resistors and Capacitors, we can control the time for which the buzzer will be ON. However, the LED will be switched ON as long as it rains.

When there is no rain, there is no trigger, so the buzzer will not start ringing.

Here is the block diagram:

![image](https://user-images.githubusercontent.com/85028192/121743746-71498380-cb1f-11eb-8ca9-fb8d160055f5.png)

**Note:** We need to place the Rain Sensor in an inclined position(30-40 deg) so that the rain water does not remain on it.

## Circuit Diagram

![image](https://user-images.githubusercontent.com/85028192/121743772-80c8cc80-cb1f-11eb-9f87-b80fdc4318a7.png)
