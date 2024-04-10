---
title: "Deformable Object Manipulation (DOM)"
collection: research
permalink: /research/dom
excerpt: "A unified modeling method for DOM planning within constrained environments<br/><br/>
<img src='/images/research/DOM-modeling.png'><img src='/images/research/DOM-planning.gif'>"
---

The manipulation of deformable objects by robots presents a new problem in robotics. Currently, due to the lack of foundational theoretical methods, the technical roadmap "modeling-planning-simulation-control" for deformable object manipulation is difficult to fully realize. Tasks involving deformable object manipulation are often completed through teach-pendant mode, greatly restricting the application of robots in such scenarios.

Modeling
======
Compared to visual servoing methods that rely on online shape feedback for local control, offline operation planning offers the advantage of being able to predict whether the target shape is reachable based on a established global physical model, thereby avoiding falling into "local minima". It has the capability to solve tasks involving deformable object manipulation in complex constraint environments. However, compared to tasks involving traditional rigid bodies, deformable objects are typically continuous bodies in space with infinite degrees of freedom and complex physical deformation processes. Consequently, establishing a global predictive model that incorporates deformable objects is often challenging.

To address this challenge, we have proposed a unified modeling framework considering the "robot-object-environment" interaction. This unified modeling framework is established based on an implicit numerical computation method coupling "rigid-body" and "deformable-body" in one world. It transforms dynamic robot operations, environmental collisions, and other external loads into unified energy constraints through a virtual spring model to construct the deformation dynamics model of objects under global constraints for parallel optimization and solution.

<div>
    <img src='/images/research/dom-result-202404.jpg'>
</div>

<ol>
    <li>
        <b>H. Deng</b>, F. Ahmad, J. Xiong and Z. Xia. (2024). &quot;A Robot-Object Unified Modeling Method for Deformable Object Manipulation in Constrained Environments.&quot; <i><b>IEEE/ASME Transactions on Mechatronics</b></i>, Early Access, doi: 10.1109/TMECH.2024.3371111.
    </li>
    <li>
        <b>H. Deng</b>, J. Xiong, Z. Xia. (2024). &quot;An Implicit Solution to the Dynamic Model for Deformable Object Manipulation.&quot; <i><b>ROBOT</b></i>, 46(1): 45-53.
    </li>
</ol>

These research findings enable deformable object manipuilation planning in environments with global constraints, significantly enhancing the operational capabilities and flexibility of existing robots, and expanding the application boundaries of robots.