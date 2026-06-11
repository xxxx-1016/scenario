# Template Matching Based Automated Test Scenarios Construction for Vehicle-Infrastructure Cooperative System

This repository presents an automated method for constructing vehicle-infrastructure cooperative test scenarios. It transforms predefined natural language scenario descriptions into OpenSCENARIO-compliant files and supports V2X message interaction in a Unity3D-esmini co-simulation platform.



## Overview

Vehicle-infrastructure cooperative systems have significantly propelled the development of intelligent transportation and autonomous driving, increasing the demand for efficient and scalable testing scenario construction. However, constructing high-quality, systematic, and reusable vehicle-infrastructure cooperative testing scenarios remains challenging due to limited scalability, insufficient coverage, and low construction efficiency.

This project addresses these issues by using template matching and structured parsing to automatically generate standardized cooperative driving scenarios.

## Methodology

<p align="center">
  <img src="./assets/framework.png" alt="V2X cooperative scenario demonstration" width="800">
</p>

The proposed framework consists of three main parts:

- Scenario template design based on the Human-Vehicle-Road-Environment framework
- Natural language parsing and OpenSCENARIO file generation
- V2X message management for RSU-OBU cooperative communication

The method supports the automatic transformation from predefined natural language descriptions to executable vehicle-infrastructure cooperative test scenarios.

## Scenario Library

A total of **1,044 vehicle-infrastructure cooperative test scenarios** were constructed.

The library provides broad coverage across scenario categories, road types, and V2X communication modes.

| Aspect | Coverage |
| :---: | :---: |
| Scenario Categories | 6 categories, including safety-related,  perception and recognition, efficiency-related, information service, formation vehicle, and operational vehicle scenarios |
| Road Types | 13 road types, covering straight roads, turning roads, continuous curves, uphill roads, and intersections |
| Communication Modes | V2I + V2N, V2V + V2N, V2P + V2N, and V2V + V2P + V2N |
| Scenario Scale | 1,044 standardized vehicle-infrastructure cooperative test scenarios |

## Demonstration

The generated scenarios were validated on a Unity3D-esmini co-simulation platform. Several representative generated scenarios are shown below as examples.

All generated scenarios were implemented and validated on the **esmini-Unity co-simulation platform**. Four representative scenarios are presented below to demonstrate the execution results.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Lane Change Warning for Forward Vehicle.gif" alt="Lane Change Warning for Forward Vehicle" width="95%">
      <p align="left">🟢 Lane Change Warning for Forward Vehicle</p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Right-Turn Collision Warning at Unsignalized T-junction.gif" alt="Right-Turn Collision Warning at Unsignalized T-junction" width="95%">
      <p align="left">🔴 Right-Turn Collision Warning at Unsignalized T-junction</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection.gif" alt="Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection" width="95%">
      <p align="left">🟡 Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection</p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Collision Warning for Parallel Turns in Consecutive Curves.gif" alt="Collision Warning for Parallel Turns in Consecutive Curves" width="95%">
      <p align="left">🔵 Collision Warning for Parallel Turns in Consecutive Curves</p>
    </td>
  </tr>
</table>

To further verify cross-platform applicability, a subset of the generated scenarios was also implemented and tested on the **CARLA platform**. Two representative scenarios are shown as examples.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Tunnel Ahead.gif" alt="Tunnel Ahead" width="95%">
      <p align="left">🟢 Tunnel Ahead</p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Intersection U-Turn Collision.gif" alt="Intersection U-Turn Collision" width="95%">
      <p align="left">🔴 Intersection U-Turn Collision</p>
    </td>
  </tr>
</table>


## Key Features

- Automated scenario generation from natural language descriptions
- OpenSCENARIO-compliant file generation
- Template matching based construction process
- RSU-OBU V2X communication support
- Unity3D-esmini co-simulation validation
- Large-scale cooperative scenario library

## Repository Structure

```text
.
├── README.md
├── assets/
│   └── v2x-scenario-demo.png
├── templates/
├── parser/
├── generator/
├── communication/
└── scenarios/
```

## Status

