---
layout: post
title: Turbopump Project
description: Development of a 3 inch diameter pump
skills: 
- FDM
- Arduino
- Pump Design
- Onshape
main-image: /PumpPrinted.jpg
---

---
# Intro
Inspired by the work of another rocketry hobbyist, I started this project to gain more understanding of turbopumps and produce my first prototype.
### Cross Section of the Turbopump
{% include image-gallery.html images="PumpCrossSec.jpg" height="400" %}
# Impeller Design and Analysis
Targeting a pressure rise of 500 PSI, a flow rate of 30 GPM, and an operation speed of 30,000 RPM, I started to roughly shape the overall dimenions of the impeller to try to acheive my goals. Iteratively drafting my basic dimentions and performing hand calculations for velocity triangles got me a pressure rise of about 501 PSI. 

The resulting impeller from hand calculations shown below:
{% include image-gallery.html images="Impeller180Sec.jpg" height="400" %}
# Volute Section
Using Bernoulli's equation and the velocities expected at the exit of the impeller and the housing, the calculated pressure delta across the housing is -0.94 PSI. Bringing the total system pressure to just over 500 PSI.
{% include image-gallery.html images="ImpellerVoluteCrossSec.jpg" height="400" %}
# Manufacturing and Assembly
The majority of parts for the pump were 3D printed from PETG. Parts were produced iteratively to improve accuracy and surface finishes. Two bearings and two shaft seals were purchased. The only part to be machined at this point is the shaft. A mini lathe was purchased and places on the floor of my kitchen to produce the shaft. The shaft is aluminum and was polished up 1000 grit sand paper for smooth seal surface contact. Only two attempts were made to produce this part (it is a miracle I hit the toleramces on this lathes.) Two tapped holes were added on bottom with a small drill jig and a hand drill. Parts were assembled and the only redesign that occured was due to a manufacturer's print being mislabeled for bearing thickness.
{% include image-gallery.html images="Lathe.JPG" height="400" %}
{% include image-gallery.html images="LatheGear.jpg" height="400" %}
{% include image-gallery.html images="Shaft.jpg" height="400" %}
# Results
Flowrate testing was done by the timing of emptying and refilling a 2 gallon bucket multiple times and averaging the flowrate. A flowrate of 26.5 Gallons per minute was found for fully open valve. Attempts to record pressure rise at the outlet were unseccesful. Nearly 0 pressure rise was found at multiple valve positions and only about 1 PSI of pressure rise occured at the fully closed and 90% closed position.Early testing using a 3D printed shaft revealed the shaft seal was bonding to the PETG. After replacing those seals and using a polished aluminum shaft, the seals were still deteriorating. This is likely due to the high RPM and limited fluid touching the rubber seals to act as a lubricant.
