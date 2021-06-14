# Infrared Thermometer

A thermometer is a device used for measuring temperature of a body. In recent circumstances (Covid), there is a wide use of thermometers. This project aims for building an infrared non-contactless thermometer. It is an effective way to make temperature measurements in situations where it is difficult to access the surface to be measured.

<div align="center">
    <img src="https://user-images.githubusercontent.com/85028192/121882646-703a7100-cd2e-11eb-9250-8e7e5ac633a8.png" width="300" height="300"/>
    <br/>
</div>

## Components

1. Arduino Pro Mini
2. MLX90614 Infrared Temperature Sensor
3. OLED Display – SSD1306
4. Laser Diode
5. 9V Battery
6. Push button

## How the Temperature Sensor works?

It works based on Stefan-Boltzmann law which states that all objects emits IR energy and the intensity of this energy will be directly proportional to the temperature of that object. The molecules that are inside our body or any object are not standing still. They move like kids when they have a chocolate overdose in a ball park. They don’t stand still even if you tie them up. The same thing happens to molecules. Also, when they move, they emit infrared radiation. This radiation is below the visible spectrum of light and therefore we, humans, cannot see it. The higher the temperature of the body or object, the faster the molecules move and the more infrared radiation the body emits. (Even if you can heat a body a lot, it can emit visible light.)

MLX90614 sensor is manufactured by Melexis Microelectronics Integrated system. The name MLX90614 refers to a family of infrared thermometers. Within this family there are several models. They are identified by a 3-letter suffix. It has two devices embedded in it, one is the infrared thermopile detector (sensing unit) and the other is a signal conditioning DSP device (computational unit). 

## The Project

The sensor is connected with the Arduino board. The sensor uses I2C communication interface. The readings from sensor is communicated to the board which then displays to the user using the OLED Display.

For the code, we need to install the Adafruit library for MLX90614 which makes the code very simple. Here is the circuit diagram:

<div align="center">
    <img src="https://user-images.githubusercontent.com/85028192/121884803-ff488880-cd30-11eb-9255-22ecdb4c9be4.png" width="600" height="400"/>
    <br/>
</div>