The scenario construction framework and co-simulation validation have been completed. The scenario library contains more than 1,000 standardized cooperative driving test scenarios.









# Template Matching Based Automated Test Scenarios Construction for Vehicle-Infrastructure Cooperative System

This repository presents a template matching-based method for automated test scenario construction in vehicle-infrastructure cooperative systems. The proposed method transforms predefined natural language scenario descriptions into OpenSCENARIO-compliant files and supports V2X message interaction on a Unity3D-esmini co-simulation platform.

## Overview

Vehicle-infrastructure cooperative systems have significantly promoted the development of intelligent transportation and autonomous driving, creating an increasing demand for efficient, scalable, and reusable testing scenario construction.

However, constructing high-quality vehicle-infrastructure cooperative testing scenarios remains challenging due to limited scalability, insufficient scenario coverage, and low construction efficiency.

To address these challenges, this project proposes an automated scenario construction framework based on template matching and structured semantic parsing. The framework enables the generation of standardized vehicle-infrastructure cooperative scenarios from predefined natural language descriptions.

## Methodology

<p align="center">
  <img src="./assets/framework.png" alt="Framework of the proposed scenario construction method" width="800">
</p>

The proposed framework consists of three main components:

- Scenario template design based on the Human-Vehicle-Road-Environment framework
- Natural language parsing and OpenSCENARIO file generation
- V2X message management for RSU-OBU cooperative communication

The method supports automatic transformation from predefined natural language descriptions to executable vehicle-infrastructure cooperative test scenarios.

## Scenario Library

A total of **1,044 vehicle-infrastructure cooperative test scenarios** were constructed.

The scenario library provides broad coverage across scenario categories, road types, and V2X communication modes.

| Aspect | Scale | Coverage |
| :---: | :---: | :--- |
| **Scenario Categories** | **6** | Safety-related, perception and recognition, efficiency-related, information service, formation vehicle, and operational vehicle scenarios |
| **Road Types** | **13** | Straight roads, turning roads, continuous curves, uphill roads, and intersections |
| **Communication Modes** | **4** | V2I + V2N, V2V + V2N, V2P + V2N, and V2V + V2P + V2N |
| **Scenario Scale** | **1,044** | Standardized vehicle-infrastructure cooperative test scenarios |

## Demonstration

Representative generated scenarios are presented below to demonstrate the execution results and cross-platform applicability of the proposed scenario construction method.

### esmini-Unity Co-Simulation Platform

All generated scenarios were implemented and validated on the **esmini-Unity co-simulation platform**. Four representative scenarios are shown below.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Lane Change Warning for Forward Vehicle.gif" alt="Lane Change Warning for Forward Vehicle" width="95%">
      <br>
      <sub><strong>Lane Change Warning for Forward Vehicle</strong></sub>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Right-Turn Collision Warning at Unsignalized T-junction.gif" alt="Right-Turn Collision Warning at Unsignalized T-junction" width="95%">
      <br>
      <sub><strong>Right-Turn Collision Warning at Unsignalized T-junction</strong></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection.gif" alt="Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection" width="95%">
      <br>
      <sub><strong>Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection</strong></sub>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Collision Warning for Parallel Turns in Consecutive Curves.gif" alt="Collision Warning for Parallel Turns in Consecutive Curves" width="95%">
      <br>
      <sub><strong>Collision Warning for Parallel Turns in Consecutive Curves</strong></sub>
    </td>
  </tr>
</table>

### CARLA Platform

To further verify cross-platform applicability, a subset of the generated scenarios was also implemented and tested on the **CARLA platform**. Two representative scenarios are shown below.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Tunnel Ahead.gif" alt="Tunnel Ahead" width="95%">
      <br>
      <sub><strong>Tunnel Ahead</strong></sub>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Intersection U-Turn Collision.gif" alt="Intersection U-Turn Collision" width="95%">
      <br>
      <sub><strong>Intersection U-Turn Collision</strong></sub>
    </td>
  </tr>
</table>

## Keywords

Vehicle-Infrastructure Cooperation, OpenSCENARIO, V2X Communication, Scenario Generation, Autonomous Driving, Intelligent Transportation, Unity3D, esmini, CARLA


