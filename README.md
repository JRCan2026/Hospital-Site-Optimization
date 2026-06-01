# Hospital-Site-Optimization

<img width="574" height="385" alt="MAP_MODEL_2" src="https://github.com/user-attachments/assets/1daf0d21-1eeb-4bb2-8851-fc4a2a1d0d3e" />

This project presents a geospatial optimization framework for hospital site selection based on accessibility and risk reduction. The project integrates spatial analysis, travel-time networks, and mathematical modeling to identify healthcare facility locations that maximize population coverage, minimize travel times, and improve the equity of healthcare accessibility. Two approaches are compared; 1) linear coverage maximization and 2) non-linear vulnerability minimization.

The project is divided in three parts:
1) Data preparation, where synthetic data representing heart attack events in Quebec City are generated and processed.
2) Determination of candidate sites, where potentially suitable locations for new hospitals are determined.
3) Hospital site selection, where an optimization model is used to select 4 facilities from a set of 12 candidates in order to maximize accessibility and reduce residual risk.

Complementary functions for simulation and visualization are provided in the "sim_utils.py" file.
