---
layout: project
date: 2014-01-20T00:00:02
title: "Bowling score keeper design "
description: ""
postphoto: "default"
category: SoC
tags: [FPGA, VHDL, SoC]
group: works
---
{% include JB/setup %}

##Abstract##
This paper provides an FPGA solution to a bowling score keeper. Specifically, 
this design achieves the functions of receiving the score of every throw in a 
bowling game, judging the performance, deciding the total score at any time 
depending on the bowling game rules and displaying the score on an LED screen. 
The key points of this project lie on changing the bowling score counting method 
to hardware description, which can be complicated as there are many branches in 
every state according to different conditions. 

Features of this design include: get the score in at every throw, save it to judge the performance and implement 
the score calculation method depending on state machine structure. 

The design is built on the Spartan 6 development board as hardware platform, described 
through VHDL code and been tested in Modelsim simulation platform. Moreover, 
synthesis, place and route process is accomplished on ISE platform.  

**Key words:** Bowling score keeper, state machine 

For full PDF: [![pdf]({{ BASE.PATH }}/images/file_pdf.png)]({{ BASE.PATH }}/assets/Qiao Gao--Bowling score keeper design.pdf)