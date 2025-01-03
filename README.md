# Runway Simulation for Energy Consumption Analysis
## Overview
### This project analyzes energy consumption across different segments of a track resembling Shell Eco-marathon routes. The simulation includes key factors such as slope, turn angle, vehicle dynamics, and speed profiles to optimize energy efficiency.

## Key Features

Track Analysis: Simulates a track divided into segments, each with specific slope percentages, lengths, and turn angles.

Vehicle Parameters: Models vehicle characteristics, including weight, drag coefficient, rolling resistance, and battery capacity.

Energy Breakdown: Computes energy consumed due to incline, rolling resistance, and aerodynamic drag for each segment.

Speed Profiles: Compares energy consumption for slow, medium, and fast speed scenarios.

Visualization: Provides detailed graphical representations of energy consumption trends.

## Formulas Used
### Total Force: 𝐹 total = 𝐹 incline + 𝐹 rolling + 𝐹 aerodynamic 
 
### Energy Consumption: 𝐸 = 𝐹 total X length / efficiency
​
## Requirements

### Programming Language: 
Python 3.x

### Libraries:

pandas: Data handling

matplotlib: Data visualization

numpy: Mathematical operations

ipywidgets: Interactive widgets (optional)

## Usage

Input: Track data and vehicle parameters.
Output: Energy consumption by segment, total energy used, and graphical analysis.

## Potential Applications

Automotive Design: Optimizing vehicle efficiency for competitive events like Shell Eco-marathon.

Educational Tools: Demonstrating real-world energy principles.

Simulation Platforms: Extending the model to include additional dynamics.
