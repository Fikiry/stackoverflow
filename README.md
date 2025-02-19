# Simulink Model for MPC-LQR-LPV Controller

## Overview
This Simulink model implements an MPC-LQR-LPV controller for a nonlinear half-car active suspension system with electro-hydraulic actuators. The control strategy aims to reduce system complexity while ensuring stability using Quadratic Stability conditions.

## Files
- `LPV_Model.m`: Defines the LPV model dynamics.
- `MPC_Controller.m`: Implements the MPC control algorithm.
- `LQR_Controller.m`: Implements the LQR control algorithm.
- `Quadratic_Stability.m`: Checks the Quadratic Stability conditions using LMIs.
- `Simulink_Model.slx`: Simulink model file for the overall system.

## Getting Started
1. Load the `Simulink_Model.slx` file in MATLAB Simulink.
2. Run the simulations to see the system's response to various disturbances.
3. Adjust the parameters in the `.m` files as needed to tune the controllers.

## Requirements
- MATLAB R2021a or later
- Simulink
- Control System Toolbox
- Model Predictive Control Toolbox
- Robust Control Toolbox

## References
- Research papers and documentation related to MPC, LQR, LPV models, and Quadratic Stability conditions.