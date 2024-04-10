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
Dr. Hao Deng is currently a Postdoctoral Fellow/Assistant Professor in robotics and biomechanics at the Institute of Advanced Integration Technology, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences (SIAT, CAS).

Hao's research mainly focuses on robotics and biomechanics, especially the fundamentals and applications of deformable object manipulation. As a key member, he has participated in many projects such as the National Key Research and Development Plan of China, Natural Science Foundation of China (NSFC), and Guangdong Province Major Science and Technology Project. He has also been the PI of Fund for Distinguished Young Scholars of the Youth Innovation Promotion Association, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences (2016-2017).

Hao obtained his Ph. D. in Pattern Recognition and Intelligent Systems from the University of Chinese Academy of Sciences, Beijing, and Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen, in 2023, supervised by Prof. Zeyang Xia and Prof. Jing Xiong. Before Ph. D., he worked as a research assistant at Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen. 

Hao obtained his master in mechatronic engineering from Harbin Institute of Technology, Shenzhen, China, in 2015, supervised by Prof. Shoubin Liu. During his master, he visited the Medical Robots and Biomechanics Lab led by Prof. Zeyang Xia at Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences for 2 years. And Hao obtained his B.S. degree in mechanical engineering and automation from the Wuhan University of Technology, Wuhan, China, in 2012.

Education
======
* Ph.D in Pattern Recognition and Intelligent Systems, University of Chinese Academy of Sciences, 2023
* M.S. in Mechatronic Engineering, Harbin Institute of Technology, 2016
  * Research Internship, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, 2014-2015
* B.S. in Mechanical and Automation, Wuhan University of Technology, 2012

Work experience
======
* July 2024 till now: Postdoctoral Fellow/Assistant Professor
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
  * Research includes: Robotic Manipulation and Control, Biomechanic System and Application.

* March 2016 to August 2017: Research Assistant
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
  * Research includes: ROS-based Robotic System Development, Planning and Control.
  
Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.state == 'selected' %}
        {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
