[ ](#Make_the_imgae_w=160_by_h=150)


# Complete Porfolio

This document showcases all projects that i have undertook. For the projects that was completed when a company there will only be a brief summary, on the otherhand other projects can be accessed in github. List of all the projects with tags to describe the project and/or my role in it is given below. 

| Project Title                                         | Descriptive Tags |
| -----------                                           | ----------- |
| [Trafic Light Fault Monitoring Board](#trafic-fault-detection)  | `Embedded`, `Software Design`, `Hardware Troubleshooting`, `PCB with Liligo Board`, `ESP8266 SoC` , `GSM` , `Wifi` , `Customer-driven` |
| [Motor Safty Control System](#Motor-safty)            |  `Embedded`, `Software Design`, `FRDM-KL25Z` , `Mbed Enabled Hardware`, `ARM Cortex M0+` , `Basic Assembly Language`|
| [Web and Native Application for Student Grouping Dashboard](#python-application)            |  `Python`, `Software Design`, `Native App:Qt`, `Web App:django`|
| [3 in a Row game in C++ using UnrealEnginge Script](#Unreal-Game)            |  `C++`, `Software Design`, `UnrealEngine`, `OOP`|
| [Snake game in C++ Using OpenGL](#c-snake-game)            |  `C++`, `Software Design`, `Game Dev`, `No game engine`, `OpenGL` , `GNU debug tool`|
| [Wireless Sensor Network Simulator](#wireless-sensor-network-simulator)            |  `Software Design`,`C`, `Parralle Programing`, `POSIX threads`, `MPI process`, `GDP debugging` , `GNU debug tool`|
| [Brushless DC motor control using Odrive](#bldc-control)            |  `ROS`,`Odrive`, `Designed a ROS node`, `Motor controlled was used in AV cart`|
| [External Keyboard PCB Design](#external-keyboard-pcb-design)            |  `Altium Designer`,`PCB layout`, `Atmega MCU`, `USB-powered`|
| [Developing API for ILI9320 Display to show QR codes](#developing-api-for-ilt9320-display-to-show-qr-codes)            |  `ILI9320 Display`,`Platform io`, `Arduino`|
| [Automatic Temperature Screening station using ESP32](#automatic-temperature-screening-station)            |  `ESP32`,`QR reader`, `platform io`, `GSM` , `working prototype designed`, `prototype was tested`|


## Trafic Fault Detection

When trafic lights behave abnormlally it is considered faulty and aletrs must be sent. For instance faults may be out of order lighting sequence or having two or more lights at a time. The old system could only detect out of sequence light switching error and the alert was sent using SMS to a particular phone number. The following function were added to the system:

- A new alerting mode with use of internet (MQTT messaging) was added. This was more cost effective than SMS.
- each device was assigned a unique ID for distiguishing between different devices.
- Device was made to operate as Wifi AP which would allow technicians or device installers to change device id, alerting mode, and phone number to be used for the SMS alerting mode. Furthermore a soft reset option was given for repair purposes.
- Additonal error was added: The error was detected when two or more lights are on at a time.

**Repository Link**: It was a compnay project so reposity can not be shared. For quick demostration it can be shown in interview. 

## Motor Safty

Large motors and equipment require safty system to ensure the safty of user. For instance a motor should only turn on if its shiled is closed. Furthermore the motor should not operate when its temperature exceeds a threshold. A simple system was desigend for such a safty system using ARM platform (simulated only). The system had the following functionality:

- When temperature exceeds a threshold or lid is open, the motor is turned off.
- The motor wouldn't start unless lid is closed.
- Real time detection of all safty preaches using interupts

**Repository Link**: https://github.com/Abdolraouf-KIE/Motor-Safty-Control-System

## Python Application

A simple python applicaton was designed for both native and web using QT and bjango respectivly. The project was done in team of 2 members.

**Repository Link**: https://gitlab.com/Murdock135/flask_groupjoin

## Unreal Game

A 4 in a row game was developed using Unreal engine that uses C++ object oriented programing. Multiple levels where added and a simple start menue was added.

**Repository Link**: not available

## C++ Snake Game

Inorder to understand low level programing (compiling) and debugging tools (GDB debugger), this project was carried out. Unlike the game development in unreal engine this project made use of no game engine and only used the OpenGL graphic library. 

**Repository Link**: https://github.com/Abdolraouf-KIE/SnakeGameC--

## Wireless Sensor Network Simulator

This project was carried out to understand how parrallel programing works. This knowledge would specialy become useful when using RTOS for MCUs. A wireless sensor network simulator would be run on Linux (C programing) and use multiple threads and multiple processors. The network is made up of a grid of nodes (each represented by different process) and the nodes communicate with eachother and do computation in parallel using multiple threads. See the repository for full design specification. The project was carried out in a team of 2.

**Repository Link**: https://github.com/Abdolraouf-KIE/tsunamiSimulation

## BLDC Control

I was involved in a team responsible to develop an autonomous cart. I was responsible for controlling the brushless DC motor using the an specifc driver. Furthermore to allow the motor to be controlled by other systems, the control was packaged into a ROS package. 

**Repository Link**: none; I obtained a certificate from the organizer.

## External Keyboard PCB Design

This was done under REC workshop. The purpose was to learn PCB layout and component selection. Using online resources, components were selected and using Altium Designer the PCB layout was designed. Due to chip shortage the PCB was only designed and it was not ordered.

**Repository Link**: https://github.com/Abdolraouf-KIE/REC-Workshop---Stream-Deck