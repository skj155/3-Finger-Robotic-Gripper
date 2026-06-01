# 3-Finger-Robotic-Gripper

**Objective**

This project focuses on the design, kinematic-dynamic modelling, and closed-loop control of an adaptive three-finger robotic gripper. The goal is to balance mechanical multi-link complexity against multi-variable control effort to establish a stable, versatile end-effector capable of secure form and force closure across diverse geometries.

**Methodology** 

A 9-degree-of-freedom planar serial mechanism framework was developed using Denavit-Hartenberg (DH) parameterization and energy-based Lagrangian mechanics to map severe multi-axis cross-coupling. Independent joint-level closed-loop Proportional-Integral-Derivative (PID) control structures were implemented and tuned within a high-fidelity MATLAB/Simulink simulation pipeline. Underactuation paradigms—including tendon-driven networks and cable-pulley transmission routing—were investigated conceptually to optimize physical system mass and bill-of-materials costs.

**Results**

The tuned controller demonstrated successful trajectory tracking and setpoint convergence across all joints within an execution window of 8–10 seconds. Steady-state errors were limited to $<0.05\text{ rad}$, demonstrating robust performance and damping against secondary time-varying Coriolis torque disturbances. The integration of underactuated cable routing paths verified a theoretical 67% reduction in necessary active actuators while maintaining functional workspace grasp dexterity. 
