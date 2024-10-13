# Cold Rolling Simulation in Abaqus

This project simulates the cold rolling process using Abaqus, focusing on varying input parameters such as roller diameters, percentage reduction, and angular velocity. The output parameter calculated is the average rolling force. The simulation aims to understand how different rolling parameters affect the rolling force, providing insights for optimizing cold rolling operations in manufacturing.

## Table of Contents
- [Project Overview](#project-overview)
- [Simulation Details](#simulation-details)
- [Input Parameters](#input-parameters)
- [Output Parameter](#output-parameter)
- [Software Requirements](#software-requirements)
- [Usage Instructions](#usage-instructions)
- [Results Analysis](#results-analysis)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Cold rolling is a metalworking process used to reduce the thickness of a metal strip by passing it through rollers. This project uses Abaqus, a finite element analysis (FEA) software, to simulate the cold rolling process. By varying key input parameters, we study their impact on the rolling force, which is a crucial factor in the process.

## Simulation Details
The simulation includes the following steps:
1. **Model Setup**: The roller and metal strip geometry are defined in Abaqus.
2. **Material Properties**: The material properties for the metal strip are specified (e.g., Young's modulus, Poisson's ratio, and yield strength).
3. **Boundary Conditions and Loads**: Appropriate boundary conditions and loads are applied to simulate the rolling process.
4. **Parameter Variation**: Different scenarios are simulated by changing the input parameters (roller diameters, percentage reduction, and angular velocity).
5. **Output Calculation**: The average rolling force is calculated for each scenario.

## Input Parameters
The following input parameters are varied in the simulations:
- **Roller Diameter**: The diameter of the rollers used in the rolling process.
- **Percentage Reduction**: The percentage reduction in thickness of the metal strip.
- **Angular Velocity**: The rotational speed of the rollers.

## Output Parameter
- **Average Rolling Force**: The rolling force is calculated as the average force experienced by the metal strip during the rolling process.

## Software Requirements
To run the simulations, you will need:
- **Abaqus/CAE**: Finite element analysis software for setting up and running the simulations.
- **Python (optional)**: For post-processing results using Abaqus Python scripts.

## Usage Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/cold-rolling-simulation-abaqus.git
