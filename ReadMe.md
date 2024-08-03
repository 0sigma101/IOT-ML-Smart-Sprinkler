# IoT-based Smart Sprinkler System

![GitHub issues](https://img.shields.io/github/issues/0sigma101/IOT-ML-Smart-Sprinkler)
![GitHub forks](https://img.shields.io/github/forks/0sigma101/IOT-ML-Smart-Sprinkler)
![GitHub stars](https://img.shields.io/github/stars/0sigma101/IOT-ML-Smart-Sprinkler)
![GitHub license](https://img.shields.io/github/license/0sigma101/IOT-ML-Smart-Sprinkler)

## YouTube Video

[![Watch the video](https://img.shields.io/badge/Watch-Video-red)](https://www.youtube.com/watch?v=zUZkXgSlLq4)

## Overview

The IoT-based Smart Sprinkler System is designed to automate irrigation processes by analyzing real-time weather and soil data. This system integrates with BLYNK IoT to provide a comprehensive dashboard for monitoring and controlling sprinkler operations. The goal is to optimize water usage and ensure efficient irrigation based on current environmental conditions.

## Features

- **Real-time Weather Analysis:** The system gathers and processes weather data to make informed irrigation decisions.
- **Soil Data Monitoring:** Measures soil moisture levels to determine when watering is needed.
- **Automated Sprinkler Control:** Adjusts sprinkler operations based on weather and soil data.
- **BLYNK IoT Integration:** Provides a fully functional dashboard for real-time monitoring and control of the system.

## Components

1. **Hardware:**
   - Sensors for weather and soil data (DHT11 sensors, temperature sensors, Air Pressure Sensor, Light Sensor).
   - Microcontroller (ESP32) for data collection and processing.
   - Sprinkler control hardware (DC motor drivers,  Buzzer).

2. **Software:**
   - Microcontroller firmware to handle data collection and control logic.
   - BLYNK IoT platform for creating and managing the dashboard.
   - Data analysis algorithms for weather and soil data.

## Installation

### Hardware Setup

1. **Create the Circuit:**
   - Follow the circuit diagrams provided in the `smart_sprinkler.ino` file to connect sensors and actuators to the microcontroller.

### Software Setup

1. **BLYNK Configuration:**
   - Create a BLYNK project and obtain your authentication token.
   - Update the firmware code with your BLYNK authentication token.
   - Configure the BLYNK IoT dashboard following the setup instructions in the `dashboard` directory.
   - Refer to the Video to check for the dashboard variable

2. **Upload Code:**
   - Connect your ESP32 to your computer.
   - Open the provided Arduino sketch in the Arduino IDE.
   - Select the correct board and port from the `Tools` menu.
   - Upload the code to the Arduino.

## Usage

1. **Monitoring:**
   - Access the BLYNK IoT dashboard to view real-time data from the sensors.
   - Monitor soil moisture levels and weather conditions.

2. **Control:**
   - Use the dashboard to manually override sprinkler operations if needed.
   - Set up automated rules for sprinkling based on the data collected.

## Contributing

Contributions are welcome! Please follow these steps if you wish to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- BLYNK IoT for providing a versatile platform for IoT applications.
- Various open-source libraries and tools used in the project.

For any questions or support, please open an issue on this repository or contact the project maintainer.
