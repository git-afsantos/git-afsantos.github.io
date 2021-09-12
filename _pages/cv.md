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
* B.Sc. in Computer Science (Bologna 1st cycle degree), University of Minho, 2012
* M.Sc. in Informatics Engineering, University of Minho, 2015
* Ph.D in Computer Science, University of Minho, 2021

Work experience
======
* Feb. 2013 - Nov. 2013: **Research Assistant**
  * University of Minho
  * Duties included: Development of a bidirectional diagram-to-text editing tool
  * Supervisor: Professor Creissac Campos

* Nov. 2015 - Mar. 2021: **Research Assistant**
  * University of Minho
  * Duties included: Verification of safety properties of software developed with the Robot Operating System (ROS)
  * Supervisor: Professor Alcino Cunha
  * Co-supervisor: Professor Nuno Macedo
  * [Ph.D. Thesis](https://git-afsantos.github.io/publication/phd-thesis)

* Apr. 2021 - Present: **Senior Researcher**
  * [VORTEX CoLab](https://www.vortex-colab.com/what-we-do/)
  * Duties included: Developing automated analysis tools for robotics software
  
Skills
======
* Software Engineering
  * Quality Assurance
  * Automated Testing
  * Model Checking
  * Automatic Analysis Tools
* Web Development
* Game Development
* Robotics

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
