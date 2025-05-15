# CSUN-ECE425-FINAL-PROJECT
Instructor: Aaron Nanas
Author: Hem Nagoo

# Introduction
This repository hosts the complete Keil µVision project files and source code for my final project in ECE 425L: Microprocessor Systems Laboratory. The project implements an Ultrasonic Object Tracking System using the TM4C123GH6PM microcontroller (EduBASE board), a US-100 ultrasonic sensor operating in UART mode, and an SG90 servo motor.

The system performs a continuous 180° sweep, and when it detects an object within a specified threshold distance, it locks on to the target and begins tracking its movement. The object’s distance and status ("Finding enemy" or "Target locked") are shown in real time on the EduBASE 16x2 LCD display. This project showcases an integration of peripheral drivers and embedded programming to build a real-time interactive system.

#  Results and Video Demonstration Link
https://drive.google.com/file/d/1GNAEnxigGnocDHizQVM3YNYUkT3DbUKr/view?usp=sharing

![image](https://github.com/user-attachments/assets/12dc9df7-1057-4e59-92c3-6fa34a458eff)

# Background and Methodology
This project applies several embedded systems concepts covered throughout the semester, including:
1) UART Communication: Used to interface with the US-100 ultrasonic sensor in UART mode.
2) PWM via General-Purpose Timer (PWM0): Used to control a standard servo motor for scanning.
3) GPIO: For LCD control and optional LED indicators.
4) SysTick Timer: For generating delays and timing intervals.
5) LCD Interface: Used to show real-time tracking information (distance and status).

# Functional Block Diagram
![image](https://github.com/user-attachments/assets/6a9f0baa-264b-44fa-96dd-a53e6995b845)


# Components Used
1)TM4C123GH6PM	
2) US-100 Ultrasonic Sensor
3) Micro Servo Motor
4) 16x2 LCD Display
5) Jumper Wires
6) USB Micro Cable
7) EduBASE board
   

# Pinout Used

![image](https://github.com/user-attachments/assets/cf31e2ed-aa7d-4d53-9f5b-f658cdbb5e29)

