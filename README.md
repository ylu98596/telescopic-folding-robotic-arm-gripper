# Telescopic and Folding Robotic Arm Gripper

A modular robotic arm and gripper system designed to achieve telescopic extension, multidirectional bending, and adaptive grasping through a compact folding mechanism.

## Overview

This project focuses on the mechanical design and system development of a telescopic and folding robotic arm with an integrated gripper.

The design was motivated by limitations of conventional robotic arms that rely on bulky pneumatic or hydraulic systems. The proposed mechanism uses modular folding structures driven by servo motors, allowing the arm to extend, retract, bend, and fold while maintaining a relatively compact mechanical structure.

The complete system includes:

- A multi-layer telescopic and folding robotic arm
- A servo-driven robotic gripper
- Modular folding units
- Mechanical transmission and linkage mechanisms
- PWM-based servo control
- Kinematic modelling of the robotic arm

## Mechanical Design

The robotic arm consists of multiple folding units arranged in layers.

Each folding unit uses interconnected plates and servo-driven joints. By controlling the opening angles of the folding structures, the distance and orientation between adjacent layers can be changed.

Coordinated motion of the servo motors enables the arm to:

- Extend and retract
- Bend in multiple directions
- Fold into a more compact configuration
- Position the gripper within a flexible workspace

The modular structure is designed to avoid the need for complex pneumatic or hydraulic systems.

## Gripper Mechanism

The end-effector uses a linkage-based mechanical gripper.

A push-pull servo drives a crank and linkage mechanism to control the opening and closing of the gripper fingers.

A separate rotation servo drives the gripper through a gear mechanism, allowing the orientation of the gripper to be adjusted independently.

This combination enables both:

- **Grasp / release motion**
- **Gripper orientation adjustment**

## Control Concept

The folding units are driven by servo motors controlled using **PWM signals**.

Coordinated changes in servo angles control the opening angles of the folding structures, enabling extension, contraction, and multidirectional bending.

The design allows multiple folding units to be stacked, creating a robotic arm with a larger and more flexible workspace.

## Kinematic Modelling

The robotic arm was also modelled as a multi-link kinematic system.

Each folding layer can be represented as a virtual link with rotational and translational components.

Transformation matrices were used to describe the relationship between successive links and to derive the position of the end-effector from the servo-controlled configuration of the arm.

This provided a mathematical model connecting:

**Servo Angles → Folding Geometry → Link Transformation → End-Effector Position**

## My Contribution

My work on this project included:

- Mechanical concept development and structural design
- 3D CAD modelling using **SolidWorks**
- Design of the telescopic and folding arm mechanism
- Design and integration of the robotic gripper
- Development and refinement of mechanical linkage structures
- Assembly modelling and component integration
- Kinematic analysis and mathematical modelling
- Iterative improvement of the mechanical design
- Preparation and development of the invention patent

## CAD Models

The complete SolidWorks models are included in the [`SW`](./SW) directory.

The repository contains:

- Individual mechanical components (`.SLDPRT`)
- Gripper assembly models (`.SLDASM`)
- Folding-arm assembly models
- Servo and transmission components
- Complete robotic arm assembly

## Patent

This project resulted in a granted Chinese invention patent:

**Telescopic and Folding Robotic Arm Gripper and Its Telescopic Grasping Method**

- **Patent No.:** ZL 2025 1 1129228.5
- **Grant Publication No.:** CN 120620291 B
- **Granted:** November 4, 2025
- **Patent Holder:** Soochow University
- **First Inventor:** Yining Lu

The patent certificate and technical documentation are available in the [`docs`](./docs) directory.

## Project Outcome

The project resulted in a complete mechanical design combining a modular folding robotic arm, servo-driven gripper, and kinematic modelling.

The design demonstrates how a mechanically reconfigurable structure can provide extension, folding, multidirectional motion, and grasping capability without relying on pneumatic or hydraulic actuation.

The project strengthened my experience in taking a robotics concept from mechanical design and CAD modelling through system integration, mathematical analysis, and formal patent development.
