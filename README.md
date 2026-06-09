# Template Matching Based Automated Test Scenarios Construction for Vehicle-Infrastructure Cooperative System

This repository presents an automated method for constructing vehicle-infrastructure cooperative test scenarios. It transforms predefined natural language scenario descriptions into OpenSCENARIO-compliant files and supports V2X message interaction in a Unity3D-esmini co-simulation platform.

<p align="center">   <p align="center">
  <img src="./assets/v2x-scenario-demo.png" alt="V2X cooperative scenario demonstration" width="900"><img src="./assets/v2x-scenario-demo.png" alt="V2X cooperative scenario demonstration" width="900">
</p>   < / p>

## Overview   # #概述

Vehicle-infrastructure cooperative systems are important for intelligent transportation and autonomous driving. However, constructing large-scale cooperative test scenarios remains challenging due to limited scalability, insufficient coverage, and low construction efficiency.车-基础设施协同系统对智能交通和自动驾驶具有重要意义。然而，由于可扩展性有限、覆盖范围不足、构建效率低，构建大规模协同测试场景仍然具有挑战性。

This project addresses these issues by using template matching and structured parsing to automatically generate standardized cooperative driving scenarios.本项目通过使用模板匹配和结构化解析来自动生成标准化的协同驾驶场景，从而解决了这些问题。

## Method Overview

The proposed framework consists of three main parts:建议的框架包括三个主要部分：

- Scenario template design based on the Human-Vehicle-Road-Environment framework
- Natural language parsing and OpenSCENARIO file generation
- V2X message management for RSU-OBU cooperative communication

The method supports the automatic transformation from predefined natural language descriptions to executable OpenSCENARIO test files.该方法支持从预定义的自然语言描述到可执行的OpenSCENARIO测试文件的自动转换。

## Demonstration

The generated scenarios were validated on a Unity3D-esmini co-simulation platform. The platform supports scenario execution, vehicle behavior simulation, and V2X message visualization.在Unity3D-esmini联合仿真平台上对生成的场景进行了验证。该平台支持场景执行、车辆行为模拟和V2X消息可视化。

<p align="center">
  <img src="./assets/v2x-scenario-demo.png" alt="Scenario demonstration" width="900">
</p>

## Scenario Library   ##场景库

A total of 1,044 vehicle-infrastructure cooperative test scenarios were constructed.共构建1044个车辆-基础设施协同测试场景。

The scenario library includes:场景库包括：

- 6 scenario categories
- 13 road types
- Multiple driving behavior patterns
- Combined driving maneuvers
- V2I, V2V, V2N, and V2P communication modes

Safety-related scenarios account for more than 80% of all cases. Intersection scenarios account for over 60%, straight-road scenarios account for about 37%, and special road condition scenarios account for about 2%.与安全相关的场景占所有案例的80%以上。交叉口场景占60%以上，直道场景约占37%，特殊路况场景约占2%。

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

## Repository Structure   存储库结构

```text   ' ' '文本
.
├── README.md
├── assets/
│   └── v2x-scenario-demo.png
├── templates/   ├──模板/
├── parser/
├── generator/   ├──上色/
├── communication/   ├──沟通/
└── scenarios/
```

## Status

The scenario construction framework and co-simulation validation have been completed. The scenario library contains more than 1,000 standardized cooperative driving test scenarios.完成了场景构建框架和联合仿真验证。场景库包含1000多个标准化协同驾驶考试场景。

## Keywords   # #关键字

Vehicle-Infrastructure Cooperation, OpenSCENARIO, V2X, Scenario Generation, Autonomous Driving, Intelligent Transportation, Unity3D, esmini
