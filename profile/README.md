# Robotics Crash Course: A Swiss Army Knife Kindred
## Overview
Robotics Crash Course is designed to introduce students  to core concepts regarding Mechanical, Electrical and Software engineering. A small differential drive robot is at the core of RCC and is used as a platform to expose students to the basics of coding microprocessors in C/C++, replicating electronic circuit diagrams, and mechanically desigining a launching mechanism or other mechanism depending on the course project for that year. 

## Background
RCC started as an alternative to a Summer STEM course MG typically taught called "Makerspace" which was a project that heavily used the engineering design process to solve a problem that was defined by the student teams themselves. Because of the pandemic MG needed to switch gears to have a remote learning version of the stem course. So they bought a bunch of robot kits online but was displeased with most aspects of the designs. So instead they designed a minimalist robot that could be churned out quickly using the rapid prototyping tools available. The first few years used the Arduino UNO and the arduino ecosystem but with the onboarding of JC as a mentor they were able to move beyond the Arduino and move to a much more powerful uC the Rpi Pico W. JC designed a beautiful "Raft" that the Pico W fits on and has all the typical peripheral capabilities that a development board for small robotics may need. With this new uC, students now can potentially use the robot wirelessly and have done so successfully during STEM in 2023.

## Future Potential
RCC plans to develop the following over time:
- Modularize and Abstract away sensor drivers so that the libraries built can be used for many different uCs with minimal development needed through a custom "HAL" (Hardware Abstraction Layer)
- Incorporate the "Carrie" car (an ackerman steering type robot) as a learning tool for: control on constrained dynamical systems, localization and mapping, actuator feedback control and trajectory control
- Generate a ros2 learning environment where students can develop using ros2 to integrate complex systems
- Integrate code generation tools (like ros2 message generator) to easily generate custom communication protocols
