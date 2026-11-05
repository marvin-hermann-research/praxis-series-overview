# PRAXIS Series – Comprehensive Overview

**PRAXIS = Physical Realization of Artificial eXecutive Intelligence Structures**

---

## 1. Project Idea

This repository provides an overview of the PRAXIS robotic actuator series, an incremental development effort focused on building increasingly capable, intelligent robotic actuators and manipulation systems.

Beginning with an affordable, predominantly 3D-printable robotic arm, the series explores a progression from basic articulated motion toward sensor-informed manipulation and coordinated, task-aware execution.

PRAXIS provides the physical actuation layer for integration with the [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview) framework. Selected designs also target integration with [ARTIFICE](https://github.com/marvin-hermann-research/artifice-series-overview) robotic platforms, extending mobile robots with manipulation capabilities.

Key aspects:

- Accessible hardware: Begin with low-cost components and approachable manufacturing methods.
- Increasing capability: Progress toward more capable mechanisms, richer feedback, and intelligent manipulation.
- [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview) integration: Expose actuation, feedback, and execution status through clearly defined interfaces.
- [ARTIFICE](https://github.com/marvin-hermann-research/artifice-series-overview) compatibility: Design selected actuators for mounting and operation on mobile robotic bodies.
- Modular development: Keep mechanical design, embedded control, and higher-level intelligence clearly separated.
- Research orientation: Provide documented platforms for experimentation, evaluation, and iterative improvement.

> PRAXIS turns higher-level robotic intent into physical action, starting with hardware that is affordable to build and straightforward to integrate.

---

## 2. Motivation

Intelligent robotic systems need physical mechanisms that can translate decisions into controlled interaction with the environment.

For students, independent developers, and research projects, access to such hardware should not depend on expensive components or specialized manufacturing infrastructure.

PRAXIS addresses this challenge through an incremental approach:

- Start with a minimal, affordable physical platform.
- Establish reliable control and clearly defined software interfaces.
- Incorporate feedback about the mechanism and its interaction with the environment.
- Develop increasingly capable execution and manipulation behaviors.
- Integrate individual actuators into coordinated robotic systems.

Affordability defines the starting point, while increasing capability defines the direction of the series. Later iterations may introduce more advanced hardware where it provides a clear functional benefit.

The objective is not simply to build mechanisms that move, but to develop actuators that can participate meaningfully in a larger intelligent system.

---

## 3. Versioning

The PRAXIS series is structured incrementally, with each iteration intended to explore additional mechanical, sensing, or control capabilities.

| Version | Focus / Features | Status |
| ------- | ---------------- | ------ |
| [PRAXIS I](https://github.com/marvin-hermann-research/praxis-I) | Low-cost, predominantly 3D-printable 5-DOF robotic arm; inverse kinematics support; ESP32 and micro-ROS integration; remote belt actuation; load monitoring | In development |
| Future iterations | Increasingly capable actuation, richer sensor feedback, advanced manipulation, and closer coordination with [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview) and selected [ARTIFICE](https://github.com/marvin-hermann-research/artifice-series-overview) platforms | Scope to be defined |

PRAXIS I establishes the accessible starting point: a robotic arm targeting a hardware budget of €25 or less, excluding the gripper and external power supply.

Its focus is to demonstrate a minimal physical foundation for ROS 2-connected manipulation before expanding the capabilities of the series.

> Future versions are intended to build on lessons from earlier designs while preserving clear integration interfaces wherever practical. Mechanical designs and hardware requirements may evolve between iterations.

---

## 4. Use Cases

The PRAXIS series targets a growing range of applications:

- Robotics education: Explore actuation, kinematics, embedded control, and physical manipulation.
- Accessible experimentation: Provide low-cost hardware for testing robotic software on a real mechanism.
- Standalone manipulators: Execute manipulation tasks under higher-level [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview) control.
- Mobile manipulation: Equip selected [ARTIFICE](https://github.com/marvin-hermann-research/artifice-series-overview) platforms with lightweight robotic arms or other actuators.
- Sensor-informed execution: Use feedback to evaluate loads, detect limits, and adapt or interrupt actions.
- Coordinated robotic behavior: Investigate how a manipulator and its supporting body can work together to reach and interact with objects.

---

## 5. Goals

- Accessibility: Lower the entry barrier to building and experimenting with physical robotic systems.
- Increasing capability: Progress from basic joint actuation toward intelligent, feedback-driven manipulation.
- Modularity & extensibility: Allow mechanisms, sensors, end effectors, and control components to evolve independently where practical.
- Seamless [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview) integration: Provide consistent interfaces for commands, feedback, execution status, and coordination.
- Selective [ARTIFICE](https://github.com/marvin-hermann-research/artifice-series-overview) integration: Support mobile-platform mounting and body–actuator coordination where appropriate.
- Reproducibility: Document hardware, assembly, software interfaces, test procedures, and verified limitations.
- Practical validation: Distinguish intended capabilities from experimentally demonstrated performance.
- System-level intelligence: Enable actuators to communicate not only how they move, but also what they require from the surrounding robotic system.

The long-term vision is an actuator that does more than execute isolated motion commands: it contributes feedback to task execution, recognizes relevant physical constraints, and participates in coordinated action.

For a robotic arm mounted on a mobile platform, this includes identifying when a target cannot be reached by the arm alone and requesting an appropriate movement of the supporting body through [AETHER](https://github.com/marvin-hermann-research/aether-framework-overview).
