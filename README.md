# CalTrans TWM

This repository integrates a suite of tools designed and developed to support the CalTrans TWM (Targeted Warning Message) project, marking a pivotal advancement in traffic management and safety.

These tools are meticulously engineered to synergize, processing and analyzing data from VIDAR cameras, communicating critical warnings through message boards, and ensuring the robustness of server networks. Their integration is key to enhancing real-time response capabilities and improving the safety and efficiency of transportation systems.

## Components

The system comprises four main components:

1. **Message Warning System**: A real-time communication interface that connects cameras to message boards, enabling the composition and transmission of warning messages. It also provides a virutal message board for our field test simulation. [MessageWarning](https://github.com/Soltanilara/MessageWarning)

2. **TWM-Dataset**: A collection of tools for data annotation, plate search, data analysis, and visualization tailored for VIDAR camera data. These tools support the automation of vehicle information searches based on license plates. [TWM-Dataset](https://github.com/Soltanilara/TWM-Dataset)

3. **MileSight UI**: A user interface that facilitates interaction between MileSight cameras and users, simulating user browsing and web requests due to the lack of direct API access from MileSight. [Targeted Warning Message](https://github.com/Soltanilara/Targeted-Warning-Message)

4. **LARA Server Monitor**: Docker configurations for monitoring server clusters for TWM projects, and maintaining optimal server health. [LARA Server Monitor](https://github.com/Soltanilara/LARA-server-monitor)

## Setup

Use the command below to clone all the submodules:

```bash
git clone --recursive https://github.com/Soltanilara/CalTransTWM
cd CalTransTWM
```
