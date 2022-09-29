[ ](#Make_the_imgae_w=160_by_h=150)


# Project Portfolio

This document showcases majority of projects that i have undertook. For the projects that was completed with a company there will only be a brief summary, on the otherhand other projects can be accessed in github. List of all the projects with tags to describe the project and/or my role in it is given below. To get full project description click on the project title.

| Project Title                                         | Descriptive Tags |
| -----------                                           | ----------- |
| [Trafic Light Fault Monitoring Board](#trafic-fault-detection)  | `Embedded`, `Software Design`, `Hardware Troubleshooting`, `PCB with Liligo Board`, `ESP8266 SoC` , `GSM` , `Wifi` , `Customer-driven` |
| [Motor Safty Control System](#motor-safty)            |  `Embedded`, `Software Design`, `FRDM-KL25Z` , `Mbed Enabled Hardware`, `ARM Cortex M0+` , `Basic Assembly Language`|
| [Web and Native Application for Student Grouping Dashboard](#python-application)            |  `Python`, `Software Design`, `Native App:Qt`, `Web App:django`|
| [3 in a Row game in C++ using UnrealEnginge Script](#unreal-game)            |  `C++`, `Software Design`, `UnrealEngine`, `OOP`|
| [Snake game in C++ Using OpenGL](#c-snake-game)            |  `C++`, `Software Design`, `Game Dev`, `No game engine`, `OpenGL` , `GNU debug tool`|
| [Wireless Sensor Network Simulator](#wireless-sensor-network-simulator)            |  `Software Design`,`C`, `Parralle Programing`, `POSIX threads`, `MPI process`, `GDP debugging` , `GNU debug tool`|
| [Brushless DC motor control using Odrive](#bldc-control)            |  `ROS`,`Odrive`, `Designed a ROS node`, `Motor controlled was used in AV cart`|
| [External Keyboard PCB Design](#external-keyboard-pcb-design)            |  `Altium Designer`,`PCB layout`, `Atmega MCU`, `USB-powered`|
| [Developing API for ILI9320 Display to show QR codes](#developing-api-for-ilt9320-display-to-show-qr-codes)            |  `ILI9320 Display`,`Platform io`, `Arduino`|
| [Automatic Temperature Screening station using ESP32](#automatic-temperature-screening-station)            |  `ESP32`,`QR reader`, `platform io`, `GSM` , `working prototype designed`, `prototype was tested`|
| [Design of Constant g_m Current Mirror in 0.13um Tech Node](#Design_of_Constant_g_m_Current_Mirror_in_0.13um_Tech_Node)            |  `Mentor Graphic`,`IC Analog`, `Current Mirror`, `Supply independent`|

<br/>

___

## Trafic Fault Detection

When trafic lights behave abnormally it is considered faulty and alerts are sent. For instance faults may be lighting sequence out of order or having two or more lights on at a time. The old system could only detect out of sequence light switching error and the alert was sent using SMS to a particular phone number. The following function were added to the system:

- A new alerting mode with use of internet (MQTT messaging) was added. This was more cost effective than SMS.
- each device was assigned a unique ID for distiguishing between different devices.
- Device was made to operate as Wifi AP which would allow technicians or device installers to change device id, alerting mode, and phone number for SMS alerting. Furthermore a soft reset option was given for repair purposes.
- Additonal error was added: The error was detected when two or more lights are on at a time.

**Repository Link**: It was a company project so reposity can not be shared. For quick demostration it can be shown in interview. 

<br/>

___

## Motor Safty

Large motors and equipment require safty system to ensure the safty of user. For instance a motor should only turn on if its shield is closed. A simple system was desigend for such a safty system using ARM-enabled platform (simulated only). The system had the following functionality:

- When temperature exceeds a threshold or lid is open, the motor is turned off.
- The motor wouldn't start unless lid is closed.
- Real time detection of all safty breaches using interupts was done. 

**Repository Link**: https://github.com/Abdolraouf-KIE/Motor-Safty-Control-System

<br/>

___

## Python Application

A simple python applicaton was designed for both native and web using QT and bjango respectivly. The project was done in team of 2 members.

**Repository Link**: https://gitlab.com/Murdock135/flask_groupjoin

<br/>

___

## Unreal Game

A 4 in a row game was developed using Unreal engine that uses C++ object oriented programing. Multiple levels and a simple start menue were added.

**Repository Link**: not available

<br/>

___

## C++ Snake Game

Inorder to understand low level programing (compiling) and debugging tools (GDB debugger), this project was carried out. Unlike the game development in unreal engine this project made use of no game engine and only used the OpenGL graphics library. 

**Repository Link**: https://github.com/Abdolraouf-KIE/SnakeGameC--

<br/>

___

## Wireless Sensor Network Simulator

This project was carried out to understand how parrallel programing works. This knowledge would specialy become useful when using RTOS for MCUs. A wireless sensor network simulator would be run on Linux (C programing) and use multiple threads and multiple processors. The network is made up of a grid of nodes (each represented by different process) and the nodes communicate with eachother and do computation using multiple threads. See the repository for full design specification. The project was carried out in a team of 2.

**Repository Link**: https://github.com/Abdolraouf-KIE/tsunamiSimulation

<br/>

___

## BLDC Control

I was involved in a team responsible to develop an autonomous cart. I was responsible for controlling the brushless DC motor using an specific driver. Furthermore to allow the motor to be controlled for inverse kinematics a ROS package was developed for it.

**Repository Link**: none; I obtained a certificate from the project manager.

<br/>

___

## External Keyboard PCB Design

This was done under REC workshop. The purpose was to learn PCB layout and component selection. Using online resources, components were selected and using Altium Designer the PCB layout was designed. Due to chip shortage the PCB was only designed and it was not ordered.

**Repository Link**: https://github.com/Abdolraouf-KIE/REC-Workshop---Stream-Deck

<br/>

___

## API for ILI9320 Display to show QR codes

Chinese electronic products are known for bad documentation. Such device was the ILI9320 Display where there was no available library to use for programing the display. This project involved making such library. Furthermore it was desired to display QR codes for a particular text. Hence the libary developed also contained functionality to display text as QR codes.

**Repository Link**: It was a company project so reposity can not be shared. For quick demostration it can be shown in interview.

<br/>

___

## Automatic Temperature Screening station

With pandemic came reduced opportunity for many companies, however different opportunities arose as well. Such opportunity was designing an automatic temperature screenig with recording capability for schools. A system was desinged where student ID QR code is scanned and then temperature is taken and sent to the cloud. I developed and tested a functioning prototype that was powered by ESP32 MCU.

**Repository Link**: It was a company project so reposity can not be shared. Demo video of product can be shown in interview.

<br/>

___

## Design_of_Constant_g_m_Current_Mirror_in_0.13um_Tech_Node

Reference current generator circuits must be designed so that they provide a constant current regardless of supply voltage variation. This project involved the systematic approach in design of such circuit using theory and aid from Mentor Graphic. By the end the design produced a reference current of 1uA with only 0.035u sensitivity to supply voltage of 1.2V.

**Repository Link**: https://github.com/Abdolraouf-KIE/constant_gm

<br/>
