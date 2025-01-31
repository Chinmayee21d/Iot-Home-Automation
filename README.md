# IoT Home Automation System using Cisco Packet Tracer

## Overview

This project demonstrates an IoT (Internet of Things) home automation system simulated using **Cisco Packet Tracer**. It showcases the integration of IoT devices such as smart lights, thermostats, air conditioners, windows, and smart plugs into a home network. The system allows for intelligent automation, such as turning off the air conditioner when a window is open. This setup simulates a smart home where devices can be controlled remotely via a mobile app or web interface, and automate based on environmental conditions.

## Features

- **Smart Light Control**: Turn smart lights on/off remotely.
- **Smart Thermostat**: Adjust the temperature settings remotely.
- **Smart AC Control**: Turn the air conditioner on/off.
- **Window Sensor Integration**: When the window is open, the air conditioner automatically turns off.
- **Smart Plugs**: Control appliances connected to smart plugs.
- **Centralized Control**: Access and manage devices from a central device like a smartphone or laptop.
- **Basic Networking**: Utilizes basic networking concepts, including IP addressing, routing, and device communication.

## Prerequisites

- Basic understanding of networking concepts (IP addressing, routers, switches).
- Familiarity with Cisco Packet Tracer.
- A Cisco Packet Tracer version that supports IoT devices (Packet Tracer 7.3 and above).

## Setup Instructions

1. **Download Cisco Packet Tracer**:
   - Install the latest version of Cisco Packet Tracer if not already installed.

2. **Open the Packet Tracer File**:
   - Download the provided `.pkt` file or create a new workspace in Packet Tracer.
   - Open the file in Cisco Packet Tracer to view and modify the setup.

3. **Configure the Network**:
   - Ensure all IoT devices are connected to the network via switches and routers.
   - Assign static IP addresses to each IoT device for easy communication.

4. **Control the Devices**:
   - Use user devices (smartphones or PCs) to control the IoT devices.
   - Devices can be controlled manually or set to automate actions based on certain triggers, like the window sensor.

## How It Works

- The IoT devices (smart lights, thermostats, smart plugs, air conditioners, and window sensors) are connected to a home network.
- A smartphone or PC simulates a user interface that can control the devices.
- **Automation**: The window sensor detects when the window is open. If the window is open, the air conditioner is automatically turned off to save energy and prevent cooling loss.
- **User Control**: Users can still manually override the automation from their smartphones or computers.
- IoT devices communicate over the network, sending data such as status updates (e.g., whether a light is on or off) to the central controller.
- Optionally, a cloud or server can be added for remote control capabilities.
  
## Project Screenshot

- Here’s a screenshot of the IoT home automation setup in Cisco Packet Tracer:
![Screenshot (295)](https://github.com/user-attachments/assets/52bf9ebd-b13b-4efd-a283-b772d0a8627c)
![Screenshot (291)](https://github.com/user-attachments/assets/586cae27-ce6d-4fbd-a96d-fdde75bbb407)
![Screenshot (289)](https://github.com/user-attachments/assets/ff552f38-950b-4a7e-854d-21d1a4c13cfb)


## Future Enhancements

- **Voice Control**: Integrate voice assistants like Amazon Alexa or Google Assistant (simulated).
- **Energy Efficiency**: Implement further automation based on environmental conditions, such as turning off lights when there’s enough daylight.

## License

This project is for educational purposes only. Feel free to modify and share with proper attribution.

