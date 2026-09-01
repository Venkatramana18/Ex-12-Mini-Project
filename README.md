# Ex-12 Mini Project
## WATER LEVEL MONITER USING ESP32

Submitted by:
VENKAT RAMANA S B ( 212224060296 )
Department of Electronics and Communication Engineering
Saveetha Engineering College

## ABSTRACT
Water level monitoring is an important application used in homes, industries, agriculture, and water storage systems. This project presents the design and implementation of an ESP32-based water level monitoring system using a water level sensor to continuously measure the amount of water present in a tank. The ESP32 microcontroller processes the sensor data and determines the current water level in real time. The measured information can be displayed on a computer or mobile device through an IoT-based monitoring interface. The system can also provide alerts when the water level becomes too low or reaches the maximum level, helping to prevent water shortage, overflow, and water wastage. This project demonstrates the integration of sensors, microcontrollers, and IoT technology to create a simple, efficient, and reliable water level monitoring system. The design is compact, cost-effective, and suitable for residential, agricultural, industrial, and educational applications.

TABLE OF CONTENTS

●Introduction
●Literature Survey
●Proposed Methodology
●Hardware Description
●Software Implementation
●Working Principle
●Applications
●Results and Discussion
●Conclusion and Future Scope
●References



## CHAPTER 1 – INTRODUCTION
Water level monitoring is the process of measuring and observing the amount of water present in a tank, reservoir, or storage system. It is widely used in homes, agriculture, industries, and water management systems to prevent water shortage, overflow, and unnecessary water wastage. With the increasing demand for smart and automated systems, there is a need for compact, low-cost, and reliable water level monitoring solutions. This project focuses on developing an ESP32-based water level monitoring system that can measure the water level in a tank and provide real-time information to the user. The system uses a water level sensor to detect the amount of water present in the tank and sends the sensor data to the ESP32 microcontroller for processing. The ESP32 determines the current water level and can display the information through a suitable monitoring interface. The system can also generate alerts when the water level becomes too low or reaches the maximum level, helping users manage water efficiently and prevent overflow.

## Objectives

● The main objectives of this project are:

● To design a simple water level monitoring system using ESP32.

● To measure and monitor the water level in a tank in real time.

● To display the detected water level through a suitable monitoring interface.

● To provide alerts when the water level is too low or reaches the maximum level.

● To understand the working of water level sensors, ESP32, and IoT technology.



## CHAPTER 2 – LITERATURE SURVEY

Water level monitoring systems have been widely studied and implemented in various fields such as agriculture, industries, domestic water tanks, and water management. Traditional methods mainly depend on manual checking of water levels, which can be time-consuming and may lead to water overflow or wastage. Recent studies have focused on developing automated water level monitoring systems using sensors such as ultrasonic sensors, water level sensors, and float sensors. These sensors can detect the water level and provide accurate measurements when connected to a microcontroller.

With the development of IoT technology, ESP32-based water level monitoring systems have become popular due to the ESP32's built-in Wi-Fi and Bluetooth capabilities. Researchers have used ESP32 to collect sensor data and transmit it to mobile applications or web-based platforms for real-time monitoring. Some systems also provide alerts when the water level is too low or reaches the maximum level. These studies show that ESP32-based water level monitoring systems are cost-effective, compact, reliable, and suitable for smart water management applications.

## CHAPTER 3 – PROPOSED METHODOLOGY

The proposed system consists of the following main components:

● ESP32 Microcontroller

● Water Level Sensor

● Jumper Wires

● Breadboard

● Power Supply / USB Cable

● Buzzer or LED for Alert

● Computer or Mobile Device for Monitoring



## CHAPTER 4 – HARDWARE DESCRIPTION

<img width="317" height="312" alt="2" src="https://github.com/user-attachments/assets/a34d0bf9-a806-4171-baec-0bc01f26c8e7" />



ESP32

ESP32 is a powerful microcontroller board developed by Espressif. It is widely used in IoT and embedded system projects because it provides built-in Wi-Fi and Bluetooth connectivity, along with multiple digital and analog input/output pins. In the water level monitoring system, the ESP32 receives data from the water level sensor, processes the information, and monitors the water level in real time. It can also send the collected data to a mobile device or web-based platform for remote monitoring.

Features:

