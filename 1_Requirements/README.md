# Intoduction

A Wiper control system have a key role during adverse weather conditions by wiping the rain continuously over the windshield area and provides a clear vision to the driver.Mud,Dust,Rain Drops,Snow Are Swept Away By the Wiper Blades in Car.WindShield Wipers enhance Visibility,Efficiency and Reliablity.The traditional system however requires driver's constant attention for controlling the wiping speed manually. The various components of wiper control system are the wiper blade, link, switch, motor, and arm.A wiper generally consists of a metal arm; one end pivots, the other end has a long rubber blade attached to it. The arm is powered by a motor, often an electric motor. In this project, STM32F4xx-discovery board is used to demonstrate a wiper control system. In the STM32F4xx-discovery board LED's are used instead of DC motor and to indicate the change of speed of the wiper control system.The colours of these LEDs are orange, green, red, and blue. For the ignition of the system and change in the speed, PUSH button is used. The purpose of the project is to provide safety for the drivers which is a basic requirement in automotive industry.

# Components & Features

#### STM32F407VG Microcontroller Board 

* STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. 
* The STM32F405xx and STM32F407xx family incorporates high-speed embedded. It has upto 1 Mbyte of Flash memory, 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM,512 bytes of OTP memory,Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories. It has 3 V and 5 V external application power supply.

#### Software Requirements

* STM32 CUBE IDE is used for the software simulation. STM32CubeProgrammer (STM32CubeProg) provides an all-in-one software tool to program STM32 devices in any environment: multi-OS, graphical user interface or command line interface, support for a large choice of connections (JTAG, SWD, USB, UART, SPI, CAN, I2C), with manual operation or automation through scripting.


# Working Of the Project 
*	The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED starts continuously glowing until the stop of the engine. This tells that the system is turned ON.
* When the users press the input push button, the other three Blue, Green and Orange LEDs come ON one at a time with the low frequency.
* The frequency changes from low to high frequency (indication speed of the wiper control system) 3 frequency levels with 1, 4 and 8 Hz.
*	The LED glow pattern stops on the 4th press; the wiper action starts with the next press.
*	If the push button is pressed again for 2 seconds, the pattern stops bringing it to default position and the RED light goes off which signifies the engine is turned   OFF.


# SWOT Analysis

## Strength

* Low cost
* Better Battery life as ARM Processors have better battery life.
* Power consumption is less.
* Low latency and gives quicker response time.

## Weakness

* Implementation costs are high due to the sensors.

## Opportunity

* It is designed to provide adequate visibility to the drivers.
* Must safety measure.

## Threats

* Noise can occur due to the machinery.

# 4W's and 1H

## What 

A  wiper control system consisting of a wiper drive and two wiper arms.

## Where 

It is used in automative industries.

## Why

It is used as a safety measure for the users.

## When 

In difficult environmental conditions like rain or screen covered with mud, dust etc.

## How

By adjusting the wiper which is done by changing its speed to enhance the visibility.


# Details of Requirements

## High Level Requirements

![image](https://user-images.githubusercontent.com/71258149/168427975-090c87c5-405e-4783-8cde-6db99013d078.png)

## Low Level Requirements

![image](https://user-images.githubusercontent.com/71258149/168427993-64ab1221-21d9-43a5-814d-975ce7bfb408.png)



###### REFERENCE

*https://github.com/VIGNESH8629/M3_WIPER_CONTROL_SYSTEM
*https://github.com/SreeLikitha/M3_WiperControlSystem








