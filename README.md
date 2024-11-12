# UAV-Fruit-detection-and-counting-simulator

## Overview

The project utilizes a customized CoppeliaSim scene featuring a quadcopter that follows a defined trajectory while using Vision RGB sensors to hover over an orchard. The sensor feed is processed through a VGG16 neural network, along with custom color masking for yellow and orange hues, to detect the presence of ripe mangoes in the orchard for harvesting purposes.

## Software Used

- Quadcopter and Environment Modelling and Simulation: CoppeliaSim
- Custom architecture and RGB Spectral Masking: Jupyter Notebook (Python)

## Features

- Custom Path Planning for Quadcopter using Trajectory Definition
- Reading sensor feeds and converting it into frames for further processing
- Color masking and VGG 16 processing to detect ripe mangoes in the orchard simulation.

## Prerequisites

- Python 3.x installed on your machine.
- GPU support for faster processing (recommended).
- NVIDIA GPU with CUDA support.
- CoppeliaSim Edu Installed.
