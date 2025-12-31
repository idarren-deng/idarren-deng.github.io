---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Bio
======
Dr. Hao Deng is currently an Assistant Professor in robotics and biomechanics at the Institute of Advanced Integration Technology, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences (SIAT, CAS).

Hao's research mainly focuses on robotics and biomechanics, especially the fundamentals and applications of deformable object manipulation and dexterous manipulation. As a key member, he has participated in many projects such as the National Key Research and Development Plan of China, Natural Science Foundation of China (NSFC), and Guangdong Province Major Science and Technology Project. He has been the PI of the Distinguished Young Scholars Fund of the Youth Innovation Promotion Association, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences (2016-2018) and the Youth Startup Program, Guangdong-Hong Kong-Macao National Center for Applied Mathematics (2025-2027).

Hao obtained his Ph.D. in Pattern Recognition and Intelligent Systems from the University of Chinese Academy of Sciences, Beijing, and Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen, in 2023. Before Ph.D., he worked as a research assistant at Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen. 

Hao obtained his Master in Mechatronic Engineering from Harbin Institute of Technology, Shenzhen, China, in 2015. During his Master, he was visiting the Medical Robots and Biomechanics Lab at Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences for 2 years. Hao obtained his B.S. degree in Mechanical Engineering and Automation from the Wuhan University of Technology, Wuhan, China, in 2012.

Education
======
* Ph.D in Pattern Recognition and Intelligent Systems, University of Chinese Academy of Sciences, 2023
  * Dissertation: Planning for Robotic Manipulation of Deformation Objects
* M.S. in Mechatronic Engineering, Harbin Institute of Technology, 2015
  * Dissertation: Research on Path Planning and Bending Control of an Orthodontic Archwire Bending System
  * Research Internship, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, 2014-2015
* B.S. in Mechanical Engineering and Automation, Wuhan University of Technology, 2012

Work experience
======
* July 2025 till now: Assistant Professor
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
  * Research includes: Dexterous Manipulation and Control, Robotic System Design and Development.

* July 2023 to July 2025: Postdoctoral Researcher
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
  * Supervisor: Prof. Guanglin Li
  * Project: Grasping Manipulation Planning and Control for Multi-fingered Dexterous Hands

* January 2016 to August 2017: Research Assistant
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
  * Research includes: ROS-based Robotic System Development, Planning and Control.
  
Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.state == 'selected' %}
        {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
