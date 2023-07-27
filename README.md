# Autonomous Indoor Drone 
Welcome to the documentation for the Autonomous Indoor Drone project! This project was undertaken as a one-semester endeavor by a team of 7 individuals. The goal of this project was to design and develop an autonomous drone capable of navigating and performing tasks within indoor environments. This documentation serves as a comprehensive guide to understanding the project's objectives, implementation, and future possibilities.

## Table of Contents

- [Features](#features)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Screenshots or Demo](#screenshots-or-demo)

## Features
The Autonomous Indoor Drone project comes equipped with several impressive features, making it a highly capable system for navigating and operating within indoor environments. The key features of the project are as follows:

### Autonomous Navigation 
The drone is capable of autonomously navigating to desired location points (x, y, z) within an indoor setting. Leveraging advanced algorithms, the drone plans its path to reach its destination.

### Python and ROS Integration
The project extensively utilizes Python and the Robot Operating System (ROS) framework. Python's versatility and ROS's modular architecture enable seamless communication and control between different components of the drone system.This also can be used to receive the drone's data like the Mission planner did.

### Localization Visualization with RVIZ
The drone's localization is visually represented through RVIZ, a powerful visualization tool in ROS. Users can observe real-time updates of the drone's position, orientation, and sensor data, enhancing situational awareness during autonomous flight.

### Waypoint Planning
Users can define waypoints for the drone to follow autonomously. The drone efficiently plans its path between waypoints, ensuring smooth and efficient traversal throughout the indoor environment.

### Real-time Telemetry (Mission Planner)
The drone provides real-time telemetry data, including battery status, GPS coordinates, altitude, and sensor readings. This data is essential for monitoring and ensuring the drone's health and safety during operation.The data will be displayed on Mission Planner

### Versatile Payload Support
The drone's design allows for the attachment of various payloads, such as cameras, sensors, or small delivery mechanisms, making it suitable for a wide range of applications, including surveillance, monitoring, and research.

---

### Prerequisites
Pixhawk Flight Controller and ArduCopter firmware.
Raspberry Pi as the onboard computer.
Router to establish a connection between the onboard computer and the main computer for RVIZ visualization.
Intel RealSense T265 camera for accurate localization in the X and Y directions.
LIDAR (Light Detection and Ranging) sensor for precise localization in the Z direction.

---

### Installation
To get started with the Autonomous Indoor Drone, follow these steps:

Install Mission Planner:
Download and install Mission Planner on your main computer. Mission Planner is a powerful ground control station that allows you to plan and monitor drone missions you need to set up the parameter for the drone so that the drone can fly autonomously with IntelRealsense T265.

ROS Installation:
Install ROS on both the onboard computer (Raspberry Pi) and the main computer. ROS provides a flexible and modular framework for managing the drone's software components.

MAVROS Package Installation:
Install the MAVROS package on the onboard computer. MAVROS acts as a bridge between the Pixhawk Flight Controller and ROS, enabling seamless communication.

Other Requirements:
Ensure you have fulfilled all other requirements listed in the provided link: https://ardupilot.org/dev/docs/ros-vio-tracking-camera.html

These prerequisites and installations are essential for the successful setup and operation of the Autonomous Indoor Drone. Make sure to follow each step carefully to ensure a smooth and efficient implementation of the project.

---

### Usage
The Autonomous Indoor Drone project has been designed with a primary application in mind: integration into a Warehouse Management System. Leveraging its autonomous flight capabilities and RFID scanning functionality, the drone offers a valuable solution for warehouse operations. Below is a detailed description of how the drone is intended to be used in this context:

#### Warehouse Inventory Management
The drone is equipped with a high-precision RFID scanner, enabling it to efficiently scan RFID tags affixed to the inventory items in the warehouse. By autonomously flying between the racks and shelves, the drone can perform rapid and accurate inventory checks, significantly reducing the time and labor required for manual inventory audits.

#### Stock Reconciliation
With the ability to navigate through the warehouse autonomously, the drone can aid in stock reconciliation tasks. By cross-referencing the RFID-tagged items with the digital inventory records, discrepancies between physical stock and database records can be identified and addressed promptly.

#### Real-time Data Updates
As the drone performs inventory scans, it can provide real-time updates to the Warehouse Management System. This ensures that the database remains current and reflects the latest stock status, enabling efficient order fulfillment and accurate demand forecasting.

#### Customizable Integration
The project's modular architecture allows for easy integration into existing Warehouse Management Systems. Warehouse owners and managers can adapt the drone to suit their specific requirements and workflows seamlessly. The potential applications of the Autonomous Indoor Drone extend beyond warehouse management, making it a versatile tool for various indoor environments. With its robust features and autonomous capabilities, the drone opens doors to enhanced efficiency and streamlined operations in various industries.

---

## Screenshots or Demo
![Image Alt Text](Images/drone_1.png)
![Image Alt Text](Images/drone_1.png)
![Image Alt Text](Images/drone_1.png)

---
Bonus Picture me and my teams :)
![Image Alt Text](Images/Teams.png)



