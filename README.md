# AV Sensor Network Data - AV23 Dataset

Welcome to the AV Sensor Network Data repository. This repository contains data collected from a network of sensors deployed in autonomous vehicles. The data includes various sensor readings, metadata, and analysis tools to help researchers and developers understand and utilize the information.

## Table of Contents
- [Overview](#overview)
- [Data Collection](#data-collection)
- [Data Structure](#data-structure)
- [Usage](#usage)
- [Installation](#installation)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview
This repository provides a comprehensive dataset from an AV sensor network, including data from cameras, LiDAR, radar, GPS, and other sensors. The goal is to support research and development in the fields of autonomous driving, sensor fusion, and machine learning.

## Data Collection
The data was collected using a fleet of autonomous vehicles equipped with a variety of sensors. Each vehicle in the fleet continuously recorded sensor data while operating in different environments and conditions.

### Sensors Used
- **Cameras**: Front, rear, and side cameras capturing high-resolution images.
- **LiDAR**: 3D point clouds representing the vehicle's surroundings.
- **Radar**: Detection of objects and their velocities.

## Data Structure
The dataset is organized into the following structure:

timestamp	
data_transfer_rate	
error_rate	
response_time	
Ultrasound range( (signal strength)-(0-100)Db	
Updates per second	
Ranges(m)	
2D Camera resolution	
Frames per second	
Point cloud Density	
Points per second	
ultrasound data type	
camera data type	
lidar data type	
status	
is_malicious

