# Easy Park 🚗

![Easy Park](https://img.shields.io/badge/Easy_Park-Embedded%20Parking%20Assistant-blue)

Welcome to the **Easy Park** repository! This project focuses on creating an embedded parking assistant using the LPC1768 microcontroller and ultrasonic sensing technology. It provides real-time distance alerts through LEDs, a buzzer, and an LCD display. Additionally, it includes features for password protection and traffic simulation, making it a comprehensive solution for modern parking challenges.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Components](#components)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Parking in urban areas can be challenging. The **Easy Park** project aims to simplify this process. By using ultrasonic sensors to measure distance, it alerts users when they are too close to obstacles. The system uses visual and audio signals to provide immediate feedback, ensuring a safer parking experience.

For the latest releases, visit [this link](https://github.com/joseanmos/Easy_Park/releases). You can download the necessary files and execute them to set up your own parking assistant.

## Features

- **Real-time Distance Measurement**: Uses HC-SR04 ultrasonic sensors to measure the distance to obstacles.
- **Alert System**: Visual alerts through LEDs and audio alerts through a buzzer.
- **LCD Display**: Shows distance measurements and system status.
- **Password Protection**: Ensures that only authorized users can access certain features.
- **Traffic Simulation**: Simulates traffic conditions to test the system under various scenarios.
- **User-Friendly Interface**: Simple controls and displays for ease of use.

## Components

The following components are required to build the **Easy Park** system:

- **LPC1768 Microcontroller**: The brain of the project, handling all processing tasks.
- **HC-SR04 Ultrasonic Sensor**: Measures the distance to obstacles.
- **LEDs**: Provide visual alerts.
- **Buzzer**: Emits sound alerts.
- **LCD Display**: Shows relevant information.
- **Power Supply**: Provides necessary power to the components.
- **Breadboard and Jumper Wires**: For prototyping and connections.

## Installation

To get started with the **Easy Park** project, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/joseanmos/Easy_Park.git
   ```

2. **Set Up the Environment**: Ensure you have Keil uVision5 installed for programming the LPC1768.

3. **Connect Components**: 
   - Connect the HC-SR04 to the LPC1768 according to the wiring diagram in the repository.
   - Connect the LEDs, buzzer, and LCD display.

4. **Upload the Code**: Open the project in Keil uVision5 and upload the code to the LPC1768.

5. **Run the System**: Power on the system and observe the functionality.

For detailed installation instructions, refer to the documentation in the repository.

## Usage

Using the **Easy Park** system is straightforward. Once installed, follow these steps:

1. **Power On**: Turn on the system.
2. **Password Entry**: If prompted, enter the password to access advanced features.
3. **Parking Mode**: Activate parking mode to start receiving distance alerts.
4. **Monitor Alerts**: Watch the LEDs and listen for the buzzer as you approach obstacles.

For any issues or questions, refer to the troubleshooting section in the documentation.

## Project Structure

The repository is organized as follows:

```
Easy_Park/
├── src/
│   ├── main.c
│   ├── sensor.c
│   ├── display.c
│   └── alert.c
├── include/
│   ├── sensor.h
│   ├── display.h
│   └── alert.h
├── docs/
│   ├── installation_guide.md
│   └── user_manual.md
└── README.md
```

- **src/**: Contains the source code files.
- **include/**: Contains header files for the project.
- **docs/**: Contains documentation files for installation and usage.

## Contributing

We welcome contributions to improve the **Easy Park** project. If you have ideas or improvements, please follow these steps:

1. **Fork the Repository**: Create your own copy of the project.
2. **Create a Branch**: Use a descriptive name for your branch.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Implement your changes and test them.
4. **Submit a Pull Request**: Share your changes with us for review.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as you wish, but please maintain attribution to the original authors.

## Contact

For questions or support, please reach out to the project maintainer:

- **Name**: Josean Mos
- **Email**: joseanmos@example.com

Thank you for your interest in the **Easy Park** project! For the latest releases, check out [this link](https://github.com/joseanmos/Easy_Park/releases). Download the necessary files and execute them to start your journey with embedded parking assistance.