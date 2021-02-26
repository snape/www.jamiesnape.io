---
layout: page
title: Smooth and Collision-Free Navigation for Multiple Mobile Robots and Video Game Characters
author: jamiesnape
permalink: /publications/phd/
---

## Abstract

The navigation of multiple mobile robots or virtual agents through environments
containing static and dynamic obstacles to specified goal locations is an
important problem in mobile robotics, many video games, and simulated
environments. Moreover, technological advances in mobile robot hardware and
video games consoles have allowed increasing numbers of mobile robots or virtual
agents to navigate shared environments simultaneously. However, coordinating the
navigation of large groups of mobile robots or virtual agents remains a
difficult task. Kinematic and dynamic constraints and the effects of sensor and
actuator uncertainty exaggerate the challenge of navigating multiple physical
mobile robots, and video games players demand plausible motion and an ever
increasing visual fidelity of virtual agents without sacrificing frame rate.

We present new methods for navigating multiple mobile robots or virtual agents
through shared environments, each using formulations based on velocity
obstacles. These include algorithms that allow navigation through environments
in two-dimensional or three-dimensional workspaces containing both static and
dynamic obstacles without collisions or oscillations. Each mobile robot or
virtual agent senses its surroundings and acts independently, without central
coordination or inter-communication with its neighbors, implicitly assuming the
neighbors use the same navigation strategy based on the notion of reciprocity.
We use the position, velocity, and physical extent of neighboring mobile robots
or virtual agents to compute their future trajectories to avoid collisions
locally and show that, in principle, it is possible to theoretically guarantee
that the motion of each mobile robot or virtual agent is smooth. Moreover, we
demonstrate direct, collision-free, and oscillation-free navigation in
experiments using physical iRobot Create mobile robots, simulations of multiple
differential-drive robots or simple-airplanes, and video games levels containing
hundreds of virtual agents.

## Full Document

[![Adobe Acrobat Reader Logo](/assets/adobeacrobatreader.png)](assets/publications/phd/dissertation.pdf) &nbsp;  [Dissertation](assets/publications/phd/dissertation.pdf)

## C++ Code

* [HRVO Library](https://github.com/snape/HRVO), Collision-Free and Oscillation-Free Navigation of Multiple Mobile Robots or Virtual Agents
* [RVO2 Library](https://github.com/snape/RVO2), Reciprocal Collision Avoidance for Real-Time Multi-Agent Simulation
* [RVO2-3D Library](https://github.com/snape/RVO2-3D), Reciprocal Collision Avoidance for Real-Time Multi-Agent Simulation in Three Dimensions

## Citation

Jamie Snape, **Smooth and Collision-Free Navigation for Multiple Mobile Robots and Video Game Characters**, Doctoral dissertation, Department of Computer Science, University of North Carolina at Chapel Hill, Chapel Hill, NC, 2012, advised by [Dinesh Manocha](https://www.cs.umd.edu/people/dmanocha), doi: [10/fmxd](https://doi.org/fmxd)

This material is presented to ensure timely dissemination of scholarly and
technical work. Copyright and all rights therein are retained by authors or by
other copyright holders. All persons copying this information are expected to
adhere to the terms and constraints invoked by each author's copyright. In most
cases, these works may not be re-posted without the explicit permission of the
copyright holder.
