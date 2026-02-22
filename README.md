## Overview  

Zh EMS2 is a full stack mechatronic systems project integrating:

- Mechanical design  
- Electronics and PCB development  
- Embedded firmware  
- Robotics software (ROS 2)  
- Simulation and validation  
- Professional engineering documentation  

The project emphasises structured engineering practice, simulation driven validation, and clean repository management while developing a fully integrated system.

This repository documents the entire development lifecycle from early concept through modelling, simulation, integration, evaluation and refinement.

---

# Table of Contents

1. Project Vision  
2. System Architecture  
3. Mechanical Design  
4. Electronics Design  
5. Embedded Software  
6. Robotics Integration (ROS 2)  
7. Simulation and Validation  
8. Repository Structure  
9. Engineering Workflow  
10. System Evaluation Framework  
11. Current Capabilities  
12. Future Development  
13. Lessons Learned  

---

# 1. Project Vision  

The objective of Zh EMS2 is to design and implement a complete mechatronic system that integrates mechanical, electrical and software components into a unified platform.

Core goals:

- Develop a physically manufacturable system  
- Design a custom PCB shield  
- Program embedded firmware for sensing and control  
- Integrate robotics software architecture  
- Maintain professional documentation standards  
- Validate design decisions using simulation  

The project is built around integration and traceability, not just isolated subsystems.

---

# 2. System Architecture  

The system consists of the following subsystems:

## Mechanical Subsystem
- Parametric CAD modelling  
- Assembly constraint validation  
- Simulation driven refinement  
- Manufacturability considerations  

## Electrical Subsystem
- Custom shield PCB  
- Sensor interfacing  
- Power regulation  
- Noise mitigation  

## Embedded Subsystem
- Microcontroller firmware  
- Signal processing  
- Control logic implementation  

## Robotics Subsystem
- ROS 2 workspace configuration  
- Simulation integration  
- Teleoperation exploration  
- Human safety concepts  

All subsystems are version controlled and developed iteratively.

---

# 3. Mechanical Design  

Mechanical development included:

- Full parametric CAD modelling  
- Iterative geometry refinement  
- Assembly interference testing  
- Design for fabrication  

## Simulation Work

Flow simulation was conducted to analyse airflow performance:

- Cell count optimisation  
- Refinement level comparison  
- Boundary condition validation  
- Performance comparison across design variants  
- Fluid cell and solid interaction analysis  

Simulation results were used to guide geometry refinement rather than relying on intuition alone.

## Documentation

- Drawing packs prepared  
- Revision control maintained  
- Engineering notes recorded per iteration  

---

# 4. Electronics Design  

A custom PCB shield was developed to interface sensors with a microcontroller platform.

## Key Work Completed

- Schematic design  
- Component selection  
- PCB layout optimisation  
- Routing refinement  
- Signal path validation  
- Power distribution design  

Design considerations included:

- Noise reduction  
- Trace routing efficiency  
- Mounting compatibility  
- Mechanical enclosure integration  

---

# 5. Embedded Software  

Firmware development focused on:

- Sensor data acquisition  
- Signal filtering  
- Threshold based logic  
- Calibration routines  
- Serial debugging  

Algorithms were iteratively tuned and validated through controlled testing.

The embedded system forms the bridge between physical sensing and higher level system logic.

---

# 6. Robotics Integration (ROS 2)

A ROS 2 workspace was configured and structured properly within the repository.

## Workspace Setup

- Colcon build system  
- Environment sourcing  
- Install folder management  
- Branch based development  

## Integration Concepts Explored

- Teleoperation control  
- 3D spatial targeting concepts  
- Digital twin environment concepts  
- Human robot safety zones using depth sensing  
- Gripper integration into simulation  

Proper repository restructuring was completed to ensure:

- Clean project submission  
- Correct branch usage  
- Removal of misplaced home directory builds  
- Standardised setup instructions for teammates  

---

# 7. Simulation and Validation  

Simulation played a central role in design validation.

## Mechanical Simulation
- Flow simulation  
- Cell refinement comparison  
- Fluid to solid interaction evaluation  

## System Validation
- Functional subsystem testing  
- Integration validation  
- Behavioural evaluation from user perspective  

All major design decisions were supported by either simulation or structured reasoning.

---

# 8. Repository Structure  

```

Zh-EMS2/
│
├── CAD/
│   ├── Parts/
│   ├── Assemblies/
│   ├── Drawings/
│   └── Simulation/
│
├── Electronics/
│   ├── Schematics/
│   ├── PCB/
│   └── BOM/
│
├── Firmware/
│   ├── Source/
│   ├── Libraries/
│   └── Calibration/
│
├── ROS2/
│   ├── src/
│   ├── install/
│   └── build/
│
├── Documentation/
│   ├── Aims/
│   ├── Resources/
│   ├── Evaluation/
│   └── Team_Process/
│
└── README.md

```

The structure supports scalability and traceability across all engineering domains.

---

# 9. Engineering Workflow  

This project emphasises disciplined engineering practice:

- Git version control  
- Branch based feature isolation  
- Revision documentation  
- Structured evaluation criteria  
- Iterative prototyping  
- Simulation before fabrication  

Team workflow improvements included:

- Proper repository cloning  
- Workspace relocation from incorrect directories  
- Clear setup instructions  
- Standardised environment sourcing  

---

# 10. System Evaluation Framework  

The system is evaluated from the user perspective using staged criteria:

## P (Minimum Viable Product)
- Core functionality operational  
- Basic integration complete  

## C
- Improved robustness  
- Reduced failure points  

## D
- Strong subsystem integration  
- Stable behaviour  

## HD
- Seamless operation  
- Clean user interaction  
- Reliable performance  

## Perfect
- Fully integrated  
- Robust to edge cases  
- Demonstrates engineering polish  
- Clear documentation and validation evidence  

Evaluation is integration focused, not just component focused.

---

# 11. Current Capabilities  

The system currently demonstrates:

- Integrated mechanical and electronic subsystems  
- Custom PCB design  
- Functional embedded firmware  
- Structured ROS 2 workspace  
- Simulation validated geometry  
- Clean repository structure  
- Full documentation support  

---

# 12. Future Development  

Planned improvements include:

- Expanded autonomy features  
- Improved human robot interaction safety  
- Higher fidelity simulation  
- Digital twin environment integration  
- Multi user collaborative control concepts  
- Performance optimisation  
- Full integration testing under stress conditions  

---

# 13. Lessons Learned  

Key engineering lessons from this project:

- Integration complexity exceeds subsystem complexity  
- Simulation prevents expensive design mistakes  
- Repository discipline saves significant time  
- Environment setup consistency matters  
- Clear documentation accelerates collaboration  
- Mechanical, electrical and software decisions must be co designed  

---

# Conclusion  

Zh EMS2 represents a complete multidisciplinary engineering effort combining:

- Mechanical design  
- Electronics engineering  
- Embedded programming  
- Robotics software  
- Simulation  
- Structured documentation  

The repository captures not only the final system but the engineering reasoning, iteration and validation that led to it.
