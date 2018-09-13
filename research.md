---
layout: mydefault
title: Research
---

## Research Interest

<div >
<p>Robots are becoming more involved in our everyday lives, because they offer a unique function – autonomous mobility – that no other technology provides. However, safety is an important requirement for robots to move around people. To actively contribute to these new developments in robotics, my current research aims to integrate perception, control and learning in the design of provably correct safe reactive motion planning algorithms for robots operating around people; for example, safe autonomous navigation in crowds of people and safe mobile manipulation with/around people. Broadly, my research interests include robotics, dynamical systems, control theory, sensor network, optimization and machine learning. </p>
</div>  

## Research Experience

I began my research in robotics during my master’s program at Bilkent University in Turkey where we developed novel mathematical models and reactive footstep planning algorithms for legged systems. This invaluable experience helped me understand that _safe autonomous mobility_ is key for robots to be part of our lives. Accordingly, during my PhD studies at the University of Pennsylvania in the US, I focused my research on provably correct safe feedback motion planning.  The design of such motion planners inevitably requires modelling and understanding of global geometry and/or topology of configuration spaces of robotics systems. In my dissertation, I argued that clustering can be utilized for unsupervised learning of hidden intrinsic structures in complex-shaped and high-dimensional configuration spaces of robotic systems. To support this claim, I demonstrated potential application of clustering to feedback motion design, in particular, for multirobot coordination and sensor-based reactive robot navigation. In addition to its use in motion planning, I also applied clustering to coverage control of mobile sensor networks. A brief overview of these results is presented below.    

### 1) Clustering-Based Motion Planning and Control

Inspired by the use of clustering for modelling global organizational structure, we introduced a novel use of hierarchical clustering for coordinated multirobot motion design. Hierarchical clustering offers a natural abstraction for identifying and representing spatially cohesive and segregated robot groups at different resolutions, by relating the continuous space of multirobot configurations to the combinatorial space of trees. Based on this new abstraction and a careful topological characterization of the associated hierarchical structure, we built a provably correct, computationally efficient hierarchical navigation framework for collision-free coordinated motion design towards a designated multirobot configuration via a sequence of hierarchy-preserving local controllers. This result breaks new ground by introducing a topologically nontrivial symbolic abstraction that comes with an explicit mathematical relation in the abstract symbol space and so reduces the complexity of high-level planning.

Building on the use of clustering for locality identification, we introduced a new, robot-centric application of Voronoi diagrams to identify a collision-free convex neighborhood of a robot moving in a cluttered environment. Based on robot-centric Voronoi diagrams, we designed a sensor-based reactive navigation algorithm for exact navigation of a disk-shaped robot in forest-like cluttered environments. More precisely, we showed that the continuous feedback motion toward the metric projection of a desired goal onto the robot’s convex local neighborhood steers almost all robot configurations to the goal position in environments cluttered with round obstacles, while avoiding collisions along the way. To the best of our knowledge, this was the first time a sensor-based reactive motion planner is shown to be provably correct with respect to a general class of environments. The conference version of this work was nominated for the Best Paper Award at the 12th International Workshop on the Algorithmic Foundations of Robotics (WAFR2016).  In addition to its extension to safe multirobot coverage coordination, we also adapted this navigation method to build a sensory steering algorithm for sampling-based motion planning in complex environments with narrow passages.

### 2) Coverage Control of Mobile Sensor Networks

Besides its use as a “magnifying glass” for understanding configuration spaces, I applied clustering to resource allocation and coverage control in mobile sensor networks. In distributed mobile sensing applications, Voronoi diagrams are often utilized for solving sensory task assignment and for modelling group heterogeneity in actuation, sensing, computation and energy sources. In addition to these usages, we tailor Voronoi diagrams to encode collisions in a heterogeneous group of disk-shaped robots. Accordingly, based on standard coverage control of point robots, we propose a constrained coverage control law for heterogeneous disk-shaped robots that solves the combined sensory coverage and collision avoidance problem. We further introduce a congestion management heuristic for unassigned robots to hasten the assigned robots' progress, while retaining the provable properties.

I also worked on coverage control of pan/tilt/zoom (PTZ) camera networks. We recently proposed a novel provably correct reactive coverage control algorithm for PTZ camera networks that continuously (re)configures camera orientations and zoom levels (i.e., angles of view) in order to locally maximize their total coverage quality of a given event distribution over an environment. This construction is based on careful modeling of visual sensing quality that is consistent with the physical nature of cameras. We introduced a new notion of conic Voronoi diagrams, based on our proposed sensing quality measures, to solve the camera network allocation problem: that is, to determine where each camera should focus in its field of view given all the other cameras’ configurations. Accordingly, We designed simple greedy gradient algorithms for both continuous- and discrete-time first-order PTZ camera dynamics that asymptotically converge a locally optimal coverage configuration. This work was nominated for the Best Paper Award on Multirobot Systems at the 2018 International Conference on Robotics and Automation (ICRA2018). 

### 3) Motion Planning via Reference Governors 

In robotics, it is often practically and theoretically convenient to design motion planners for approximate simple robot and environment models first, and then adapt such reference planners to more accurate complex settings. In this project, we introduced a new provably correct approach to extend the applicability of motion planners of simple settings to more complex settings using reference governors. Reference governors are add-on control schemes for closed-loop dynamical systems to enforce constraint satisfaction while maintaining stability, and provide a systematic way of separating the issues of stability and constraint enforcement. Conceptually, we showed that reference governors offer a bidirectional interface between high-level and low-level motion planning. We demonstrated example applications of reference governors for smooth extensions of low-order (e.g., position- or velocity-controlled) feedback motion planners to high-order (e.g., force/torque controlled) robot models, while retaining stability and collision avoidance properties. This was the first time a smooth extension framework can augment global navigation and collision avoidance properties of a generic path planner or a vector field planner to the second-order systems. Our current work targets application of reference governors to safe navigation control of quadrotor UAVs.

## Research Projects

Some of the current research projects I work on are:

<ul style="margin-left:2em">
  <li> Statistical Learning for Motion Planning and Control </li>
  <li> Statistical Coverage Control of Mobile Sensor Networks </li>
  <li> Safe Exploration and Navigation using Sparse Visual Point Clouds </li>
  <li> Safe Navigation Control of a Quadrotor UAV via Reference Governors </li>
</ul>    

Please stay tuned for further updates.


