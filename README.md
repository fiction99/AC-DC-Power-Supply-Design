# AC-DC-Power-Supply-Design Report and Project
This document is broken up into two distinct portions, one is a research report wherein the goal was to design a regulated AC-DC Zener diode based power supply that minimizes output ripple voltage and have the AC Vripple < 10 mV, providing 100mA into the load. The design was constructed and tested in laboratory and using SPICE simulation software. The other is a physical project wherein the goal was to design a fixed and variable voltage linear power supply with AAA Li-On battery charging capability. This design was constructed external to laboratory and implemented via trial and error. Both are docuemnted below.



### 1 ### 
Report: https://github.com/fiction99/AC-DC-Power-Supply-Design/blob/main/AC-DC%20Power%20Supply%20Design%20.pdf

Executive Summary: The output plots of the AC to DC power supply circuit configurations were analyzed, with the value of the ripple voltage decreasing steadily with each circuit configuration. In the lab portion, transformer only configuration had the greatest peak to peak value at 19Vpp, resembling that of the input AC wave, while the filter, Zener, and BJT configuration was able to successfully reduce the Vripple down the most, to 4.9mV, with simulations of the same circuits providing similar results.

### 2 ###

![alt text](https://github.com/fiction99/AC-DC-Power-Supply-Design/blob/main/media/IMG-3737.jpg)

This was a project built due to my personal need for a working power supply for my electronics projects. As such it required quick selection to common voltage levels as well as a variable voltage option. 

Future Design Considerations: 
I wanted to implement battery charging capabilities because it wanted the device to be multipurpose, thoguh in retrospect, 18650 batteries would have been a much more logical choice than AAA due to their pervasiveness in many electronics hobby projects. Also, the chosen chassis has very thin 2mm walls that flex signficiantly when detaching the outlet cable, so if repeated, I would use a thicker walled chassis to solve longevity concerns.

Here is the close to final design diagram from my notes:

![alt text](https://github.com/fiction99/AC-DC-Power-Supply-Design/blob/main/media/unnamed(3).jpg)

...as well as a layout image I took early on to get an idea of how components should fit.

![alt text](https://github.com/fiction99/AC-DC-Power-Supply-Design/blob/main/media/unnamed(2).jpg)
