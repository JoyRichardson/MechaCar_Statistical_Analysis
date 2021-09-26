#  MechaCar_Statistical_Analysis
## Overview
Jeremy has worked at AutosRUs for 10 years and recently started a new role as a primary analyst.  His team is made of 5 other members and they are tasked with performing retrospective analysis of historical data.

## Resources
Software(s): R v 4.1.1, R Studio and libraries:  ggplot2

## Purpose
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG

Write a short summary using a screenshot of the output from the linear regression, and address the following questions:

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?<br/>
Per the summary results, the vehicle length and vehicle ground clearance variables provide a non-random aount of variance.  Other variables have p-values that indicate a random amount of variance.<br/>

* Is the slope of the linear model considered to be zero? Why or why not?<br/>
Analysis indicates the slope of the linear model is not zero.  The ```p-value: 5.35e-11``` is much smaller than the 5% assumed significant level, indicating there is enough evidence to reject our noull hypothesis.<br/>

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?<br/>
This model predicts the mpg of MechaCar prototypes effectively.  The ```Multiple R-squared:  0.7149``` indicates that approximately 71% of all mpg predictions will be determined.<br/>

![](Deliverable1.PNG)<br/>
