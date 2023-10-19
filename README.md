# Farm Automation Project

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Materials Used](#materials-used)
- [Software](#software)
- [Usage](#usage)
- [Future Works](#future-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the Farm Automation Project! This project aims to automate the irrigation system of a farm or greenhouse based on the specific water needs of different crops. By utilizing moisture sensors, this system can detect the moisture level in the soil and activate the water pump when the moisture level drops below a certain predefined threshold.

In addition to automated irrigation, the project also includes a manual control mode, allowing users to override the automated system for manual watering. A user-friendly web-based user interface (UI) has been developed to display relevant information and controls, making it easy to manage and monitor the irrigation process.

## Project Overview
The project is designed to achieve the following key objectives:
- **Automated Irrigation:** Use moisture sensors to monitor soil moisture levels and trigger the water pump when the moisture falls below a specified level for a particular crop.

- **Manual Control:** Implement manual control options for manual watering, allowing users to override the automated system.

- **Web-Based User Interface:** Develop a user-friendly web-based interface that provides real-time data and control options for monitoring and managing the irrigation system.

## Materials Used
The following materials and components were used to build the Farm Automation Project:

- **Raspberry Pi Pico:** Used as the microcontroller to control and manage the automation system.

- **Relays:** Employed for controlling water pumps or other irrigation-related devices.

- **Capacitive Moisture Sensors:** Utilized to measure soil moisture levels accurately.

## Software
The software for this project is implemented in MicroPython, a lightweight Python-based programming language. The software is responsible for reading moisture sensor data, controlling the water pump via relays, and managing the web-based user interface. The software logic incorporates both automated irrigation and manual control modes.

## Usage
To use the Farm Automation Project, follow these steps:

1. **Hardware Setup:** Connect the Raspberry Pi Pico to the moisture sensors and relays according to the project's wiring diagram and guidelines.

2. **Software Installation:** Flash the MicroPython firmware to the Raspberry Pi Pico and load the project's Python code onto the device.

3. **Web Interface:** Access the web-based user interface through a browser by navigating to the Raspberry Pi Pico's IP address. This interface provides real-time data and control options.

4. **Automated Mode:** Set the desired moisture thresholds for different crops and enable automated irrigation.

5. **Manual Control:** Use the web interface to manually control the water pump and irrigation system.

## Future Works
In the future, we plan to enhance the Farm Automation Project with the following features:

- **MQTT Protocol Integration:** Implement the MQTT (Message Queuing Telemetry Transport) protocol for efficient data exchange and communication between devices and systems.

- **Database Integration:** Set up a database to store historical data, allowing for data analysis, reporting, and improved control of the irrigation system.

## Contributing
We welcome contributions from the open-source community to help improve and expand this project. If you would like to contribute, please follow the guidelines in the project's repository and submit your pull requests.

## License
This project is released under the [MIT License](LICENSE). Feel free to use, modify, and distribute it in accordance with the terms of this license. Please review the full license for more details.

