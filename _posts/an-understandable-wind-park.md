---
layout: post
author: lanzieri
title: "An Understandable Wind Park"
---
An Understandable Wind Park
[Franziska-Sophie Göttsch](/people/goettsch), [Mohammad Alkhiyami](/people/alkhiyami), [Leandro Lanzieri](/people/lanzieri), [Görschwin Fey](/people/fey)
Institut für Eingebettete Systeme, https://www.tuhh.de/es/ce 

## Topic
There is an increasing deployment of and dependency on
large, distributed cyber-physical systems: embedded devices
that sense their surroundings, act on them, and coordinate
over networks to pursue a common goal (e.g., smart grids,
transportation). Implementing such systems presents several
challenges: they must act in coordination, they must have clear
interfaces, and, given their complexity, they should be able to
explain their behaviour, so that we can trust, debug, and
improve them. A wind park is a representative instance of
such systems: multiple turbines, each with an embedded
controller, interacting physically via wakes, and digitally over
wireless networks. Turbines are then coordinated by a central controller in order to feed the grid. In this
project, we are building a wind park model using IoT infrastructure and RIOT OS (https://www.riot-os.org/),
including physical actuators, sensors, wireless communication, complemented by a simulation environment.

## Objectives
Over the course of the project, we will design and implement the model wind park as a modular, layered
cyber-physical system, consisting of:
• Turbine nodes: embedded firmware on RIOT, low-level drivers for the rotor and yaw mechanism, as
well as turbine model, and user interface.
• Simulation model: simulated wind field, and a digital twin of the turbines and the park.
• Park controller: wireless communication between the turbines and a central, autonomous controller
that coordinates the park operation.
Along the way, we will study interesting challenges: should a park behave? Can systems explain their behaviours using IoT protocols?

## Prerequisites
If you like the idea of building real systems that you can watch move, getting hands-on with embedded and
IoT technologies, and building a coordinated, self-explaining system, then „An Understandable Wind Park“ is
for you. You bring: very good programming skills, experience in software engineering, interest in team work
and commitment to self-driven work. Basic knowledge of embedded systems and control is very useful.

## Literature
 Self-Explanation in Systems of Systems Görschwin Fey, Martin Fränzle, Rolf Drechsler, “Self-Explanation in Systems of Systems,” RE4ES,
2022. DOI: https://doi.org/10.1109/REW56159.2022.00023
 Template Decision Diagrams for Meta Control and Explainability Dubslaff, C., Klös, V., Päßler, J.,“Template Decision Diagrams for Meta
Control and Explainability,” Explainable Artificial Intelligence (xAI), 2024. DOI: https://doi.org/10.1007/978-3-031-63797-1_12
 Towards Self-Explainable CyberPhysical Systems, M. Blumreiter et al., “Towards Self-Explainable Cyber-Physical Systems,” 2019
ACM/IEEE 22nd International Conference on Model Driven Engineering Languages and Systems Companion (MODELS-C), Munich,
Germany, 2019, pp. 543-548, DOI: https://doi.org/10.1109/MODELS-C.2019.00084
 A generic and modular reference architecture for self-explainable smart homes. Etienne Houze, Ada Diaconescu, Jean-Louis Dessalles,
and David Menga, In 2022 IEEE International Conference on Autonomic Computing and Self-Organizing Systems (ACSOS), pages 101–
110, CA, USA, September 2022. IEEE.
 RIOT: An Open Source Operating System for Low-End Embedded Devices in the IoT. Emmanuel Baccelli, Cenk Gündoğan, Oliver Hahm,
Peter Kietzmann, Martine Lenders, Hauke Petersen, Kaspar Schleiser, Thomas C. Schmidt, Matthias Wählisch. IEEE Internet of Things
Journal, Vol. 5, No. 6, pp. 4428-4440, December 2018.
