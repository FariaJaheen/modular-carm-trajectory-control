# Modular C-arm Trajectory Planning & Computed Torque Control (MATLAB)

In this repository the **MATLAB/Simulink codebase** is hosted for 2nd of my PhD thesis on **Trajectory Planning for Multiple Degrees of Freedom C-arm Systems**. The implementation focuses on **5DoF to 9DoF configurations** and demonstrates **trajectory generation, computed torque control (CTC), and evaluation under clinically relevant imaging poses**. 

---

## Key Features
- **Trajectory Planning**
  - Minimum Jerk, Minimum Snap, Polynomial, and Trapezoidal profiles
  - Smooth position, velocity, and acceleration generation across all joints

- **Computed Torque Control (CTC)**
  - Joint-space Motion Model
  - Demonstrates accurate tracking of desired vs measured joint trajectories

- **9-DoF Modular System**
  - 6 C-arm joints: Lateral, Vertical, Wigwag, Horizontal, Tilt, Orbital  
  - 3 Surgical Table joints: Vertical, Longitudinal, Transverse
 
- **8-DoF Modular System**
  - 6 C-arm joints: Lateral, Vertical, Wigwag, Horizontal, Tilt, Orbital  
  - 2 Surgical Table joints: Vertical, Longitudinal

- **7-DoF Modular System**
  - 6 C-arm joints: Lateral, Vertical, Wigwag, Horizontal, Tilt, Orbital  
  - 1 Surgical Table joints: Vertical
 
- **6-DoF Modular System**
  - 6 C-arm joints: Lateral, Vertical, Wigwag, Horizontal, Tilt, Orbital 

- **5-DoF Modular System**
  - 5 C-arm joints: Vertical, Wigwag, Horizontal, Tilt, Orbital 

---

## Quick Start
### Requirements
- MATLAB **R2023a or later**  
- Toolboxes: *Robotics System Toolbox*, *Simulink*.
