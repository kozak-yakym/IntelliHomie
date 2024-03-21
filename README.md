# IntelliHomie open source project.

[Git repo: git@github.com:kozak-yakym/IntelliHomie.git](https://github.com/kozak-yakym/IntelliHomie)

## Table of Contents
- [Introduction](#introduction)
- [Modules and Submodules](#modules-and-submodules)
  - [A fleet of robots](#a-fleet-of-robots)
  - [Central Part](#central-part)
    - [Integration with Robot](#integration-with-robot)
    - [AI Object Recognition](#ai-object-recognition)
    - [Navigation](#navigation)
    - [Cartography](#cartography)
    - [Remote Control and Telecommunication](#remote-control-and-telecommunication)
    - [Intelligent Task Execution](#intelligent-task-execution)
    - [Smart Home Integration](#smart-home-integration)
    - [Porting to a Compact form-factor](#porting-to-a-compact-form-factor)
  - [Submodules](#submodules)
    - [Safety Submodule](#safety-submodule)
- [Contributing](#contributing)
- [License](#license)

[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine/)

## Introduction

## Overview
This open-source initiative aims to revolutionize the smart home landscape by introducing an advanced control system powered by artificial intelligence. Our project transcends traditional smart home scenarios, focusing on automating household processes with a keen emphasis on safety, efficiency, and user engagement.

## Motivation
The inspiration behind this endeavor is to foster a harmonious environment where humans and pets coexist with technology in a seamless manner. By leveraging AI, we strive to create intuitive interactions and provide a layer of intelligence that anticipates and caters to the occupants' needs, ensuring their comfort and security.

## Current Status
Currently, the project is in the development phase, with a beta version on the horizon. The system's architecture is modular, allowing for flexible enhancements and integrations. It features a central hub that orchestrates a fleet of home robots, each equipped with capabilities such as sophisticated navigation, precise task execution, and a robust testing environment for firmware and neural networks. Documentation is continuously updated to reflect the system's evolution and ease of integration with existing smart home ecosystems.
More detailed status can be found on the [Kanban board of our project](https://github.com/users/kozak-yakym/projects/1).

# Central Component

## Intelligent Gateway
The heart of our project is an intelligent gateway designed to enhance the capabilities of smart home systems. Initially planned to be implemented on a Linux PC, this central hub serves as the brain of the operation, orchestrating a seamless interaction between various home automation modules. The AI-driven core of the gateway will allow it to adapt to the changes that are constantly taking place in the home, providing a personalised experience for users and a robust platform for developers.

## Interaction with Other Modules
At its inception, the gateway will function as a standalone unit, supporting a single robot designed to work with the system. As the project evolves, we plan to integrate it with popular smart home ecosystems like HomeAssistant or Hubitat, expanding the gateway's compatibility and control over a diverse range of devices. Future updates will introduce support for additional robot APIs and the ability to scale the fleet of service robots.

## Connectivity
The initial phase focuses on local network connectivity, ensuring a secure and responsive system. Subsequent phases will explore the integration of Bluetooth and ZigBee, broadening the gateway's communication capabilities. This forward-thinking approach lays the groundwork for a versatile and expandable smart home solution.

# Modules and Submodules

## A fleet of robots

The IntelliHomie system is designed to be the central hub for a diverse fleet of robots with different APIs. Our vision is to create a versatile and inclusive ecosystem that supports integration of various robotic platforms, enabling them to work in harmony within the smart home environment.

To kickstart this ambitious integration, we are beginning with our custom-built [IntelliHomie-Roboplatform](https://github.com/kozak-yakym/IntelliHomie-Roboplatform). This platform is tailored to align closely with the IntelliHomie system, providing a seamless experience and robust functionality right out of the box. The IntelliHomie-Roboplatform serves as the first step towards realizing our goal of a fully integrated, multi-robot smart home solution.

More about this roboplatform: [github.com/kozak-yakym/IntelliHomie-Roboplatform](https://github.com/kozak-yakym/IntelliHomie-Roboplatform)

## Central Part
The Central Part serves as the intelligent gateway and control center for the smart home system.

### Integration with Robot
- **Function:** Establishes a communication link between the robot and the smart home system.
- **Interaction:** Allows for the coordination of tasks and data sharing.

### AI Object Recognition
- **Function:** Identifies and categorizes objects within the robot's environment.
- **Interaction:** Enhances the robot's interaction with its surroundings by providing context-aware responses.

### Navigation
- **Function:** Guides the robot through the environment with minimal human intervention, calculating the most efficient routes and avoiding obstacles dynamically.
- **Interaction:** Relies on sensor data to navigate efficiently and update routes in real-time, ensuring safe and optimal movement throughout the operating environment.

### Cartography
- **Function:** Creates and updates a map of the robot's operating environment.
- **Interaction:** Supports the Navigation Module by providing a spatial framework.

### Remote Control and Telecommunication
- **Function:** Enables users to control the robot and communicate with it from a distance.
- **Interaction:** Relies on the Connectivity Module for stable and secure connections.

### Intelligent Task Execution
- **Function:** Allows the robot to perform complex tasks autonomously.
- **Interaction:** Combines input from various submodules to carry out instructions.

### Smart Home Integration
- **Function:** Connects the robot with other smart home devices and systems.
- **Interaction:** Facilitates a unified ecosystem where the robot and smart home devices work in harmony.

### Porting to a Compact form-factor
- **Function:** Adapts the system for operation in a smaller, more efficient form factor. Planned possibly of ARM Architecture
- **Interaction:** Ensures that the system remains fully functional after the transition to new hardware.

## Submodules
Submodules are specialized components of each module, providing additional granularity and control:

### Safety Submodule
- **Detail:** Ensures all tasks are performed without causing harm to people, pets, or property.
- **Dependency:** Works closely with all other submodules to monitor and adjust actions in real-time.


# Integration

## Smart Home Integration
Our system will be engineered to seamlessly integrate with existing smart home ecosystems, providing a unified control experience:

### HomeAssistant Compatibility
- **Detail:** Allows users to manage and automate their smart home devices through our central gateway, leveraging the robust features of HomeAssistant.

### Hubitat Ecosystem
- **Detail:** Offers integration with Hubitat's local control solutions, ensuring fast and reliable smart home management without reliance on the cloud.

## Matter Standard Compliance
- **Detail:** Ensures that our system adheres to the Matter standard, promoting interoperability and security across different smart home devices.

# Installation
*Currently under development.* Detailed installation and configuration instructions will be provided upon completion. For updates and more information, please refer to the Wiki.

# Usage
*Currently under development.* Examples of how to use the main features will be available soon. For more details, check the Wiki.

# Contributing
*Note: Contributions are not currently being accepted.* The project's architecture and strategic vision are still in the formulation stages. Once the foundation is established, guidelines for contributions will be provided. Please refer to the Wiki for future updates on how you can contribute.

# License
This project is released under a permissive license, allowing everyone to use, modify, and distribute the code as they see fit. However, it may incorporate modules with different licenses, which will be clearly indicated in their respective subdirectories.

## **BSD 3-Clause License** 
Copyright (c) 2024, kozak-yakym
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the kozak-yakym nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


**Legal Use Compliance:** Users must comply with all applicable laws in using this code and are solely responsible for ensuring their use conforms to legal requirements.


