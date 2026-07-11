# monte-carlo-criticality-simulation
Monte Carlo simulation of neutron transport and uranium-235 criticality in 1D and 3D.


## Overview

This project investigates the criticality conditions required for a self-sustaining uranium-235 chain reaction using Monte Carlo simulation techniques. Starting with a simple one-dimensional model before extending to a three-dimensional simulation, the project explores how neutron transport can be modelled numerically to estimate the critical dimensions and mass of a reactor.

The project was developed as part of a computational physics module.


## Methodology

The simulation models the random paths of neutrons produced during nuclear fission and determines whether they escape the system or trigger further fission events. By varying the size of the simulated reactor and repeating the process many times, the project estimates the critical dimensions required for a sustained chain reaction.

Key techniques include:

- Monte Carlo simulation
- Random sampling
- Parameter sweeps
- Numerical modelling
- Statistical analysis


## Results

The simulation successfully estimated the critical dimensions for a uranium-235 reactor using both one-dimensional and three-dimensional models. Increasing the model complexity improved the realism of the simulation while demonstrating the trade-off between computational cost and accuracy.


## Repository Contents

- `criticality_simulation.ipynb` – Complete simulation and analysis
- `report.pdf` – Project report
- `requirements.txt` – Python dependencies


## Technologies

- Python
- NumPy
- Matplotlib
- SciPy


## Future Improvements

Possible extensions include modelling more realistic neutron interactions, improving computational efficiency through parallelisation, and investigating alternative reactor geometries.
