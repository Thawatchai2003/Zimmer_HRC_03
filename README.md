## URDF Description

The `urdf` directory contains the robot description files for the Zimmer HRC-03 gripper. These files define the mechanical structure, links, joints, visual models, collision models, and kinematic relationships required for visualization and integration within ROS2 applications.

### Purpose

The URDF (Unified Robot Description Format) model provides a digital representation of the Zimmer HRC-03 gripper that can be used in:

* RViz visualization
* MoveIt2 motion planning
* Robot simulation environments
* UR5e gripper integration
* TF frame generation
* Collision checking

### Main Components

* Gripper base link definition
* Left and right finger links
* Joint definitions and motion constraints
* Visual mesh configuration
* Collision geometry
* Inertial parameters
* Tool center point (TCP) definition

### Features

* ROS2-compatible robot description
* Support for MoveIt2 integration
* Compatible with Universal Robots (UR Series)
* Accurate gripper kinematic model
* Visualization support in RViz

### Application

The URDF model is attached to the UR5e end-effector and enables the gripper to be represented as part of the complete robot system. This allows motion planning, visualization, and collision detection to include both the robotic arm and the Zimmer HRC-03 gripper.
