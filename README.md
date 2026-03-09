# Smart-Street-Lighting-and-energy-optimization

## Overview

The Smart Street Lighting and Energy Optimization System is an Internet of Things (IoT) based solution designed to improve the efficiency and management of street lighting infrastructure. Traditional street lighting systems consume large amounts of electricity because lights remain fully illuminated throughout the night regardless of environmental conditions or traffic movement. This leads to unnecessary energy consumption and increased operational costs.

This project introduces an intelligent street lighting system that automatically adjusts brightness based on ambient light conditions and motion detection, thereby reducing energy waste while maintaining safety and visibility.


## System Architecture

The system is built around an ESP32 microcontroller, which acts as the main processing unit. It collects data from sensors, controls the lighting behavior, and communicates with cloud services for monitoring.

## Working Principle

An MH-series light sensor detects ambient light levels to determine whether it is day or night.

During daytime, when sufficient natural light is present, the street lights remain turned off to conserve energy.

At night, the system activates motion detection using a PIR sensor.

When pedestrians or vehicles are detected, the street light increases brightness to provide proper illumination.

If no motion is detected, the light switches to a low-power dim mode to reduce energy consumption.

## Energy Monitoring

To analyze energy usage, the system integrates an ACS721 current sensor. This sensor measures the current drawn by the streetlight, enabling the system to estimate power consumption and evaluate overall energy efficiency.

## Local Monitoring

An OLED display is included to provide real-time monitoring of system parameters, including:

Ambient light levels

Motion detection status

Power consumption

This allows technicians or users to quickly understand the operational condition of the system directly on the device.

## Cloud Integration

The ESP32’s built-in Wi-Fi capability enables the system to transmit collected data to a cloud platform. The cloud service allows:

Remote monitoring of streetlight status

Data storage for historical analysis

Energy consumption tracking

Predictive maintenance insights

This makes the system suitable for integration into smart city infrastructure.

## Hardware Components

The project uses the following hardware components:

ESP32 Microcontroller

PIR Motion Sensor

MH-Series Light Sensor

ACS721 Current Sensor

OLED Display

LED (Street Light Simulation)

Breadboard

Jumper Wires

## Key Features

Automatic brightness control based on ambient light

Motion-based lighting activation

Energy consumption monitoring

Real-time local display using OLED

Wi-Fi based cloud monitoring

Energy-efficient street lighting management

## Applications

Smart City Infrastructure

Energy Efficient Public Lighting

IoT-based Urban Monitoring Systems

## Conclusion

This project demonstrates how IoT technology can be used to develop intelligent and energy-efficient street lighting systems. By combining sensors, real-time monitoring, and cloud connectivity, the system helps reduce electricity consumption, optimize lighting usage, and support the development of sustainable smart cities.
