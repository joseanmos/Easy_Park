# Easy_Park

# EasyPark – Smart Parking Assistance System

**EasyPark** is an embedded systems mini-project designed to assist with safe and efficient vehicle parking. It uses ultrasonic distance measurement and provides both visual and auditory feedback to help prevent collisions.

## Features

- Real-time distance measurement (up to 3mm accuracy)
- 16x2 LCD display showing live distance data
- Visual alert system using multiple LEDs
- Buzzer alert when an object is dangerously close (< 20 cm)

## Hardware Used

- LPC1768 ARM Cortex-M3 Microcontroller
- HC-SR04 Ultrasonic Sensor
- 16x2 Character LCD
- 8 LEDs (connected to GPIO)
- Buzzer
- Power supply (5V regulated)
- Jumper wires and connectors

## Software & Tools

- Keil uVision IDE
- Embedded C
- LPC1768 peripheral libraries
- NXP documentation

## Working Principle

The HC-SR04 ultrasonic sensor emits ultrasonic pulses and listens for echoes. The LPC1768 measures the time delay to calculate distance. The system uses this data to:

- Display distance on the LCD
- Trigger LEDs in sequence based on proximity
- Activate a buzzer if the object is too close

## System Flow

1. System initializes 
2. Once authenticated, it begins continuous distance monitoring
3. Alerts are triggered based on object proximity
4. Optional modules demonstrate use cases like traffic monitoring

## Project Report

Detailed documentation including diagrams, component explanations, use-case simulations, and source code is available in the report:

[📄 Group9_ES_merged.pdf](./docs/Group9_ES_merged.pdf)

## Repository Structure


```
EasyPark/
├── src/                  # Source code
│   └── main.c
├── docs/                 # Project documentation
│   └── Group9_ES_merged.pdf
├── README.md
└── LICENSE
```

## 🧑‍💻 Contributors

* Akshar Agrawal – 230911534
* Urvi Kedar Mapsenkar – 230911538
* Soham Singh – 230911528
