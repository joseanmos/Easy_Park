# Easy_Park

# 🚗 EasyPark – Smart Parking Assistance System

EasyPark is an embedded systems mini-project developed to assist in safe and efficient reverse parking using ultrasonic distance measurement. Built using the **LPC1768 ARM Cortex-M3** microcontroller and the **HC-SR04 ultrasonic sensor**, the system provides both **visual** and **audio** cues to help prevent collisions.

## 🔧 Features

* Real-time distance measurement (accuracy up to 3mm)
* 16x2 LCD display for live distance feedback
* Visual alert system using LEDs
* Buzzer alert when object is dangerously close (< 20 cm)
* Password-protected system startup
* Additional simulation features:

  * Blind spot/rear detection
  * Traffic flow counting
  * Smart speed bump violation alert
  * Forward obstacle prevention

## 🧰 Hardware Used

* LPC1768 Microcontroller
* HC-SR04 Ultrasonic Sensor
* 16x2 LCD Display
* 8 LEDs (distance indicators)
* Buzzer
* Power Supply (5V regulated)
* Connecting cables (FRC, jumper wires)

## 🖥️ Software & Tools

* Keil uVision IDE
* Embedded C
* NXP Documentation & Libraries

## 🧠 Working Principle

The HC-SR04 sensor sends ultrasonic waves which reflect off obstacles. The LPC1768 measures the time taken for the echo to return and calculates the distance using the speed of sound. Based on this data:

* The **LCD** displays distance.
* **LEDs** light up progressively as the object nears.
* The **buzzer** activates when distance < 20 cm.

## 📐 System Flow

1. System initialization
2. Password authentication via keypad
3. Continuous distance monitoring
4. Alerts triggered based on distance
5. Optional simulation modules for traffic and safety use-cases

## 📸 Demonstration

Check the project report (`Group9_ES_merged.pdf`) for:

* Circuit diagrams
* Flow diagrams
* Hardware setup photographs

## 🧾 Documentation

📄 **Project Report**: [Group9\_ES\_merged.pdf](./Group9_ES_merged.pdf)

This includes:

* Full component descriptions
* Circuit schematics
* Code explanation
* Use-case simulations
* Photographs and results

## 📂 Repository Structure

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
