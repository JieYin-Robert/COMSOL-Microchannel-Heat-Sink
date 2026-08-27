# COMSOL Microchannel Heat Sink Simulation

## Overview

This project presents a COMSOL Multiphysics simulation of fluid flow and heat transfer in a microchannel heat sink.

The model was developed to reproduce and study the thermal-fluid behavior of a microchannel cooling system. The simulation focuses on the interaction between coolant flow and heat transfer within the microchannel structure.

## Simulation Software

- COMSOL Multiphysics
- Laminar Flow
- Heat Transfer
- Non-Isothermal Flow / Multiphysics Coupling

## Model

The COMSOL model is available in the [`model`](./model) directory.

The model contains the geometry, material properties, physics settings, boundary conditions, mesh, study configuration, and simulation setup required to reproduce the analysis.

## Simulation Workflow

1. Construct the microchannel geometry.
2. Define the solid and fluid domains.
3. Assign material properties.
4. Configure laminar fluid flow.
5. Configure heat transfer in the solid and fluid domains.
6. Couple the fluid-flow and heat-transfer physics.
7. Generate the computational mesh.
8. Solve the coupled thermal-fluid model.
9. Analyze the temperature and flow-field distributions.

## Results

Simulation results and visualization figures will be added to this repository.

Planned result visualizations include:

- Temperature distribution
- Coolant velocity field
- Flow behavior inside the microchannel
- Thermal performance of the microchannel heat sink

## Repository Structure

    COMSOL-Microchannel-Heat-Sink/
    ├── model/
│   └── microchannel_heat_sink.mph
└── README.md

## Author

Jie Yin
