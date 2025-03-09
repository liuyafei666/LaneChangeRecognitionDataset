# Lane Change Detection Dataset

## Overview

This repository contains a dataset designed for lane change detection in autonomous driving research. The dataset integrates multi-sensor data, including inertial measurement unit (IMU) readings, Visual-based lateral distances, and GPS coordinates, to facilitate accurate identification of vehicle lane-changing behaviors. It addresses the scarcity of publicly available datasets tailored for this purpose, offering a low-cost, efficient, and robust resource for researchers and practitioners in the field of intelligent transportation systems.

## Dataset Description

### Data Collection
The dataset was collected using an experimental vehicle equipped with the following sensors:
- **IMU Sensor**: Normal acceleration, and tangential angular velocity from IMU sensors to capture vehicle motion dynamics.
- **Camera**: Normal distance measurements between the vehicle and adjacent lane markings, obtained via vision-based cameras.
- **GPS Module**: Provides latitude and longitude for location annotation.

Data was gathered across diverse scenarios, including urban roads, highways, and suburban areas, under varying weather and lighting conditions. The dataset comprises approximately 10,143 samples, categorized into three behaviors: straight driving (3381 samples), left lane change (3381 samples), and right lane change (3381 samples). Each sample is a 5-second time series (500 timesteps).

