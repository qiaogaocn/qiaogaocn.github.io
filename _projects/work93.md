---
layout: project
date: 2014-01-21T00:00:08
title: "NoC Implementation of Butterfly Fourier Algorithm"
description: ""
postphoto: "default"
category: NoC
tags: [DSP, NoC, SystemC]
group: works
---
{% include JB/setup %}

##Introduction##
In this project, a Butterfly Fourier Algorithm is implemented in to 3*3 NoC structure. 

The challenge of this project focuses on: 

- Extend the origin design into a 3*3 NoC network. 
- Map all 14 the processes into 9 PE in total.
- Evaluate the performance of the newly built system. 

To solve these problems, methods below are used correspondingly: 

- Modify the module declaration and change the connection in top.cpp. Add y axis function to router.cpp. 
- Merge some of the functions of processes into one PE. Let the functions be determined by the coordinate of current PE and the source location of current. 
- Add counters to all the output queue to judge whether there is a stuck or not and decide the fastest rate of this system depending on the evaluate result. 

All implementation details will be served in part 3...

For full PDF: [![pdf]({{ BASE.PATH }}/images/file_pdf.png)]({{ BASE.PATH }}/assets/NoC Implementation of Butterfly Fourier Algorithm.pdf) 