# Automated Headlight Dimmer & Adaptive Driving Beam (ADB) Prototype

![Hardware](https://img.shields.io/badge/Hardware-ATmega328-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Prototyping-green?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Automotive%20IoT-red?style=for-the-badge)

## 📋 Project Overview (Team Navaacharana)
This project outlines the system architecture and prototype design for an Automatic Headlight Dimmer to improve night-time road safety. By automating the transition between high and low beams, this system aims to eliminate the sudden glare experienced by oncoming drivers, commonly known as the "Troxler Effect". 

*(Note: Add your MP4 video here by dragging and dropping it from your computer directly into the GitHub editor!)*

## ⚠️ The Problem
* **Night-time Hazards:** In 2022, approximately 20.4% of accidents on single-lane roads occurred at night due to poor visibility and high-beam misuse.
* **The Troxler Effect:** A high beam from an oncoming vehicle causes a blinding glare, temporarily reducing a driver's visibility to almost zero. 
* **Human Error:** The primary cause is driver unawareness or fatigue regarding when to manually dip headlights.

## ⚙️ System Architecture & Technology
The core prototype operates using a responsive hardware-software loop:
* **Sensing Layer:** Utilizes a Light Dependent Resistor (LDR) sensor that acts as a variable resistor, changing its resistance based on the intensity of oncoming light.
* **Processing:** An **ATmega328 Microcontroller** serves as the brain, processing the LDR inputs to detect specific light source frequencies (200 – 400 kHz).
* **Actuation / ADB Integration:** The system is designed to scale into an Adaptive Driving Beam (ADB) system. It interfaces with an electronic control unit (ECU) to dynamically dim individually addressable LEDs within the headlight array.

## 📈 Market Commercialization Potential
The automotive smart-lighting sector presents a massive opportunity for scalable IoT integration:
* **Total Addressable Market (TAM):** $108.10 Billion USD.
* **Serviceable Obtainable Market (SOM):** $25 Billion USD.
* **Serviceable Available Market (SAM):** $10 - $15 Billion USD.

## 🚀 Future Scope
Beyond simple dimming, the integration of ultra-low latency LED technology allows for highly dynamic control. The future architecture aims to optimize lighting scenarios in real-time, improving visibility for the driver without blinding preceding or oncoming vehicles.
