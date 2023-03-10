# Mathematical modelling and virtual decomposition control of heavy-duty parallel-serial manipulators
The repository contains Simulink model and MATLAB code for the real-world hydraulic manipulator forces simulation, based on the approach proposed in the article:

https://doi.org/10.1016/j.mechmachtheory.2021.104680

The code is such that enables easy parametrization and consequently easy code generation for running on a hardware target.

# Requirements
The simulation is performed in MATLAB/Simulink. Simulink Simscape Multibody Add-On libraries are required and MATLAB version 2020a or newer.

# Usage
Make the main folder as a working folder and run 'initializeSimulationGP.m' for the simulation initialization. Afterwards, run 'SimForces2020a.slx' or 'SimForces2022a.slx'.

# Licence
See LICENSE.txt for licencing information.

# Find it also at MATLAB Central File Exchange

[![View Hydraulic manipulator forces modelling on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/98464-hydraulic-manipulator-forces-modelling)

# Acknowledgement

Credit for all the CAD models goes to Dr Janne Koivumäki.

Check out his list of publications https://scholar.google.fi/citations?user=Llrx-nsAAAAJ&hl=fi
