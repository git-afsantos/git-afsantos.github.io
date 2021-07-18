---
title: "Property-based Testing for the Robot Operating System"
collection: publications
permalink: /publication/2018-A-TEST
excerpt: 'This paper presents a first approach towards automatic generation of test scripts for property-based testing of various configurations of a ROS system.'
date: 2018-11-05
venue: '9th ACM SIGSOFT International Workshop on Automating TEST Case Design, Selection, and Evaluation (A-TEST)'
paperurl: 'http://git-afsantos.github.io/files/2018-atest.pdf'
citation: 'A. Santos, A. Cunha, N. Macedo. (2018). &quot;Property-based Testing for the Robot Operating System.&quot; <i>A-TEST@ESEC/SIGSOFT FSE 2018</i>. 56-62.'
---
**Abstract:**
The Robot Operating System (ROS) is an open source framework for the development of robotic software, in which a typical system consists of multiple processes communicating under a publisher-subscriber architecture.
A great deal of development time goes into orchestration and making sure that the communication interfaces comply with the expected contracts (eg receiving a message leads to the publication of another message).
Orchestration mistakes are only detected during runtime, stressing the importance of component and integration testing in the verification process.
Property-based Testing is fitting in this context, since it is based on the specification of contracts and treats tested components as black boxes, but there is no support for it in ROS.
In this paper, we present a first approach towards automatic generation of test scripts for property-based testing of various configurations of a ROS system.

[Download paper here](http://git-afsantos.github.io/files/2018-atest.pdf)
