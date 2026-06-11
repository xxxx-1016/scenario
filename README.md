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

<table align="center">
  <thead>
    <tr>
      <th align="center">Aspect</th>
      <th align="center">Scale</th>
      <th align="center">Coverage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>Scenario Categories</strong></td>
      <td align="center"><strong>6</strong></td>
      <td align="center">Safety-related, perception and recognition, efficiency-related, information service, formation vehicle, and operational vehicle scenarios</td>
    </tr>
    <tr>
      <td align="center"><strong>Road Types</strong></td>
      <td align="center"><strong>13</strong></td>
      <td align="center">Straight roads, turning roads, continuous curves, uphill roads, and intersections</td>
    </tr>
    <tr>
      <td align="center"><strong>Communication Modes</strong></td>
      <td align="center"><strong>4</strong></td>
      <td align="center">V2I + V2N, V2V + V2N, V2P + V2N, and V2V + V2P + V2N</td>
    </tr>
    <tr>
      <td align="center"><strong>Scenario Scale</strong></td>
      <td align="center"><strong>1,044</strong></td>
      <td align="center">Standardized vehicle-infrastructure cooperative test scenarios</td>
    </tr>
  </tbody>
</table>

## Demonstration

Representative generated scenarios are presented below to demonstrate the execution results and cross-platform applicability of the proposed scenario construction method.

### Unity3D-Esmini Co-Simulation Platform

All generated scenarios were implemented and validated on the **Unity3D-esmini co-simulation platform**. Four representative scenarios are shown below.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Lane Change Warning for Forward Vehicle.gif" alt="Lane Change Warning for Forward Vehicle" width="95%">
      <p align="center"><strong><small>Lane Change Warning for Forward Vehicle</small></strong></p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Right-Turn Collision Warning at Unsignalized T-junction.gif" alt="Right-Turn Collision Warning at Unsignalized T-junction" width="95%">
      <p align="center"><strong><small>Right-Turn Collision Warning at Unsignalized T-junction</small></strong></p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection.gif" alt="Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection" width="95%">
      <p align="center"><strong><small>Left-Turn Collision Warning with Pedestrian Crossing at Unsignalized Intersection</small></strong></p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Collision Warning for Parallel Turns in Consecutive Curves.gif" alt="Collision Warning for Parallel Turns in Consecutive Curves" width="95%">
      <p align="center"><strong><small>Collision Warning for Parallel Turns in Consecutive Curves</small></strong></p>
    </td>
  </tr>
</table>

### CARLA Platform

To further verify cross-platform applicability, a subset of the generated scenarios was also implemented and tested on the **CARLA platform**. Two representative scenarios are shown below.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="./assets/Tunnel Ahead.gif" alt="Tunnel Ahead" width="95%">
      <p align="center"><strong><small>Tunnel Ahead</small></strong></p>
    </td>
    <td align="center" width="50%">
      <img src="./assets/Intersection U-Turn Collision.gif" alt="Intersection U-Turn Collision" width="95%">
      <p align="center"><strong><small>Intersection U-Turn Collision</small></strong></p>
    </td>
  </tr>
</table>
