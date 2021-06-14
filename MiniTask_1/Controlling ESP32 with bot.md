# Controlling ESP32 with a Bot
## About the Project

This is a simple project in which we will be controlling ESP32 outputs using a Telegram Bot from anywhere in the world. In this project we will be controlling LEDs (switching ON and OFF).

## Principles Involved

This project is basically an application of __Internet of Things__ or **IoT**. The Internet of things (IoT) describes the network of physical objects that are embedded with sensors, software, and other technologies for the purpose of connecting and exchanging data with other devices and systems over the Internet. In IoT, the sensors/devices share the data by connecting to a IoT gateway from where it goes to the cloud. Once the data reaches the cloud, it gets processed and depending on the data, the software performs some action which reaches the User Interface. The reverse process can happen too, where the user gives an input which is received by the cloud and the data is sent back to the device.

Here is a summarized form of how IoT works:

<div align="center">
    <img src="https://user-images.githubusercontent.com/85028192/121926552-b3f79f80-cd5b-11eb-8dde-0f0175dbab86.png" width="400" height="400"/>
    <br/>
    <sub><sup>© 2019, licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sup></sub>
</div>

In this project, the ESP32 board and telegram bot are connected via IoT.

## Components Required

This simple project can be done at our homes easily if we have these components:
### Hardware Requirement

1. ESP32 board
2. Smart Phone with Telegram app installed

### Software Requirement

1. Arduino IDE
2. Applicable softwares

## The Project

We start by creating a bot in Telegram. Bots are third-party applications that run inside Telegram. Users can interact with bots by sending them messages, commands and inline requests. You control your bots using HTTPS requests to Telegram Bot API. To know more about Bots and how to create them, refer https://core.telegram.org/bots.
The ESP32 will interact with the Telegram bot to receive and handle the messages, and send responses.

After creating the Bot, we need install required Libraries in the Arduino IDE. 2 Libraries 
- Universal Telegram Bot Library
- ArduinoJson Library. 

That's it! Now code the ESP32 and have fun :)

For the complete project, visit : https://randomnerdtutorials.com/telegram-control-esp32-esp8266-nodemcu-outputs/



