# Radar Speed Gun

Have you ever watched Cricket? Did you wonder how they calculated the speed of the balls by bowlers or speed of Bat? The speed calculated is displayed almost immediately after the ball is thrown. For this they use the **Radar Speed Gun**. This gun has many applications - in Cricket, Tennis, measuring speed of vehicles, etc. It can be used to measure speed of any moving object. This project aims at making a radar gun.

<div align="center">
    <img src="https://user-images.githubusercontent.com/85028192/121888493-b21ae580-cd35-11eb-9634-c8ba4f29fed6.png" width="300" height="400"/>
    <br/>
</div>

## Components

1. Microcontroller
2. OLED Display<div align="center">
3. HB100 Doppler Sensor

## How the Gun Works?

A radar gun transmits a narrow beam of radio-frequency energy out the front of the gun and looks for that signal to be reflected back to the gun after bouncing off an object. the speed measurement is calculated by how much the received signal has changed in frequency after reflecting off the moving object. This phenomenon is called the [Doppler effect](https://en.wikipedia.org/wiki/Doppler_effect) and is the same reason that a car sounds different as it approaches and drives away from you.
<div align="center">
    <img src="https://cdn.shopify.com/s/files/1/0181/3771/files/withoutlaserjammer.gif?7556415246682363679" width="600" height="300"/>
    <br/>
</div>

## The Project

HB100 sensor works on the Doppler shift effect. This sensor is connected to Arduino and it is coded. The results are displayed in an OLED display.
