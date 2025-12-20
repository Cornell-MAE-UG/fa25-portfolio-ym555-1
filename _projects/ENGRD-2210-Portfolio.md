---
layout: project
title: Energy Transfer in Heat Exchanger
description: Lab experiment of heat exhchanger
technologies: Heat Exchanger, Water Pumps, Thermometer 
image: /assets/images/Labeled.jpg 
---

For this assignment, I used the heat exchanger lab as a real-world instance to show how energy is transferred. The device used in this experiment is a small-scale liquid–liquid counterflow/parallel-flow heat exchanger operating under steady-flow conditions.


<div style="clear: both;"></div>

The setup of this system included:

- Heat exchanger, where the energy transfer occurred
- Pumps, which moved the liquid up through the pipes
- Pipes, which held the liquid that moved from the initial container
- Cold water, dyed blue
- Hot water, dyed red
- Containers to hold the water

Here is a visual setup of the system:

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Labeled.jpg' | relative_url }}"
       alt="Set up of entire system with labeled devices"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 1. Labeled Devices.
  </figcaption>
</figure>

My group and I decided to test the design performance of counterflow vs. parallel flow. We conducted both designs twice to see if the outcomes were consistent enough to draw a more accurate conclusion. Our main question was which design resulted in a more efficient energy transfer between the two liquids. 

## Counterflow
First, we conducted the counterflow design. 
Here is a visual setup of the design and the direction of flow for each water:

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Counter.jpg' | relative_url }}"
       alt="Directions the liquids in Counter Flow"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 2. Counter Flow Setup.
  </figcaption>
</figure>

Cold water and hot water are entering and leaving on opposite sides. Cold water is entering from the left and leaving on the right; hot water is entering from the right and leaving on the left. 
System diagram of the counterflow (Constant Volume):

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Counter-2.png' | relative_url }}"
       alt="System Diagram of Counter Flow with directions"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 3. Counter Flow System Diagram.
  </figcaption>
</figure>

Cold water is entering the 2 inlet and leaving through the 1 outlet.
Hot water is entering the 3 inlet and leaving through the 4 outlet. 

### Counterflow, trial 1
The cold (blue) water’s initial temperature was measured at 3.9 °C using a thermometer. The hot (red) water’s initial temperature was set to 35 °C using an immersion heater, but measured at 34.9 °C with the thermometer. 
Initial Blue Temperature 1 (cold): 3.9 °C
Initial Red Temperature 1 (hot): 34.9 °C

We let the flow continue until half of the water in each container had passed through the heat exchanger.
After the heat exchanger, the final temperature of each water was:
Final Blue Temperature 1: 21.5 °C
Final Red Temperature 1: 17.7  °C

We found it interesting that the final temperature of the original cold (blue) water was higher than that of the final original hot (red) water. 

### Counterflow, trial 2
To confirm our findings, we conducted a second trial of this design. 
Initial Blue Temperature 2 (cold): 7.6 °C
Initial Red Temperature 2 (hot): 34.6  °C

Final Blue Temperature 2: 22.8 °C
Final Red Temperature 2: 19.6 °C

The result of this trial was the same as the first one. Parallel flow in a heat exchanger results in the initially cold fluid reaching a higher temperature than the final initially hot fluid. We tested parallel flow in the heat exchanger to compare its outcome. 


## Parallel flow

Here is a visual setup of parallel flow:

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Parallel.jpg' | relative_url }}"
       alt="Directions of liquids in Parallel Flow"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 4. Parallel Flow Setup.
  </figcaption>
</figure>

Cold water and hot water are entering from the top in this view, and exiting through the bottom outlets. 
System diagram of the parallel flow (Constant Volume):

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Parallel-2.png' | relative_url }}"
       alt="System Diagram of Parallel Flow with directions"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 5. Parallel Flow System Diagram.
  </figcaption>
</figure>

As seen here, cold and hot water flows are in the same direction. 
Cold water is entering the 2 input and leaving through the 1 outlet.
Hot water is flipped compared to counterflow, entering the 4 input and leaving through the 3 outlet. 

### Parallel flow, Trial 1
We conducted the rest of the experiment and collected data in the same way as in the counterflow experiment. 
Initial Blue Temperature 3 (cold): 5.4 °C
Initial Red Temperature 3 (hot): 35 °C

Final Blue Temperature 3: 17.8 °C
Final Red Temperature 3: 23.3 °C

There is a difference in the outcome between parallel flow and counterflow. The final temperature of the originally hot water is now warmer than that of the final originally cold water. Like in counterflow, we repeated the experiment to verify the results. 

### Parallel flow, Trial 2:
Initial Blue Temperature 4 (cold): 7.3 °C
Initial Red Temperature 4 (hot): 34.8 °C

Final Blue Temperature 4: 18.5 °C
Final Red Temperature 4: 21.9 °C

The result in this trial was the same as the previous trial. The final temperature of initially hot water is higher than that of the initial cold water in parallel flow. 


## Performance Comparison and Reason

Counterflow is a more efficient design than parallel flow. Now comes the question, why? 
In parallel flow, the hot and cold water enter and exit the heat exchanger in the same direction. The heat from the hot water transfers to the cold water consistently throughout, and by the time they exit, the cold water reaches its maximum temperature. However, this is not the case in counterflow. Since the hot and cold water enter and exit the heat exchanger in opposite directions, the cold water at the output is exposed to the hot water at its almost initial temperature. This increases the cold water beyond that maximum temperature. The ‘shock’ from the hot water causes the cold final temperature to be warmer than that of the initially hot water. 

While the analysis assumes no heat loss to the surroundings, in practice some energy loss occurred due to convection to ambient air and imperfect insulation. This likely contributed to discrepancies between the hot-side and cold-side energy calculations.


## Energy Balance Equation

In this experiment, I am making assumptions to simplify the energy balance equation. 
Assumptions I am making include:
- No external heat transfer, Q̇ = 0
- No shaft work, Ẇ = 0
- Energy transfer is at a steady state, Ė = 0
- Change in kinetic energy and potential energy is negligible, - ΔKE = 0 and ΔPE = 0

<figure style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
  <img src="{{ '/assets/images/Energy-Calcs.png' | relative_url }}"
       alt="Energy Balance Equation of Heat Exchanger System"
       style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">
    Figure 6. Energy Balance.
  </figcaption>
</figure>

### Energy Balance Application

For a steady-state heat exchanger with no shaft work and negligible kinetic and potential energy changes, the steady-flow energy balance reduces to:

ṁₕ cₚ (Tₕ,in − Tₕ,out) = ṁ𝑐 cₚ (T𝑐,out − T𝑐,in)

Assuming water properties with cₚ ≈ 4.18 kJ/kg·K and equal mass flow rates, the energy transferred from the hot stream in Counterflow Trial 1 is:

Q̇ₕ = ṁ · 4.18 · (34.9 − 17.7)

Q̇𝑐 = ṁ · 4.18 · (21.5 − 3.9)

The calculated heat transfer rates for the hot and cold streams were approximately equal in magnitude, which is consistent with the First Law of Thermodynamics for a steady-flow system. Within experimental uncertainty, the energy lost by the hot water matched the energy gained by the cold water, indicating conservation of energy within the heat exchanger. Any small discrepancies can be attributed to heat loss to the surroundings, measurement uncertainty in temperature readings, and assumptions such as negligible heat transfer to the environment.
