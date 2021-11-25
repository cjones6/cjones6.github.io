---
layout: page
title: Computing
order: 4
---

Several miscellaneous projects I've worked on include:

- Writing an [AWS EC2 tutorial ]({{ site.url }}/public/AWS_intro.pdf) that discusses how to run code on an EC2 (P2) instance from start to finish.
<div style="float:right"><img src="http://cjones6.github.io/public/contour_plot_resized.png" /></div>
- Implementing the cubic and adaptive cubic regularization algorithms of Nesterov and Polyak (2006) and Cartis et al. (2011)  
 [[code]](https://github.com/cjones6/cubic_reg) [[report]]({{ site.url }}/public/final_report.pdf)  
 These unconstrained optimization algorithms are guaranteed to converge to either a local minimum or a degenerate saddle point, assuming the objective function satisfies certain regularity conditions. To my knowledge, my code was the first publicly available implementation of them.
<div style="float:right"><img src="http://cjones6.github.io/public/ui_output_resized.png" /></div>
- Creating a framework that, given output from a relatively simple SQL query and the table in the database from which it came, can discover a query that will produce this output. It does this intelligently, so that the number of necessary guesses is much fewer than a brute-force approach.  
This could be potentially useful if, e.g., you have the data you used to create a figure and need to update the figure, but don't know where the data came from within your database.
- Contributing to the creation of a [lab book](http://faculty.washington.edu/marzban/labs_Apr2021_jpg.pdf) for students in an introductory statistics course to learn R alongside the course material. 
<div style="float:right"><img src="http://cjones6.github.io/public/financial_crises_resized.png" /></div>
- Visualizing the trends in the type and frequency of financial crises across time and by geographic location by creating a motion chart.  
[[motion chart]](https://drive.google.com/file/d/1XuhXYBPGfQt0yCavpMdz6Xf0xbf1rWhj/view?usp=sharing)[[code]](https://github.com/cjones6/financial-crises-chart)  
Often crises [spread](https://en.wikipedia.org/wiki/Financial_contagion) from one country to another, and the visualization I created gives a sense of this. 
