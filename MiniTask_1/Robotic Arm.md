# Robotic Arm

This projects controls a robot arm using Arduino and Matlab.

## Components Required
### Hardware Components

1. ESP32 with MPU6050 installed in it
2. 3D Printed Robotic arm
3. Servo Motors
4. Webcam

### Software Components

1. Arduino IDE
2. Matlab

## What is Matlab?

<img align = "left" height = "150" width = "150" src = "https://user-images.githubusercontent.com/85028192/121769238-185e0780-cb80-11eb-9aa4-fb417db5664f.png">
MATLAB (an abbreviation of "matrix laboratory") is a proprietary multi-paradigm programming language and numeric computing environment developed by MathWorks. It has hundreds of built-in functions and toolboxes to make the work of a user much easier. MATLAB allows matrix manipulations, plotting of functions and data, implementation of algorithms, creation of user interfaces, and interfacing with programs written in other languages. There are many applications - Machine Learning, Signal Processing, Image Processing and Computer Vision, Robotics, Wireless Communications, etc.
<br />

## The Project

The arm can be operated in 2 modes - manual and automatic. The project uses 4 Servos - 3 servos as 3 degrees of freedom and one to work as a gripper.

<img align = "right" height = "400" width = "400" src = "https://user-images.githubusercontent.com/85028192/121769171-bf8e6f00-cb7f-11eb-91ae-23600eb19d67.png">

### Manual mode

In manual mode we will be controlling the arm by moving the ESP32. On moving the board in different directions, the accelerometer reads different values. These values are fed to the microcontroller which is then callibrated according to the code. The microcontroller then relays the signals to control the servo motors depending upon our movement action.

### Automatic mode

In this mode, we use Matlab image processing to control the robot. We set up the Webcam and code it in Matlab. The image taken by webcam is processed and many calculations will be done by Matlab and after all the calculations, the data is sent to the microcontroller. The microcontroller then relays the signals to the servo motors.

That's it! A fully functioning Robotic Arm with 2 modes is ready!
