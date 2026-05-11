[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Awesome ABB Robots [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/topics/awesome-list)

A curated list of awesome tools, libraries, and resources for programming and working with ABB industrial robots. This list includes various programming languages, frameworks, and utilities that help in controlling, simulating, and managing ABB robots.

## Contents
- [Awesome ABB Robots ](#awesome-abb-robots-)
  - [Contents](#contents)
  - [Inclusion Criteria](#inclusion-criteria)
  - [Development Tools](#development-tools)
    - [💻 C++](#-c)
    - [🎯 C#](#-c-1)
    - [🧮 MATLAB](#-matlab)
    - [🐍 Python](#-python)
    - [⚡ RAPID](#-rapid)
  - [Communication](#communication)
    - [🌐 TCP/IP](#-tcpip)
    - [🔌 PLC Integration](#-plc-integration)
    - [🔧 SDKs and Documentation](#-sdks-and-documentation)
  - [3D and Simulation](#3d-and-simulation)
    - [🟦 Autodesk Maya](#-autodesk-maya)
    - [🦏 Rhino Grasshopper](#-rhino-grasshopper)
    - [🎮 Unity](#-unity)
  - [Frameworks and Platforms](#frameworks-and-platforms)
    - [🤖 ROS](#-ros)
    - [🧰 Multi-Function Tools](#-multi-function-tools)
  - [Utilities](#utilities)
    - [💾 Backup Tools](#-backup-tools)
    - [🔀 SYSPAR Utilities](#-syspar-utilities)
    - [🌐 Web Applications](#-web-applications)
  - [Editor Support](#editor-support)
    - [📝 VSCode Extensions](#-vscode-extensions)
  - [Contributing](#contributing)

## Inclusion Criteria
- Relevant to ABB industrial robot development, integration, or operations.
- Publicly accessible and reasonably maintained.
- Useful documentation or examples are available.
- Clear practical value for developers, integrators, or researchers.

## Development Tools

### 💻 C++
- [madelinegannon/abb_egm_hello_world](https://github.com/madelinegannon/abb_egm_hello_world) - A simple example of how to use the ABB External Guided Motion (EGM) interface to control an ABB robot in real-time using C++.

### 🎯 C#
- [EkhiABB/ABB-PCSDK-examples](https://github.com/EkhiABB/ABB-PCSDK-examples) - Examples of PCSDK applications communicating with an ABB controller. Demonstrates a C# program connecting to an ABB OmniCore robot controller, managing RAPID modules, and running programs.

### 🧮 MATLAB
- [4rtur1t0/ARTE](https://github.com/4rtur1t0/ARTE) - ARTE is a MATLAB toolbox focused on robotic manipulators; both serial and parallel mechanisms are included.

### 🐍 Python
- [compas-rrc/compas_rrc](https://github.com/compas-rrc/compas_rrc) - Online control for ABB robots over a simple-to-use Python interface.
- [FLo-ABB/ABB-EGM-Python](https://github.com/FLo-ABB/ABB-EGM-Python) - Example of Externally Guided Motion (EGM) with ABB robots using Python.
- [madelinegannon/abb_rapid_python](https://github.com/madelinegannon/abb_rapid_python) - Generate ABB Rapid code via Python.
- [rpiRobotics/abb_robot_client](https://github.com/rpiRobotics/abb_robot_client) - Python clients for ABB robots using Robot Web Services (RWS) and Externally Guided Motion (EGM).
- [vbirgus/Collaborative-Air-Hockey-Robot](https://github.com/vbirgus/Collaborative-Air-Hockey-Robot) - Implementation of a collaborative robotic air hockey system using computer vision and EGM interface for real-time control.

### ⚡ RAPID
- [ernell/ABB-RAPID-UTILITY-LIBRARY](https://github.com/ernell/ABB-RAPID-UTILITY-LIBRARY) - A collection of utility modules for ABB industrial robots.
- [FLo-ABB/RAPID-Scripts-and-Demos](https://github.com/FLo-ABB/RAPID-Scripts-and-Demos) - A collection of modules/documentations/simulations for ABB industrial robots.
- [FLo-ABB/Hershey-ABB-Robot-Handwriting](https://github.com/FLo-ABB/Hershey-ABB-Robot-Handwriting) - ABB robot handwriting implementation using Hershey fonts for text-to-robot-motion conversion.


## Communication

### 🌐 TCP/IP
- [madelinegannon/abb_tcpip_server](https://github.com/madelinegannon/abb_tcpip_server) - Example for TCP/IP communication with ABB industrial robots.

### 🔌 PLC Integration
- Siemens
  - [FLo-ABB/GSDML_ABB_ROBOTS](https://github.com/FLo-ABB/GSDML_ABB_ROBOTS) - Repository that groups GSDML files for ABB robot PROFINET devices. [GitHub Page](https://flo-abb.github.io/GSDML_ABB_ROBOTS/)
- B&R
  - [loupeteam/A3br](https://github.com/loupeteam/A3br) - AR Library for communicating with ABB targets via RWS. ABB + BR = A3BR!

### 🔧 SDKs and Documentation
- [Developer Center](https://developercenter.robotstudio.com/) - A suite of SDKs and web services to communicate with ABB robots.

## 3D and Simulation

### 🟦 Autodesk Maya
- [AutodeskRoboticsLab/Mimic](https://github.com/AutodeskRoboticsLab/Mimic) - An open-source Autodesk Maya plugin for controlling industrial robots.

### 🦏 Rhino Grasshopper
- [robin-gdwl/Robots-in-Grasshopper](https://github.com/robin-gdwl/Robots-in-Grasshopper) - A collection of plugins and software that can be used to control industrial robots with Grasshopper in Rhinoceros3D.
- [visose/Robots](https://github.com/visose/Robots) - A visual and parametric framework for simulating and programming industrial robots, including ABB robots.

### 🎮 Unity
- [rparak/Unity3D_Robotics_ABB](https://github.com/rparak/Unity3D_Robotics_ABB) - A digital twin of ABB robots integrated into the Unity3D development platform.

## Frameworks and Platforms

### 🤖 ROS
- [JOiiNT-LAB/abb_wrapper](https://github.com/JOiiNT-LAB/abb_wrapper) - These packages are intended to ease the interaction between ABB OmniCore controllers and ROS-based systems, by providing ready-to-run ROS nodes.
- [MerlinLaboratory/ABB_omnicore_ros_driver](https://github.com/MerlinLaboratory/ABB_omnicore_ros_driver) - ROS driver for ABB OmniCore robots.
- [PickNikRobotics/abb_ros2](https://github.com/PickNikRobotics/abb_ros2) - This is a meta-package containing everything to run an ABB robot or simulation with ROS 2.
- [ros-industrial/abb (noetic-devel, URDFs)](https://github.com/ros-industrial/abb/tree/noetic-devel#) - URDF files for different ABB manipulators for use with ROS.
- [ros-industrial/abb_libegm](https://github.com/ros-industrial/abb_libegm) - A C++ library for interfacing with ABB robot controllers supporting Externally Guided Motion (EGM).

### 🧰 Multi-Function Tools
- [eliasbitsch/abb-robotstudio-mcp](https://github.com/eliasbitsch/abb-robotstudio-mcp) - MCP server for ABB RobotStudio and ABB controllers via SDK and Robot Web Services tools.
- [robotics/open_abb](https://github.com/robotics/open_abb) - RAPID, Python, and C++ libraries for communicating with ABB robots directly or via ROS.

## Utilities

### 💾 Backup Tools
- [RoboTech360/ABBRobotBackupSorter](https://github.com/RoboTech360/ABBRobotBackupSorter) - Python script to find and zip ABB robot backups in a file tree.
- [tonycab/AbbBackup](https://github.com/tonycab/AbbBackup) - Windows app for saving backups of ABB IRC5 robots over the network.

### 🔀 SYSPAR Utilities
- [SYSPAR-Config-Sorter](https://flo-abb.github.io/SYSPAR-Config-Sorter/) - A web-based tool designed to sort SYSPAR configuration files (such as EIO.cfg and PROC.cfg) from ABB robot controllers, making it easier to compare configurations across different robots using standard comparison tools.

### 🌐 Web Applications
- [EkhiABB/ABB-OmniCore-file-uploader](https://github.com/EkhiABB/ABB-OmniCore-file-uploader) - Web application to upload files to ABB OmniCore controllers from a web browser.
- [ichbinmeraj/abb-rws-client](https://github.com/ichbinmeraj/abb-rws-client) - Fully typed TypeScript/Node.js client for ABB Robot Web Services on IRC5 and OmniCore.


## Editor Support

### 📝 VSCode Extensions
- [Official ABB Extension](https://marketplace.visualstudio.com/items?itemName=abb-robotics-ecosystem.abb-robotics) - Official extension for ABB Robotics development, providing syntax highlighting, code autocompletion.
- [ichbinmeraj/abb-rws-vscode](https://github.com/ichbinmeraj/abb-rws-vscode) - VS Code extension for live ABB controller workflows, RAPID language support, and controller operations.

## Contributing
Please take a moment to read our [Contributing Guidelines](contributing.md) to make the process easy and effective for everyone involved!
