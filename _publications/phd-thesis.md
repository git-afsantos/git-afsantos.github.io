---
title: "Safety Verification for ROS Applications"
collection: publications
permalink: /publication/phd-thesis
excerpt: 'This thesis answers the research question of how to adapt state-of-the-art quality assurance techniques to ROS applications, and how to make them usable by non-experts.'
date: 2021-07-16
venue: 'University of Minho'
paperurl: 'http://git-afsantos.github.io/files/dissertation.pdf'
citation: 'A. Santos. (2021). &quot;Safety Verification for ROS Applications.&quot; <i>University of Minho</i>. Braga, Portugal.'
---
**Abstract:**
Robots are now part of our daily lives and their usefulness is, seemingly, never-ending.
They manufacture our goods, harvest our crops and drive us from place to place.
Innovation in the field of robotics is constant, expectations are high, and the responsibilities we place on robots are ever increasing; robots are the new definition of safety-critical devices.
In part, this success is due to the abundance of open source frameworks to help develop robotic systems, such as the Robot Operating System (ROS).

ROS has a large and active community.
It was mostly used in research, but is recently finding its way into commercial and government projects as well.
With such a diverse community, and being based on an ecosystem of reusable software components, ensuring that ROS-based systems are dependable is paramount.
However, showing that robotic software is dependable is not an easy task.

Many techniques, such as Formal Verification, Model Checking, Runtime Verification, and more, have proved, over and over, to be capable of verifying a diverse range of properties in other software domains.
However, if there is one characteristic that often defines these techniques, it is their steep learning curve.
They have a hard requirement on expert knowledge, and the vast majority of the ROS community is composed of non-experts.

In this thesis, we answer the research question of how to adapt state-of-the-art quality assurance techniques to ROS applications, and how to make them usable by non-experts.
We take into consideration the fact that most systems are developed with a code-first approach, rather than following Model-driven Engineering practices.
We propose a unified workflow that takes in ROS application code, automatically extracts system models from it, and then applies a variety of static and dynamic analysis techniques with respect to user-specified properties.
If a property violation is detected, the results of the analyses can be used as a debugging aid.
Otherwise, they provide compelling evidence to structure a dependability case for the given properties.
This workflow is implemented in the HAROS framework, and later evaluated with two robot case studies.
We have found this approach to be effective, both at building models and at finding faults for user-specified properties.
Overall, it has been well-received in the ROS community.
Several members are now independently using it, as well as proposing their own extensions.

[Download paper here](http://git-afsantos.github.io/files/dissertation.pdf)
