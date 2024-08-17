# SuperheatedSteamSimulation-NASA-Internship-2024
This repository contains a code to simulate the takeoff of an airship fueled by 1/3 superheated steam 

## Background Information:

The steam will be generated in a boiler reactor at 285 degrees C.
The airship specifications (including volume and cargo mass) are variable, and so is the starting elevation, input temperature, and cross sectional area (necessary for drag calculations)
Time intervals and sim duration are variable

## Math:

Used steam tables to compute density of steam at certain pressures and temperatures
Used Q=UAT and Q=MC delta T to calculate decrease in temperature.
Used buoyant force, gravitational force and drag in net force calculations.
Used 1D kinematics equations and mass value to translate force into altitude change.
