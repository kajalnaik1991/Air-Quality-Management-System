# Air-Quality-Management-System
# Air Quality Monitoring System Using IoT

## Overview

The Air Quality Monitoring System is an Internet of Things (IoT) based solution developed to monitor environmental conditions in real time. The system measures air quality, temperature, and humidity using low-cost sensors integrated with an ESP8266 NodeMCU microcontroller. Sensor data is transmitted to the Arduino IoT Cloud platform, enabling remote monitoring through an interactive dashboard.

The project aims to provide an affordable, scalable, and efficient alternative to traditional air quality monitoring systems, making environmental monitoring more accessible for educational, residential, and industrial applications.

---

## Key Features

* Real-time monitoring of air quality, temperature, and humidity
* Wireless data transmission using ESP8266 Wi-Fi connectivity
* Cloud-based visualization through Arduino IoT Cloud
* Continuous sensor data logging and monitoring
* Low-cost and portable system architecture
* User-friendly dashboard for remote access

---

## System Architecture

The system consists of the following components:

* **ESP8266 NodeMCU** – Main controller and communication module
* **MQ135 Gas Sensor** – Air quality detection
* **DHT11 Sensor** – Temperature and humidity measurement
* **Arduino IoT Cloud** – Data storage and visualization platform

### Workflow

1. Environmental data is collected through MQ135 and DHT11 sensors.
2. ESP8266 processes sensor readings.
3. Data is transmitted over Wi-Fi.
4. Arduino IoT Cloud receives and stores the readings.
5. The dashboard displays real-time environmental parameters.

---

## Hardware Requirements

| Component       | Description                     |
| --------------- | ------------------------------- |
| ESP8266 NodeMCU | Wi-Fi enabled microcontroller   |
| MQ135 Sensor    | Air quality sensor              |
| DHT11 Sensor    | Temperature and humidity sensor |
| Breadboard      | Circuit prototyping             |
| Jumper Wires    | Hardware connections            |
| USB Cable       | Power and programming           |

---

## Software Requirements

* Arduino IDE
* Arduino IoT Cloud
* ESP8266 Board Package
* DHT Sensor Library
* ArduinoIoTCloud Library
* WiFi Connection Manager Library

---

## Parameters Monitored

* Temperature (°C)
* Humidity (%)
* Air Quality Level

---

## Results

The system successfully monitored environmental conditions and provided real-time updates through the cloud dashboard.

### Normal Indoor Environment

* Temperature: 29°C – 35°C
* Humidity: 40% – 70%
* Air Quality Value: 500 – 600

### Heat Exposure Testing

* Increase in temperature
* Reduction in humidity
* Observable changes in air quality values

The dashboard reflected environmental changes instantly, demonstrating reliable real-time monitoring and cloud synchronization.

---

## Applications

* Smart Homes
* Environmental Monitoring
* Industrial Safety
* Educational Projects
* Smart City Infrastructure
* Indoor Air Quality Assessment

---

## Future Enhancements

* Integration of PM2.5 and PM10 sensors
* SMS and mobile notification alerts
* Machine Learning based air quality prediction
* Voice assistant integration
* Large-scale smart city deployment
* Multi-location monitoring and analytics

---

## Authors


**Kajal Naik**



---


