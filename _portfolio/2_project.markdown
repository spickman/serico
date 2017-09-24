---
layout: post
title: <strong>SixSigma Toolbox </strong>
description: A toolbox for statistical training
img: img/2.jpg
---

This toolbox aims to be an extensible application that provides useful tools for trainers of statistics in the classroom. Initially focused on visualizing distributions later tools will explore normality testing, non-normal data and confidence intervals.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/Splash2.png" alt="" title="Toolbox splash art"/>
</div>
<div class="col three caption">
Splash art for the toolbox.
</div>
<div class="img_row">

Currently the toolbox has 3 tools:<br/><br/>
 - <strong>Single distributions</strong> - displays a selection of statistical distributions with adjustable parameters so that it is easy to visualize how the parameters affect PDF/CDF shape and size.<br/><br/>
 - <strong>Central Limit Theorem</strong> - A population is created (or loaded in) from a given distribution and is then sampled. The program allowes the user to change the inital population size, number of samples and sample size. Regardless of the initial distribution chosen, the mean of the samples tends to a normal distribution as the Number and size of the sampels is increased. <br/><br/>
 - <strong>Normal Distribution</strong> - Explores the Normal Distribution within SixSigma. Including an upper and lower limit, a target value and the mean / standarddeviation of the normal. The user can see graphically how DPMO / ZValues / Cp and Cpk change based on the current parameter choices.<br/><br/>


This is my first attempt at using C# and while I have previously used Visual Basic and windows forms, this will be an attempt at the latest Windows Presentation Foundation within the MVVC (Model View ViewModel) architecture.
