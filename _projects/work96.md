---
layout: project
date: 2014-01-21T00:00:05
title: "Carry Ripple Adder Implementation using Data Driven Dynamic Logic"
description: ""
postphoto: "default"
category: VLSI
tags: [digital arithmetic algorithms, Data Driven Dynamic Logic, schematic, Spice]
group: works
---
{% include JB/setup %}

##Abstraction##

This paper provides some implementation examples of a 4-bit carry ripple adder (CRA) depending on Data-Driven Dynamic logic based structures. In this design, the 4-bit CRA is designed depend on two different logic expressions and based on two techniques: D3L and SPD3L respectively. Then, by comparing the performance of these four designs, a best design can be choose from them. Moreover, a discussion about the differences between these two techniques will be provided.  

**Keywords:** D3L, SPD3L, 4-bit CRA 

##Introduction##

As the fast development of integrated circuit technology, we concentrate our researches increasingly on increasing speed and reducing power dissipation when implementing specific logic functions. One well-known method is Domino dynamic logic, which makes a circuit much faster than conventional logic. However, it comes with large dynamic power consumption. In this paper, I am going to use two new techniques: D3L [1] and SPD3L [2]. The basic thought of D3L is using a combination of inputs as the dynamic signal which will not affect the logic accuracy of the whole circuit and make the design work as it is in dynamic logic. However, it makes the capacitance for charge much larger and reduces the speed of a circuit. As a result, we involve SPD3L, in which D3L are separated into difference part to reduce the charging capacitance. The description in detail will be provided in next part... 

For full PDF: [![pdf]({{ BASE.PATH }}/images/file_pdf.png)]({{ BASE.PATH }}/assets/Qiao Gao--Carry Ripple Adder Implementation using Data Driven Dynamic Logic.pdf)
