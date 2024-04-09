---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

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
