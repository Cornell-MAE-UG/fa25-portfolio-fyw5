---
layout: project
title: Heat Exchanger Lab
description: Experimenting with a Heat Exchanger
image: /assets/images/heat.jpg
fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
---

**Parallel vs Anti-Parallel Flow in Heat Exchanger**\

Heat Exchanger: A heat exchanger is a device that allows thermal energy to be transferred between two fluids without the fluids mixing, by passing them by each other through two sides of a conducting surface. One fluid is hotter (in our experiment, red) and releases heat; the other is colder (blue) and absorbs heat.\

Change in Design: We decided to observe the differences between parallel and anti-parallel flow.
Parallel flow: Both fluids enter at the same end and flow in the same direction.
Anti-parallel flow: Fluids enter from opposite ends and flow against each other.\

Photos:
/assets/images/Image_20251220_154438_154.jpeg
Photo: Experimental setup with parallel tubing.
/assets/images/Image_20251220_154437_979.jpeg
Photo: Experimental setup with anti-parallel tubing.\

System Diagram:
The CV consists of the heat exchanger itself.
Hot stream enters with mass flow rate mh and temperature Th,in and exits at Th,out.
Cold stream enters with mc and Tc,in and exits at Tc,out.
There is no shaft work, significant KE, or PE.\

Relevant equations:
Mass Balance
For incompressible water: ṁin = ṁout; ṁh = constant and ṁc = constant.
Energy Balance
Heat lost by hot equals heat gained by cold: ṁh cp (Th,in – Th,out) = ṁc cp (Tc,out – Tc,in)
Heat transfer rate: Q̇ = ṁh cp (Th,in – Th,out)
Entropy Balance
For s.s. w/ negligible external heat loss: Ṡgen = ṁh (sh,out – sh,in) + ṁc (sc,out – sc,in)
For liquids: sout – sin = cp ln(Tout / Tin)
Because heat transfer occurs across a finite temperature difference, entropy is generated. 
Performance Comparison: Parallel vs. Anti-Parallel Flow
Effectiveness  = Q̇actual / Q̇max; Q̇max = Cmin (Th,in – Tc,in) and C = ṁ cp.\

Data:
Parallel
Th,in (°C): 37.6
Tc,in: 10.5
Th,out: 26
Tc,out: 23.4

Anti-Parallel
Th,in (°C):37.5
Tc,in: 8
Th,out: 20.4
Tc,out: 25.6\


			
Results:
Overall, our results show that running the flow Anti-Parallel is more effective than running the flow Parallel in a heat exchanger. This makes sense because when running the flow anti-parallel,  the fluids are maintaining a higher temperature difference for longer, as well as lower entropy generation, making it the thermodynamically superior design.
In addition, although it looked like a law of Thermodynamics was violated in the anti-parallel trial because the hot outlet (20.4 °C) was colder than the cold outlet (25.6 °C), we came up with some reasoning as to why that might have happened. In the first parallel trial, the cold outlet warmed up over time. Then, in the anti-parallel trial, that warmed water entered the system, and because the outlets in a counter-flow arrangement are on opposite ends, the cold water leaving near the hot inlet can end up warmer than the hot water leaving near the cold inlet.
