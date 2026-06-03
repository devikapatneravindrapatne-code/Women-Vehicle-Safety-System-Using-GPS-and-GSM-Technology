# Women-Vehicle-Safety-System-Using-GPS-and-GSM-Technology
Developed a GPS and GSM-based emergency alert system using Raspberry Pi, enabling real-time location tracking and instant SMS notifications during emergencies. Integrated a panic button, GPS, and GSM modules to create a low-cost embedded safety solution for rapid communication and assistance.

Introduction

Safety is one of the most important requirements for women traveling alone. In many emergency situations, victims may not have sufficient time to make phone calls or explain their location. This project aims to provide an immediate alert mechanism that can be activated with a single button press. The system automatically sends the user's current location to trusted contacts, thereby reducing response time and increasing personal safety.

Problem Statement

Women often face unsafe situations while traveling alone, especially during night hours or in unfamiliar locations. Existing safety measures may not provide immediate assistance. Therefore, there is a need for a compact, reliable, and easy-to-use safety system that can quickly communicate the user's location during emergencies.

Objectives

To provide immediate emergency assistance.
To track the user's location using GPS.
To send emergency alerts through GSM communication.
To reduce response time during critical situations.
To develop a low-cost and portable safety solution.

Block Diagram

Panic Button
      ↓
ESP32 / Raspberry Pi
      ↓
GPS Module
      ↓
GSM Module
      ↓
Emergency Contacts

Working Principle

The system remains in monitoring mode.
During an emergency, the user presses the panic button.
The ESP32/Raspberry Pi receives the trigger signal.
The GPS module retrieves the current coordinates.
The controller formats an emergency message.
The GSM module sends the message to predefined emergency contacts.
Family members or authorities receive the location and provide assistance.

Expected Results

Successful emergency alert generation.
Accurate GPS location acquisition.
Instant SMS transmission to emergency contacts.
Faster response during emergencies.
Improved safety for women travelers.
