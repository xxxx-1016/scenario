# Template Matching Based Automated Test Scenarios Construction for Vehicle-Infrastructure Cooperative System

This repository presents an automated method for constructing vehicle-infrastructure cooperative test scenarios. It transforms predefined natural language scenario descriptions into OpenSCENARIO-compliant files and supports V2X message interaction in a Unity3D-esmini co-simulation platform.



## Overview

Vehicle-infrastructure cooperative systems have significantly propelled the development of intelligent transportation and autonomous driving, increasing the demand for efficient and scalable testing scenario construction. However, constructing high-quality, systematic, and reusable vehicle-infrastructure cooperative testing scenarios remains challenging due to limited scalability, insufficient coverage, and low construction efficiency.

This project addresses these issues by using template matching and structured parsing to automatically generate standardized cooperative driving scenarios.

## Methodology

<p align="center">
  <img src="./assets/framework.png" alt="V2X cooperative scenario demonstration" width="700">
</p>

The proposed framework consists of three main parts:

- Scenario template design based on the Human-Vehicle-Road-Environment framework
- Natural language parsing and OpenSCENARIO file generation
- V2X message management for RSU-OBU cooperative communication

The method supports the automatic transformation from predefined natural language descriptions to executable vehicle-infrastructure cooperative test scenarios.

## Demonstration

The generated scenarios were validated on a Unity3D-esmini co-simulation platform. The platform supports scenario execution, vehicle behavior simulation, and V2X message visualization.

<p align="center">
  <img src="./assets/v2x-scenario-demo.png" alt="Scenario demonstration" width="900">
</p>

## Scenario Library

A total of 1,044 vehicle-infrastructure cooperative test scenarios were constructed.

The scenario library includes:

- 6 scenario categories
- 13 road types
- Multiple driving behavior patterns
- Combined driving maneuvers
- V2I, V2V, V2N, and V2P communication modes

Safety-related scenarios account for more than 80% of all cases. Intersection scenarios account for over 60%, straight-road scenarios account for about 37%, and special road condition scenarios account for about 2%.

## Key Features

- Automated scenario generation from natural language descriptions
- OpenSCENARIO-compliant file generation
- Template matching based construction process
- RSU-OBU V2X communication support
- Unity3D-esmini co-simulation validation
- Large-scale cooperative scenario library

## Platform

- OpenSCENARIO
- Unity3D
- esmini
- V2X message management module

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

## Keywords

Vehicle-Infrastructure Cooperation, OpenSCENARIO, V2X, Scenario Generation, Autonomous Driving, Intelligent Transportation, Unity3D, esmini
