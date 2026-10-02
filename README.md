# Engineering Portfolio

University engineering projects by **Adrian-Dragos Crivilescu** (B.Sc. Robotics, Transilvania University of Brasov; M.Sc. Service Engineering and Management, POLITEHNICA University of Bucharest, from Oct 2026).

The projects cover mechanical design (calculations, standard-component selection, 3D modelling and technical documentation), mechatronics and robotics (kinematics, dynamics, simulation, ROS 2). All of them were completed as coursework at Transilvania University of Brasov.

**Tools:** CATIA V5, MDESIGN, Adams View, MATLAB/Simulink/SimMechanics, ROS 2 (Jazzy), Python, C/C++ (Arduino)

## Projects

| # | Project | What it is | Tools |
|---|---------|------------|-------|
| 1 | [Industrial Manipulator Design](./01-robotic-manipulator) | 2-module fixed robot (270 mm translation, 255° rotation, 47.75 kg payload): gripper, harmonic drive, servomotors, ball screw, couplings, bearings and linear guides; actuation sized from dynamic simulation. | CATIA V5, MATLAB/SimMechanics |
| 2 | [Single-Stage Helical Gearbox](./02-helical-gearbox) | 12 kW, 2000 rpm, ratio 5 gearbox: gear sizing with profile shift, shafts, bearings, keys; shaft verification; assembly and workshop drawings. | CATIA V5, MDESIGN |
| 3 | [Hydraulic Cylinder](./03-hydraulic-cylinder) | Cylinder for a 450 kg load on a 45° incline (280 mm stroke, 80 mm bore, 32 mm rod): rod buckling check, wall thickness, seals and guide rings, 3D model and assembly. | CATIA V5 |
| 4 | [Photovoltaic Panel Orientation System](./04-pv-tracker) | Tilting mechanism for a 400 W PV module (+60° / -65°): kinematic layout, linear actuator selection, motion simulation and a stepwise control profile. | CATIA V5, Adams View |
| 5 | [2-DOF Robot Arm Modelling](./05-2dof-arm-matlab) | Geometric, kinematic (Jacobians) and dynamic (Lagrange-Euler, Newton-Euler) models of a 2-DOF arm; Simulink simulation and motor selection from joint torques. | MATLAB, Simulink |
| 6 | [Robotic Arm Model and Controller (ROS 2)](./06-ros2-arm) | 10-link, 4-DOF arm in URDF and a Python node publishing JointState commands; two ROS 2 packages with a launch file for RViz2. | ROS 2 Jazzy, URDF, RViz2, Python |
| 7 | [Mobile Robot with Trajectory Interface](./07-mobile-robot) | 4-wheel differential-drive robot following trajectories with encoder-based P control and odometry; Python/Tkinter GUI to draw and export paths. | Python, C/C++ (Arduino) |

## What is in each folder

Each project folder has its own README with a short description, the tools used and the main results, plus the technical report (PDF) and, where applicable, source code and renders.

## Notes

- These are academic projects: designs are validated by calculation and simulation, not manufactured or field-tested.
- Manufacturer datasheets used during the projects are referenced by link and not redistributed here.

## Contact

- LinkedIn: [linkedin.com/in/adrian-crivilescu](https://www.linkedin.com/in/adrian-crivilescu/)
- Email: crivilescu.adrian@outlook.com
