# Smart-Street-Lighting-and-energy-optimization
Aim:
 To Design an IoT-enabled street lighting system that automatically adjusts brightness based on ambience light and motion detection. The system should display operational status and power consumption data locally using display components, while also transmitting energy usage statistics to a cloud platform for optimization analysis 
Description:
The Smart Street Lighting and Energy Optimization System is an Internet of Things (IoT) based solution designed to improve the efficiency and management of street lighting infrastructure. Traditional street lighting systems consume a large amount of electricity because they remain fully illuminated throughout the night regardless of environmental conditions or traffic movement. This leads to unnecessary energy consumption and increased operational costs.

This project proposes a smart lighting system using an ESP32 microcontroller that automatically adjusts street light brightness based on ambient light levels and motion detection. The system uses an MH series light sensor to detect environmental lighting conditions and determine whether it is day or night. When sufficient daylight is detected, the street lights remain turned off to conserve energy.

During nighttime conditions, a PIR (Passive Infrared) motion sensor detects the movement of pedestrians or vehicles near the streetlight. When motion is detected, the street light increases its brightness to provide proper illumination. When no motion is detected, the brightness level is reduced to a low-power mode, thereby minimizing energy consumption.

To monitor energy usage, an ACS721 current sensor is integrated into the system. This sensor measures the current consumed by the streetlight, allowing the system to calculate power usage and analyze energy efficiency.

The system also includes an OLED display, which provides real-time local monitoring of system parameters such as ambient light level, motion detection status, and power consumption. This helps users or technicians quickly understand the operational condition of the system.

Additionally, the ESP32's built-in Wi-Fi capability enables the system to transmit collected data to a cloud platform. The cloud platform allows remote monitoring, data storage, and analysis of energy consumption patterns. This feature supports predictive maintenance, energy optimization, and system performance tracking.

Overall, this project demonstrates how IoT technology can be applied to create intelligent street lighting systems that reduce power consumption, improve energy management, and support smart city development.

