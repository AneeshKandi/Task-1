# LED Skateboard

This project uses LED lights controlled by an accelerometer and gyroscope to challenge your skateboarding creativity. The LED lights change according to what trick is being
performed. For example, a shuvit (180-degree yaw rotation) changes the lights blue. a kickflip (360-degree roll) changes the color to red. when both tricks are done
simultaneously (varial flip) the colors are added together, turning the lights purple. This functionality of adding colors challenges the skater to come up with new trick
variations to create interesting colors.

## Principle

The basic concept is using additive colors to change the R B G values of the LED strip. Each value is controlled by a different trick. just popping the board up (like an ollie)
represents blue. A kickflip represents red, and a shuvit represents green. Each time a trick is performed 10 is added to the respective R B G value.

|<img width = "300" src="https://user-images.githubusercontent.com/85028192/121384007-837fc200-c965-11eb-9502-7ece8655c1c7.gif"/>|<img width = "500" src="https://user-images.githubusercontent.com/85028192/121384417-e07b7800-c965-11eb-8815-f118fba9dfb3.gif"/>|
|:---:|:---:|
|**_360 KICKFLIP_**|**_SHUVIT_**|

To sense the trick being performed, we use the values of the Accelerometer and Gyroscope. The MPU-6050 module contains the 3-axis accelerometer and 3-axis gyroscope. The accelerometer measures the x,y,z acceleration whereas the gyroscope measures the angular velocity along x, y, z direction i.e (roll, pitch, yaw).

## Components Required

1. The New Deal Deck rails
2. Neopixel LED strip
3. Arduino nano 33 IOT(Other boards can be used)
4. Solderable breadboard
5. Female to male pin headers
6. 9 volt battery
7. 5v regulator

## The Project

Behind the Skateboard, the LED Strips and rails are soldered and glued. Then the whole assembly/circuit is placed and glued to the board. The circuit and assembly is shown below:

<img width = "500" src="https://user-images.githubusercontent.com/85028192/121397648-28a09780-c972-11eb-8765-7261b87087a6.png"/> <img height = "500" width = "450" src="https://user-images.githubusercontent.com/85028192/121397800-4ec63780-c972-11eb-8881-d157cbf63bac.png"/>



