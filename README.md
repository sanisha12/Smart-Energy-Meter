# Smart Energy Meter (SEM) Project

## Overview

This project focuses on enhancing energy management through a Smart Energy Meter (SEM) module, which integrates IoT technology for real-time monitoring and reporting of energy consumption. The SEM module uses advanced sensors and Wi-Fi communication to provide precise, minute-resolution data on electricity usage. Key features include real-time energy consumption tracking, theft detection, remote monitoring, and two-way communication with utility providers. This system helps consumers manage their energy use more efficiently, reduces costs, and supports utilities in real-time supply and demand management. Additionally, it offers significant benefits such as accurate billing, reduced tampering, and lower carbon emissions.

## Features

- **Real-time Monitoring:** Provides precise, minute-resolution data on energy consumption.
- **Two-way Communication:** Allows communication between the meter and utility providers for maintenance and control.
- **Theft Detection:** Detects and reports energy theft.
- **Remote Monitoring:** Enables users to monitor energy usage via a web application.
- **Accurate Billing:** Eliminates estimated bills by providing exact usage data.
- **Energy Management:** Helps consumers manage and reduce their energy consumption and costs.

## Components

### Hardware Requirements

- ESP8266 12E
- ACS712 Current Sensor
- 0.96 OLED Display
- BT136 Triac
- MOC3021 Opto Triac
- MCT 2E
- LM1117 3.3V LDO Regulator
- 5V SMPS Module

### Software Requirements

- Programming IDE: Arduino 1.6.12
- Programming Language: Embedded C
- Compiler: AVR GCC
- Programmer: Arduino Bootloader

## Functional Requirements

- **Consumer Interface:** Provides real-time energy consumption data to consumers.
- **Metering Operator:** Enables remote reading and two-way communication for system maintenance and control.
- **Commercial Aspects:** Supports advanced tariff systems and remote on/off control supply.
- **Security:** Ensures secure data communication and fraud prevention.

## Non-Functional Requirements

- **Performance:** Provides high accuracy and reliability in energy measurement.
- **Usability:** User-friendly interface for easy monitoring and control.
- **Scalability:** Capable of handling increased data loads and additional features.
- **Security:** Implements strong data protection measures.

## Methodology

1. **Energy Measurement:** Uses the ACS712 current sensor to measure energy consumption.
2. **Data Processing:** Employs the ESP8266 12E microcontroller to process the data.
3. **Communication:** Utilizes Wi-Fi to upload data to the cloud for real-time monitoring.
4. **User Interface:** Displays energy consumption data on a 0.96 OLED screen and a web application.

## Installation

1. **Hardware Setup:**
   - Connect the ACS712 current sensor, OLED display, and other components to the ESP8266 12E.
   - Ensure proper power supply using the 5V SMPS module and regulators.

2. **Software Setup:**
   - Install Arduino IDE and necessary libraries for ESP8266 and sensors.
   - Load the provided Arduino sketch onto the ESP8266 microcontroller.

3. **Cloud Integration:**
   - Set up a cloud server to receive and store data from the SEM module.
   - Configure the web application for data visualization and monitoring.

## Usage

1. Power up the SEM module and connect it to a Wi-Fi network.
2. Access the web application to monitor real-time energy consumption.
3. Use the OLED display for on-site data viewing.
4. Set alerts and notifications for unusual consumption patterns or theft detection.

## Benefits

- **Accurate Consumption Tracking:** Provides precise data, helping users understand and reduce energy usage.
- **Cost Savings:** Helps in reducing energy bills by promoting efficient energy usage.
- **Enhanced Security:** Detects and reports energy theft, ensuring reliable service.
- **Convenient Monitoring:** Offers remote monitoring capabilities through a web application.

## Future Scope

- **Machine Learning Integration:** Implement algorithms for more accurate and adaptive energy consumption analysis.
- **Biometric Security:** Incorporate fingerprint and facial recognition for enhanced security.
- **Vehicle Communication Systems:** Integrate vehicle-to-everything (V2X) communication for better grid management.
- **Cloud-Based Monitoring:** Utilize cloud platforms for centralized monitoring, data analysis, and system optimization.

## Conclusion

The Smart Energy Meter (SEM) module offers a comprehensive solution for modern energy management. By providing real-time data and enhancing communication between consumers and utility providers, it promotes efficient energy use and cost savings. This project showcases the potential of IoT in revolutionizing the energy sector and contributing to a smarter, more sustainable future.
