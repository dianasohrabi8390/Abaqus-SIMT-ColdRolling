# Thermo-Mechanical Simulation of Cold Rolling of AISI 316L Stainless Steel

## Project Overview

This project investigates the thermo-mechanical behavior of AISI 316L austenitic stainless steel during multi-pass cold rolling using Abaqus/Explicit.

The simulation focuses on temperature evolution during rolling and the effects of plastic deformation, friction, and heat transfer at the roll–sheet interface.

## Simulation Setup

- **Material:** AISI 316L stainless steel
- **Software:** Abaqus/Explicit
- **Process:** Multi-pass cold rolling
- **Initial sheet thickness:** 4 mm
- **Roll radius:** 75 mm
- **Rolling speed:** 40 rpm (as indicated by the output filename; verify against the final model)
- **Analysis:** Coupled temperature–displacement analysis
- **Output variable:** NT11 (nodal temperature)

## Results

The animated temperature contour illustrates the temperature field during the simulated rolling process.

The temperature distribution is evaluated to investigate the influence of plastic deformation, frictional heating, and heat transfer on the sheet temperature.

**Note:** The animation should be analyzed over the complete rolling step. The initial frame alone does not represent the final thermal response.

## Project Objectives

- Simulate the cold-rolling process.
- Analyze temperature evolution during deformation.
- Investigate the role of thermal boundary conditions.
- Support comparison between numerical predictions and experimental observations.

## Tools

- Abaqus/Explicit
- Finite Element Analysis (FEA)
- Thermo-mechanical modeling
- Post-processing and visualization
## Temperature Contour Animation

![coldrolling.gif](Rcoldrolling.gif)
