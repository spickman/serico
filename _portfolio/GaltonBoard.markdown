---
layout: post
title: Galton Board
description: A Galton board animation 
img: img/3.jpg
---

A Galton board is a usefull tool for explaining the central limit theorem (CLT). It is a visual representation of how the binomial can be approximated by a normal in the right circumstances : NP > ~5, a large number of trials and a non extreme probablity of success. 

The program is written in python with graphics handled by the pygame library. At each pin the ball has a 50-50 chance of going left or right. This satisfies one of the CLT constrains that the probability is non-extreme p = 0.5. The other  constraint is dealt by allowing time for the balls to fall, increasing the number of trials. 

The user can change the speed / number and delay of the balls being fed in and the number of pins present. 

A normal distribution can be fitted to the histogram to show the strength of the equivalence.  