ESP32 Microcontroller
34 GPIO pins
18 ADC channels
Built-in Wi-Fi and Bluetooth connectivity
Dual-core processor with up to 240 MHz clock speed
USB connectivity through development board
Low power consumption

The ESP32 is the main controller of the water level monitoring system. It receives data from the water level sensor, processes the information, and determines the current water level. Its built-in Wi-Fi capability allows the system to transmit water level data for remote monitoring.

Water Level Sensor

The water level sensor detects the amount of water present in the tank. It provides an electrical signal corresponding to the water level, which is read by the ESP32 through its analog input.

The sensor helps monitor whether the water level is low, medium, or high and can be used to identify conditions such as low water level or tank overflow.

Jumper Wires

Jumper wires are used to connect the water level sensor, ESP32, buzzer, LED, and other components. They provide electrical connections between the components and allow the circuit to be assembled easily on a breadboard.

Buzzer / LED

A buzzer or LED can be used to provide an alert when the water level reaches a predefined limit. For example, the system can activate the buzzer when the tank is full or the water level becomes critically low.

Power Supply

A USB cable or suitable power supply provides power to the ESP32 and connected sensors. The power source allows the system to operate continuously and monitor the water level in real time.
<img width="526" height="345" alt="1" src="https://github.com/user-attachments/assets/582ac904-4320-48a4-8078-5d4608e55b37" />



## CHAPTER 5 – SOFTWARE IMPLEMENTATION


The system is programmed using the Arduino IDE. The code reads the data from the water level sensor and processes it using the ESP32 microcontroller. The ESP32 continuously monitors the water level and determines whether the tank is at a low, medium, or high level. The measured data can be transmitted through Wi-Fi to a suitable mobile or web-based monitoring application for real-time observation.

● The program performs the following steps:

● Initialize the ESP32 and water level sensor.

● Read the sensor values.

● Process the sensor data.

● Calculate the water level.

● Display the water level status.

● Send the data through Wi-Fi for remote monitoring.

● Activate an alert when the water level is too low or reaches the maximum level.

## CHAPTER 6 – WORKING PRINCIPLE

The ESP32-based water level monitoring system works based on water level sensing and microcontroller processing. The water level sensor is placed inside or connected to the water tank to detect the amount of water present. As the water level changes, the sensor produces a corresponding electrical signal. The ESP32 reads and processes this sensor data to determine the current water level. The measured level is then displayed on a monitoring interface or sent through Wi-Fi for remote monitoring. If the water level becomes too low or reaches the maximum level, the system can activate an alert using a buzzer or LED. This provides a simple and efficient method for real-time water level monitoring and preventing water overflow or shortage.

## CHAPTER 7 – APPLICATIONS

The ESP32-based water level monitoring system can be used in various applications such as:

● Domestic water tank monitoring

● Agricultural irrigation systems

● Industrial water storage monitoring

● Smart home automation systems

● Water overflow prevention systems

● Reservoir and overhead tank monitoring

● IoT-based water management systems

The system can also be used in smart cities, water treatment plants, and remote monitoring applications where real-time water level information and automatic alerts are required.

## CHAPTER 8 – RESULTS AND DISCUSSION

The developed ESP32-based water level monitoring system successfully detects and monitors the water level in the tank using the water level sensor. As the water level changes, the sensor provides corresponding readings to the ESP32, which processes the data and determines the current water level accurately.

The results are displayed in real time through the monitoring interface or serial monitor. The system can also provide alerts when the water level becomes too low or reaches the maximum level, helping to prevent water shortage and overflow.

This demonstrates the successful integration of ESP32, water level sensor, and IoT-based monitoring to create a simple, reliable, and cost-effective water level monitoring system.

## CHAPTER 9 – CONCLUSION AND FUTURE SCOPE

Conclusion

The ESP32-based water level monitoring system was successfully designed and implemented. The system effectively detects and monitors the water level in a tank using a water level sensor and displays the status in real time.

The project helped in understanding the working of water level sensors, ESP32 microcontrollers, IoT connectivity, and embedded system programming. It provides a simple, reliable, and cost-effective solution for monitoring water levels and preventing water overflow or shortage.
## OUTPUT
<img width="317" height="312" alt="2" src="https://github.com/user-attachments/assets/775a5887-1a32-46f7-b026-47e9031bed9d" />
The system successfully monitors the water level in real time using ESP32.
The water level status is displayed, and alerts are provided for low or high water levels.
