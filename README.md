# Industrial IoT Monitoring Platform (CASIRI)

Industrial IoT monitoring platform designed to collect, transmit, and visualize real-time industrial data using MQTT Sparkplug B and SCADA integration.

This project demonstrates how industrial data can be acquired, processed, and monitored using a modern IIoT architecture combining Python, MQTT, Ignition SCADA, and MySQL.

---

## Project Overview

The goal of this project was to develop a monitoring platform capable of acquiring industrial data from sensors and transmitting it to a SCADA system using industrial communication standards.

The system implements a complete Industrial IoT pipeline:

* Sensor data acquisition
* MQTT Sparkplug B communication
* Real-time monitoring through SCADA
* Data storage in relational databases
* Industrial protocol integration

This project was developed as part of an industrial research initiative in collaboration with **Universidad Industrial de Santander and DAUTOM**.

---

## Key Features

• Industrial data acquisition using Python
• MQTT communication using the Sparkplug B protocol
• Integration with HiveMQ broker
• Real-time visualization using Ignition SCADA
• Structured data storage using MySQL
• Modular system architecture for industrial environments

---

## System Architecture

The platform follows a typical Industrial IoT architecture:

Sensors / Industrial Data Sources
↓
Python Data Acquisition Layer
↓
MQTT Publisher (Sparkplug B)
↓
HiveMQ Broker
↓
Ignition SCADA Platform
↓
MySQL Database Storage

This architecture allows scalable integration of industrial devices and monitoring systems.

![Graphical abstract](/arquitecture/system_arquitecture.png)

---

## Technologies Used

**Programming**

Python

**Industrial Communication**

MQTT
Sparkplug B

**Industrial Software**

Ignition SCADA

**Data Infrastructure**

MySQL

**Messaging Broker**

HiveMQ

---

## My Contributions

My main contributions to the project included:

* Development of Python scripts for industrial data acquisition
* Implementation of MQTT communication using Sparkplug B
* Integration with the SCADA monitoring platform
* Data structuring and storage using MySQL
* System testing and validation in an industrial monitoring environment

---

## Repository Structure

```
casiri-iiot-monitoring-system/

README.md
Videos.md

scripts/CASIRI
    camera
    weather_station
    readme.txt

architecture/
    system_architecture.png

dashboard_images/
    home_dashborad.jpg
    camera_dashborad.jpg
    variable_dashborad.jpg

```

---

## Example Data Flow

1. Sensor data is acquired.
2. Python scripts package the data following the Sparkplug B format.
3. Data is published to the MQTT broker.
4. Ignition SCADA subscribes to the MQTT topics.
5. Data is visualized and stored in the MySQL database.

---

## Project Context

This repository contains a **portfolio-oriented version** of the CASIRI Industrial IoT monitoring project.

The original project was developed within the **Universidad Industrial de Santander and DAUTOM** as part of an industrial collaboration initiative. This can be visited in https://github.com/uis-dautom/CASIRI

Some elements of the full system are not included due to institutional repository management.

---

## Contact
For more information about the project, feel free to visit: https://sites.google.com/e3t.uis.edu.co/proyectoiiot/subproyectos/e3t/casiri?authuser=0

If you are interested in Industrial IoT, automation, or monitoring systems, feel free to connect.
LinkedIn: (https://www.linkedin.com/in/andr%C3%A9s-felipe-rubio-toloza-a8b6001b9/)

