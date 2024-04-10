---
title: "Planning for Robotic Manipulation of Deformation Objects"
state: selected
collection: publications
permalink: /publication/2023-07-01-dissertation
excerpt: 'This dissertation is about unified methods for manipulation modeling and planning that incorporate both rigid and deformable elements.'
date: 2023-07-01
venue: 'Dissertation of University of Chinese Academy of Sciences'
citation: '<b>H. Deng</b>. (2023). &quot;Planning for Robotic Manipulation of Deformation Objects [D].&quot; <i><b>University of Chinese Academy of Sciences</b></i>, 2023.'
---

Most of the current robotic manipulations aim to drive the pose changes (i.e., translation and rotation) of rigid objects. However, with the rapid improvement of robot hardware performance and extensive expansion of application requirements in the recent years, a new class of applications targeting driving the shape change of objects has emerged. Deformable object is usually a continuous body in space with infinite degrees of freedom and complicated underlying laws of deformation, which constitute challenges to classical robotics methods, such as the difficulty in handling complex deformation representation, and implementing task planning with dynamic deformation constraints. The lack of fundamental theoretical approaches has led to the fact that manipulation tasks involving deformable objects are mainly performed manually, which greatly limits the application of robotics.

Taking into account the distinctive characteristics of rigid robots and deformable objects, this dissertation adopts the classic technical approach of "modeling-planning-offline simulation-online execution" to systematically establish unified methods for manipulation modeling and planning that incorporate both rigid and deformable elements. The main contribution of the dissertation is as follows: 

(1) A concept of robot-object unified manipulation state and unified configuration space is proposed, along with a definition and mathematical description of deformable object manipulation. Furthermore, a manipulation planning framework based on forward model prediction and configuration space searching is established. 

(2) A modeling method of deformable object manipulation based on hyper Finite-Element description and a series-parallel calculation strategy is proposed to predict the unified state under robotic manipulating actions and global environmental constraints. Numerical experiments show that our proposed method outperformed existing methods in terms of computational efficiency and prediction accuracy. Thus, it satisfies the high performance requirements for state prediction in sampling-based planning algorithms. 

(3) The manipulation tasks with two different types of deformation characteristics, continuous and segmental discrete, can be then converted into planning problems of deterministic and dynamic robot-object connection in the constructed unified space, and a manipulation planning method based on sampling under deformation constraints and a manipulation planning method based on optimization of transition sequences are proposed. Simulation experiments are carried out to evaluate the efficacy of proposed unified manipulation planning method in practical tasks, and the results show that a higher success rate than conventional methods can be achieved. 

Finally, three typical scenarios are selected: (i) handling of elastic object (soft tissue puncture), (ii) manipulation of plastic object (aircraft cable routing) and (iii) manipulation of elastoplastic object (orthodontic archwire bending), to demonstrate the integration of the proposed methods. The outcomes reveal that the approach presented in this dissertation enables automated offline task planning and online execution of deformable object manipulation. 