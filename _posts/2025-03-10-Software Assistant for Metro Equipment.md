---
layout: page

---
## **Software Assistant for Metro Equipment**

![Project3]({{ site.baseurl }}/assets/images/3.jpg)

The **Software Assistant** is a comprehensive management system designed for metro onboard equipment. The system integrates multiple technologies to provide real-time monitoring, software updates, and management of metro devices.

## Key Components

- **Backend Server (C Language & BOA)**:  
  The backend of the system is powered by C language, running a BOA server that handles requests from the frontend and communicates with the Qt-based programs running on each metro board.

- **Frontend (HTML/CSS)**:  
  The frontend is built using HTML and CSS, providing a user-friendly interface where users can monitor the status of each device, update software, and perform other management tasks.

- **Qt-based Program on Each Board**:  
  A Qt application runs on each metro board to manage device interactions, send and receive data from the backend server, and update the device's software. The Qt program acts as the bridge between the backend and each device, allowing real-time status updates and control.

- **Main Server (Qt Communication)**:  
  The main server uses Qt to communicate with all the onboard devices, collect data, and push software updates. It serves as the central hub for managing the entire fleet of metro equipment.

## Features

- **Real-time Monitoring**:  
  The system enables real-time monitoring of onboard device statuses, allowing operators to ensure all devices are functioning properly.

- **Software Updates**:  
  The backend server facilitates the process of pushing software updates to each device, ensuring all devices remain up-to-date with the latest software version.

- **Device Management**:  
  Through the web interface, users can interact with the onboard devices, check their health, perform troubleshooting, and issue commands to each device.

## Technologies Used

- **Backend**:  
  C Language, BOA Server

- **Frontend**:  
  HTML, CSS

- **Qt**:  
  Qt for device communication and management

## Architecture

1. **Frontend (HTML/CSS)**:  
   The user interface built with HTML/CSS where operators can interact with the system.

2. **Backend Server (BOA)**:  
   The backend logic running on a C-based BOA server, handling HTTP requests and sending updates to the Qt applications.

3. **Qt Application on Devices**:  
   Each onboard device runs a Qt-based program to handle communication with the backend, monitor device status, and update device software.

## Conclusion
   This system helps operators manage and maintain metro equipment efficiently, ensuring the smooth operation of the entire metro fleet.
---

---
