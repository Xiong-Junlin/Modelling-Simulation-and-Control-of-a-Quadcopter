# Quadrotor Attitude Control Simulation (Reproduction of Zhangping's Lab)

This repository contains a Simulink-based reproduction of the attitude control modeling and simulation of a quadrotor aircraft, as presented in the paper "Modeling and Simulation of Attitude Control of Quadrotor Aircraft" by Zhangping. The objective of this project is to replicate the results of the paper using Simulink and MATLAB, providing an understanding of the quadrotor’s attitude dynamics and control system. The main focus is on controlling the roll, pitch, and yaw of the quadrotor.

## Results

### Attitude Stabilization

The simulation results show how the quadrotor responds to various initial conditions and disturbances. The plots below (generated from the Simulink simulation) show:

Step Response: The system's ability to reach desired roll, pitch, and yaw angles under step inputs.

Disturbance Rejection: The control system's performance when external forces act on the quadrotor.

Steady-State Error: After initial disturbances, the control system brings the quadrotor back to its desired orientation with minimal steady-state error.

### Sample Results (Step Responses for Roll, Pitch, and Yaw)
Roll Response

Pitch Response

Yaw Response

The results are consistent with those reported in the paper, demonstrating effective attitude control with appropriate damping and fast response times.
