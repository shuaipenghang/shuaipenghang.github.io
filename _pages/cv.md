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
* M.S. in University of Chinese Academy of Sciences, 2025
* B.S. in Chengdu University of Technology, 2022

Skills
======
* Programming
  * C, Python, Matlab, Verilog
* Robotics Hardware
  * ARM(STM32), FPGA, SolidWorks, PCB Design and Assembly

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

